<div align="center">
<img  height="100%"  src="https://i.ibb.co/WxJdF0b/react-logo.png" />
</div>

<div align="center">

  <h1>Day - 02 in React</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/coding-ranjith-97b6ab238">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>

  <a class="header-badge" target="_blank" href="https://youtube.com/@coding-ranjith">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=Youtube&logo=youtube&style=social">
  </a>

<sub>Author: <a href="https://www.linkedin.com/in/coding-ranjith-97b6ab238" target="_blank">Coding Ranjith</a><br>
<small> August to September, 2023</small></sub>

</div>


- Day 2: JSX syntax, rendering elements, and understanding components. 
  - [Explore JSX syntax.](#jsx-syntax)
  - [Create and render React elements.](#react-render)
  - [Understand the component structure.](#react-components)
 
    
--- 

## JSX syntax

### Explore JSX syntax.

#### What is JSX ?

JSX stands for JavaScript XML.

JSX allows us to write HTML in React.

JSX makes it easier to write and add HTML in React.

### Coding JSX.

JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods.
JSX converts HTML tags into react elements.

Example:

JSX:
```bash
const myElement = <h1>Hi Guys!</h1>;

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(myElement);
```

Without JSX:
```bash
const myElement = React.createElement('h1', {}, 'I do not use JSX!');

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(myElement);
```

---

## React Render

### Create and render React elements

React's goal is in many ways to render HTML in a web page.

React renders HTML to the web page by using a function called createRoot() and its method render().

The createRoot Function
The createRoot() function takes one argument, an HTML element.

The purpose of the function is to define the HTML element where a React component should be displayed.

The render Method
The render() method is then called to define the React component that should be rendered.

### But render where?

There is another folder in the root directory of your React project, named "public". In this folder, there is an index.html file.

You'll notice a single <div> in the body of this file. This is where our React application will be rendered.

Example :

Display a paragraph inside an element with the id of "root":

```bash
const container = document.getElementById('root');
const root = ReactDOM.createRoot(container);
root.render(<p>Hello</p>);
```

The result is displayed in the <div id="root"> element:

```bash
<body>
  <div id="root"></div>
</body>
```

### The HTML Code

The HTML code in this tutorial uses JSX which allows you to write HTML tags inside the JavaScript code:

Do not worry if the syntax is unfamiliar, you will learn more about JSX in the next chapter.

Example: 

Create a variable that contains HTML code and display it in the "root" node:

```bash
const myelement = (
  <table>
    <tr>
      <th>Name</th>
    </tr>
    <tr>
      <td>John</td>
    </tr>
    <tr>
      <td>Elsa</td>
    </tr>
  </table>
);

const container = document.getElementById('root');
const root = ReactDOM.createRoot(container);
root.render(myelement);
```

## React Components

### Understand the component structure

#### What is a ReactJS Component?

A Component is one of the core building blocks of React. In other words, we can say that every application you will develop in React will be made up of pieces called components. Components make the task of building UIs much easier. You can see a UI broken down into multiple individual pieces called components and work on them independently and merge them all in a parent component which will be your final UI. 





[Day 2 >>]()


❤️👨‍💻❤️ HAPPY CODING ❤️😇❤️






