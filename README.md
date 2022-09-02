# What is React?
ANS:-React is a free and open-source front-end JavaScript library for building user interfaces based on UI components. 

# Who made React?
ANS:-React was originally created by Jordan Walke. Today, React has over a thousand open source contributors.
We'd like to recognize a few people who have made significant contributions to React and its documentation in the past and have helped maintain them over the years.

# What is Babel?
ANS:-Babel is a free and open-source JavaScript transcompiler that is mainly used to convert ECMAScript
2015+ code into backwards-compatible JavaScript code that can be run by older JavaScript engines. 

# How does Babel convert html code in React into valid code?
ANS:-React arrived in 2013 as a better way to build web apps with JavaScript. It's often referred to as a library for building UIs,
short for "user interfaces".
What makes React such a desirable library to learn is that it doesn't replace HTML.
It takes advantage of HTML's popularity and strength as the most popular programming language,
by letting you use a very similar syntax to HTML to build interfaces and add dynamic features to it using JavaScript.

# Example:  <!DOCTYPE html>
<html>
  <head>
    <title>reactjs Search Results</title>
  </head>

  <body>
    <section>
      <div>
        <a href="https://reactjs.org"
          >React - A JavaScript Library for Building User Interfaces</a
        >
        <div>
          <h3>reactjs.org</h3>
        </div>
        <div>
          React makes it painless to create interactive UIs.
        </div>
      </div>
      <div>
        <a href="https://en.wikipedia.org/wiki/React_(web_framework)"
          >React (web framework) - Wikipedia</a
        >
        <div>
          <h3>https://en.wikipedia.org › wiki › React_(web_framework)</h3>
        </div>
        <div>
          React is a JavaScript library for building user interfaces.
        </div>
      </div>
      <div>
        <a href="https://twitter.com/reactjs?lang=en"
          >React (@reactjs) | Twitter</a
        >
        <div>
          <h3>https://twitter.com › reactjs</h3>
        </div>
        <div>
          The latest Tweets from React (@reactjs).
        </div>
      </div>
    </section>
  </body>
</html>

# What is ReactDOM used for? Write an example?
ANS:-ReactDOM is a package that provides DOM specific methods that can be 
used at the top level of a web app to enable an efficient way of managing DOM elements of the web page.
# Example: 
import React from 'react';
import ReactDOM from 'react-dom/client';

function Hello(props) {
  return <h1>Hello World!</h1>;
}
const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<Hello />);

# What are the packages that you need to import for react to work with?
ANS:- 14 Useful Packages Every React Developer Should Know. Increase your development productivity with these packages.
React Testing Library. The React Testing Library is a lightweight solution for testing React components. 
Framer Motion. 
styled-components. 
Cypress. 
Prettier. 
ESLint.
Redux.
 
 # How do you add react to a web application?
 
ANS:-Step 1: Add a DOM Container to the HTML. First, open the HTML page you want to edit.
Step 2: Add the Script Tags. Next, add three <script> tags to the HTML page right before the closing </body> tag: .
Step 3: Create a React Component. Create a file called like_button.js next to your HTML page.


# What is React.createElement?
ANS:-React. createElement( type, [props], [... children] ) Create and return a new React element of the given type. 
The type argument can be either a tag name string (such as 'div' or 'span' ),
a React component type (a class or a function), or a React fragment type.

# What are the three properties that createElement accept?
 ANS:- 
 # Syntax:
 React.createElement(type,{props},children); 
 type: the type of the HTML element (h1,p,button).
props: properties of the object({style:{size:10px}} or Eventhandlers, classNames,etc).
children: anything that need to be displayed on the screen.

# What is the meaning of render and root?
ANS:- render-Render derives from the Latin verb reddere, "to restore," from the prefix re-, "back," plus dare, "to give." Definitions of render. verb. give or supply. “The estate renders some revenue for the family”
root-The root node is the HTML element where you want to display the result. It is like a container for content managed by React.






