React Navigation Project (Vite)

This is a simple React project built using Vite.
The purpose of this project is to understand the basic structure of a React application, component-based development, client-side routing using React Router, and version control using Git and GitHub.

Project Objectives

Learn how a React project is structured

Understand component creation and reuse

Implement navigation using react-router-dom

Learn the difference between SPA and MPA

Practice pushing a project to GitHub

Project Setup

Created the project using Vite

Installed dependencies using:

npm install


Started the development server using:

npm run dev


The application runs in the browser without issues

Folder Structure
FSD-2/Experiment1
│
├── public
├── src
│   ├── components
│   │   ├── Home.jsx
│   │   └── About.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── index.html
├── package.json
├── vite.config.js
└── README.md

Explanation

src contains all the main React code

components contains page-level components like Home and About

App.jsx manages routing

main.jsx is the entry point of the React application

index.css is used for global styling

Components
Home Component

Functional React component

Contains a navigation bar

Uses Link from react-router-dom

Displays:

Home heading

Navigation links

Author name

About Component

Separate page component

Navigates without page reload

Uses React Router for smooth transitions

Routing

Routing is implemented using react-router-dom.

Components used:

BrowserRouter

Routes

Route

Link

Navigation happens without refreshing the page, making the application fast and responsive.

Styling

Styling is done using index.css

className is used instead of class

Styled elements include:

Navigation bar

Headings

Links

Running the Project Locally

To run this project on your system:

npm install
npm run dev

Git and GitHub Workflow

Initialized Git repository using git init

Added files using git add .

Committed changes using git commit

Created a GitHub repository

Pushed code using:

git push -u origin main

Architecture: SPA vs MPA
MPA (Multi Page Application)

Page reloads on every navigation

Server sends a new HTML file each time

Slower performance

SPA (Single Page Application)

Loads once

No full page reload

Only components and data change

Faster and smoother experience

Why This Project is an SPA

Built with React and Vite

Uses client-side routing

Navigation does not reload the page

Components update dynamically

Technologies Used

React.js

Vite

JavaScript (JSX)

HTML

CSS

Git & GitHub

What I Learned

React project structure

Component-based development

Routing in React

Basic Git and GitHub workflow

Author

Om Kumar Jha make it .md file