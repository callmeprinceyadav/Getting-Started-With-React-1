What is React?
Ans - React is a javascript library for builiding user interface.


2. Who made React?
Ans = React was made by Jordan Walke

3. What is Babel?
Ans = Babel is a JavaScript compiler that converts ECMAScript 2015+ code into a backwards compatible version of JavaScript. It can convert modern JavaScript code into a version compatible with all browsers. This allows React developers to use the latest JavaScript syntax in their components. 


4. How does Babel convert html code in React into valid code?
Ans = Babel is a key tool that can translate JSX syntax, which is used to create HTML-like code in React components, into valid JavaScript code that can be executed in preferred browsers. By converting the JSX code into JavaScript functions that return the same HTML-like structures.


5. What is ReactDOM used for? Write an example?
Ans = ReactDOM is a package in React that provides DOM-specific methods that can be used at the top level of a web app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with an API containing the various methods to manipulate DOM.


6. What are the packages that you need to import for react to work with?
Ans =  The packages that you need to import for react to work with  React are Following:-
       1- react 
       2- react-dom
       3- babel
       4- webpack (or another bundler)
       5- Other dependencies like 
          . prop-types
          . react-router-dom
          . axios


7. How do you add react to a web application?
Ans = Step 1: Add a DOM Container to the HTML. First, open the HTML page you want to edit. ...
Step 2: Add the Script Tags. Next, add three <script> tags to the HTML page right before the closing </body> tag: ...
Step 3: Create a React Component. Create a file called like_button.js next to your HTML page


8. What is React.createElement?
Ans = React.createElement is a function that lets you create a React element. It serves as an alternative to writing JSX.
The main use of React.createElement is the Creation of a React component. It is the JavaScript format for creating react components. Also, the JSX react component when transpired invokes this only method for creating the component.
Here is the syntax for React.createElement:
               createElement(type, props, ...children)

9. What are the three properties that createElement accept?
Ans = createElement Accept Following Properity :-
    1. Type
    2. Properties
    3. Children


10. What is the meaning of render and root?
Ans = Render :- React renders HTML to the web page by using a function called render(). The purpose of the function is to display the       specified HTML code inside the specified HTML element. In the render() method, we can read props and state and return our JSX code to the root component of our app.

Root :- In React, the root element refers to the top-level element that is the parent of all other components in your application. It is typically represented as a DOM node within the public/index. html file that serves as the entry point for your React app.