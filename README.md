# 🚀 #100DaysOfCode Challenge

Welcome to my journey of #100DaysOfCode! This is where I'll be documenting my daily progress as I grow and improve my skills as a web developer. Over the next 100 days, I'll focus on learning new technologies, honing my coding abilities, and building projects that showcase my development journey.

## Challenge Goals 🎯
- **Primary Goal:** Master JavaScript and become proficient in front-end web development.
- **Secondary Goals:**
  - Goal 1: Build and deploy a personal website using HTML, CSS, and JavaScript.
  - Goal 2: Enhance my JavaScript skills by developing various projects.
  - Goal 3: Learn to implement clean code practices and collaborate effectively in coding environments.

## Daily Log 📅

| Day  | Date       | Summary of Work Done                                                                                 | Links/Notes |
|------|------------|------------------------------------------------------------------------------------------------------|-------------|
| Day 44| 2024-11-07|Optimizing CartProduct Initialization and Updates: Learned how to initialize and update the CartProduct class to manage item-specific details such as amount and pricing in project-pizzeria. This made me more proficient in using class constructors and DOM manipulation to enhance interactivity and maintain a seamless user experience.||
| Day 43| 2024-11-06|Implementing a Quantity Widget for Cart Products: In the project-pizzeria, I added a quantity adjustment widget to the cart items, allowing real-time price recalculations. This experience taught me the importance of encapsulating such functionality within class methods for better code reuse and maintenance.||
| Day 42| 2024-11-05|Enhancing Dynamic Product Handling in project-pizzeria: Worked on refining the Product class to dynamically render menu items and handle product options. This organization enables more modular code, making future updates like customization options easier to implement.||
| Day 41| 2024-11-04|Creating and Updating Class Methods for Cart in project-pizzeria. For project-pizzeria, I focused on improving the Cart class by implementing an add() method to handle new items being added to the cart. This involved generating an HTML element for each item, based on a predefined template, and updating the cart dynamically. By organizing this functionality in the Cart class, I made the code modular and more manageable. This approach will help scale the cart functionality with additional features, like quantity adjustment and item removal, in the future.||
| Day 40| 2024-11-03|Event Handling and Interaction with the Cart in project-pizzeria. In project-pizzeria, I explored handling user interactions by attaching event listeners to elements. Specifically, I added a click event to the `"Add to Cart"` button that triggers the process of adding selected products to the cart. I learned the importance of using addEventListener instead of inline event handlers, as it keeps the JavaScript code separate from HTML, making it more readable and easier to maintain.||
| Day 39| 2024-11-02|Working with Templates and DOM Manipulation in project-pizzeria. Today, in the project-pizzeria project, I worked on dynamically adding items to the cart using JavaScript templates. I learned how to generate HTML content based on data templates and insert it into the DOM. Using innerHTML for HTML generation and appendChild for DOM insertion allowed me to add items to the cart in a structured way. This approach makes it easier to create reusable components and keep the HTML clean.||
| Day 38| 2024-11-01|Today, I learned how to use the `addEventListener()` method in JavaScript to add `events` to HTML elements. This method attaches an event handler to a specific element without overwriting existing events, allowing multiple events on the same element. I explored adding event handlers like `"click"` or `"mouseover"` and saw how it works on various elements, including the window object. I also learned about event propagation (bubbling and capturing) and how to use the `removeEventListener()` method to remove event handlers when needed.||
| Day 37| 2024-10-31|Today, I explored how JavaScript interacts with HTML elements through `events`. I learned that events can trigger JavaScript code in response to `user actions` like clicking, loading a page, or moving the mouse over an element. Key takeaways included using onclick for user clicks, onload for page loading, oninput for updating as the user types, and onchange for validating input fields. These event handlers allow for dynamic, interactive elements on a web page, enhancing user experience by responding to actions in real-time.||
| Day 36| 2024-10-30|Today, I practiced locating HTML elements using JavaScript to enable dynamic interaction with web pages. I explored several methods, including accessing elements by ID (getElementById), tag name (getElementsByTagName), class name (getElementsByClassName), CSS selectors (querySelectorAll), and HTML object collections like forms. Each method offers a unique way to target and manipulate specific HTML elements, building the foundation for creating interactive, responsive websites.|https://www.w3schools.com|
| Day 35| 2024-10-29|Today, I learned how to make a restaurant website with important sections like a Hero section, About Us, Menu, and Contact & Reservation form. I used HTML for building the layout, CSS for design, and JavaScript for adding interactive features. I also explored options to let customers book tables, order takeaway, and pay online.|https://www.w3schools.com /howto/howto_website_restaurant.asp|
| Day 34| 2024-10-28|Today, I practiced using `AJAX` to handle server responses with `XMLHttpRequest`. I explored two main properties: `responseText`, which receives the server's response as a simple text string, and `responseXML`, which parses XML data directly into a DOM object. Additionally, I learned about the `getAllResponseHeaders()` method, which retrieves all server response headers, and `getResponseHeader()`, which can fetch specific header details.|https://www.w3schools.com /js/js_ajax_http_response.asp|
| Day 33| 2024-10-27|Today, I explored `AJAX` basics using the `XMLHttpRequest` object, which helps web pages interact with servers without needing a full page reload. I learned how to set up both `GET (for getting data)` and `POST (for sending data)` requests, and the differences between synchronous (which pauses JavaScript until done) and asynchronous (non-blocking) requests. Also, I practiced handling data securely and efficiently, such as preventing cached responses by adding a unique ID to each request.|https://www.w3schools.com|
| Day 32| 2024-10-26|Today, I Learned `fetch API` for server requests in JavaScript, covering HTTP methods, Promises with `.then()` chaining, error handling with `.catch()`, and options like headers and JSON payloads for data exchange; now familiar with robust API interactions and handling both client-side and server-side errors.|https://poradnik-js.kodilla.com/ajax-fetch|
| Day 31| 2024-10-25|Today, I enhanced the `Project Pizzeria` application by integrating event handling and data validation within the AmountWidget class. I updated the setValue method to validate and restrict the input values based on predefined settings. Additionally, I created and emitted a custom event (updated) to notify other components when the widget’s value changes. This required adding event listeners to the `Product` class to ensure that the changes triggered the processOrder method. These updates improve the app’s responsiveness and accuracy.||
| Day 30| 2024-10-24|Today, I made significant advancements in `Project-Pizzeria` by refining `the Product and AmountWidget classes`. I added methods to handle widget events, such as changing, increasing, and decreasing values. Additionally, I integrated validation within the setValue method, ensuring that quantities remain within set boundaries (defaultMin and defaultMax). Debugging and testing DOM queries were also part of today's work, which helped me ensure the proper functioning and smooth interaction of the amount widget with the product component.||
| Day 29| 2024-10-23|Today, I explored the two main ways to include JavaScript in HTML: using an external script file and inline scripts within HTML. The recommended approach is linking an external file with the `<script> tag`, which ensures better organization and separation of concerns. Inline scripts, wrapped directly in the `<script> tag within HTML`, should only be used when using an external file isn’t possible. Understanding these methods helps in structuring code efficiently and maintaining clean, manageable projects.||
| Day 28| 2024-10-22|Today, I deepened my understanding of JavaScript `functions`. I practiced different types of functions like named, anonymous, and arrow functions. I explored function declaration, calling functions with arguments, default values, and the use of the return statement. I also learned about anonymous functions for event handlers and how to structure functions within objects for better code organization. Arrow functions stood out for their concise syntax and different handling of this, making them useful in specific scenarios like maintaining context in event handlers.|https://poradnik-js.kodilla.com/functions|
| Day 27| 2024-10-21|Today, I focused on learning different types of `loops` in JavaScript, including for, for...in, for...of, while, and do...while. I practiced using each loop type with examples, understanding when and how to use them effectively. I learned the specific scenarios for each loop type, such as iterating over arrays, objects, or repeating actions until a condition is met. Additionally, I explored the differences between while and do...while loops, especially how the latter guarantees at least one execution.|https://poradnik-js.kodilla.com/loops|
| Day 26| 2024-10-20|Today, I learned about the `conditional (ternary) operator` and how it acts as a shorthand for simple `if-else` statements. Additionally, I explored the `switch` statement as an alternative to complex if...else conditions. It helps evaluate multiple conditions and execute the corresponding code block based on matches. I practiced using switch with examples, understanding how cases, the break statement, and the optional default case work to manage different outcomes effectively.|https://poradnik-js.kodilla.com|
| Day 25| 2024-10-19|Today, I deepened my understanding of `arrays` in JavaScript. I learned how arrays store multiple values and how to access them using indices, which start at zero. I practiced adding elements with push, finding elements using indexOf, and removing elements with splice. I also explored how to generate strings from arrays using join and split strings back into arrays with split. Additionally, I experimented with loops (for and for...of) to iterate through arrays and handle multi-dimensional arrays for complex data structures.|https://poradnik-js.kodilla.com|
| Day 24| 2024-10-18|Today, I explored the concept of `classes` in JavaScript. Classes serve as blueprints for creating objects (instances) that share common properties and methods. I learned how to define a class using the class keyword and initialize instances with a constructor method. I also practiced using the this keyword to assign and access properties within methods. Additionally, I understood how to create methods like calculateMonthlySalary and showDetails that interact with these properties. I applied these concepts by building instances, modifying their attributes, and verifying the changes through console logs.|              | 
| Day 23| 2024-10-17|Today, I wrote the `README` file for the `Project Pizzeria`. The file includes essential project details such as: `1` - A brief description of the project. `2` - Usage instructions to guide users on how to interact with the menu, customize pizzas, and place an order. `3` - Information about the license (MIT License) under which the project is available. This process helped me improve my skills in writing clear and concise documentation, ensuring that users can easily understand and navigate the project.|          |
| Day 22| 2024-10-16|Today, I spent time learning more about JavaScript best practices. I reinforced concepts like naming conventions, such as using camelCase, and the importance of keeping code clean with proper spacing, indentation, and semicolons. I also explored the benefits of enabling `'use strict'` mode for better error handling. Additionally, I focused on understanding reserved words in JavaScript and ensuring they aren’t used as variable names. These practices help improve code readability, reduce errors, and follow JavaScript conventions. |https://poradnik-js.kodilla.com     |
| Day 21| 2024-10-15|I have completed the pizza project and spent time analyzing the code and functions. I focused on understanding how the `DOM` (Document Object Model) works, which represents the structure of a webpage as objects. I learned that when making changes with JavaScript, those changes happen `in the DOM`, `not` directly in the `HTML`. I used methods like getElementById, querySelector, and querySelectorAll to interact with elements in the DOM, helping me navigate and modify the content dynamically based on user interactions. This deepened my understanding of JavaScript and DOM manipulation.|https://poradnik-js.kodilla.com/target-dom-elements             |
| Day 20| 2024-10-14|Today, I further refined the `processOrder()` function by adding specific logic for handling product options like olives, mushrooms, and salami. These ingredients are now dynamically reflected in the total price and visibility of their corresponding images. By properly associating each option with its respective image and price adjustment, I improved both the user interface and functionality of the menu selection. This task helped solidify my understanding of `DOM` manipulation, conditional logic, and how to handle multiple dynamic UI elements based on user input.|              |
| Day 19| 2024-10-13|In today's lectures on `Software Engineering Fundamentals` and `Information Systems`, I learned the basics of how software is designed and developed. We discussed the stages of software development, like planning, design, coding, testing, and maintenance. I also learned about Information Systems, which help manage and process data in organizations. This includes understanding how systems like databases, hardware, and software work together to support business functions. These topics provide the foundation for building and managing technology systems effectively.|              |
| Day 18| 2024-10-12|Today, I attended lectures on `Computer Networks` and `Physics`. In the computer networks session, I focused on learning about the structure of the internet, protocols, and how data is transmitted across networks. I also explored the different types of network architectures and their functionalities. In physics, I reviewed key concepts such as force, motion, and energy, enhancing my understanding of fundamental physical principles. These topics helped me connect theoretical knowledge with practical applications in technology and science.|              |
| Day 17| 2024-10-11|Today, I implemented the `processOrder` method into the Product class for the `project-pizzeria`. These changes added the ability to dynamically calculate the product price based on user-selected options and ensured the order form is fully interactive. I tested these functionalities thoroughly and confirmed that all updates were successfully integrated into the overall project structure. This was a significant step forward in building a dynamic menu and cart system for the pizzeria.|              |
| Day 16| 2024-10-10|Today, I expanded my knowledge on the `DOM` by using additional properties and methods, such as `document.cookie`, `document.domain`, and `document.lastModified`. I practiced accessing elements through `getElementsByName()` and `getElementById()`, and explored the structure of the `DOM Tree`. I also looked into methods like `document.write()` and `document.close()`, understanding how they manipulate HTML content directly. This experience enhanced my familiarity with how the browser represents and interacts with HTML documents programmatically.|              |
| Day 15| 2024-10-09|Today, I deepened my understanding of various tools for debugging and manipulating the `DOM` in JavaScript. I explored the usage of `console.log` and the debugger statement for step-by-step code inspection. Additionally, I utilized the Elements tab in the browser's Developer Tools to inspect and modify the HTML structure dynamically. I also explored the JavaScript Snippets feature for testing small code blocks in the browser context. This hands-on approach improved my ability to troubleshoot and interact with the DOM effectively.|              |
| Day 14| 2024-10-08| Today, I focused on adding new functionality to the Product class in the `project-pizzeria`. I successfully implemented the `getElements` method to organize element selection and created the `initAccordion` method for managing product panel interactions. Additionally, I set up the `initOrderForm` method to handle form submissions and changes, ensuring that product options dynamically update. These methods were added to the constructor, improving the structure and readability of the code. Overall, this task deepened my understanding of class methods and event handling in JavaScript.|             |
| Day 13| 2024-10-07| Today, I implemented the Product class for the project. I learned how to structure a class in JavaScript using the constructor to initialize properties and handle individual product instances. I also integrated the Product class into the existing application flow, ensuring that the class works with the dynamic data. Additionally, I improved my understanding of how to pass data into class instances and manage them effectively. This step was foundational for expanding functionality and making the project more maintainable.|             |
| Day 12| 2024-10-06| Today, I started a new project called project-pizzeria using Git and NPM. I set up the initial project structure, created necessary files, and configured the build and testing workflows using various tools like eslint, stylelint, and sass. I learned how to properly structure a project using NPM scripts, automate tasks like building, testing, and watching file changes, and manage dependencies effectively. This setup has helped me understand how task runners work and improved my project organization skills.|             |
| Day 11| 2024-10-05| Today, I focused on JavaScript classes and learned how they act as blueprints for creating objects. Using class, I defined properties and methods for objects. The constructor method initializes new objects, and the this keyword allows each instance to manage its own data. I practiced creating multiple instances and modifying their properties without affecting others. This showed me how to use classes for code organization and flexibility, making it easier to manage complex data structures in applications.|https://poradnik-js.kodilla.com|
| Day 10| 2024-10-04| I learned how to dynamically render content using Handlebars, implemented Object-Oriented Programming (OOP) concepts, set up npm for task automation, integrated Sass for styling, resolved ESLint configuration issues, and managed Git version control, which provided insights into organizing and debugging real-world web applications efficiently.             |
| Day 9| 2024-10-03| Continuing my learning, I focused on object-oriented programming (OOP) concepts in JavaScript. I started by exploring the idea of objects and classes, understanding how they help organize code and create reusable components. I learned how to use constructors to create multiple instances of objects with shared properties and methods. Next, I studied inheritance, which allows one class to extend another, passing down properties and behaviors to child classes. I also explored the super keyword to access and modify parent class properties. Additionally, I practiced using encapsulation, using private and public methods to control how data is accessed and modified. This helps create more secure and maintainable code. Finally, I reviewed the concept of polymorphism, which allows methods in different classes to have the same name but behave differently based on the class context. Overall, these OOP concepts will be crucial for building more structured and scalable applications in my new project.||
| Day 8| 2024-10-02 | I’m starting a new project and have learned some key concepts. First, I understood the difference between simple and complex data types and how they are handled in code. I also explored how functions work when using different data types and the impact this has on the original values. I learned about the this keyword, which changes its behavior depending on the context. Additionally, I discovered methods to control the this context in different situations. Overall, I gained a better understanding of how JavaScript manages data and memory to make programs more efficient.|             |
| Day 7| 2024-10-01 | Project Summary: JavaScript Blog - Throughout this project, I worked on building a dynamic blog using JavaScript and Handlebars.js. I successfully integrated Handlebars templates to generate HTML elements dynamically and learned how to manage user interactions such as filtering articles by tags and authors. Additionally, I tackled challenges with Git version management, using commands like rebase and merge to handle conflicts. I also improved code quality by configuring ESLint and addressing indentation and syntax errors. This experience enhanced my understanding of modular JavaScript structure, templating, and documentation using Markdown.|             |
| Day 6| 2024-09-30 | Today, I learned several important lessons about working with Git, resolving conflicts, and project management. First, I reverted to an earlier stable version because the current state was too problematic. After modifying the code and attempting to push it to GitHub, I encountered issues due to conflicts between my local changes and the remote repository. I learned how to use strategies like git pull --rebase and manually resolving merge conflicts to ensure a smooth integration. This experience emphasized the importance of maintaining version history and understanding Git commands thoroughly.|             |
| Day 5| 2024-09-29 | Today, I focused on configuring `Prettier` and `ESLint` to maintain consistent code styling and improve readability. I explored how specific settings in Prettier, such as using single quotes, enforcing semicolons, and trailing commas, impact code formatting. Additionally, I learned to customize ESLint rules to support modern JavaScript (ES6) while allowing for browser-specific globals. I also experimented with disabling and modifying ESLint rules like no-console and quotes, to adapt them to my coding needs. This process helped me understand how these tools work together to create a streamlined development experience.|             |
| Day 4| 2024-09-28 | Today I focused on enhancing my skills in both HTML and JavaScript. I worked extensively on refactoring the structure of HTML to improve readability and maintainability, specifically updating the data attributes and reorganizing the hierarchy of elements in the sidebar. In JavaScript, I deepened my understanding of DOM manipulation and event handling by refining functions such as generateTitleLinks, generateTags, and generateAuthors. I also tackled logical errors in event handlers and fixed variable scope issues. This session helped solidify my knowledge of code modularization and debugging.|             |                                                                                                     
| Day 3| 2024-09-27 | Today, I enhanced my JavaScript skills by refactoring the generateTags function and learning how to work efficiently with objects and arrays. I implemented a new calculateTagsParams function to dynamically analyze tag frequency and adjust styles accordingly. Additionally, I improved event listeners for both tags and authors, ensuring a smooth user experience when filtering articles.|             |
| Day 2| 2024-09-26 | Today, I refactored the `generateTags` function to eliminate duplicate code and improve efficiency. I also fixed event listener bindings for both tags and authors, ensuring proper interaction when filtering articles. The `titleClickHandler` function was enhanced for better link activation and article display management. I successfully tested the dynamic tag and author filtering system. |             |
| Day 1| 2024-09-25 | Today, I set the foundation for my #100DaysOfCode challenge by working on JavaScript basics and setting up my development environment. I configured essential tools like Git for version control and ESLint for code quality. I also began working on a dynamic blog project where tags and authors are generated from data-attributes, ensuring cleaner HTML. Additionally, I learned how to manage dependencies using NPM and practiced integrating Prettier for code formatting. | [Link to code/project] |

## Milestones 🏆

| Milestone | Target Date | Status       | Details                                                                                          |
|-----------|-------------|--------------|--------------------------------------------------------------------------------------------------|
| Milestone 1| 2024-10-10  | In Progress  | Build a personal website using JavaScript, HTML, and CSS                                          |
| Milestone 2| 2024-11-05  | In Progress  | Complete three JavaScript projects                                                               |

## Tools & Resources 🛠️

- [VS Code](https://code.visualstudio.com/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [JavaScript Info](https://javascript.info/)
- ESLint, Prettier, Git

## Reflections 💭

Here I will share any major takeaways, reflections, or thoughts as I progress through the challenge.

---

_Started on 25/09/2024_  
You can follow my journey on GitHub, Twitter, etc.
