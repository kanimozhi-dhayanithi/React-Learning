Theory
What is Emmet?
● Difference between a Library and Framework?
● What is CDN? Why do we use it?
● Why is React known as React?
● What is crossorigin in script tag?
● What is diference between React and ReactDOM
● What is difference between react.development.js and react.production.js files via CDN?
● What is async and defer? - see my Youtube video ;

What is Emmet?
As the name implies, Emmet Abbreviation saves you time and effort while allowing you to focus on more important matters. By converting acronyms into blocks of structured code in (X)HTML, CSS, XML, XSL, and JSP, Emmet speeds up coding. We'll go over a variety of acronyms to help you write syntax quickly and easily


Difference between a Library and Framework?

Libraries
The developer controls the flow of the application by calling specific functions from the library. Libraries are collections of pre-written code that provide developers with tools to perform specific tasks. Developers can easily link libraries into existing programs to add functionality. 
Frameworks
The framework controls the flow of the application by calling functions from the developer's code. Frameworks are collections of pre-written code that provide developers with a structured environment to build applications. Frameworks are often used as a base for building apps for specific platforms. 





What is CDN? Why do we use it?
A content delivery network (CDN) is a group of servers that speeds up the delivery of web content by storing it closer to the user: 
How it works
A CDN stores content on servers located near the user, so that when a user requests content, it doesn't have to travel as far to reach the user's device. 
Why it's useful
CDNs can improve website performance by reducing latency, or the delay in communication between a website and a user. They can also help protect websites from malicious attacks, such as DDoS attacks. 
Who uses it
Many major websites, including Facebook, Netflix, and Amazon, use CDNs. Other organizations that use CDNs include e-commerce companies, banks, and mobile application providers

Why is React known as React?
React is called React because it reacts to changes in data and updates the user interface without reloading the entire page: 

Reacts to changes
React only updates when the state or props of a component change. It doesn't redraw the entire page, but instead responds to specific data changes. 
Uses a virtual DOM
React uses a virtual DOM, which is a copy of the actual DOM. When the data state changes, React immediately updates the virtual DOM. It then compares the virtual DOM to the actual DOM to determine what has changed and how to update it. 
Built around components
React is built around components that update and "react". Developers use components to create web pages, similar to how toy parts are used to create figures. 
React was developed by Facebook to improve user interface development. It's a JavaScript library that allows developers to build single-page applications (SPAs). 

what is crossorigin in script tag?

The crossorigin attribute in a script tag sets the mode of a request to an HTTP CORS Request. CORS stands for Cross-Origin Resource Sharing, and it allows a web page to request resources from another domain. 
The crossorigin attribute can be used on the following HTML elements: <audio>, <img>, <link>, <script>


What is diference between React and ReactDOM?


The main difference between React and ReactDOM is that React is used to define user interfaces, while ReactDOM is used to render those interfaces in a web environment: 
React
A JavaScript library that provides tools and concepts for building user interfaces. React is used for components, classes, and elements. 
ReactDOM
A package that provides methods for managing React components and rendering them on the web. ReactDOM is used for methods like render() or findDOMNode(). 
React and ReactDOM are two packages that work together to form the foundation of React web applications. React components are used to organize user interfaces, and ReactDOM acts as a bridge between React components and the DOM elements that make up a web page. 
React and ReactDOM were split into two libraries when React Native was introduced, a React platform for mobile development. React is used in both web and mobile, while ReactDOM is only used in web apps


What is difference between react.development.js and react.production.js files via CDN?

When using React via CDN, you can choose between react.development.js and react.production.js. Here's a breakdown of their differences:
react.development.js:
Purpose: Used during development.
Features:
Includes helpful warnings and error messages to aid debugging.
Unminified, making it easier to read and debug.
Larger file size due to the extra debugging features.
Slower performance compared to the production version.
react.production.js:
Purpose: Used for deploying your application to production.
Features:
Minified and compressed, resulting in a smaller file size.
Faster performance due to optimizations and removal of debugging code.
No warnings or error messages, as they are not needed in production.
In summary:
Use react.development.js while developing your app to benefit from debugging tools and warnings.
Switch to react.production.js when deploying your application to ensure optimal performance and a smaller bundle size.





What is async and defer?

In JavaScript, the async and defer attributes are used to load scripts asynchronously without blocking rendering. The main difference between the two is when the script is executed:
async
Executes as soon as possible, in no particular order. This is a good choice for scripts that don't need to interact with the DOM, like scripts that load images or videos.
defer
Executes in sequence toward the end of the loading process, just before the DOMContentLoaded event. This is a good choice for scripts that need to interact with the DOM, like scripts that initialize widgets or add event listeners.