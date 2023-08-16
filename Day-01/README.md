<div align="center">
<img  height="100%"  src="https://i.ibb.co/WxJdF0b/react-logo.png" />
</div>

<div align="center">

  <h1>Day - 01 in React</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/coding-ranjith-97b6ab238">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>

  <a class="header-badge" target="_blank" href="https://youtube.com/@coding-ranjith">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=Youtube&logo=youtube&style=social">
  </a>

<sub>Author: <a href="https://www.linkedin.com/in/coding-ranjith-97b6ab238" target="_blank">Coding Ranjith</a><br>
<small> August to September, 2023</small></sub>

</div>


- [Introduction](#introduction)
- [Setup](#setup)
- [React ES6](#react-es6)
- [React Render](#react-render)
  
--- 

## Introduction


### What is React?

<div align="center">
<img  height="80%"  src=""/>
</div>

ReactJS, a JavaScript library for creating user interfaces,makes the development of UI components easy and modular.
React JS was created by Jordan Walke, a software engineer at Facebook and open sourced to the world by Facebook and Instagram.

### The key features of React are:

- Component-based architecture: A Component is the smallest unit in a React application. Anything that you want to render on the browser can be rendered through components. Components help in maintainability and re-usability.
- Virtual DOM: React uses virtual DOM concept for DOM manipulation which improves the performance of the application
Unidirectional data flow:  React’s one-way data flow (also called one-way binding) keeps everything modular and fast and easy for debugging.
- JSX syntax: React used JSX syntax which is similar to XML and HTML syntax which makes it easy for writing markup and binding events in components 
- SEO performance: The SEO performance can be improved using the server-side rendering concept. We can develop isomorphic applications using React which increases the SEO performance.

### Angular is one of the popular frameworks used for UI development. Let us compare React and Angular in brief:

| REACT | ANGULAR |
| ----- | :-------------------------------------------------------------------------------------------------------------------------: |
| React is a small view library | Angular is a full framework | 
| React covers only the rendering and event handling part | Angular provides the complete solution for front-end development |
| Presentation code in JavaScript powered by JSX | Presentation code in HTML embedded with JavaScript expressions |
| React's core size is smaller than Angular, so bit fast | Angular being a framework contains a lot of code, resulting in longer load time |
| React is very flexible | Angular has less flexibility |
| Great performer, since it uses Virtual DOM | Angular uses actual DOM which affects its performance |

---

## Setup

### To install create-react-app, follow the below steps:

If you have npx and Node.js installed, you can create a React application by using create-react-app.

You can check the node version installed 

```bash
D:\> node -v
v17.2.0
```

If you've previously installed create-react-app globally, it is recommended that you uninstall the package to ensure npx always uses the latest version of create-react-app.

To uninstall, run this command: npm uninstall -g create-react-app.

Run this command to create a React application named my-react-app:

```bash
npx create-react-app my-react-app
```

Run the React Application
Now you are ready to run your first real React application!

Run this command to move to the my-react-app directory:

```bash
cd my-react-app
```

Run this command to run the React application my-react-app:

```bash
npm start
```

A new browser window will pop up with your newly created React App! If not, open your browser and type localhost:3000 in the address bar.

Output :

<div align="center">
<img  height="80%"  src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" />
</div>

### Modify the React Application

So far so good, but how do I change the content?

Look in the my-react-app directory, and you will find a src folder. Inside the src folder there is a file called App.js, open it.

Replace all the content inside the <div className="App"> with a h1 element.

See the changes in the browser when you click Save.

<div align="center">
<img  height="80%"  src="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-logo-shadow.png" />
</div>

### Upgrade to React 

To install the latest version, from your project folder run the following from the terminal:

```bash
npm i react@latest react-dom@latest
```













 




[Day 2 >>]()


❤️👨‍💻❤️ HAPPY CODING ❤️😇❤️






