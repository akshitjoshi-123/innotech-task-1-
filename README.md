# INNOTECH Internship Assignment - Task 1: Authentication UI

This project is a front-end implementation of a multi-screen user authentication flow, built as a submission for the Full Stack Developer Internship technical assignment at INNOTECH. The user interface is a faithful reproduction of the provided Figma design.

### **Project Overview**

The goal of this task was to build a fully responsive and interactive authentication interface. The project consists of a single-page application that simulates a complete user flow, including user registration, login, and password recovery. The focus was on creating a clean, intuitive, and pixel-perfect UI that matches the design specifications.

### **Features Implemented**

- **Multi-Screen Flow:** A seamless, interactive flow between different authentication screens.
- **Signup Form:** A comprehensive registration form with fields for email, password, role selection, and terms agreement.
- **Login Form:** A standard login interface with a "Forgot Password?" link.
- **Password Recovery:** A complete "Forgot Password" flow that leads to a confirmation screen.
- **Confirmation Screens:** Dedicated views to confirm actions like successful registration or password reset instructions being sent.
- **Responsive Design:** The layout is fully responsive and optimized for a seamless experience on all devices, from mobile phones to desktop monitors.

---

### **Technology Stack**

This project was built using fundamental web technologies to demonstrate core front-end skills.

- **HTML5:** Utilized for structuring the content with semantic markup.
- **Tailwind CSS:** A utility-first CSS framework was used for rapid and precise styling to match the Figma design system.
- **JavaScript (Vanilla):** Used for DOM manipulation to handle the interactive elements, such as switching between different views (Signup, Login, etc.) without page reloads.

---

### **Development Approach**

- **Single-Page Structure:** I chose to build this as a single HTML file containing all the different "views" or screens. A simple JavaScript function (`switchView`) manages the visibility of these views, creating the illusion of a multi-page application. This approach is lightweight, fast, and avoids the need for a more complex front-end framework or router for this specific task.
- **Figma-Driven Design:** The development process was driven directly by the Figma prototype. I meticulously extracted design tokens like colors, fonts, spacing, and component layouts to ensure the final product is a high-fidelity match.
- **Component-Based Thinking:** Although built with a single HTML file, the layout was mentally broken down into reusable components (forms, buttons, side panels), and styled consistently using Tailwind's utility classes.

---

### **How to Run Locally**

This project requires no complex setup or build process.
