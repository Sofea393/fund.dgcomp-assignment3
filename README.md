from pathlib import Path

readme = """# Campusly — Student Timetable and Academic Planner

Campusly is a simple interactive student planner designed for engineering students.  
The program helps students set up their class timetable, track academic tasks, manage attendance records, and store absence or medical certificate submissions.

This project was developed as Part 2 of the **LDCW6123 Fundamentals of Digital Competence for Programmer** group assignment.

---

## Project Overview

Campusly is a browser-based interactive program built using HTML, CSS, and JavaScript.  
The system allows students to create a basic academic dashboard after entering their student profile and timetable information.

The project focuses on building a practical student support tool with clear user input, output, program logic, and interactive features.

---

## Features

### 1. Student Profile Setup
Users enter basic student details:

- Full name
- Engineering major
- Student ID

The profile information is then displayed inside the dashboard.

---

### 2. Timetable Setup
Users can set up their timetable in two ways:

- Manually add class details
- Use a sample timetable for quick testing or demonstration

Each timetable entry includes:

- Course code
- Subject name
- Class type
- Day
- Start time
- End time
- Location
- Lecturer

Before entering the dashboard, users can review, edit, add, or remove timetable rows.

---

### 3. Dashboard
The dashboard displays:

- Student details
- Next class
- Total number of classes
- Number of pending tasks
- Average attendance percentage

---

### 4. Timetable Management
After setup, users can continue editing their timetable from the Timetable page.

Users can:

- Add new timetable rows
- Edit existing rows
- Delete rows
- Save timetable changes

---

### 5. Task Tracker
Users can manually add academic tasks such as:

- Assignments
- Lab reports
- Quizzes
- Midterms
- Final exams
- Reminders

Each task includes:

- Course
- Task type
- Task name
- Due date

Users can mark tasks as completed or delete them.

---

### 6. Attendance and Absence Management
The Absence & Medical page allows users to:

- View attendance percentage by course
- Update attendance manually
- Record absence details
- Attach a medical certificate file name
- Delete absence records

---

### 7. Saved Progress

The program can save progress in the browser using `localStorage`.

Saved data includes:

- Student profile
- Timetable
- Tasks
- Attendance percentages
- Absence records

A reset button is provided to clear saved data.

> Note: Since this is a front-end prototype, saved data is stored only on the same browser and device. It is not stored in an online database.

---

## Technologies Used

- HTML
- CSS
- JavaScript
- Browser `localStorage`

No external framework is required.

---

## How to Run the Project

### Method 1: Open Locally

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.

Example:

```text
Campusly/
│
├── index.html
└── README.md
