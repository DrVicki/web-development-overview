# Web Development 

The web development program overview will provide details of what’s involved’, and list all the “need to know” topics. 
 
This document covers the fundamentals. Web development can get much more complicated than this. The additional skills and knowledge you need will vary for each project / job. 
 
## How to use this guide? 

This guide is divided into 7 sections. Each one covers a major component of web development and the fundamental topics you should learn. Each topic is accompanied by detailed instructions and explains its importance.  
 
If you already have an idea of what web development is, you can skip ahead and go straight to the topic you want to read about. 
 
## What is web development? 

Web development is building websites and web applications like Facebook, Twitter, or internal web portals within businesses. Web development has two disciplines: front-end and back-end. 
 
Front-end is visual and interactive aspects of a website. You will learn HTML, CSS and JavaScript to master Front-end web development. 
 
Back-end is all the logic behind the scenes which supports your website: databases, user management, etc. You will need learn the following back-end language and framework: 
 
●	Node.js (JavaScript but for backend; used by many startups) 

You will learn about database, model-view-controller, testing. 
 
You will build a unique full-stack project, Capstone project, and even learn how to deploy your project so it's live and accessible on the Internet. 
Table of Contents  
 
●	HTML & CSS - Content, layout, and styling of web page 

●	JavaScript Programming - Programming language of the web 

●	Dynamic Website Development - Make a web page interactive and do things 

●	ReactJS Development - Learn to develop components and single page apps in React 

●	Node.JS for Back-End Development

●	Back-end Development - Storing and manipulating data permanently 

●	Full-stack Deployment - Get a full-stack web application up and running 

●	Capstone Portfolio Project - Build a full-stack application you are proud of 
 	 
## HTML & CSS

Content, layout, and styling of web page. 
 
### What is HTML and CSS? 

To understand what HTML and CSS are, we need to understand the process of viewing a website. When we enter a website’s address on a browser, a request is sent to a computer, usually referred to as a web server, somewhere in the world. 
 
This web server then sends a bunch of files back to our browser. Our browser renders these files into human readable content that we commonly call a website. These files are usually HTML and CSS files. 
 
When you are looking at a website, like Facebook, you are looking at a newspaper, or more precisely an animated and interactive newspaper. 
 
A web developer defines a website’s content using HTML (Hyper Text Markup Language). You can add structural meaning to content using HTML tags, such as headings, paragraphs, lists, links, and media items such as images, videos or even embed other websites. 
 
