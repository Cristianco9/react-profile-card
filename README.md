# React Profile Card

A beginner-friendly React.js project designed to introduce the fundamental 
concepts of modern React development.

This application displays a developer profile card with personal information, 
technical skills, and a dynamic availability status that can be updated through 
user interaction.

The project was built as part of the React.js Fundamentals module and 
demonstrates the core principles of component-based development.

---

## Learning Objectives

By completing this project, students will learn how to:

* Create and run a React application using Vite
* Understand the React project structure
* Create reusable React components
* Use JSX syntax
* Pass data using Props
* Manage component state with the `useState` Hook
* Handle user events
* Implement conditional rendering
* Apply CSS styling to React components
* Build responsive and reusable user interfaces

---

## Features

* Developer Profile Card
* Dynamic Availability Status
* Interactive Button
* Skills Display Section
* Component-Based Architecture
* Modern and Clean User Interface

---

## Technologies Used

* React.js
* JavaScript (ES6+)
* Vite
* HTML5
* CSS3

---

## Concepts Covered

### React Components

The application is divided into reusable components that encapsulate their 
own structure, behavior, and styling.

### JSX

The user interface is built using JSX, which combines JavaScript and 
HTML-like syntax.

### Props

Props are used to pass data from parent components to child components.

Example:

```jsx
<ProfileCard
  name="Cristian Camilo"
  role="Full Stack Developer"
/>
```

### State Management

The `useState` Hook is used to manage dynamic data within components.

Example:

```jsx
const [available, setAvailable] = useState(true);
```

### Event Handling

User interactions are handled through event listeners.

Example:

```jsx
<button onClick={handleChangeStatus}>
  Change Status
</button>
```

### Conditional Rendering

The interface updates dynamically based on component state.

Example:

```jsx
available
  ? "Available"
  : "Busy"
```

### Rendering Lists

Arrays are rendered dynamically using the `.map()` method.

Example:

```jsx
skills.map((skill) => (
  <div key={skill.id}>
    {skill.name}
  </div>
))
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Cristianco9/react-profile-card.git
```

Navigate to the project directory:

```bash
cd react-profile-card
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

---

## Application Components

### ProfileCard

Displays:

* Profile Picture
* Developer Name
* Professional Role
* Skills
* Availability Status

### SkillsList

Displays:

* Developer Skills
* Skill Level Information
* Show/Hide Skills Functionality

---

## Educational Purpose

This project was developed as a practical introduction to React.js and serves 
as a foundation for more advanced topics such as:

* Forms and Controlled Components
* React Hooks
* State Management
* API Consumption
* CRUD Applications
* React Router
* Full-Stack Web Development

---

## Author

Created as part of the React.js Fundamentals course to help students understand 
modern frontend development using React.
