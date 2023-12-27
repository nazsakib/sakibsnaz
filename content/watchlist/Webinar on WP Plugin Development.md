---
title: An Exclusive Webinar on WordPress Plugin Development
date: 2023-12-27
description: উইডেভস একাডেমী আয়োজিত ওয়ার্ডপ্রেস প্লাগিন ডেভেলপমেন্ট এর জন্য বেষ্ট কোডিং প্র্যাকটিস, ক্যারিয়ার অপরচুনিটি এবং প্রশ্নোত্তর পর্ব নিয়ে ওয়েবিনার।
images: 
- https://lh3.googleusercontent.com/drive-viewer/AEYmBYQ7XlmZTieuCSiRY2UOGEUabJdhLGm3hfgEtkuqJYcKMAglhMaayEX-bKcitSUUgWjoFDbnjCr8yCIF0vgV3_lVA8_0=s1600

---

#### A webinar organized by weDevs Academy on WordPress plugin development covers the best coding practices, career opportunities, and a Q&A session dedicated to this field. The session covered aspects such as career opportunities for developers, the current state of WordPress plugin development, and additional in-depth discussions on relevant subjects.
---
I recently had the amazing opportunity to attend the webinar on WordPress plugin development, hosted by [weDevs Academy](https://wedevs.academy/) and featuring industry leaders. It was an incredibly valuable chance to learn from senior experts like Hasin bhai, Nahid bhai, and Tareq bhai. My sincere thanks to weDevs and the wonderful host, Raad bhai, for providing such a fantastic learning experience. 

First, I'll focus on summarizing the key topics and key points covered in the webinar. These are the essential takeaways that I want to remember and be able to refer back to later. Then, I'll add the Q&A section, which will provide further insights and clarify any outstanding questions.

---
## Host
1. Raad Sheraz, SMM Specialist, [weDevs](https://wedevs.com/)

## Guests
1. Tareq Hasan, Founder & CTO, [weDevs](https://wedevs.com/)
2. Hasin Hayder, Founder, [Learn With Hasin Hayder](https://learnwith.hasinhayder.com/wp/)
4. Nahid Ferdous Mohit, Senior Developer, [10up](https://10up.com/)

You can watch the webinar on [Facebook](https://www.facebook.com/wedevs.academy/videos/1779843149143527) & [YouTube](https://www.youtube.com/watch?v=YgCYOYS4I8Y&ab_channel=weDevsAcademy)

---
This wasn't just any webinar; it was a goldmine of knowledge shared by experts. From plugin architecture and best practices to security considerations and monetization strategies, the session covered everything you need to know to create high-quality plugins that stand out.


## What is Plugin Development and how to start.
Tareq Bhai started by defining WordPress plugin development and diving into the reasons why one might choose it as a career. He shared his own journey, explaining how he began with Joomla in his early days. While Joomla's complexities caused a terrible challenge for beginners, discovering WordPress felt like a leap from hell to heaven. WordPress is easy to started and beginner friendly where Joomla is a good choice in the long run and for the experienced developers. Since then, he's built countless plugins and continues to explore the platform's endless possibilities.

Nahid Bhai's WordPress adventure began in 2014, taking flight with a website he built for himself. This hands-on experience ignited his passion, leading him to explore customizing plugin core functions to his needs. He then embraced the freelance world through Upwork. Then he joined WPMU Dev as a Technical Support Engineer. Besides he's an active to the WordPress Gutenberg project as a core contributor. Recognizing his talent, WPMU Dev promoted him from support engineer to a developer role, paving the way for his current job as a Senior Developer at 10up. Here, he continues to excel within Google's only official WordPress plugin team, Google Site Kit.

Hasin Bhai seconded Tareq Bhai's sentiment, describing plugin development as an addictive pursuit that leaves you wanting more. Once you start, there's no coming back from it. So what is plugin actually, or plugin development? Think of plugins as extensions that add new features or modify existing ones within a system, like building blocks for customizing your software. Think of software like a basic car and plugins as the customization kits. You can add features that enhance performance like a turbocharger, introduce comfort upgrades like plush seats and air conditioning, or even completely change the look with custom paint jobs and rims. All without rebuilding the engine from scratch! Building plugins is like navigating a new city: knowing the layout is crucial to getting where you want to go. That's why rule number 1 is understanding the system you're building for, and rule number 2 is never forget the rule number 1. It's that important! 

Hasin bhai also added that, plugin development isn't about making digital gadgets only; it's about solving real-life problems. So, before you start coding, identify the challenges you want to solve. Once you've found your mission, here's a roadmap to guide your plugin's journey:

- Understanding the system you're building for is like having a GPS in an unfamiliar city—essential for reaching your destination!
- Build a solid foundation by addressing core concerns shared by all web applications: security, database optimization, and the underrated one, UI/UX.
- While functionality is important, don't forget that a plugin's interface is also important. Make it intuitive, welcoming, and easy to navigate for everyone.
- Pricing is the final piece of the puzzle. It's about finding your plugin's worth aligns with its cost, ensuring a win-win for both you and your users.

Remember, building plugins isn't just about lines of code; it's about building bridges between technology and human needs. Keep those real-life problems in focus, and you'll create solutions that truly make a difference. 


## Architecture, design approach of WordPress Plugin
Tareq Bhai shed light on some important aspects of plugin development: architechture, design and code base. Plugins small or big, it should be maintenable, readable for others. Not just you make it and publish, it'll have to by maintaining by others, they'll read and try understant what you've written or try to say. 

So how to do that? He shared some essential tips for writing code that's easy to understand, not just for you, but for everyone who might need to work on it later. Think of it like building a house: you want your blueprints to be clear and organized so anyone can add a new room or fix something;

- **Hooks:** WordPress hooks are like magic buttons that let your code plug into different parts of the platform. Use them wisely to make your plugin flexible and powerful.
- **Readable Code:** Don't write code like you're talking to a computer; write it like you're explaining things to a friend. Use clear names for variables and functions, and add comments to explain what you're doing.
- **Follow Others:** Check out the code of popular plugins – they're like model houses! See how they organize things (classes, functions, hooks) to make it easy to understand.
- **Updated PHP:** PHP has gotten much better at using object-oriented programming and functions. These tools can make your code cleaner and easier to maintain.
- **One for One:** Don't cram everything into one giant class. Give each class its own specific task, like a dedicated kitchen or bathroom. This makes it easier to find and fix problems.

Tareq Bhai started when PHP was a different beast! He mentioned the struggles with classes and compatibility back then. Now, things are way easier, so embrace the new features and write code that takes advantage of them.

Moving on to the user experience, he emphasized the importance of adaptability in UI/UX design for plugins. There's no one-size-fits-all approach; the focus should be on creating an eye-catching, user-friendly, and easy-to-use interface that works for any situation. He pointed out the various tools at your disposal, including React, Vue, and REST API, which give you the flexibility to craft interfaces that seamlessly integrate with different WordPress themes and user workflows.

Hasin bhai emphasized the importance of adopting the "WordPress way" when thinking about WordPress and plugins. He aligned with Tareq bhai's perspective and dived into the significance of WordPress hooks, considering them an essential feature in the platform's internal architecture. For instance, in data handling, instead of opting for PHP PDO (PHP Data Objects) framework or raw MySQL functions, WordPress offers a dedicated database function called WPDB.

Additionally, When developing a plugin, it is considered good practice to leverage WordPress internal modules, libraries, and functions. The platform provides functions for tasks such as sanitization, validation, and more. Becoming familiar with these internal functions and APIs not only saves time but also enhances the overall quality of your plugin.


## Essentials Tools and Technolgies for Plugin Development
Nahid bhai discussed about the significance of having the *WordPress Codex* as a fundamental tool for every WordPress developer. According to Hasin bhai and Tareq bhai, the codex contains comprehensive information on every function, including community notes that facilitate easy comprehension of functions. They highlighted that adhering to the codex ensures compliance with a majority of coding standards.

Additionally, for local development, widely used tools include Local By Fly Wheel. Some companies, such as 10up, use their internal system, 10up Docker, based on Docker, even though it's open source. With a simple command, a WordPress site can be created in 10up Docker. Other universally recognized tools include the VS Code Editor, Git for version control, Composer for dependency management, and Webpack for frontend bundling.

A critical aspect for creating a scalable plugin is testing. For PHP, [PHPUnit](https://phpunit.de/) is recommended, and for [React](https://react.dev/), [Jest](https://jestjs.io/) is commonly used. Linting tools like PHP_CodeSniffer help maintain a consistent coding structure throughout the codebase.


## Security Best Practices
Hasin bhai supported Nahid bhai's viewpoint and further emphasized the importance of using a configurable editor. While preferences may vary, with some favoring Visual Studio Code and others opting for PHP Storm, Hasin bhai personally uses VS Code. He highlighted the necessity of being familiar with command line tools like WP-CLI for efficient WordPress development.

In terms of quick deployment, he suggested using tools like SFTP and Rsync. These methods facilitate rapid and reliable deployment of WordPress projects, ensuring smooth and efficient processes in the development workflow.

Back in topic, secure plugin development. To mitigate these vulnerabilities, developers can implement practices such as::

- XSS ( Cross-site scripting )
- CSRF ( Cross-site request forgery )
- SQL Injection

From these types of vulnerabilities you can do some things like:

- **Validation**: Check input for malware when it is provided.
- **Sanitization**: Sanitize input on the server side.
- **Escaping**: Ensure that any input with malware is not displayed on the client side, filtering out potential threats in the output.

It's essential to consistently follow these three practices. In the context of WordPress, tools like WPDB are commonly used to prevent SQL Injection, as mentioned by Nahid bhai. He also highlighted that the Codex dedicates an entire chapter to WordPress security.

Furthermore, it's crucial to ensure that no one can execute files from your plugin directory via the WordPress directory. Writing code in a way that prevents SQL Injection in your plugin's code is essential. Understanding security and potential vulnerabilities is key to safeguarding against potential attacks.

Hasin bhai mentioned something important that Tareq bhai said about keeping your plugin easy to maintain. If there are any issues or vulnerabilities, you should be ready to quickly fix them and release updates. This ensures that your plugin stays secure and users can rely on it and suggested to follow [Patchstack](https://patchstack.com/index.php) and emphasized on self learning, read documentation and internal [WordPress security](https://developer.wordpress.org/advanced-administration/security/) guidelines.

Tareq bhai agreed with Hasin bhai and emphasized the importance of simple but crucial practices like Validation, Sanitization, and Escaping. He also dropped some hints about the significance of authentication and authorization in ensuring the security of a WordPress plugin. Many people believe that WordPress sites are not secure, but that's not entirely true. WordPress itself is a secure system. Being open-source with millions of users means that any vulnerabilities can be quickly identified and fixed. The large community surrounding WordPress contributes to a robust security ecosystem, ensuring a timely response to potential issues.

Tareq bhai also highlighted an important aspect: the security of WordPress depends on plugin developers as well. If a plugin with vulnerabilities is installed on a significant number of sites, say 50 thousand, its impact can be substantial. Therefore, it's crucial for plugin developers to be mindful of potential security issues and actively work towards ensuring the safety of their plugins to prevent widespread vulnerabilities.


## Feedback Handling
As Tareq bhai manages a popular plugin like [Dokan](https://dokan.co/wordpress/), he discussed how he handles feedback from thousands of users. 

Building a great plugin isn't about adding every bell and whistle at once. It's like baking a cake – you start with a recipe (your goal), but the real magic happens when you taste it (get user feedback).

Here's why listening to your users is the secret ingredient:

- **Unexpected Twists:** When users dig into your plugin, they discover new ways to use it, or find missing pieces. These new ideas are like sprinkles for your recipe, making it even tastier!
- **Support Hints:** Your support team are like taste testers, telling you which parts taste off or need more sweetness. Pay attention to their tips and tricks – they'll help you improve your recipe.
- **Marketing Mixes it Up:** Your marketing team knows what everyone's craving. They listen to what people want (through surveys and online chatter) and tell you what flavors to add to your cake.

Of course, you can't bake every request, just like you can't put everything in a cake. But gathering feedback helps you choose the best flavors (features) to add to your development roadmap.

By listening to your users and their needs, your plugin becomes more than just a tool; it becomes a treat everyone enjoys. And like a delicious cake, the more feedback you get, the better it gets!


## Testing Methodologies
Nahid bhai is currently working on the Google Site Kit plugin, which boasts over 3 million active installations. He shared insights into the real-life scenario of working on this plugin, detailing the challenges and experiences encountered during its development and maintenance.

Firstly, they conduct thorough testing of each function and class. For the PHP component, PHPUnit is utilized. As for the administrative panel of Google Site Kit, which is built on the JavaScript framework React, testing is carried out using Jest.

Secondly, they perform end-to-end integration testing, focusing on automated testing components. Given that the plugin comprises various modules that interact with each other, this phase ensures the seamless collaboration and functionality of these modules.

Thirdly, using JavaScript Library [BackstopJS](https://github.com/garris/BackstopJS) they do Visual Regression Testing. This testing involves comparing current screens from the plugin's latest branch with screenshots from the pull request branch, generating a diff. If significant changes are detected, it triggers an alert in the pull request.

These testing processes are fully automated.

For manual testing, after merging each pull request, a QA session is organized. Every two weeks, an update is released for each sprint, preceded by a release session with the entire team.

This provides a concise overview of Nahid bhai's approach to working on a plugin.


## Updated with WordPress newly released versions
Hasin bhai described that it's a good practice to upload plugins to a newly released version of WordPress and test them using proper testing methodologies. This immediate testing helps identify any issues.

For each WordPress version, the minimum compatible version of PHP is stated. This allows developers to download that specific PHP version on their local machines and check for compatibility.

Tareq bhai emphasized following WordPress standards as a good practice. He cited WooCommerce as an example, highlighting its rapid evolution over the past 4-5 years.

Additionally, Tareq bhai mentioned a plugin called WooCommerce Conversion Tracking. Although not updated for years, it still works perfectly. The key to its continued functionality lies in its development following standard coding practices and the use of standard APIs.


## QnA
Questions from Facebook Comments!

***1. Faisal Ahammad:*** আমি সাপোর্ট ইঞ্জিয়ার হিসাবে কাজ করছি প্রায় ২ বছর। যখন PHP OOP শিখি, তখন মনে হয় জিনিস গুলো বুঝতেছি। কিন্তু প্লাগিন ডেভ করতে গেলে মনে হয় সব ভুলে গেছি বা ডট গুলো কানেক্ট করতে পারছি না। ভয় হয় হয়ত বেস্ট প্র্যাকটিস ফলো করতে পারছি না। এইভাবে করলে হয়ত ভাল হবে না। আর আগাতে পারি না। কিভাবে এই সমস্যা কাটিয়ে উঠতে পারি ভাই?
- ***তারেক ভাই  এবং হাসিন ভাই উত্তর দিয়েছেন:*** যেটা বানাইতে চান বানায় ফেলেন। যেমনই হোক, জোড়াতালি দিয়ে হলেও বানায় ফেলেন। এরপর আপনি নিজেই বুঝবেন ফাংশনের ব্যবহার, রিপিটেড ফাংশনের অপ্রয়োজনীয়তা এবং বারবার এত এত ফাংশনের নাম ঠিক করতে যেয়ে বুঝতে পারবেন ক্লাসের প্রয়োজনীয়তা। একটা ক্লাস নিয়ে তার মধ্যে যত ইচ্ছা ফাংশন রাখবো। তারপর দেখতে পাবেন, এবস্ট্রাক্ট ক্লাস এবং ইন্টারফেস এগুলো অটোম্যাটিক্যালি চলে আসবে। আপনার প্লাগিনের ফিচারই আপনাকে বলে দিবে নেক্সট আপনাকে কই করত হবে। প্লাগিন বানানোর পরামর্শ এবং অন্যান্য প্লাগিনের কোড পড়ার সাজেশন দিয়েছেন। তারপর হাসিন ভাই সাথে যোগ করেছেন, পারফেকশনিষ্ট হবার চেষ্টা করলে প্লাগিন কোনোদিনই রিলিজ হবে না।

***2. Mohammad Taufiqur Rahaman Akunjee:*** প্লাগিন ডেভেলপমেন্ট এ এক্সপার্ট হবার জন্য কি কোন কোম্পানিতে জব করার প্রয়োজনীয়? কিভাবে রিমোট জবের উপযুক্ত হবো? কখন মনে করবো - আমি রিমোট জবের জন্য উপযুক্ত?
- ***হাসিন ভাই, নাহিদ ভাই এবং তারেক ভাই উত্তর দিয়েছেন:*** যেকোনো ক্ষেত্রেই রিমোট জব অথবা টিম, কিছু জিনিস রয়েছে যেমন সফট স্কিল। কিভাব প্রবলেমগুলোকে অন্যদের সাথে শেয়ার করতে হয়, কিভাবে আপনি প্রবলেমগুলো বুঝতে পারছেন কিনা সেটা শেয়ার করতে হয়, টিমের সাথে কাজ করতে পারেন কিনা, প্রপারলি গিট ব্যবহার করতে পারেন কিনা। মোট কথা, টিম প্লেয়ার হতে পারবেন কিনা, এটি যখন আপনি বুঝতে পারবেন তখন জব গ্লোবালি করবেন নাকি লোকালি করবেন এটি বুঝতে অনেক ইজি হবে। কিন্তু জব লোকালি শুরু করার একটা সুবিধা রয়েছে, আপনি ফিজিক্যালি একটা চমৎকার এনভাইরনমেন্টে কাজ করতে পারছেন যেটি রিমোট টিমে হয় না। লোকাল টিমে ফিজিক্যালি কাজ করতে গেলে অনেক এক্সট্রা কিছু ফেইস করা লাগে, অনেক কিছু শেখা যায়,  কমিউনিক্যাশন স্কিল বিল্ড আপ হয়, অনেক ধরণের এক্টিভিটিস ও হয় যেটি আপনাকে বার্ন আউট হতে বিরত রাখে। আর রিমোট জবের জন্যে উপযুক্ত কিনা এটা নিজেকেই বের করতে হবে, দেখতে হবে আমার স্কিলসেটস জবের ডেসক্রিপশনের সাথে মিলে কিনা, আমি পারবো কিনা। হাসিন ভাই প্রাথমিকভাবে লোকালি শুরু করার পরামর্শ দিয়ে উনার উত্তর শেষ করেছেন। 

    যদিও নাহিদ ভাই উনার ক্যারিয়ার শুরু করেছেন রিমোট জব দিয়ে তারপরেও উনি হাসিন ভাইয়ের সাথে একমত হয়ে সাজেষ্ট করেছেন লোকালি শুরু করাটা অনেক দিক থেকে বেটার। 

    তারেক ভাই বলেছেন, ডিপেন্ড করে ইন্ডিভিজুয়ালের উপর। আপনি কি নিজে নিজে শিখতে পারেন কিনা, যদি সেলফ ম্যানেজ করার ক্যাপাবিলিটি থাকে তাহলে রিমোট জব বেটার হবে। আর যদি না থাকে তাহলে আপনার আশেপাশের মানুষগুলোর সাথে মিশে, একটা টীমের মত করে থাকলে অনেক কিছু শিখতে পারেন, অন্যকে দেখে শেখার আগ্রহ তৈরি হবে। সেক্ষেত্রে আপনার জন্যে লোকাল জব ভালো হবে। রিমোট জবে ধরে ধরে শিখানোর ওয়ে নাই, তাই কমিউনিকেশন স্কিলটা খুবই গুরুত্বপূর্ণ।

***3. Sunwarul Islam:*** How can we achieve smooth integration of javascript frontend ecosystems namely NextJs, VueJs, etc when develop a wordpress plugin, give us some tips, tricks and resource we may don't know. Thanks.
- ***Tareq Bhai answered:*** He stated that you can use React and Vue for developing plugins in WordPress, but NextJS is not suitable for direct integration. However, you can utilize NextJS in a headless manner. He recommended starting with Vue and shared his [vue-wp-started](https://github.com/tareq1988/vue-wp-starter) repository as a helpful resource to begin working with Vue for WordPress development.

***4. Abu Al Muhid:*** I like php but I'm confused which one to start first. wp or laravel? Many say that wp is messy whereas laravel is so clean. Kindly shed some light on this. I want to work with docker, aws etc. Can I do it with wp? Full Stack dev is possible? And also SASS dev?
- ***হাসিন ভাই এবং তারেক ভাই উত্তর দিয়েছেন:*** আপনি কনফিউজড যে মানুষজন কি বলছে। মানুষ বলতেছে যে "পিএইচপি ইজ ডেড" সেই ২০০৫ থেকে। কিন্তু পিএইচপি এখনো আছে এবং দিন দিন শক্তিশালী হচ্ছে। তাই মানুষজনের কথা কানে নেওয়া যাবে না। মানুষজণ মাইক্রোসার্ভিস এর থেকে বেশি ফোকাসড, একচুয়াল কোড অপটিমাইজেশনের থেকে। লারাভেল ডেভলাপার অথবা ওয়ার্ডপ্রেস ডেভলাপার, কোন দিকে ক্যারিয়ার ভালো হবে, এই প্রশ্নে উনি বলেছেন, দুইটাই ভালো হবে যদি আপনি ভালো জানেন। ব্যাকেন্ডে ওয়ার্ডপ্রেস ইউজ করতে পারবেন কিছু লিমিটেশন নিয়ে। তবে মাথায় রাখতে হবে যে এটি শুধুমাত্র একটি কনটেন্ট ম্যানেজমেন্ট সিস্টেম। আপনি এপিআই দিয়ে কন্টেন্ট রিট্রিট করতে পারলে সেটি ভিউ অথবা লারাভেল যেটি দিয়েই ইচ্ছা ফ্রন্টেন্ডে দেখাতে পারবেন। তবে প্রতিটি প্রজেক্ট শুরু করার আগে সিস্টেম এনালাইসিস করল আপনি বুঝতে পারবেন যে আপনার ষ্ট্যাক আসলে কি হওয়া উচিত। ঢালাওভাবে আসলে কখনোই বলা সম্ভব না যে, এটি আমি লারাভেল দিয়ে পারবো, ওয়ার্ডপ্রেস দিয়ে পারবো না অথবা লারাভেল এটার জন্যে বেষ্ট আর ওয়ার্ডপ্রেস এটার জন্যে বেষ্ট না। আর ডকার, এডব্লিউএস(AWS) এসব হচ্ছে কোডের জন্যে হোষ্টিং প্ল্যাটফর্ম। টুলস, প্ল্যাটফর্ম অথবা ষ্ট্যাক ডিপেন্ড করে প্রজেক্ট রিকোয়ারমেন্টের উপর। 

    তারেক ভাই বলেছেন, ডকার এবং এডব্লিউএস(AWS) এগুলোর সাথে রিলেটেড না। আপনি এপ্লিক্যাশন লারাভেল অথবা ওয়ার্ডপ্রেস দুইটা দিয়েই বানাতে পারেন, এগুলো হচ্ছে টুলস। সব প্রজেক্টের জন্যে সব টুলস সুইট্যাবল না। স্যাস প্রোডাক্ট বানানোর ভালো প্র্যাকটিস হচ্ছে লারাভেল দিয়ে বানানো, কিন্তু আপনার যদি লারাভেলে বানানো প্রোডাক্টটার জন্যে মার্কেটিং এর দরকার হয়, যেমন ল্যান্ডিং পেইজ বানাতে হবে তখন লারাভেল দিয়ে সেটা আপনি করতে পারবেন না। তখন দেখা যাবে ওয়ার্ডপ্রেস দরকার হচ্ছে। আপনার যদি জানা থাকে কোনটার কি কাজ তাহলে ইজিলি কাজ করতে পারবেন, স্যাস বানাতে গেলে দুইটারই দরকার হবে। ওয়ার্ডপ্রেস এবং লারাভেল দুইটাই পিএইচপি বেইজড, তাই দুইটারই দরকার পড়তে পারে একই প্রজেক্টে। 


## Learn WordPress Plugin Development
For those interested in learning plugin development from experienced professionals, [weDevs](https://wedevs.com/) has expanded their educational offerings through [weDevs Academy](https://wedevs.academy/). They've introduced a Plugin Development course, providing a thorough and expert-guided learning experience in this domain.

Instructors are [Hasin Hayder](https://www.facebook.com/hasin), Founder, [Learn with Hasin Hayder](https://www.facebook.com/learnwithhasinhayder) and [Nahid Ferdous Mohit](https://www.facebook.com/nfmohit), Sr. Software Engineer at [10up](https://www.facebook.com/10up.agency).

You can checkout the course details in weDevs Academy [Facebook page](https://www.facebook.com/wedevs.academy) and their [website](https://wedevs.academy/).


## Tips for Newcomers
**Nahid Ferdous Mohit:** When you're learning something new, start with the basics. Make sure to read the instructions and don't just rely on one platform without understanding the basics.

**Hasin Hayder:** Having a strong foundation is like having a solid base. It allows you to build up to 10/20 floors on top of it. Wherever you are, staying consistent is important. Set goals, stay focused, and you can achieve anything. Age and other factors don't really matter.

**Tareq Hasan:** Quoting the weDevs hiring process, he mentioned that they ask questions based on fundamentals, and unfortunately, many candidates get disqualified because their basics aren't strong. So, it's essential to build a solid foundation. The concepts of almost every programming language are similar. Strengthen your basics and have the mindset that you can learn. Building things from scratch is like having a superpower. Programming is easy once you learn how to do it, and then you're ready to go. Stay consistent.

---

And that's a wrap! The wonderful session has come to an end. Raad Bhai hosted the program amazingly, keeping the viewers engaged throughout the session, just like the guests did.