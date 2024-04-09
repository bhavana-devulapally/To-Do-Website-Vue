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

## Description of the To-Do Application:

 I developed a To-Do Application using Vue.js, facilitating users in managing their tasks efficiently. The application allows users to input activities they intend to accomplish, providing a convenient means of task organization. Users can access a comprehensive list of their To-Do activities, with the ability to mark tasks as complete by clicking on the bullet button, visually striking through the activity upon completion. Additionally, users have the option to delete tasks, removing them from the list altogether.

## Components Used: 

In implementing this functionality, I explored various components and features of the Vue.js framework:

=> I utilized Vue instances to manage the application's reactivity and maintain state across components. This enabled seamless interaction between different parts of the application.
=> 	I have used the following Vue directives in my application :

1)	v-if - To impose  various conditions such as deleting the to-do activity in the to-list only if the user clicked on the delete button, add the activity to the list only when the user clicks on the Add button. 
2)	v-for -  To traverse through various inputted tasks entered by the user and displaying it in the To-Do list.
3)	v-bind – To maintain component connectivity.
4)	v-on -  To listen to various DOM events like onClick etc. 

This allowed for dynamic rendering of components and responsive user interactions.
=> The template syntax was leveraged to construct the application's UI, integrating HTML syntax within Vue templates for straightforward implementation.

=>	Furthermore, I also utilized the following Vue lifecycle hooks to manage component usestates :
1)	– created:  The created hook initialized components, setting up initializations for  smooth operation.

	 
  <b> Ex: Inside App.vue in the script section I have used,
	    const todos_asc = computed(() => todos.value.sort((a,b) =>{
		      return a.createdAt - b.createdAt
      })) 
  
  The above code defines a computed property called `todos_asc`, sorting 	the `todos` array in ascending order based on each todo item's 	`createdAt` property. This guarantees that `todos_asc` consistently 	displays todos in chronological order of creation.
</b>
	
2) Onmounted:  The mounted hook executed actions such as adding and deleting tasks from the list upon button clicks.

  <b>Ex: Inside App.vue in the script section I have used,
		  onMounted(() => {
			  name.value = localStorage.getItem('name') || ''
			  todos.value = JSON.parse(localStorage.getItem('todos')) 		|| []
		  })
  
  In the above code, the `onMounted` hook initializes the `name` and 	`todos` values by retrieving them from the browser's `localStorage`, 	ensuring that the application loads the previously saved `name` and 	`todos` data when the component is mounted. If no data is found, it 	initializes the `name` value to an empty string and `todos` to an empty 	array.

  
      
</b>

3.) -updated:  The updated hook facilitated re-rendering of components, allowing for code execution after DOM updates, crucial for managing user 		actions and maintaining application states.
  
=> Furthermore, I also employed Vue's watch and computed() properties to dynamically react to changes in data and compute derived data 			respectively, enhancing the application's reactivity and efficiency.
	
  <b>
  Ex: Inside App.vue in the script section I have used,
  watch(name, (newVal) => {
	localStorage.setItem('name', newVal)
	})

  
  In the above code, the `watch` function monitors changes to the `name` 	property and updates the corresponding value stored in the browser's 	`localStorage`, ensuring that it reflects the latest value of the `name` 	property .So that everytime when a user enters the to-do item the state 	will be updated and printed accordingly.
</b>


## Referecnes and Citations: ##

1) Tyler Potts. (2022, May 31). Build a Todo List App in Vue JS with LocalStorage in 2022 | Vue 3 for Beginners [Video]. YouTube. https://www.youtube.com/watch?v=qhjxAP1hFuI

2) Traversy Media. (2023, November 8). Vue 3 & Composition API - Full project [Video]. YouTube. https://www.youtube.com/watch?v=hNPwdOZ3qFU

3) Webpack “vue-loader” compilation issues with “@vue/compiler-sfc.” (n.d.). Stack Overflow. https://stackoverflow.com/questions/67399894/webpack-vue-loader-compilation-issues-with-vue-compiler-sfc

4) Creating Vue application: vue create does not work. (n.d.). Stack Overflow. https://stackoverflow.com/questions/50731834/creating-vue-application-vue-create-does-not-work

5) Vue.js. (n.d.). The Progressive JavaScript Framework | Vue.js. https://vuejs.org/

6) Vue.js. (n.d.-b). https://vuejs.org/examples/#simple-component

7) Vue.js. (n.d.-c). https://vuejs.org/examples/#fetching-data

8) Vue.js. (n.d.-d). https://vuejs.org/examples/#grid

9) Vue.js. (n.d.-e). https://vuejs.org/examples/#form-bindings

10) Vue.js. (n.d.-f). https://vuejs.org/examples/#conditionals-and-loops

11) Event handling — Vue.js. (n.d.). https://v2.vuejs.org/v2/guide/events

12) Template Syntax — Vue.js. (n.d.). https://v2.vuejs.org/v2/guide/syntax

13) The Vue instance — vue.js. (n.d.). https://v2.vuejs.org/v2/guide/instance

14) Props — Vue.js. (n.d.). https://v2.vuejs.org/v2/guide/components-props

15) Build software better, together. (n.d.). GitHub. https://github.com/topics/todo-list-project

16) Guylil. (n.d.). GitHub - guylil/todo-list-vuejs: A simple todo list project in vuejs. GitHub. https://github.com/guylil/todo-list-vuejs

17) Mdn. (n.d.). GitHub - mdn/todo-vue: Sample todo app built with the Vue framework. GitHub. https://github.com/mdn/todo-vue

18) Apress. (n.d.). GitHub - Apress/pro-vue-js-2: Source Code for Pro Vue.js 2 by Adam Freeman. GitHub. https://github.com/Apress/pro-vue-js-2

19) https://codepen.io/vuejs-examples/pen/WNYbaqo. (n.d.). CodePen.

20) Vue.js to do. (n.d.). https://codepen.io/jackwalk/post/beginning-vue-js-on-codepen

21) Vue tutorial. (n.d.). https://www.w3schools.com/vue/index.php

22) Vue v-bind Directive. (n.d.). https://www.w3schools.com/vue/ref_v-bind.php

23) Vue lifecycle hooks. (n.d.). https://www.w3schools.com/vue/vue_ref_lifecycle-hooks.php

24) freeCodeCamp.org. (2018, July 2). Learn Vue.js in this free course! ?✨. https://www.freecodecamp.org/news/learn-vue-js-in-our-free-course-85d5df41e47f/



By leveraging these Vue.js components and features, I was able to develop a 	robust and user-friendly To-Do Application, ensuring efficient task management 	for users.
































