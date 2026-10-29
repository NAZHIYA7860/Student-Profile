# 🎓 Student Profile Management System

## 📌 Project Overview

The **Student Profile Management System** is a simple and interactive web application developed using React.js. This project demonstrates the fundamental concepts of React, including components, JSX, JavaScript expressions, props, and component reusability.

The application displays student information in a structured and attractive format. It contains a header, reusable student profile cards, and a footer. Each profile displays the student's name, department, and academic year.

This project is developed as part of **Task 1: Student Profiles Using Components, JSX and Props** to understand how React applications are divided into smaller, reusable components.

---

## 🎯 Objectives

The main objectives of this project are:

- To understand the basics of React.js.
- To learn how to create functional components.
- To understand JSX syntax and its usage.
- To use JavaScript variables inside React components.
- To learn how to pass data from one component to another using props.
- To create reusable components to avoid repeating code.
- To apply CSS styling to React components.
- To display student details dynamically using JSX expressions.
- To understand the basic structure of a React application.

---

## ✨ Features

### 1. Header Component
- Displays the heading **Student Management System**.
- Uses CSS styling to change the heading colour.
- Provides a consistent title for the application.

### 2. Student Profile Component
- Displays individual student information.
- Receives data through props.
- Shows the student's name, department, and academic year.
- Uses a border and padding to create a profile card.
- Supports multiple students using the same reusable component.

### 3. Multiple Student Profiles
The application displays two student profiles.

**Student 1**
- Name: Anu
- Department: CSE
- Year: 3rd Year

**Student 2**
- Name: Bala
- Department: Computer Science
- Year: 3rd Year

### 4. Footer Component
- Displays the text **© 2026 Student Management System**.
- Provides a consistent footer at the bottom of the application.

### 5. Component Reusability
- The same `StudentProfile` component is used for both students.
- Student details are passed through props.
- The code is easier to maintain and update.

### 6. Simple and Structured UI
- Organizes student information clearly.
- Uses JSX to display dynamic values.
- Applies CSS for borders, spacing, and colours.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Building the user interface |
| JavaScript | Storing student details and application logic |
| JSX | Writing HTML-like syntax inside JavaScript |
| CSS | Styling the header, profiles, and footer |
| HTML5 | Basic web page structure |
| Node.js and npm | Running the React development environment |
| Git and GitHub | Version control and project hosting |

---

## 📂 Project Structure

The project can be organized using the following structure:

```text
Student-Profile/
│
├── public/
│   └── vite.svg
│
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── StudentProfile.jsx
│   │   └── Footer.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── index.html
├── package.json
├── package-lock.json
└── README.md
```

*Note: The folder structure may differ depending on how the React project was created.*

---

## ⚙️ Concepts Implemented

### 1. React Components

Components are independent and reusable parts of a user interface.

This project uses three main components:

- `Header` – Displays the application heading.
- `StudentProfile` – Displays student details.
- `Footer` – Displays the footer message.

Components help organize the application into smaller sections.

### 2. JSX

JSX stands for JavaScript XML. It allows developers to write HTML-like code inside JavaScript.

Example:

```jsx
<h2>Student Management System</h2>
```

JSX makes React code easier to read and understand.

### 3. JavaScript Expressions

JavaScript expressions can be written inside curly braces `{}` in JSX.

Example:

```jsx
<h3>{name}</h3>
<p>{department}</p>
<p>{year}</p>
```

These expressions display the values stored in JavaScript variables or received through props.

### 4. Props

Props are used to pass data from a parent component to a child component.

Example:

```jsx
<StudentProfile
  name="Anu"
  department="CSE"
  year="3rd Year"
/>
```

The `StudentProfile` component receives these values and displays them.

### 5. Component Reusability

A reusable component can be used multiple times with different data.

Example:

```jsx
<StudentProfile
  name={student1.name}
  department={student1.department}
  year={student1.year}
/>

<StudentProfile
  name={student2.name}
  department={student2.department}
  year={student2.year}
/>
```

Both profiles use the same component, but each displays different student information.

### 6. CSS Styling

CSS is used to improve the appearance of the application.

Styling includes:
- Heading colours.
- Borders around student profiles.
- Padding inside profile cards.
- Spacing between components.
- Clear and readable text.

---

## 👨‍🎓 Student Information

| Student | Name | Department | Academic Year |
|---|---|---|---|
| Student 1 | Anu | CSE | 3rd Year |
| Student 2 | Bala | Computer Science | 3rd Year |

---

## 🚀 Installation and Setup

Follow these steps to run the project on your local computer.

### Step 1: Install Node.js

Download and install Node.js from:

https://nodejs.org/

Node.js includes npm, which is used to install project dependencies.

### Step 2: Create a React Project

Open a terminal and run:

```bash
npm create vite@latest Student-Profile -- --template react
```

### Step 3: Open the Project Folder

```bash
cd Student-Profile
```

### Step 4: Install Dependencies

```bash
npm install
```

### Step 5: Add the Project Code
