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


- Introduction to React, setup development environment (Node.js, npm/yarn, code editor). 
  - [Learn about React's role and advantages.](#introduction)
  - [Install Node.js and a code editor.](#setup)
  - [Set up your first React project using create-react-app.](#first-react-app)
 
    
--- 

## Introduction

### Learn about React's role and advantages.

### What is React?

<div align="center">
<img  height="80%"  src="https://i.ibb.co/WxJdF0b/react-logo.png"/>
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

### What is Node.js ?

- Node.js is an open source server environment
- Node.js is free
- Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
- Node.js uses JavaScript on the server

### What can Node.js Do ?

- Node.js can generate dynamic page content
- Node.js can create, open, read, write, delete, and close files on the server
- Node.js can collect form data
- Node.js can add, delete, modify data in your database

### What is npm ?

npm is the world's largest Software Registry.
The registry contains over 800,000 code packages.
Open-source developers use npm to share software.
Many organizations also use npm to manage private development.

```bash
npm install <package>
```

---

## Setup

### Install Node.js and a code editor

#### Install Node.js

The first step to install Node.js on windows is to download the installer. Visit the official Node.js website i.e) https://nodejs.org/en/download/ and download the .msi file according to your system environment (32-bit & 64-bit). An MSI installer will be downloaded on your system.

Double click on the .msi installer.

Verify that Node.js was properly installed or not.

```bash
D:\> node -v
v20.3.1
```
Example:

<img src="https://i.ibb.co/m57KVdQ/node.png" alt="node-version" />

#### Install code editor

[Visual Studio](https://code.visualstudio.com/download)

---

## First React App

### Set up your first React project using create-react-app

If you have npx and Node.js installed, you can create a React application by using create-react-app.

If you've previously installed create-react-app globally, it is recommended that you uninstall the package to ensure npx always uses the latest version of create-react-app.

To uninstall, run this command: npm uninstall -g create-react-app.

Run this command to create a React application named react-challenge:

```bash
npx create-react-app react-challenge
```

Run the React Application
Now you are ready to run your first real React application!

Run this command to move to the react-challenge directory:

```bash
cd react-challenge
```

Run this command to run the React application my-react-app:

```bash
npm start
```

A new browser window will pop up with your newly created React App! If not, open your browser and type localhost:3000 in the address bar.

Output :

<div align="center">
<img  height="80%"  src="https://i.ibb.co/k5GWjq7/react-app.png" />
</div>

### Modify the React Application

So far so good, but how do I change the content?

Look in the my-react-app directory, and you will find a src folder. Inside the src folder there is a file called App.js, open it.

Replace all the content inside the <div className="App"> with a h1 element.

See the changes in the browser when you click Save.

<div align="center">
<img  height="80%"  src="https://i.ibb.co/3h9H42j/rk-react-code.png" />
</div>

Output:

<div align="center">
<img  height="80%"  src="https://i.ibb.co/6sqc9s6/rk-react.png" />
</div>

### Upgrade to React 

To install the latest version, from your project folder run the following from the terminal:

```bash
npm i react@latest react-dom@latest
```



[Day 2 >>]()


❤️👨‍💻❤️ HAPPY CODING ❤️😇❤️






