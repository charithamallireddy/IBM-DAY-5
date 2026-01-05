# IBM-DAY-5

 📚 Library Book Management System – Frontend (React + Vite)

This repository contains the **frontend implementation** of a **Library Book Management System** developed using **React** and **Vite**.
The project demonstrates how a modern React application is structured and how different configuration and source files work together to build a web application.

This project is created mainly for **learning purposes**, focusing on:

* React fundamentals
* Project structure understanding
* Dependency management using npm
* Using Git and GitHub for version control
 🎯 Project Objective (Why this project exists)

The main objectives of this project are:

* To understand how a **React frontend project** is organized
* To learn the role of important files like `package.json`, `index.html`, and `App.jsx`
* To practice running a React application using **Vite**
* To learn how to push a complete project to **GitHub**
* To build confidence in explaining a project during **viva or evaluation**
 🛠️ Technologies Used

* **React** – For building user interface components
* **Vite** – For fast development server and build process
* **JavaScript (ES6)** – Core programming language
* **HTML5** – Basic web structure
* **CSS** – Styling the UI
* **Git & GitHub** – Version control and code hosting
 📁 Project Files – Detailed Explanation

Below is a **detailed explanation of each important file** in this repository.
🔹 1. `package.json` – Project Configuration File

`package.json` is the **most important file** in a React / Node.js project.

 📌 Purpose of `package.json`

* Identifies the project (name and version)
* Manages all required libraries (dependencies)
* Defines commands (scripts) to run and build the project
* Tells npm how the project should behave

In simple words:

> `package.json` acts as the **instruction manual** of the project.

 📌 Important Sections in `package.json`

 ✔ Project Information

* **name** – Name of the project
* **version** – Current version of the project
* **private** – Prevents accidental publishing to npm

This information helps identify the project uniquely.

 ✔ Scripts Section

Scripts are **commands** that help run the project easily.

Common scripts used:

* `npm run dev` → Starts the development server
* `npm run build` → Creates optimized production files
* `npm run preview` → Previews the production build

These scripts save time and avoid writing long commands manually.
 ✔ Dependencies

Dependencies are **libraries required for the application to run**.

* `react` – Used to create UI components
* `react-dom` – Used to render React components in the browser

Without these, a React application cannot function.
 ✔ Dev Dependencies

Dev dependencies are tools used **only during development**.

Examples:

* **Vite** – Fast build and development tool
* **ESLint** – Helps find coding errors

These tools are not included in the final production output.

🔹 2. `package-lock.json` – Dependency Lock File

`package-lock.json` is an **auto-generated file** created by npm.

 📌 Purpose of `package-lock.json`

* Stores the **exact versions** of all installed dependencies
* Maintains a complete dependency tree
* Ensures the project behaves the same on all machines

This file avoids problems like:

> “It works on my system but not on yours.”
📌 Important Notes

* This file should **never be edited manually**
* It should always be pushed to GitHub
* It improves project reliability and consistency
🔹 3. `index.html` – Main HTML Entry File

`index.html` is the **only HTML file** used in a React application.

📌 Purpose of `index.html`

* Acts as the **starting point** of the web application
* Loaded first by the browser
* Contains a root element where React renders the UI

Inside `index.html`, there is:

```html
<div id="root"></div>
```

This is **very important** because:

* React does not directly write HTML pages
* Instead, React renders everything inside this `root` div
* The entire UI is controlled by JavaScript (React)
 📌 Script Loading

The script tag loads the main React file:

* This starts the React application
* Connects HTML with React components
🔹 4. `App.jsx` – Root React Component

`App.jsx` is the **main React component** of the application.

📌 Purpose of `App.jsx`

* Acts as the **entry point of the UI**
* Controls the main layout of the application
* Imports and displays child components
* Displays the main heading of the project
 📌 Why `App.jsx` is Important

* All other components are connected to `App.jsx`
* It represents the top level of the component hierarchy
* Any UI change usually starts from this file
 📌 Key Concepts Used

* **Functional Component** – Modern React approach
* **JSX** – HTML-like syntax inside JavaScript
* **Component Import & Export** – Code reusability
🔹 5. `react.svg` – Static Asset File

`react.svg` is a **static image asset**.

📌 Purpose

* Used as an icon or logo
* Helps in UI appearance and branding
* Safe and common to include in frontend projects

▶️ How to Run the Project Locally

To run this project on your system:

1. Clone the repository
2. Install dependencies using `npm install`
3. Start the development server using `npm run dev`
4. Open the browser and access the local server URL

This will start the React application successfully.

 📌 GitHub Best Practices Followed

* `node_modules` folder is excluded using `.gitignore`
* Dependency lock file is included
* Clear project structure
* Meaningful commit messages
* Clean and readable README documentation

🎓 Learning Outcomes

From this project, I learned:

* Structure of a React + Vite project
* Role of each important configuration file
* How React renders UI using a root element
* How npm manages dependencies
* How to push and manage projects on GitHub

