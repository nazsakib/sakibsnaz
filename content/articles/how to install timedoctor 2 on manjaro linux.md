---
title: How to install Time Doctor 2 on Manjaro Linux
date: 2024-09-15
images:
- https://res.cloudinary.com/dr1nwz8am/image/upload/v1726383730/how_to_install_time_doctor_2_on_manjaro_linux_by_sakibsnaz_tzestp.webp
---

# Installing Time Doctor 2 on Manjaro Linux

In today’s work environment, keeping track of time and staying productive is really important, whether you’re working on a team or as a freelancer. Time Doctor 2 is a helpful time tracking tool that lets you record how much time you spend on tasks, manage your work, and even track breaks. It helps people and businesses make the most of their time and get more done.

Manjaro Linux is a popular, user-friendly operating system that’s based on Arch Linux. It’s known for being fast, reliable, and easy to customize. Many people like using Manjaro because it gives them access to the latest software while still being stable and easy to use, even for beginners.

In this guide, I’ll show you how to install Time Doctor 2 on Manjaro Linux so you can manage your time effectively while enjoying a flexible and powerful Linux system.

### Download and Execute the File

1. First, download the Time Doctor 2 app from the official website:
   [Time Doctor Download](https://help.timedoctor.com/article/322-time-doctor-download)

2. Open a terminal.

3. Navigate to the directory where you have downloaded the file, for example:
    ```
    cd ~/Downloads
    ```
4. Make the AppImage file executable:
    ```
    chmod +x timedoctor-desktop_3.12.16_linux-x86_64.AppImage
    ```
5. If you do not want to keep the file in the Downloads folder, you can create a temporary installation directory:
    ```
    mkdir ~/temp-timedoctor
    ```
6. Run the installer with the target set to the temporary directory:
    ```
    ./timedoctor-desktop_3.12.16_linux-x86_64.AppImage --target ~/temp-timedoctor
    ```
7. Move the installed files to a system directory such as /opt:
    ```
    sudo mv ~/temp-timedoctor /opt/timedoctor
    ```

Now, you can remove the temporary directory from the Downloads folder. This way, you install the application in a proper system directory and keep your Downloads folder clean.

### Create a Desktop Entry

To create a desktop shortcut for launching the application from your desktop environment’s menu or launcher:

First, create a .desktop file:

    sudo gedit /usr/share/applications/timedoctor.desktop
    
Note: Since I am using Gedit as a text editor, I have used Gedit. You can use Nano or any other text editor if you prefer.

Second, Add the following contents to the file:

    [Desktop Entry]
    Name=Time Doctor
    Comment=Time tracking and productivity tool
    Exec=/opt/timedoctor/timedoctor2
    Icon=/opt/timedoctor/timedoctor2.png
    Terminal=false
    Type=Application
    Categories=Utility;Productivity;

Save and close the file.

### Explanation:

**Terminal=false:** This means the application will be launched directly as a graphical application, without opening a terminal window. This is the appropriate setting for most GUI applications.

**Terminal=true:** This means the application will be launched inside a terminal window. This is useful for command-line applications or scripts that require a terminal to run properly.

Now you should be able to launch Time Doctor from your application menu or launcher.