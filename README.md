# 💰 JavaScript Employee Payroll Tracker

A browser-based payroll management app built in vanilla JavaScript. A manager can add employees interactively via browser prompts, view them sorted by last name in a table, and see the average salary and a randomly selected employee logged to the console.

---

## 📖 Overview

This project focuses on core JavaScript fundamentals: loops, arrays, objects, DOM manipulation, and `Math.random`. The UI renders a sortable employee table from data collected entirely through browser `prompt()` dialogs — no HTML form needed.

---

## ✨ Features

- ➕ Add multiple employees in one session using a `while` loop with a continue prompt
- 📊 Displays all employees in a dynamically rendered HTML table, sorted A–Z by last name
- 💵 Salary defaults to `$0` if a non-numeric value is entered
- 📉 Logs the average salary and total employee count to the console
- 🎲 Logs a randomly selected employee's full name to the console

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Logic | Vanilla JavaScript (ES6) |
| Markup | HTML5 |
| Styling | CSS3 |
| Deployment | GitHub Pages |

---

## 🚀 Getting Started

No install or build step — open directly in a browser.

```bash
git clone https://github.com/Voobane/JavaScript-Employee-Payroll-Tracker.git
cd JavaScript-Employee-Payroll-Tracker
open index.html
```

Click **Add Employees** to start entering data.

---

## 📁 Project Structure

```
JavaScript-Employee-Payroll-Tracker/
├── index.html         # App shell with the "Add Employees" button
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js  # collectEmployees, displayAverageSalary, getRandomEmployee
└── README.md
```

---

## 💡 What I Learned

- Using a **`while` loop** to collect a variable number of inputs
- Building and sorting an **array of objects** by a property value
- Calculating an **average** from an array with `reduce`
- Picking a **random array element** with `Math.random` and `Math.floor`
- Dynamically updating the **DOM** to render a table from a data array

---

## 📸 Screenshots

> _Add screenshots to the repo and update this section._

---

## 👤 Author

**Matt (Voobane)**
- GitHub: [@Voobane](https://github.com/Voobane)
