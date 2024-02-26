---
title: Install Tailwind CSS using PostCSS as a plugin and Vite
date: 2024-02-27
images: 
- https://res.cloudinary.com/dr1nwz8am/image/upload/v1708987666/tailwindcss-postcss-vite-by-sakibsnaz-dev_sbpk4p.webp
---
Ready to boost your website's building? Let's explore Tailwind CSS and Vite, two tools that make web design super fast and easy.

Installing Tailwind CSS can be straightforward, especially when using a Content Delivery Network (CDN). While it's true that CDN setups are simple, they might lack flexibility for customization. However, there's another method that might make you feel like a pro developer: using PostCSS.

Jokes aside, there are three main ways to install and use Tailwind CSS. The first method involves using a CDN, which is indeed super easy—just copy the link and paste it into your HTML file. However, customizing your setup might be challenging with this approach.

The second method involves using Tailwind's CLI (Command Line Interface) and terminal, but we won't explore those today. Instead, we'll focus on using the PostCSS plugin with the build tool Vite.

Follow these steps and install Tailwind CSS using PostCSS and Vite:

**Step 1:**
Open your terminal in the project folder and ensure node and npm is installed.

```node -v
npm -v```

By checking their version. If not installed, download Node from here.

**Step 2:**
Initialize your project with npm

```npm init```

in your terminal.

**Step 3:**
Install Vite using npm

```npm i vite```

**Step 4:**
Install Tailwind CSS, PostCSS, and Autoprefixer using npm:

```npm install -D tailwindcss postcss autoprefixer```

**Step 5:**
Initialize the Tailwind CSS configuration:

```npx tailwindcss init```

**Step 6:**
Create a postcss.config.js file in your project root folder and paste

```module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}```

these into it.

**Step 7:**
Customize your Tailwind CSS configuration in tailwind.config.js file:

```/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}```

**Step 8:**
Add a script to your package.json for starting Vite inside scripts:

```"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "vite"
  },```

You can keep the test as it is, or if you want, you can remove it.

**Step 9:**
Create a CSS file (e.g., style.css or main.css) and include Tailwind CSS by adding the below 3 lines:

```@tailwind base;
@tailwind components;
@tailwind utilities;```

**Step 10:**
Run your project with:

```npm start

Finally, link your CSS file to your HTML file.

Dive into the world of Tailwind CSS and Vite, experiment with different setups, and enjoy the journey of building beautiful, responsive websites. Happy coding!

References:
[Google](google.com)
[Tailwind CSS](https://tailwindcss.com/docs/installation/using-postcss)

Thanks for reading this article, I hope you found it interesting!