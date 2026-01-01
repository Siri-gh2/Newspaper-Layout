# Newspaper Layout – Web Project (Code360)

This project implements a **responsive newspaper-style layout** using **HTML, CSS, and JavaScript**, as part of a **Web Development problem on Code360 (by Naukri / Coding Ninjas)**.

The objective of this task was to understand and apply **CSS multi-column layouts**, **responsive design**, and **light/dark mode toggling** strictly according to the instructions provided in the starter kit.

---

## 📌 Problem Source

- Platform: **Code360 (Coding Ninjas / Naukri)**
- Track: **Web Projects**
- Problem Name: **Newspaper Layout**
- Focus Areas:
  - CSS Multi-column Layout
  - Responsive Design
  - Light & Dark Mode Toggle
  - CSS Variables
  - DOM Manipulation with JavaScript

---

## 🧩 Features Implemented

### ✅ Responsive Newspaper Layout
- Uses **CSS multi-column layout** on the `<section>` tag
- Column behavior by screen size:
  - **Small screens**: 1 column
  - **Medium screens (≥768px)**: 2 columns with column rule
  - **Large screens (≥1200px)**: 3 columns with column rule
- Correct `column-gap` values applied as per instructions

---

### ✅ Light & Dark Mode Toggle
- Default mode: **Dark mode**
- Toggle button switches between:
  - 🌙 Dark Mode
  - 🌞 Light Mode
- Implemented using:
  - CSS variables
  - `.light-mode` class on `<body>`
  - JavaScript DOM manipulation

---

### ✅ Column Spanning Content
- Special paragraphs with class `.span-all`
- These span across **all columns** using:
  ```css
  column-span: all;

**Technologies Used**

HTML5 – semantic structure

CSS3

CSS Variables

Multi-column Layout

Media Queries

JavaScript (Vanilla JS)

Event listeners

Class toggling

DOM selection

No frameworks or libraries were used.

**Project Structure**

Newspaper-Layout/
│
├── index.html     # Main HTML structure
├── index.css      # Styling & responsive column layout
├── script.js      # Light/Dark mode toggle logic
└── README.md      # Project documentation


🎯 Key Learnings

How CSS multi-column layouts work

Difference between column-gap and column-rule

Using CSS variables for theming

Implementing light/dark mode without frameworks

Writing code that passes strict automated test cases

🚀 Status

✔ Completed
✔ Tested
✔ submitted on code360

📝 Note

This project was implemented strictly according to the Code360 starter kit and instructions.
No additional styling or logic beyond the required specifications was added.

Author: Korupolu Siri
Platform: Code360
Purpose: Learning & Practice (Web Development – Responsive Layouts)

