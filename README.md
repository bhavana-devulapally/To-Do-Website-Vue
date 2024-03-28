# Assignment 2 - To-Do List Using Vue

# Introduction

As part of Assignment 2, I've developed a To-Do Application utilizing Vue.js. This application empowers users to input activities they wish to accomplish, providing a convenient way to keep track of their tasks. Users can easily access a comprehensive list of their To-Do activities, displayed below.

A notable feature of the application is the ability for users to mark their tasks as complete by simply clicking on the bullet button adjacent to each activity. Upon completion, the application visually strikes through the activity, indicating that the task has been fulfilled.

Additionally, users have the option to delete tasks, removing them from the list of To-Do activities altogether.

# What framework did I pick and why?

I chose to use the Vue.js framework for the development of my To-Do application due to its remarkable features and ease of use. Vue.js offers a seamless combination of script and template features, making it straightforward to develop applications. 

With Vue.js, I found it effortless to create understandable interfaces, which is essential for user-friendly applications.

Upon research I found out that, Vue.js incorporates various performance optimization techniques, such as virtual DOM (VDOM) rendering and efficient update mechanisms. These optimizations minimize DOM manipulation and enhance application performance, resulting in faster rendering and improved user experience.  Vue.js employs reactive data binding, which ensures that changes to the application state automatically reflect in the user interface (UI). 


From my personal observation while running the To-Do application, Vue.js clearly demonstrated faster rendering and UI updates. Vue.js showcased remarkable responsiveness and agility, enabling rapid changes to be reflected on the user interface. This could be one of the reasons why Vue.js is predominantly favored in real-world applications, underscoring its reputation for exceptional performance.
Vue was easily comatible with third-part applications like Glich where i was able to easily run the application .Whereas when i developed the application on Glick using React it took a lot of time for the UI to load. Which is evidnet that Vue is more compatible with any third part applications.

One of the main reasons which I experienced personally that made me go for using Vue.js over other framework, such as React, is its template-centric approach. I initially attempted to build the To-Do application using React, but I found myself creating numerous components to handle different parts of the To-Do list. However, Vue.js provided me with the flexibility to consolidate all the code within a single file using template tags for markup and script tags for JavaScript logic. 
This approach simplified the development process immensely, allowing me to focus more on the functionality of the application rather than getting bogged down in component management which Vue.js would do it automatically.

Vue.js offers seamless integration with other libraries and tools, allowing for greater flexibility and customization. Vue.js has a gentle learning curve, making it accessible to developers with varying levels of experience. Its clear and concise syntax, along with comprehensive documentation, allows developers to quickly grasp its concepts and start building applications.

# What about Vue.js appealed to me, for this project?

Vue.js appealed to me for this project due to its simplicity, flexibility, and robust ecosystem. Its user-friendly nature allowed for a smooth learning curve, enabling me to quickly grasp its concepts and start building without significant hurdles. The clear and concise documentation provided invaluable guidance throughout the development process, empowering me to efficiently translate ideas into code.

The component-based architecture of Vue.js was particularly attractive as it facilitated modularity and reusability of code, making maintenance and collaboration within the project team a breeze. This approach not only accelerated development speed but also ensured a structured and organized codebase.

Moreover, Vue.js' reactive data binding and intuitive reactivity system simplified data management, resulting in consistent and responsive user experiences. This was crucial for the project's interactive elements, ensuring seamless user interactions and real-time updates.

Furthermore, Vue.js boasts an extensive ecosystem of libraries and plugins, offering a plethora of tools to extend functionality and address specific project requirements. Whether it was integrating state management with Vuex, routing with Vue Router, or seamlessly incorporating third-party libraries, Vue.js provided ample support to tailor the application precisely to our needs.

In summary I can say that Vue.js' ease of use, adaptability, and comprehensive ecosystem made it the perfect fit for developing this application. Its developer-friendly approach facilitated efficient development, resulting in a high-quality application that met both functional requirements and aesthetic standards, ensuring a seamless user experience.


# What alternative frameworks did I consider?

In the initial stages, I planned to develop the application using React. However, while running the application, I observed that React presented certain challenges. One notable issue was its performance, as the application built with React was loading quite slowly. This sluggish loading speed was concerning, especially considering the project's requirements for responsiveness and efficiency.