The first website mainly consisted of plain text and links. It had no styles, such as colors, fonts and positioning. You can check out a [brief history of the World Wide Web by W3C](https://www.w3.org/History.html). 
 
A website with merely plain text would be boring and indifferent, so websites are dressed up with styles. A developer defines a website’s styles with CSS (Cascading Style Sheet). 
 
CSS allows you to specify the exact styling at the exact place on your website, so you can make it look the way you want. Just to name a few, you can specify the following styles of a website with CSS: 
 
●	Position of any content 

●	Spacing between content, borders 

●	Font style, color, weight, size of text 

●	Backgrounds 
 
With HTML and CSS, you can make a good-looking static website, just like how you can make a good-looking image with photoshop. Static websites are not interactive, and their contents don’t dynamically change (i.e., no matter what you do to a newspaper, its content cannot dynamically change, you will not get a live feed of the stock index prices on a print newspaper). 
 
We have divided the fundamental topics and concepts you will learn into multiple parts. 
 
* Part 1: Intro to HTML and CSS*

* Part 2: HTML Fundamentals 

* Part 3: CSS Fundamentals 

* Part 4: Positioning 

* Part 5: Bootstrap 3 

* Part 6: Advanced CSS and Bootstrap 4 

* Part 7: Development Cycle with Git 

* Part 8: HTML CSS Project 

* Part 9: Deploying Basic HTML CSS Website 
 
### Part 1: Intro to HTML and CSS 

You will learn how to write basic HTML and CSS, install and use a code editor, create and view a bare bone website locally on your computer. 
 
●	HTML and CSS syntax - Like grammar in spoken languages, each computer language has their own syntax. Syntax is a set of rules that you must follow when you write code, otherwise the computer cannot understand your instructions. You will learn the syntax for HTML and CSS. 

●	HTML elements - Elements are the basic building blocks of HTML. Each element represents a certain content type. Elements are defined using HTML tags. HTML elements give meaning to your content as well as help you organize it. 

●	HTML document structure - HTML documents have a standard structure you need to follow otherwise browsers won’t be able to read, process, and render it properly. You will learn what this structure is and adhere to it. 

●	CSS selectors, properties, and values - CSS can target specific elements in HTML	 and apply styles to it. To do this, you need to specify a selector, choose the correct property and define its property value. Selectors do the targeting, properties and values do the styling. 

●	Where to write CSS - You can write inline CSS directly on HTML elements, inside a style element, or in a separate dedicated CSS file. You will learn know how to write CSS in all three ways and how to connect CSS files with HTML files. 

●	Code commenting in HTML and CSS - Comments are not interpreted by the browser so they don't get rendered for the user to see when they are looking at your website. You  can use comments to leave commentary in your source code and help you compartmentalize sections of code.

●	Pick a code editor - When working on HTML and CSS files locally on your computer,	 you will learn to use a text editor. Your efficiency can be greatly improved if you use a text editor designed for coding. We recommend  [Visual Studio Code](https://code.visualstudio.com/). 

●	Build your first web page - Create a simple webpage with a heading using one HTML file and one CSS file and view it with a web browser. You will learn to do this correctly and your HTML and CSS files are connected and syntax error free. 

●	Get familiar with browser DevTool - Most modern web browsers will have developer tools which aids developers in website development. You should get familiar with the devtool of your browser. If you don’t know which browser to choose, we recommend Google Chrome. 
 
### Part 2: HTML Fundamentals 

Learn about different types of HTML elements and the semantic meaning they carry. Adopt best practices for writing HTML to keep your code clean and readable. 
 
●	Semantics of HTML - Most HTML elements carry semantic values. Semantic values are used by screen readers and search engines to make sense of what the content represents, such as using the `<address>` element for addresses, or the `<h1>` element for primary heading. Using correct semantic elements can potentially improve your search engine ranking. 

●	Block and inline elements - Most HTML elements are either block or inline elements. 

Block elements always start on a new line and span the full width of its parent element. 

Inline elements can stack horizontally since they only take up the width of their content. You will understand thoroughly the difference between block and inline elements, so you know when to use which. 

●	Nesting of elements - You will learn how to nest elements within elements, it is often used to create complex layout structures. 

●	Text elements - Text elements are used to contain text content. You will learn about the six heading elements, the paragraph element, and inline elements such as strong and emphasize. Text elements are the bread and butter of most informational websites. 

●	Structure elements - Structure elements are used to break up an HTML page into compartments so search engines understand the structure better. Learn about `header`, `nav`, `articles`, `sections`, `aside` and `footer`. Those carry semantic values and should be used to layout your HTML file. 

●	Hyperlinks - Hyperlink, or anchor tag, is an element which links to another file, page, or website. You will use it to build connections between pages of your website. It is what search engines will use to map out the relationship between pages of your website, and even relationships between different websites. 

●	Lists - Unordered and ordered lists are used to create lists in HTML. You will learn the structures. 

●	Image, video, audio elements - You can add media content to a web page by using image, video, and audio HTML elements. Each of them has their own set of attributes you can use for fine tuning. 

●	Iframe elements - Iframe elements are used to embed and render other websites. Think of it like screen within screen on TV. It is often used to embed services provided by third parties, such as map, forms, booking management, etc. 

●	Tables - Tables are used for, well tables. This element requires the use of multiple HTML elements and can be a bit confusing at first. 

●	Forms - Forms are the predominant way to retrieve information from users. You will learn about form, input, textarea, select, and button element. 

●	HTML best practices - Just getting the syntax right doesn’t mean your code will be clean and easy to read. Just like knowing how to spell and form sentences doesn’t mean your handwriting is legible or you can write wonderful novels. It is important to adapt a good set of best practices for writing HTML. These are usually called style guides and you can find many popular ones by searching. 

●	Create a basic multi page website - At this point, you should try to create a multi-page website with multiple three to four HTML files. Use hyperlinks to connect each HTML file. Launch the website on your browser and make sure you can access all pages. Keep the content minimal. 
 
### Part 3: CSS Fundamentals  

Get familiar with the cascading effect of CSS and learn how to combine selectors to target HTML elements you want to style. Learn basic CSS style properties for typography and background. 
 
●	Cascading effect - CSS stands for Cascading Style Sheet. Cascading means CSS code is read and processed from top to bottom. You will learn how this affects your CSS code.

●	Specificity - CSS selectors, used for targeting HTML elements, each carry a specificity weight. Selectors with higher specificity will get to render their styles, while styles from selectors with lower specificity will be ignored. 

●	Combining and layering selectors - You can combine different types of selectors, namely `Type`, `Class`, and `Id`, for HTML targeting. You will learn how to calculate the specificity from combined selectors. You can leverage this to write efficient, modularized CSS. 

●	Advanced selectors - You will learn how to use pseudo-classes, such as: `hover`,: `focus`, :`first`, and attribute selectors to effectively target elements. As an example, the selector `path-child(odd)` will let you target and apply styles to all odd numbered paragraph elements. 
`
●	Colors - Colors are used in defining font colors, border colors, background colors and box shadow colors. You will learn how to define colors using color keywords, e.g. `blue`, `white`, `black`; hexadecimal code, e.g. `#fff`, `#678998`; `rgb()`, `rgba()` functions; and `hsl()`, `hsla()` functions. 

●	Lengths - Length is used to define the size and position of things. It is used for font size, height, width, padding, margin and many more size and position properties. You will  learn about absolute lengths, e.g., `pixel`, `points`, `cm`, `mm`, `inch`; and relative lengths, e.g. percentage (`%`), `em`, `rem`, `vh`, `vw`. 

●	Typography - Most websites are for serving information, text styling is therefore a large part of front-end development. You will learn how to use common CSS typography properties. These properties deal with text and are categorized into font- and text-. Common ones include `font-family`, `font-size`, `font-weight`, `text-align`, `text-decoration`, `text-transform`, `letter-spacing`, `word-spacing`. 

●	Backgrounds and gradients - Learn how to add background colors and background images to elements. Be able to position and repeat background images. Learn how to add gradient color backgrounds. 

●	CSS resets - Every browser has their own set of default styles for rendering HTML. To	 tackle this cross-browser consistency issue, we can use CSS resets. A CSS reset is a set of CSS rules that strips or tones down the styles of each HTML element, setting a consistent base for us to work on. 

●	CSS best practices - Adapt a good style guide for writing clean CSS. Learn to name your class and id selectors effectively. This is very important for writing CSS that can be easily understood by fellow developers. 
 
## Part 4: Positioning 

Content of a webpage can be laid out for better design and user experience. To do this effectively, you need to understand the box model, position elements using different methods, and be able to create simple grid structures. 
 
●	The box model - All HTML elements are basically rectangular boxes made up of content, `padding`, `border`, and `margin`. You will be able to understand the real size of an element based on the dimensions of each component, and to adjust the size of each component. This is important for creating spacing around elements and for aesthetics. 

●	Positioning with floats - Float is a CSS property which lets you position an element to either the left or right of its parent element. It is a very old technique, but it is a hardy one.  When using floats, you need to take care of clearing the float.

●	Positioning with inline-blocks - An inline-block element is a cross between a block element and an inline element. You can set elements to inline block so they will stack horizontally one after the other. This is the preferred method for creating horizontal column structures for the last decade. 

●	Creating a grid structure - You will learn how to create reusable grid structures using classes that define columns of different widths. This is important for creating structure layouts very quickly. 

●	Precise Positioning - Learn how to fine tune the position of elements using the position property and its three values, `relative`, `absolute`, and `fixed`. 

### Basic website clone - At this point, you should have enough knowledge to try to build a simple website. Instead of coming up with something of your own, you will learn more by trying to clone someone else’s website. Pick a website that is simple in design and consists of mostly static content. Do it a couple times until you are ready to move on. 
 
## Part 5: Bootstrap 3 

Bootstrap is a CSS framework which helps front-end web developers add style and structure to websites very quickly. Bootstrap provides a set of standards in spacing, typography, color, interactive behaviors, and more. 
 
Bootstrap 3 was released in 2013 and has remained popular to this day. 15% of the top 100 thousand most visited websites are built with Bootstrap. Even though a new version, Bootstrap 4, was released in 2017, it is worth learning Bootstrap 3 as many companies still use it. 
 
●	Installation - There are multiple ways to add Bootstrap in a project. The easiest way is to link to Bootstrap’s official CDN (content delivery network) and let the CDN handle serving Bootstrap’s CSS file to the clients. The other way is to install Bootstrap locally into your project. This is useful if you are working without internet. You will learn the pros and cons of each method. 

●	Responsive grid system - Probably Bootstrap’s most popular feature is its grid system.  You need to know it well enough to create complex nested grid structures with ease. This is used to create responsive layout for web content very quickly. Responsive layout means the layout will change based on the screen size of the viewing device. 

●	Bootstrap's style standards - Bootstrap comes with a standardized set of styles for typography, colors, buttons, forms, tables, images and more. It also has a large selection of helper classes that lets you add predefined styles to elements. You will gain a good command of these styles and classes. 

●	Responsive CSS - You will learn how to write CSS effective only on specific screen width ranges. This is called responsive CSS and it is how Bootstrap’s responsive grid is made. Knowing this will allow you to create custom responsive styles for web pages. 

●	Responsive development with browser devTools - When working on responsive CSS, it would be useful to quickly view the result on screen sizes of different devices. Most web browser devtools will have a device mode that lets you do exactly this. Use this feature to increase your efficiency. 

●	Responsive website clone - Equipped with Bootstrap 3, you should try to build a responsive webpage. Pick a couple simple responsive pages to clone. 
 
## Part 6: Advanced CSS and Bootstrap 4 

At this point, you should have a good foundation of the basics. So, it’s time to move on to more advanced CSS. Learn how to modify the shape and position of elements using transform and create simple state transitions and animations. 
 
It is also a great opportunity to learn the new CSS flexbox module which lets developers create flexible layouts. This will set you up for Bootstrap 4 which has a revamped grid structure based on flexbox. 
 
●	Transform - Transform is a CSS property capable of distorting and moving a HTML element. Learn how to use `scale`, `skew`, `rotate`, and `translate`. 

●	Transition - The CSS transition property is used to add transition effects during element state changes. Elements change states when they are `hovered`, `focused`, or `active`, such as making a link change color when the mouse is hovering it. You will learn how to write basic transitions and understand the difference between each transition timing function. 

●	Animation - You can create animations using the CSS `animatio`n property. Although animations are generally frowned upon, you will at least know how it works. 

●	Flexbox - Flexbox is a CSS module which lets you create flexible layout structures. It is super convenient and a must learn for the modern developer. You will understand the relationship between a flex container and its flex items; flex container properties such as flex-direction, flex wrap, justify-content, align-items; flex item properties such as order, flex-grow, flex-shrink, flex-basis. 
●	Bootstrap 4 - Bootstrap 4 was released in 2017 and the team rewrote the grid structure from the ground up using CSS flexbox. Bootstrap 4 is super fun to use, and it has a new set of helper classes that you can use for margin, padding, border, backgrounds, flex behavior. Be sure to learn about the major changes in Bootstrap 4. Which includes a new responsive breakpoint for extra-large devices. 
●	Responsive website clone - Clone a couple more complex web pages using Bootstrap 4. I suggest Airbnb as its grid structure is very similar to Bootstrap. Make sure your clone is responsive too. 
 
Part 7: Development Cycle with Git 
When working on projects which involve multiple developers, version control becomes super important. Version control is the management of versions. In a web dev project, a new version is created whenever someone edits part of a project. 
 
A version control system will let you review new changes before it is deployed live. It will also let you revert to a previous working version when you discover an unforeseen software bug in the live site. 
 
The most popular version control tool is Git, and you should learn how to use it. You should also learn how to command your computer through the command line interface, as it is paramount when it comes to deploying your projects. 
 
●	Command line interface - Command line interface is a text-based interface you can use to command your computer. Learn to navigate folder structures; create, move, delete files and folders. You need to know this well to use Git. 
●	Track versions with Git - Git is a version control system. It means that if you are editing a project, you can save a version of the project as snapshot. It is also very useful for managing projects with multiple contributors. You will understand the Git lifecycle, from initiation to committing changes. 
●	Cloud storage with GitHub - Just like backing up your photos to Google drive or iCloud, developers back up their project to third party storage services like GitHub. GitHub is also a project management tool that offers issue tracking, code reviews, and project collaboration. 
 
Part 8: HTML CSS Project 
To further solidify all the skills you learned, you will come up with a simple website idea and build it out. If you don’t know what to build, consider creating your personal portfolio page. Use a CSS framework and track your project with Git. Try to achieve the following in your website. 
 
●	Has a navigation bar, a main content section, and a footer 
●	Has at least two pages 
●	Design is mobile responsive 
 
Part 9: Deploying Basic HTML CSS Website 
You should know how to host your simple HTML CSS websites on third party services so people can access it. For a basic website to work, you simply need a dedicated computer that will listen for requests to serve the corresponding HTML CSS files. 
 
Many web hosting services offer free hosting for static file websites, that is websites that only consist of static files, such as HTML, CSS, JavaScript, and images. But you will be restricted to a subdomain. Getting a custom domain will usually cost you 8 to 10 USD a month. Below are some free services to host your HTML CSS projects. 
 
●	GitHub Pages (https://pages.github.com/) - GitHub offers one free site for each project. You just need to activate it in your project settings. 
●	Netlify (https://www.netlify.com/) - Netlify is a simple to use static web project hosting service. You just need to drag your project folder onto the browser to upload the deploy your projects. 
●	Neocities (https://neocities.org/) - Also an easy-to-use web hosting site that offers free static file hosting with a subdomain of your choice. 
 	  
JavaScript Programming 
Programming language of the web 
 
What is JavaScript? 
We have already established HTML and CSS can build static websites. But if we want to have dynamic content, such as a live feed of stock prices, or live chat, the browser needs to be able to get the data and inject it without refreshing the page. It needs a programming language for executing tasks. 
 
JavaScript is the programming language for websites. It was initially designed as the ‘glue’ to 
HTML so web developers could assemble components such as images and plugins. Since then, JavaScript has been getting more and more powerful in the tasks it can perform on the browser. 
 
JavaScript enables developers to create interactive functions, such as live polls and games, and build web applications, such as accounting and budgeting apps. Pretty much anything you can write in a program; you can do it on a web page with JavaScript. 
 
To fully utilize JavaScript on a website, you first need to learn how to program in JavaScript. The parts below cover all the fundamental topics for programming in JavaScript. Having a good understanding of the following will help you make the connection between JavaScript and HTML CSS much smoother. 
 
Part 1: Intro to JavaScript 
Part 2: Basic Program Structure 
Part 3: Function Fundamentals 
Part 4: Object Data Structure 
Part 5: Advanced Function Concepts 
Part 6: Advanced Object Concepts 
Part 7: Bonus Concepts 
Part 8: JavaScript Project 
 
Part 1: Intro to JavaScript 
Get a sense of the basic building blocks of programming in JavaScript. You will learn about values and types, some simple arithmetic, and comparison operators, how to create variables, and where to write and test your JavaScript programs. 
 
●	Values and Types - Programming is mostly for dealing with data. There are six basic types of data values in JavaScript. You will learn the most basic four first. Numbers, strings, Booleans, and undefined values. 
●	Operators - Operators are used to combine, compare, and manipulate data values. Learn to use arithmetic operators such as +, -, *, /, %; comparison operators such as <, <=, ===, !==, >, >=; logical operators such as &&, ||, !. You also will learn the automatic type conversion that happens in JavaScript operators, which can lead to unintuitive outputs. 
●	Variables - Variables are used to temporarily store values, so we can reuse them at different stages of a program. For example, when you are counting in your head, you keep check of the current count and continue to add numbers to it. In JavaScript, you create a variable to do this. Learn how to create new variables; assign and re-assign values to variables; use variable update shortcuts such as -=, +=, ++, --; and variable naming conventions in JavaScript. 
●	Where to write and test JavaScript - To improve, you need to practice. The most accessible resource for you to write and test JavaScript programs is to use the browser devTool JavaScript console. Most browser’s that have a devTool suite will have a JavaScript console. It works when you don’t have internet connection too. If you want something more sophisticated, check out online coding environments such as repl.it. It offers a side by side view of a text editor and a JavaScript console for you to write and test your code. 
 
Part 2: Basic Program Structure 
You will learn about the basic constituents of JavaScript programs; how to write simple programs, conditional statements, loops, and switch statements. You also need to follow a good syntax guide and learn how to add comments to programs. 
 
●	Statements, expressions, and programs - An expression is a fragment of code. While	 a statement is a line of expression(s) with a semicolon after it. A program is simply a collection of statements. Understand the difference between the three and learn about the straight control flow of JavaScript programs. 
●	Conditional statements - When you want to execute some code only on certain conditions, you will need to use conditional statements. For example, the alarm should only sound on Sundays. Learn to use if, else, else if conditional statements with comparison expressions to create basic programs. 
●	Loops - Loops are very common in programming. It is used when we want to repeat the execution of some tasks. There are three basic types of loops in JavaScript, while, do, and for. Each has their own syntax and quirks. You also will learn how to conditionally break out of a loop. 
●	Switch - A switch statement is a special construct that lets you write easier to read conditional statements. You can use switch statements to replace lengthy and convoluted if/else statements. 
●	Syntax guide and commenting - Following a good set of best practice for JavaScript	 syntax will keep your code consistent and easy to read. Which makes bug finding a lot easier. You also will learn how to add comments to your code so you can leave reminders or explanations. 
 
Part 3: Function Fundamentals 
A function can be thought of as a machine that performs a specific task. Such as make sandwich. Every time you want a sandwich to be made, you just must turn on the machine; or execute the function, as programmers would say. 
 
Functions are important in programming because it allows programmers to dissect parts of the program where the same task is carried out repeatedly. 
 
Instead of repeating all the instructions to make a sandwich. The programmer can pack all the instructions inside a function, call it makeSandwich. Execute the function whenever a sandwich needs to be made. 
 
Functions can take inputs and give outputs. You can think of the inputs as ingredients. Outputs as the end products. For makeSandwich, you can give it inputs of bread, peanut butter, and jelly. The output would be a peanut butter jelly sandwich. 
 
●	Defining custom functions - If we want to create a reusable program that does some custom things, we must define our own function. Functions can be created using a specific syntax. You will learn how to create functions and assign it to variables. 
●	Side effects and return value - The output of a function is called a return value. Each function can only output one return value. Apart from return values, JavaScript functions can also be useful for their side effects. Learn about what constitutes as side effects in JavaScript. Functions that only have return value and no side effects are called pure functions. 
●	Parameters and optional parameters - Parameter is another name for inputs. Learn how to define parameters in a function. You can make certain parameters optional by giving them default values. This reduces the number of inputs needed when functions are executed. But still allows for on the fly customization. 
●	Scope and closure - Learn about how functions can use and store data in the global	 scope, local scope, and nested scope. Scope makes each function execution an independent siloed environment that won’t affect each other. When a function returns a local nested function as the return value. Local variables created in the outer function are still alive even though the outer function is no longer in effect. This effect is called a closure. Scope and closure are important concepts you need to understand thoroughly if you want to write clean and efficient programs. 
●	Declaration and expression - There are two ways to define a new function, declaration	 and expression. Function defined through declaration is hoisted to the top of its scope, which can cause some unexpected bugs. In general, try to define functions through expression only. 
●	Call stack - You will understand the flow of how a computer executes a program. Especially when you have functions in your program. The computer uses something called a call stack to remember the current location in the program it is at whenever it encounters a function. So that it can return to this position when the function has returned. Learn about the “Maximum call stack size exceeded” error and how to make functions return early. 
●	Learn to keep your code DRY - DRY stands for Don’t Repeat Yourself, it is a principle in programming that strives for reduction in repetition of code. When you must repeat a very similar code at multiple places, you should write a function instead and replace those code. Because more code means higher probability for mistakes. 
 
Part 4: Object Data Structure 
Object is the most complicated data type in JavaScript. You will use it to store complex data structures. Such as product inventories, user profiles, etc. You will learn how to create arrays and objects; and learn how to use properties and methods of objects. 
 
●	Array - Array is a special kind of Object that is very good at storing data of the same type. Such as a list of numbers or strings. You will learn how to create arrays; how to access individual values using bracket notation; how to iterate the values using a for loop; how to create nested arrays and iterate them. 
●	Object, properties, and methods - Object is also called a hash, a collection, a map, or a dictionary in other programming languages. Object stores data in key value pairs. These data are called properties. You can store any other types of values as a property. Properties that store functions are called methods. You will learn how to create complex objects with properties and methods; how to add and remove properties; and how to iterate an object’s properties. You also will learn about the difference in mutability between the object data type and other data types such as number and string. 
●	Array properties and methods - The array object has a bunch of useful default properties and methods. Learn about length, push, pop, shift, unshift, indexOf, slice, join. You also will learn about method chaining	, which is to execute one function after another consecutively. 
●	Built-in data object - All the JavaScript data types have a counterpart built-in object, and each of them will have a unique set of properties and methods. As an example, Number is the built-in object that represents the number data type. You should take a look at the properties and methods of each data type’s built-in object; especially for Number and String, since they are the most common data types you will use in programs. 
●	Arguments object - A function provides a special default parameter called arguments which is an object that contains all the input provided to a function when it is executed. 
You will learn how to utilize this object to write functions that can accept variable number of inputs. 
●	Math object - Math is a standard built-in object that is not associated with data types. It is used to contain a bunch of useful math related properties and functions. Useful methods include round, ceil, floor, abs, pow, sqrt, min, max, random, and trigonometry functions. 
 
Part 5: Advanced Function Concepts 
It is important to dive deeper into JavaScript functions and understand that functions are just values. Like other data values, you can use functions as input arguments and return values in other functions. You also will learn how to create recursive functions; and learn about the implication of input data mutation caused by the pass by reference mechanism. These concepts will help you write easier to read and less buggy programs. 
 
●	Recursive function - A function that calls itself is called a recursive function. A function is allowed to call itself, if you don't create infinite recursions in any way which will overflow the stack. The advantage of recursion over loops is that recursive functions can sometimes be easier to understand. However, for programs that require heavy workload, you should use loops instead. 
●	Higher order functions - A higher order function is a function that accepts another function as an input, or returns a function as an output, or both. Higher order functions are useful because you can use them to create abstraction. Abstraction helps us make clearer, easier to understand commands by hiding parts of the inner workings of our programs. It’s like giving directions to a tourist by saying, “Walk straight down this street until you see a bakery, then turn left”. Instead of saying “Put one foot in front of the other foot towards 60-degree direction for 100 meters, then turn 90 degrees counterclockwise and put one foot in front of the other foot for 200 meters”. The first direction is much more concise because we abstracted the action “walk” and the expression of “orientation”. 
●	Array's Higher Order Functions - The built-in array object contains a bunch of higher order function properties that can help you abstract a lot of the code. The most used ones include map (iterating), forEach (iterating), filter, reduce (summarizing), sort. Having a good command of those methods will allow you to write less bug prone programs. 
●	Passing by Reference - When arguments are passed to functions during a function call, they are either passed by value, or passed by reference. Simple data types such as number, string, boolean, and undefined, are passed by value. While objects are passed by reference. Manipulating object arguments inside a function will change the original object too. You will have a clear idea what consequences passing by reference implies and know how to write programs that will account for this behavior. 
 
Part 6: Advanced Object Concepts 
The topics in this part are more theoretical than practical. But understanding the theory is going to give you more clarity on why JavaScript works the way it does. You will understand a well-known computer science paradigm called Object Oriented Programming and how it influenced the design of JavaScript. You also will learn how to use the “this” variable in objects and methods; how to create new object instances using constructors; and the relationship between primitive data values and object wrappers. 
 
●	Object oriented programming - Object Oriented Programming, or OOP, is a design pattern for writing computer programs. Many significant languages such as Java, C++, C#, Python, Ruby, Objective-C are OOP languages. You will learn the basic design idea of OOP as it has significant influence on JavaScript and programming in general. 
●	Prototype-based programming - JavaScript is classified as Prototype-based programming, which is a style of object-oriented programming. You will learn how to set and get the prototype of objects using Object.setPrototypeOf() and  
Object.getPrototypeOf(). And understand that objects can inherit properties from its prototypes. 
●	Everything is an object - Almost everything in JavaScript is an object. Functions are also objects, if you get the prototype of a function variable, it will return the Function prototype. However, if we get the prototype of the Function prototype, it will return the Object prototype. You will learn that almost everything in JavaScript is based off the Object prototype. And additional functionalities are added to different data types through their own specific prototypes. But it all links back to the Object prototype. 
●	The "this" variable - When a function is called as a method of an object, it will have access to the properties of the object. Calling object.method will give method access to object using the special variable this. You will know how to use this variable to write methods that uses object properties. And know how to attach a different object to a function using apply, bind, and call. Understanding how the this variable works will make life easier when using JavaScript libraries such as jQuery and frameworks such as Angular and React. 
●	Constructors - JavaScript functions serve dual purposes. The first purpose is to store a particular program that we can execute as needed. The second purpose is functions can be used as constructors for other objects. Executing a normal function with the new keyword in-front will turn it into a constructor. A constructor returns a new object. Learn how to use the this variable in constructors to assign arguments as properties of the new objects. You will know how to override properties of an object instance from its prototype, and how to create private properties in a constructor. Also learn about the special get  and set  methods for setting custom functions for getting and setting public properties of a method. Even though constructors might be an overkill for simple JavaScript programs, having it in the back pocket is never a bad idea. 
	●	Prototype interference and inheritance - Learn how to create objects using 
Object.create() that don’t have any prototypes so it is not prone to prototype interference 
where we can alter the properties of an object by changing/adding methods to its prototype and subsequently calling it on the object. Learn how to link one custom prototype to another custom prototype through prototype inheritance by using the call method in a constructor. Like constructors, you might not ever add prototype inheritance to your code, especially for simple programs. But it’s important to understand how it’s applied. 
●	Primitive values and object wrappers - Some values in JavaScript are primitive	 values, they are string, number, boolean, null, and undefined. Primitive values are not able to store properties because they are not objects. But you can still execute methods of primitive values, such as “abc”.charAt(0). The reason this works is because JavaScript automatically wraps the primitive string value in the String object, so that you can use the properties available in String.prototype. You will learn the difference between object values and primitive values and how to create the object version of a primitive value by using value type object constructor, such as new String(‘foo’). 
 
Part 7: Advanced Concepts 
At this point, you should be able to create most basic programs. It is a good time to learn regular expressions and improve your programming skills by solving some common programming exercises. 
 
●	Regular expressions - Regular expression, or regex, is a text pattern matching system for performing text search in strings. For example, /abc/ is a regex pattern that will match strings that consist exactly the characters 'abc'. Meaning 'abc 123' will give a positive match whereas 'Happy crab Sunday' will give a negative match. You will learn how to create complex regex patterns using special characters such as *, \, ^, $, +, ., [ ]; use regex flags; and apply the regex using methods such as match, replace, search, split, exec, test. Regex can be hard to understand and master, but it might prove to be quite useful in many work scenarios. 
●	Debugging - Bugs are inevitable when it comes to programming. Therefore, it is crucial that you develop a sturdy protocol for writing programs and debugging. Many trivial bugs can be avoided if you have a habit of testing programs while you write them, instead of typing out 100 lines of code and test at the end. When you do encounter bugs, the general rule of thumb is recreating - analyze - locate - fix - test. 
●	Programming exercises - The best way to improve is to practice. Aim to solve as many JavaScript fundamental and algorithm exercises as you can. When solving those exercises, try to keep your code clean, efficient, and precise. 
 
Part 8: JavaScript Project 
It will benefit you to work on a medium scale pure JavaScript project to apply all the concepts you have learned. Look for a project idea that can be useful to you. If nothing comes to mind, consider building a text-based game such as blackjack, rock paper scissors, or financial calculation functions such as mortgage payments, stock investment returns. Try to ensure your project covers most of the following points. 
 
●	Has custom functions 
●	Use objects or arrays 
●	Use higher order functions 
●	Is DRY “Don’t repeat yourself”, clean, and efficient 
●	Has no bugs 
 	  
Dynamic Website Development 
Make a web page interactive and do things 
 
How does JavaScript work with HTML and CSS? 
We know that HTML is the file format for web page contents, and CSS is the file format for styles. Early websites were constructed from just HTML and CSS files for the purpose of providing static information. But as people started discovering new uses for the Internet, engineers needed a way to add new functionalities to websites. 
 
A programming language called JavaScript was created to be executable on the browser (client-side). It allows engineers to add features like live chat, payment processing, animation, and all kinds of interactivity to web pages. 
 
The fundamental use case of JavaScript in websites is its ability to manipulate content on a web page, such as: 
 
●	JavaScript can add, change, and remove all the HTML elements and attributes in the page 
●	JavaScript can change all the CSS styles in the page 
●	JavaScript can react to all the existing events in the page 
●	JavaScript can create new events within the page 
●	Animation of page elements, fading them in and out, resizing them, moving them, etc. 
 
The other very important use case is JavaScript can utilize the networking protocols of a browser to communicate with other computers, clients, and servers alike. This allows the user to post a new status update on a social network without leaving or refreshing a page. Because JavaScript is run on the browser, it makes the web browsing experience much faster and more responsive. 
 
Part 1: Document Object Model 
Part 2: DOM Manipulation 
Part 3: DOM Events 
Part 4: JavaScript Libraries (jQuery and Underscore) 
Part 5: Persistent Data Storage with Back-end Servers 
Part 6: Simple HTML CSS JavaScript Project with AJAX 
 
Part 1: Document Object Model 
The Document Object Model, or DOM, is a representation of the HTML (and CSS) documents created by the browser to be used as an interface between the documents and JavaScript. You will learn how to add JavaScript to HTML, how the DOM is structured, how to access, traverse, find elements in the DOM, and be comfortable working with the DOM. 
 
●	Adding JavaScript to HTML - You can write JavaScript directly inside a HTML file by using an HTML < script> tag. Or write JavaScript in a separate .js file and link it to the HTML file also using a <script> tag. Learn about the pros and cons of the two different methods. 
●	The DOM Structure - Explore and understand how a DOM looks like, and how to access it in JavaScript. Understand that HTML elements are represented as JavaScript objects in the DOM. The DOM is the interface that JavaScript uses to manipulate content in a web page. 
●	Trees and Nodes - Learn about the tree structure of the DOM, and how every element is a node. There are 12 different node types, such as element nodes, text nodes, etc., representing the different content types in a HTML file. Explore the different properties available in a node object. 
●	Traversing the DOM - You can access different parts of the DOM tree by moving from one node to another. Each node has a selection of properties that will give you access to its neighboring nodes. Learn to use parentNode, childNodes, children, firstChild, lastChild, nextSibling, previousSibling, hasChildNodes(). 
●	Finding Elements - Accessing elements by traversal can be slow and cumbersome.	 The document object has some better methods you should learn to use to find elements in the DOM quickly. They are getElementsByTagName, getElementsByClassName, getElementById, querySelectorAll, and querySelector. Learning how to use those methods will be super useful when it comes to DOM manipulation. 
 
Part 2: DOM Manipulation 
Having a JavaScript representation of the HTML document wouldn’t be very useful unless we can manipulate it. You will learn how to move and remove HTML nodes, create, inject, and edit nodes. And create simple animation by editing node styles using JavaScript. 
 
●	Move and Remove Nodes - Understand how to use methods such as removeChild()	, appendChild(), replaceChild(), and insertBefore() to edit the position of HTML nodes in the DOM. Changes in the DOM are directly reflected on the web page. This is a crucial part of dynamic website development. 
●	Create and Insert New Nodes - Learn to create new nodes using createElement()	 and createTextNode(). Simultaneously create and insert new HTML content into the DOM using the innerHTML property of element nodes. This is useful for creating infinite load feeds such as the ones in facebook and twitter and many other dynamic features. 
●	Edit Node Attributes and Styles - You can use JavaScript to edit all the attributes in an HTML node. Such as class, id, style, etc. Learn to use the classList property to edit classes; style property to edit inline-styles; getAttribute(), setAttribute(), and removeAttribute() to edit other attributes. Learn how to add CSS to the DOM by inserting <style> elements and manipulate existing style sheets. 
●	Animation with JavaScript - Before CSS animation was available, developers used JavaScript to create simple animations. JavaScript animation is done by changing the top, left, right, and bottom value of an element periodically. This is done by using timing functions such as setInterval() and requestAnimationFrame(). JavaScript animation is particularly good for animations that need to be calculated dynamically, such as a trail of stars that is following the movement of the mouse pointer on the web page. 
 
Part 3: DOM Events 
The interactive input of a user is registered by the browser as DOM events. User activated events include mouse movements, mouse clicks, keyboard inputs, drag and drop, and more. DOM events also include non-user input events, such as when the DOM is loaded and ready, or when a CSS animation has started or stopped. 
 
You can add JavaScript programs to the webpage that will be triggered when a specific event occurs. This is what makes a website interactive. Such as when the user clicks the search button and gets a list of results; or a 2d snake game that is controlled by the keyboard arrow buttons. 
 
●	Event Listeners and Handlers - Learn how to attach and remove programs to events on particular HTML nodes using on- attributes, addEventListener(), removeEventListener(). Understand what properties are available inside an event object, how does event propagation work, and how to prevent default browser behaviors when an event is triggered. 
●	Mouse Events - Mouse events include clicks, double clicks, mouse movements, wheel scroll and more. Learn to attach programs to those events to create interactive features. 
●	Scroll Events - The scroll event triggers whenever the user scrolls a web page. It lets us know which part of the page the user is viewing, so we could use this information to change some elements' CSS or switch off some calculation heavy animation that is not in view anymore. 
●	Key Events - When the user presses on any keys, a key event would be triggered. Learn how to determine key combinations and use key events to create good user experience features. 
●	Focus Events - HTML elements like buttons, inputs, textareas, links, enter the focus mode when you click on them. This is especially useful for signaling the user where they are inputting in forms, and for users with disabilities which element they are focused on the page. Learn how to use the focus and blur event to create good user experience features. 
●	Load Event - Understand the order of which the browser reads and execute programs in a HTML file. Learn to use the load and DOMContentLoaded events to run JavaScript programs only after HTML content and dependent resources are loaded and parsed. 
●	Timers - Learn to use JavaScript timing functions such as setInterval() and setTimeout(). The former lets you repeat a program periodically until you terminate it. The latter lets you set a time delay for running a program. For programs that require precise timing, learn to incorporate the JavaScript Date object in your timing functions. 
●	Debouncing Events - For events that can fire in succession very quickly, such as scroll, keydown, mousemove, you will learn how to delay the execution of the linked event listener program. This technique is called debouncing and involves the use of the setTimeout() function. Also learn how to rate limit the firing of some event listeners. 
Debouncing and rate limiting are handy techniques for real work. 
●	Small Project in Vanilla JavaScript - Build a simple HTML CSS JavaScript project that combines all the concepts you have learned. You can base the project on a previous pure JavaScript project you worked on. The key learning goal is to combine HTML CSS with JavaScript to make your JavaScript programs come to life. Such as a rock paper scissors game, or a financial calculator. 

Part 4: JavaScript Libraries (jQuery) 
In programming, a library is a collection of programs that perform specific tasks. Engineers incorporate libraries into their projects, so they don't have to write the programs themselves, to save development time. 
 
Different libraries solve different problems, big or small. Engineers pick and choose the libraries they use based on their project needs. 
 
You should get introduced to JavaScript libraries through exploring two sturdy and easy-to-use libraries. jQuery deals mostly with DOM manipulation and traversal, events, animation, and network requests. Whereas Underscore is a collection of useful functions that deal with JavaScript data manipulation and functional programming, but not much about the DOM. 
 
●	jQuery Object and Selector - For our DOM elements to be able to use the methods in the jQuery library, we first need to turn them into jQuery objects. You can do so by either passing a DOM node reference to the jQuery() function, or use the jQuery() function to select HTML nodes from the DOM using a CSS selector string. This is the first step to using jQuery. 
●	jQuery DOM Traversal - Learn to use jQuery’s traversal methods that are more convenient than the ones supplied by vanilla JavaScript. You can use CSS selector strings in jQuery traversal methods to refine selections. Noteworthy ones includes parents(), closest(), next(), prev(), siblings()	. 
●	jQuery DOM Manipulation - The jQuery() function can create new HTML nodes by passing a HTML string to it. You can then use one of jQuery’s DOM manipulation methods to insert those new nodes to the DOM. jQuery’s manipulation methods include append(), prepend(), before(), after(), replaceAll(), remove() and more. You can also edit existing DOM contents, attributes, and properties using jQuery. 
●	jQuery DOM Events - jQuery’s purpose is to make developer’s life easier. You can see	 this especially in its event handling suite. jQuery adds an array of convenience methods that let you easily add event handlers to DOM nodes. These include click(), focus(), scroll(), hover(), keypress(), etc. Learn how to add the same event handler to multiple DOM elements in one step; how to add event handlers to nodes that are not yet in the DOM; add the same handler to multiple events; and how to use the trigger() method to programmatically trigger events. 
●	Other jQuery Methods - Learn to use each() and map() to iterate jQuery objects and get() to convert jQuery objects back into standard JavaScript data. Learn to use basic jQuery animation functions such as show(), hide(), slideUp(), and fadeIn()	 to create simple transition for your HTML elements. 
●	Small Project Using jQuery - It’s a good point to work on another HTML CSS 
JavaScript project to solidify your learning. Except this time, you will be soliciting the help of libraries such as jQuery. You can either rebuild a previous project using jQuery or build an entirely new one. Stick to simple one-page projects which have a good amount of dynamic interaction. Keep the scope small. Apart from games and calculators, consider building individual components of everyday websites. 
 
Part 5: Persistent Data Storage with Back-end Servers 
Basic front-end websites that only has HTML CSS and JavaScript cannot store state. What that means is if you built a website for an investment portfolio return calculator, the user will have to re-input all the information every time they open it. Because the webpage has nowhere to store the data. 
 
How can we solve that? Well, we need a back-end server to help us remember the states of our applications and to provide us the data when we need it. 
 
This is the relationship between front-end and back-end. A front-end application is usually just an interface for users to interact with a back-end server. While all data and business logic are handled in the backend server. 
 
A front-end website can use network requests to retrieve data from a back-end server. It can then inject this data into the DOM as HTML nodes. All of this is done using JavaScript. 
 
●	TCP/IP, HTTP - Before starting to make network requests, you will gain a brief understanding of how the internet works. Especially around the topics of Internet Protocol (IP), Transmission Control Protocol (TCP), which are the standard protocols that computers use to send and receive data with each other. You will also read about Hypertext Transfer Protocol (HTTP), which is the protocol to exchange or transfer hypertext documents. 
●	XHR And AJAX - XMLHttpRequest (XHR) is the interface that browser JavaScript uses to make HTTP requests. Request can either be made synchronously, or asynchronously. A synchronous request means the browser will wait for the back-end server to return a response before continuing executing the rest of the program. While an asynchronous request will continue to process and execute other programs, then come back to handle the server response when it’s received. Asynchronous XHR is also called AJAX, which stands for Asynchronous JavaScript and XML. You will learn how to create and send an Ajax request, and handle the success and error state of the request when it returns. 
●	API and JSON - Application Programming Interface (API) is an interface that programmers can use to interact with a software system. For example, Bob is a waiter at a restaurant. He relays your order to the kitchen, and Bob brings the food back to you. The kitchen is the software system, and Bob is the API. Most back-end servers will have a well-defined API for developers to interact with. Explore some public APIs to get a sense of how they function. JavaScript Object Notation (JSON) is a widely used data format for storage and communication on the web. Many back-end servers send back data in the JSON format. Learn to parse and create JSON data in JavaScript. 
●	CRUD and RESTful API - CRUD stands for Create, Read, Update, Delete. These are	 the four basic functions of persistent storage on back-end servers. Most back-end web servers are just dealing with CRUD data manipulation. REpresentational State Transfer, Application Programming Interface (RESTful API) is a set of standards for building back-end web server APIs. Learn about those standards and how to make AJAX requests to RESTful APIs to perform CRUD operations on back-end servers. These include Post, Get, Put, Delete for Create, Read, Update, Delete. 
 
Part 6: Simple HTML CSS JavaScript Project With AJAX 
Combine all the skills you have learnt and build a front-end website that utilizes a back-end API for persistent storage. You can pick a public API from this API list. Try to satisfy the following criteria. 
 
●	Data from the API is retrieved and rendered in the DOM through JavaScript DOM manipulation in a meaningful way. 
●	An index (list) view of the data and a detailed view of individual data, preferably in two separate pages. 
●	A search feature for the user to search for data in the API database, result is injected into the DOM as list view. 
●	Allow user to sort or filter data. 
●	API allowing, add a feature for the user to create new data points and persist it in the back-end server. 
 	 
ReactJS Development 
Learn to develop components and single page apps in React 
 
What is a front-end framework? 
In programming, a framework is a standard for building applications. Frameworks deal with low level details so engineers can focus on high level problems which matter. Frameworks can significantly reduce development time. 
 
A front-end framework is usually capable of speeding up the development of DOM manipulation programs significantly. Some frameworks are focused on building user interfaces only, while others provide a full suite of tools such as state management and routing. The three most popular frameworks of today are React (by Facebook), Angular (by Google), and Vue.js (independent). 
 
●	React - Popular amongst startups with a strong job market. Designed for gradual adoption. Has lots of resources and third-party tools with a large active ecosystem. But lots of choices for supporting tools can be overwhelming for beginners. Learning curve can be steep. 
●	Angular - A full monolithic approach that comes with default systems for state management, routing, and a development language called Typescript. It is popular amongst large companies due to strong corporate support by Google. Learning curve can be steep. 
●	Vue.js - Like React, it is a lightweight, gradual adoption framework that mostly focuses on building user interfaces. But also comes with optional official tools for state management and routing. Popular amongst early-stage startups. 
 
We teach React as it is currently the most popular one with the most resources. Also, with a good understanding of React, you can transition into the other frameworks quite easily. Following are the fundamental topics you need to learn for React. 
 
Part 1: JavaScript ES6 
Part 2: Basic React 
Part 3: Intermediate React 
Part 4: Create React App 
Part 5: React Project 
Part 1: JavaScript ES6 
JavaScript goes through continuous improvements and the organizations in charge of writing JavaScript standards is ECMA International. 
 
The 6th JavaScript edition which was published in 2015 is the latest supported version across major browsers. This version is referred to as ECMA 2015 or ES6 (6th edition). 
 
Many updates were added to ES6. The important ones you will learn are: 
 
●	Arrow functions - A new way to define functions () => {}. Arrow functions are not the same as standard functions. They don’t have a separate this variable, they can’t be used as constructors, and they don’t have their own arguments	 object. 
●	Classes - ES6 Class is a syntactic sugar that coats the JavaScript prototype-based Object Constructor to look like a more traditional OOP Class object. It's the industry's attempt to make JavaScript more like traditional OOP languages and easier to pick up by OOP language developers. 
●	Object enhancements - New property shorthand for assigning key value pairs from variables. Support for computed property key name during object definition. Plus, shorter syntax for object method definitions. 
●	Template literal - This is a new way to construct text strings. With this, there is no need to worry about escaping quotation marks, and dynamic content can be added using a special syntax. 
●	Rest param and spread operator - ES6 rest param allows us to group function	 parameters into a JavaScript array. Then we can access it in the function as an array. We can also spread an array into comma separated output using the new spread operator. 
●	Default params - We can now define default parameter values in the parentheses with a new syntax e.g., function (a = 1). This reduces written code. 
●	Let and const variables - In ES6, two new keywords for creating variables are added, let and const. let will replace var, and const is for creating constant variables. 
 
Part 2: Basic React 
React is designed for gradual integration. In this part, you will learn to add React to an existing project, learn to write in React JSX, compile JSX locally, learn to construct React components, use props, add state to a component, and handle events. 
 
●	Smallest React example - Learn React by creating the smallest React component and inject it into the DOM. You will learn how to use React library methods such as React.createElement, ReactDOM.render. Learn to use props, and style React elements. 
●	Use same React component in multiple places - We can insert as many react components to a HTML page as we want. Learn to do this with a simple react component. 
●	React JSX - Reacts templating language lets us combine HTML and JavaScript in	 one fluent structure. This is a powerful feature of React. Learn to add styles in JSX and incorporate JavaScript expressions. 
●	Custom components and props - Learn to create custom React components that are fully programmable to do anything. Learn to use props to pass in data to custom components. 
●	Composing components - Learn to nest custom components in other custom components to create larger, more complex components. 
●	Add state to components - React components can store states that are independent for each component instance. Learn to use states in React class components. 
●	Component lifecycle - React components have helper methods that are called during the render lifecycle. Learn to use methods such as componentDidMount, and componentWillUnmount to run code that modifies component states. 
●	Event handling - Learn to attach event handlers to React elements through JSX attributes. This enables the building of interactive React components. 

Part 3: Intermediate React 
After learning how to create basic React components. You will get into the more advanced concepts and learn to use React to build more complex components. Learn to render lists, handle form elements, structure conditional rendering, make ajax calls with the new fetch API, and more. 
 
●	Rendering lists - Learn to convert array values into React elements. Learn about the importance of the key attribute. Learn to embed map() expressions in JSX. 
●	Form elements - Form elements are usually used as controlled elements in React. What that means is the values of form elements come from component states. Learn to handle value change and state updates for different types of form elements, such as, input, textarea, select, checkbox, etc. 
●	Build a stock portfolio - Deepen your understanding of lists and forms by going through a stock portfolio building tutorial. 
●	Handling state in a parent component - States are often seen as single source of truth for data, and often flow down from parent-to-children components. Learn to construct composed components that have state stored at the top parent component. 
●	Build a currency converter - Learn to build a currency convertor that will simultaneously update values of both currencies based on an editable conversion ratio. While keeping state of all values in a parent component. 
●	Conditional rendering - In React, we can conditionally render outputs using if statements, logical &&, || and ternary operators. We can incorporate them either as inline JSX expressions, or as final return values. 
●	Fetch and promises - A new ajax tool amongst modern web browsers is the Fetch API. Key difference between Fetch and traditional XMLHTTPRequest is that Fetch uses promises instead of callbacks to handle request response. Promise is a new feature in 
ES6 for asynchronous programming. You will learn to use Fetch and promise to make ajax calls. 
●	Build a movie finder - Build a React application that searches a movie database and render the results. 
●	Build a to do list - Build a to do list React application that connects with a back-end api for persistent data storage. 

Part 4: Create React App 
Learn to use the Create React App NPM package to create SPA (Single Page Applications). You will learn the folder structure, learn how to install additional dependencies, import a component, add a stylesheet, and run the app locally and deploy it live. 
 
●	Node and NPM - Node is a runtime environment for JavaScript and is often used for running JavaScript based back-end web servers. NPM (Node Package Manager) is the package manager for Node packages, which are libraries. You will learn to install Node and NPM in your local system to use Create React App. 
●	Run app locally - Learn to setup a new React app and serve it locally. 
●	Add dependencies - Learn to add dependencies to a React app with NPM. 
●	Single Page App - Single page apps are web applications that load a single HTML page and update the page dynamically using JavaScript. Learn the single page app structure for React. 
●	Front-end routing with react router - Routing, changing of URL and subsequent page content, is done in the front-end for single page apps. Learn to use react router to handle routing. 
●	Build a movie finder 2 - Combine all the knowledge into a multi route single page app	 that lets you search for movies and view individual movie details. 
●	Deploying an app - Learn to deploy a React app onto static file hosting servers and server hosting platforms. 

Program Structure 
As you will learn, the constituents of writing programs for most programming languages are quite similar. It can generally be broken down into variables, statements, conditionals, loops, and functions. 
 
But different languages will have different strictness. A stricter programming language requires the programmer to define more details in a program; such as the datatype of the parameters a function accepts, or how to handle errors when it happens. 
 
More old school languages such as C++ and Java are stricter and harder to learn. 
 
●	Variables - Variables are memory boxes used to remember values so they can be used later. Learn to create variables in Ruby; assign and re-assign values to them; learn the list of reserved words that cannot be used as variables names. 
●	Functions / Methods - Function is a box of program that takes inputs and returns an output. In Ruby, functions are also called methods. Learn to define custom methods that accept parameters and return outputs; and learn how to execute custom methods. 
●	Control Flow - Ruby executes programs in a top-down flow. We can alter this flow by adding control flow statements to our programs. These include conditional statements that will only execute programs when certain condition is true; for loops and while loops that let you repeat certain programs over and over again. Learn to incorporate control flow into methods too. 
●	Ruby Best Practices - You will adopt a good best practice guide for code indentation	 and variable naming convention. Keeping your code consistent and clean will make it easy to read and extremely beneficial when it comes to bug finding. 
 
Part 5: Data Structure 
Apart from standard data values such as Numbers and Strings, you will learn how to create, read, and manipulate data structures such as Array and Hashes. These are frequently used to structure data sent between front-end and back-end applications and are common data types amongst most programming languages. 
 
●	Array - Array are used to store a collection of data. Usually, you would keep data of the same type in an array. You will learn to create arrays, read values, and manipulate arrays. Also learn to use array methods such as push, pop, shift, unshift, and how to iterate arrays using loops. 
●	Hashes - A hash, also called a dictionary, is a data structure used to store a collection of arbitrary data. A hash is made up of properties, each property will have one key, and one value. The key is used to retrieve the value, and each key needs to be unique in a hash. You will learn how to create a new hash; how to read, add, and remove properties; and how to iterate a hash. 
 
Part 6: Object Oriented Programming 
Object Oriented Programming, or OOP, is a design pattern for writing computer programs. Many significant languages such as Java, C++, C#, Python, Ruby, Objective-C are OOP languages. You will understand the fundamental design idea of OOP and how it’s applied in programming. 
 
●	Class - A class is a concept in OOP where certain types of objects belong to the same class. An analogy would be that Cats, Dogs, Lions all belong to the Animal class. Because they share certain common characteristics. Different breeds of cats will then be subsets of the Cats class. And Animal is the superset of all those classes. You will learn how to define custom classes. 
●	Instance - Classes can be thought of as blueprints, which are used to create actual objects from. The objects created from a class are called class instance. Learn to generate object instances from classes using the new keyword. 
●	Inheritance - A class will inherit methods and properties from its superclass, e.g., 	Cats and Dogs will inherit from the Animal class. This reduces redundancy so code that is common across multiple classes do not have to be repeated. Learn to declare inheritance when creating a new class. 
●	Attributes - Learn to create instance attributes in Ruby classes that have both read and write capabilities. Also learn to instantiate attributes during the class instance creation process and to define default attribute values. 
●	Attribute Visibility - You can set the visibility of class methods and attributes to one of three values, public, protected, or private. Public attributes can be accessed outside of the class definition, while protected and private attributes can only be accessed during class definition. Protected attributes are inherited by subclasses but private attributes are not. Learn to create all three types of class attributes. 
●	Instance vs Class Attributes - Instance attributes are independent between class instances, edits to one won’t affect others. But we can also create class attributes too. Class attributes are tied to a class, it can be used to store data that needs to be shared amongst class instances. Learn to create class attributes during class definition. 
●	Super - When you create a new subclass that inherits a parent class, but you have a method in the subclass that shares the same name as a method in the parent class, the subclass method will completely overwrite the parent class method. If you want the method of the parent class to run before the subclass method executes, you can use the super keyword in the definition of the subclass method. This is also useful for instance initialization so that attribute instantiation code doesn’t have to be repeated in subclasses. 
	 
Back-end Development 
Storing and manipulating data permanently 
 
What does a back-end web server application do? 
If you have noticed, front-end is mostly just the UI (user interface) view of an application. All the front-end websites you build are not able to remember states, unless you connect them with a back-end application. 
 
A back-end web server application deals with data storage and business logic. It’s all about creating, retrieving, modifying, and deleting data. Say a message board such as Twitter, where the core business logic is tweet creation and tweet retrieval. But of course, there are also other things to consider, such as user authentication, data validation, and security. 
 
So how does a back-end server application interaction work? Well, there are three parts to it. First, the party who wants to interact with the back end must send a request. This is usually a person on a web browser. For example, Vicki who wants to post a new tweet on her Twitter feed. 
 
1.	Vicki types a message and clicks the tweet button. The JavaScript program in the browser that handles this action translates it into a Post request and sends it to the back end of Twitter. 
2.	The Twitter back-end receives the request and starts processing it. It adds the tweet to the database and does whatever tasks it needs to. 
3.	Twitter back-end then sends a response back to Vicki’s browser. Most likely saying that the tweet has been successfully added. Also, the data of the new tweet is usually sent back with the response as well. 
 
At this point, the job of the back end is done. It is up to the front-end how to deal with the response. If the tweet was successfully added, then the front-end will likely update Vickis feed to reflect that. Otherwise, it will show an error message. 
 
But here’s the thing, a back-end server is only able to execute the tasks it is programmed for. You cannot send a request to post a new tweet on your Twitter account to Google’s back-end server. So, how do we know what kind of tasks a back-end server can carry out? 
 
This is exactly the purpose of an Application Programming Interface (API). An API is a set of definitions of routines. For a back-end web application, an API refers to the logic of all the requests it is programmed to handle. APIs will generally come with API documentation too, which is how other programmers can learn how to use a particular back-end API. 
 
You will learn the model-view-controller (MVC) structure of an application; How to define routes for a back-end server, how to create, edit, delete data in a database, how to process requests and send back responses, how to write application features such as user authentication, photo upload, email sending, how to write automated tests, and finally deploy your back-end application live onto the web. 
 
Part 3: Writing Back-end Web Application 
You will learn the complete process of how to create a back-end application; study topics such as database, migrations, associations, testing, routing, and the crucial MVC components. 
 
●	Database - Back-end applications’ primary task is permanent data storage. You will understand the concept behind relational databases, a type of database structure popular for mission critical applications amongst financial institutions and large internet companies. Also learn about database schema and migration. 
●	Model - Model is the first component of MVC. It's the core of data management because it lives between the controller and the database. Learn to create new models; add data attributes and run migration to edit the database; create a new data entry. 
●	Controller - Controller is the interface between model and view. When a request is sent to the back end, it will first be filtered by route management, then passed to the corresponding controller for handling. In the controller file, you can define how you want to handle and process the request. Learn to create controller methods and corresponding route end points for GET/POST/PUT/DELETE requests; learn to test your end points with the Postman app; learn to craft text and JSON responses directly in the controller; and learn to read request params in the controller. 
●	Database Migrations - Migrations are a convenient way to alter database structure over time in a consistent and simple manner. Traditionally, you write raw SQL to modify the database schema. Learn to add tables, attributes, and modify the database structure by using migration. 
●	Associations - Association is a connection between two data tables. For example, you can have a table for authors, and a table for books. And you can create a connection between the books and their authors. This kind of connection is called an association. 
Learn to add associations such as has_many, has_one, belongs_to to Rails models. 
●	Views - Back-end applications can return responses in different formats, such as HTML, JSON, XML. The view component oversees determining the response format. 

Part 4: Learn by Example - ToDo List 
Plan and implement the API endpoints of a ToDo list application. There is one model, and five endpoints. The front-end application is already written and ready to connect with the API endpoints. 
 
●	Tasks model - a model containing 3 attributes, content, completed, timestamps, and a validation that content must be present. 
●	GET /tasks - return all tasks from database. 
●	POST /tasks - create a new task based on given parameters. 
●	DELETE /tasks/:id - delete a task identified by its object id. 
●	PUT /tasks/:id/mark_complete - update a task to change completed to true. 
●	PUT /tasks/:id/mark_active - update a task to change completed to false. 
 
Part 5: Deploying Your Application 
It doesn’t matter how awesome your application is unless you are able to deploy it live. Also, there are often many kinks in the way when you try to deploy a local project. So, it is recommended to deploy your application as early as possible, even if it doesn’t do anything yet, so you have the deployment process ironed out. 
 
●	Deploy to Heroku - Heroku is a simple to use application hosting service provider. It acts as a layer on top of Amazon Web Services (AWS) that manages all the small details 
of running your web server instance for you. Learn to create and deploy your local application to Heroku. 
 
Part 6: Model Validations 
When you submit a tweet on Twitter, it has a default limit of 140 characters. The best place to validate this is in the model. Since model is the component which manages all the business logic for data.  
 
Part 7: User Authentication 
When you post a new tweet on Twitter, the back end needs to make sure you are the owner of the account. Without a user authentication mechanism in place, users will be able to impersonate each other. You will learn how to setup a login system to enable user authentication. 
 
●	User - User authentication starts with a user model. Websites often use the user model to hold information such as contact email, username, first and last name, and password. Learn to create a user model to store username and password for a ToDo list application so users can sign up for an account. 
●	Session - Once users can sign up, they need to be able to sign in too. Signing in requires a concept called session. A session is simply a database entry that records a user’s unique sign in token which is also stored on a user’s browser. Every time a user makes a request from the browser, this token is sent together with the request. The back-end application then checks and validates this unique token to authenticate the user, before carrying out the tasks requested. Learn to implement the session system and use it to ensure users are authenticated before carrying out tasks in other API endpoints. 
●	Encrypting Passwords - If we store user passwords as plain text, we risk exposing	 them if the server or database is compromised. This is especially damaging when users use the same password across many different websites. Making their accounts on multiple websites vulnerable. To combat this, we should encrypt the user’s password stored in our database. Learn to use BCrypt to encrypt passwords for storing and decrypt them when users login. 
 
Part 8: Project - Twitter Clone (Or Similar)
You are going to combine all the concepts you learned and build the API back-end for a Twitter clone. The application comes with a front-end application that is ready to consume the API endpoints you create. There will be three models and nine endpoints. 
 
●	Models - You will create three models, Users, Sessions, and Tweets. 
●	POST /users - create a new user based on given parameters. 
●	POST /sessions - create a new session based on given parameters. 
●	GET /authenticated - validate user authentication by comparing cookie with session token. 
●	DELETE /sessions - delete session token from database to logout a user. 
●	POST /tweets - create a new tweet based on given parameters. 
●	DELETE /tweets/:id - delete tweet based on given id. 
●	GET /tweets - get all tweets by all users. 
●	GET /users/:username/tweets - get all tweet by one user. 
●	GET /tweets/search/keyword - get all tweet based on given keyword. 
 
	 
Full-stack Deployment 
Get a full-stack web application up and running 
 
What constitutes a Full-stack Web Application? 
FS needs to have a back-end application which handles business logic and permanent data storage; and a front-end application which acts as the interface for users to interact with the back end. 
 
For example, Facebook, Twitter, and Google are all full-stack applications. Each has a back-end API application that handles API requests, and a web interface which lets users interact with the API. 
Monolithic Structure vs Split Structure? 
There are two general approaches to developing and running a full-stack web application. You can either separate the front-end from the back end, called the split approach. Or you can create one monolithic structured full-stack application that handles both front-end and back-end. 
 
If you take the split approach, you will need two independent servers. One is responsible for serving the front-end web application, and the other will host the back-end API application. If your front-end web application is simple and only consists of static files, e.g., HTML, CSS, JavaScript, images, etc. It can easily be hosted and served using cloud-based file hosting services, such as AWS S3, or Netlify. 
 
Furthermore, the split structure is the better approach if you plan to build multiple front-end applications, such as a website, and a mobile app. So, the back-end application only functions as an API endpoint application which the different front-end applications interact with. This way you will have better separation of concerns. 
 
The monolithic approach is combining the front-end application and back-end application into one. A monolithic application will handle business logic, data storage, and serving the front-end interface to the user. This means the application will be serving HTML, CSS, JavaScript files as well. 
 


Capstone Portfolio Project 
Build a full-stack application you are proud of 
 
What is a capstone project? 
A capstone project is an integrative experience of your learnings. The term derives from the final decorative coping, or "cap-stone" used to complete a building or monument. You will plan and build your project by leveraging all the knowledge and practical skills you've learned so far. 
 
A capstone project is likely the centerpiece of your portfolio and the main talking point for you when you attend job interviews. It is where you will convey your knowledge and capabilities to potential employers. 
 
The process of developing a capstone project includes project idea generation, planning, drafting, prototyping, user testing, and finally building. Learn best practices in each part of the process to ensure you create a project that accurately reflects your abilities. 
 
Part 1: Project Scope 
You will be calling the shots on what you want to build. But, we will be setting some minimum requirements to ensure you have a project technically advanced enough it will be the most prominent one in your portfolio. 
 
●	Project Requirements - You will build a full-stack application with an interactive front-end. It needs to be a complete product. It needs to have permanent data storage. It needs to be visually impressive. And it needs to be deployed online. 
●	Deliverables - The deliverables include your working application hosted live on the	 internet, the link to the Github repository of your project, and a readme file in your Github repository which explains what the project does. 
●	Project Evaluation  - Your project will be evaluated on your workflow and code quality, complexity of the project, and your creativity towards problem solving. 
 
Part 2: Project Idea Generation 
To help you come up with a project idea. We have prepared a workflow you can use to generate, evaluate, and choose your idea. 
 
●	Brainstorming - Let your mind run wild and generate as many ideas as possible. It is important to not say no here. 
●	Market Research - Choose up to five ideas from the brainstorming stage and perform market research on those ideas. Look for existing products in those industries and try to deduce if they are meeting the demands of their customers. 
●	Idea Refinement - Shortlist to only three ideas based on all the data you have gathered. The most important factor is how excited you are to work on an idea. 
 
Part 3: Planning 
Planning is key for a smooth building process. You will decide on the features you want to build; wireframe the user interface; carry out user testing with real people; plan the data structure and the API endpoints. 
 
●	Scope and Timeline - The timeline for the capstone project is 2 weeks; you will scope the project into something you can comfortably finish in this time. That means you must choose only a few features most important and representative for your idea. 
●	Wireframing The User Interface - Actual development is costly, so you should never start by coding. Instead, spend a day to build a fake product through wireframing. You will sketch out the user interface and envision how it will be used. 
●	Conduct User Testing - Take your wireframe and conduct interviews with real people. This is the best way to get feedback on whether users understand what your product is, and how to use it. This feedback will help you revise your design and features. 
●	Plan Your Database Structure - Based on your wireframe, you should have a decent idea of how your application is going to work and what features you will build. You should plan out your database structure. What kind of data you will store, and what are the relationships between the data. 
●	Plan Your API Endpoints - The API is the node between the front-end and the back end. You will list out each API endpoint’s route, the controller it connects, and a simple description of what the end point does. 
●	Plan Your Build Process - We recommend building one feature at a time. For each feature, you can build the front-end first, then the back end. You should decide on the order of the features based on their importance. 
●	DIY vs Community Packages - For many common features, there will be community packages you can use, so you don’t have to build from scratch. We recommend only using packages if the feature would take you too long to build it yourself. Plan and research on community packages, then decide which features you would build from scratch, and which you will leverage on community packages. 
 
Part 4: Building 
If you planned everything out, your building process shouldn’t be too difficult. The most important thing to remember here is to deploy all the time, so you know that your application works in the production environment. 
 
●	Create an Empty React App - Always start by creating an empty application, and make sure the server runs fine. 
●	Always Be Deploying - Make sure you deploy your application at every stage of the build process. After you complete each feature, you should deploy it live. 
 

