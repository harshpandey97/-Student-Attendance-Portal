# 🎓 Student Attendance Portal

A lightweight, browser-based attendance tracker built with vanilla HTML, CSS, and JavaScript — no backend, no database, no frameworks. Create classes, add students, mark each one Present / Absent / Leave, and see a live summary as you go.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🔗 Live Demo
[View live site](https://harshpandey97.github.io/ecommerce/ecommerce%20website/)

## ✨ Features
- **Add classes** on the fly and switch between them from a dropdown
- **Add students** to any class with name + roll number
- **Mark attendance** per student as Present, Absent, or Leave
- **Live summary** — total students, present, absent, and on leave, updating instantly
- **Submit attendance** to generate a timestamped result card for the selected class

## 🛠️ Built With
- HTML5
- CSS3
- Vanilla JavaScript (no frameworks or libraries)
- Deployed via GitHub Pages using GitHub Actions

## 📂 Project Structure
```
ecommerce/
├── .github/workflows/
│   └── static.yml         # GitHub Pages deployment workflow
└── ecommerce website/
    ├── index.html          # App markup
    ├── style.css           # Styling
    └── script.js           # App logic (classes, students, attendance state)
```

## 🚀 Running Locally
```bash
git clone https://github.com/harshpandey97/ecommerce.git
cd "ecommerce/ecommerce website"
```
Then open `index.html` directly in your browser — no build step or server required.

## 📌 Notes
- All data lives in memory for the current session only — refreshing the page clears it. There's no `localStorage` or backend yet.
- Beyond "required" form fields, there's no validation, so duplicate roll numbers or empty class names aren't currently blocked.

## 🔮 Possible Improvements
- Persist data with `localStorage` (or a small backend) so attendance survives a refresh
- Export attendance records as CSV/PDF
- Add edit/delete for existing students and classes
- Track date-wise attendance history instead of a single running session

## 👤 Author
**Harsh Pandey**
GitHub: [@harshpandey97](https://github.com/harshpandey97)