Moreover, React's unidirectional data flow pattern, while powerful for managing complex data interactions, introduced some complexities that weren't necessary for the scope of the To-do application. This pattern often led to boilerplate code and increased cognitive load, making development less straightforward.

Additionally, the React ecosystem, while vast and rich with resources, sometimes felt overwhelming for the To-do application's needs. Sorting through numerous libraries and tools to find the right fit for specific requirements could be time-consuming and detract from the primary development focus.

Hence I felt that Vue.js was a more suitable alternative. Vue.js offered several advantages over React that aligned better with the project's goals. Firstly, Vue.js' reactivity system and two-way data binding provided a more intuitive approach to managing data flow within the application. This simplicity led to cleaner and more concise code, reducing development time and potential errors.

Furthermore, Vue.js' component-based architecture, combined with Single File Components , promoted better organization and encapsulation of code. This approach enhanced maintainability and facilitated collaboration within the development team.

Overall, Vue.js' combination of simplicity, performance, and a cohesive ecosystem made it the preferred choice for developing the To-Do application. By leveraging Vue.js, the application could be developed more efficiently, with faster loading times and a smoother development experience.


# What resources did I read or watch or listen to?


In the process of developing the application, I utilized a variety of resources to enhance my understanding and overcome challenges. Primarily, I watched YouTube videos of Tyler Potts, Traversy Media to gain insights into Vue.js development practices and techniques. 

When faced with errors during development, I sought assistance on Stack Overflow, a platform where developers share their queries and receive answers from the community. Additionally, I extensively relied on Vue.js's official documentation available on vuejs.org to deepen my understanding of Vue.js syntax and features.

To gain further insights into the application and get an idea of the how the user-interface should look like, I examined source codes on GitHub, studying interfaces and functionalities of similar projects. Integrating my own ideas with these, I iteratively refined the application's design and functionality.

For a more structured learning experience, I leveraged resources such as CodePen, which provided practical examples and demonstrations to solidify my understanding of Vue.js concepts and syntax. For styling the To-Do Page, I frequently referenced W3Schools to ensure consistency and adherence to best practices in web design. At times, I utilized ChatGPT to assist in resolving errors and clarifying concepts, leveraging its vast knowledge base and problem-solving capabilities.

Furthermore, I supplemented my learning by exploring educational platforms like freeCodeCamp and W3Schools, which offered comprehensive tutorials and guides on Vue.js development. By leveraging these diverse resources, I was able to effectively navigate challenges, deepen my understanding of Vue.js, and successfully develop the application.

# Describe the site you built for this assignment. What does it do? What components or features of the framework did you explore for this project?


































[Vue](https://vuejs.org/) is a front end JavaScript framework for building user interfaces and single-page applications. [Vite](https://vitejs.dev/) is a powerful tool for building javascript apps that bundles all of your code and shows immediate changes while you're editing. We're big fans!

While you're in the editor working, Glitch is running your `start` script in the background (`vite dev`). The site will be in dev mode and you'll see your changes happen immediately in the preview window. Once you close the editor window and your app goes to sleep, Glitch runs the `build` script and Vite builds your app for modern browsers.

## What's in this project?

← `README.md`: That’s this file, where you can tell people what your cool website does and how you built it.

← `index.html`: This is the main page template Vue uses to build your site. When you're ready to share it or add a custom domain, change SEO/meta settings in here.

← `src/`: This folder contains all the files Vue will use to build your site.

### Working in the `src/` folder 📁

← `src/main.js`: This is the root file of the Vue app. If you install plugins (like `vue-router`), they need be specified in that file!

← `src/App.vue`: The base for your Vue app, here is where the magic really happens. 

← `src/public/`: Static assets should be placed in the `public` folder. The files put in the `public` folder will simply be copied into the built files. 

← `src/assets/`: Media, such as images, can be placed in this folder.

← `src/components/HelloWorld.vue`: A demo Vue component that uses the *new* Vue Composition API to create a simple working counter.

All styles for this SPA can be found in `src/App.vue`.

### Made by [@khalby786](https://khaleelgibran.com) for Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.