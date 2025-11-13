# 🎓 Computer Science Department - SIT Nagpur Portal

A modern, responsive web portal for the Computer Science Department at Symbiosis Institute of Technology (SIT), Nagpur.

This portal is designed to provide quick access to department information, a student database overview, and key academic/service details.

## ✨ Features

* **Department Focus:** Dedicated page for the Computer Science Department.
* **Student Database:** A viewable, scrollable table featuring student records (Roll No, Name, Department, Year, and Resume link).
* **Responsive Navigation:** Navigation links (`Home`, `Database`, `About`, `Contact`) with smooth scrolling to relevant sections.
* **Interactive Hero Section:** Buttons for a **Welcome Message** (Alert) and **Student Information** (Modal).
* **Student Info Modal:** A detailed, dismissible popup providing:
    * Academic Information (Enrollment, Calendar, Grading System).
    * Student Services (Library, Lab Facilities, Placement Support).
    * Student Activities (Coding Competitions, Tech Clubs, Workshops).
* **Department Overview:** Highlights of the department's core strengths (Modern Curriculum, Research Excellence, Industry Connect).
* **Contact Information:** Detailed contact section with address, phone, and email.
* **Modern Design:** Utilizes **Tailwind CSS** for a clean, professional, and gradient-enhanced look.

---

## 💻 Technology Stack

* **HTML5:** Structure and Content.
* **Tailwind CSS:** Utility-first framework for styling and responsiveness.
* **JavaScript:** For interactive elements like the Welcome Alert, Student Info Modal, and smooth scrolling.

---

## 🛠️ Usage

### Installation

No installation is required. Simply download the `Version 2.html` file and open it in any modern web browser.

### Key JavaScript Functions

| Function | Description | Trigger |
| :--- | :--- | :--- |
| `showWelcomeAlert()` | Displays a standard browser alert box with the message "Welcome to SIT Nagpur". | Triggered by the **Welcome Message** button and automatically 1 second after page load. |
| `showStudentInfo()` | Displays the full-screen **Student Information Modal**. | Triggered by the **Student Information** button. |
| `hideStudentInfo()` | Closes the **Student Information Modal** and restores background scrolling. | Triggered by the 'Close' button and the 'X' icon within the modal, or clicking the semi-transparent background. |
| **Smooth Scrolling** | Implements smooth scrolling behavior for all internal navigation links (`#home`, `#database`, etc.). | Triggered by clicking a navigation link. |
