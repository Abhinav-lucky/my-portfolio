# 🌐 Task 2 — Version Control with Git

> A personal portfolio website built with **HTML & CSS**, managed and version-controlled using **Git & GitHub** as part of the **DecodeLabs DevOps Internship – Batch 2026**.

---

## 📌 Project Overview

This project is part of **Project 2: Version Control with Git** under the DecodeLabs Industrial Training Kit. The goal was not just to build a portfolio — but to manage it like a **professional software engineer** using industry-standard Git workflows.

| Detail | Info |
|---|---|
| **Intern** | Abhinav Marrela |
| **Role** | DevOps Engineer Intern |
| **Organization** | DecodeLabs |
| **Batch** | 2026 |
| **Project** | Task 2 — Version Control with Git |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and layout |
| Git | Local version control |
| GitHub | Remote repository & collaboration |
| GitHub Actions | CI/CD Pipeline (Project 3) |

---

## 📁 Project Structure

```
Task-2-Abhinav_Marrela/
│
├── My_Portfolio/
│   ├── portfolio.html        # Main portfolio webpage
│   └── style.css             # Stylesheet for all sections
│
├── outputs/
│   ├── 1.png                 # Screenshot of portfolio website
│   ├── 2.png                 # Screenshot of GitHub commit history
│   └── 3.png                 # Screenshot of Git commands executed
│
├── .gitignore                # Excludes OS, editor & env files
└── README.md                 # Project documentation
```

---

## ⚙️ Installation & Setup

```bash
# Step 1: Clone the repository
git clone https://github.com/Abhinav-lucky/my-portfolio.git

# Step 2: Navigate into the project folder
cd Task-2-Abhinav_Marrela

# Step 3: Open the portfolio in your browser
start My_Portfolio/portfolio.html        # Windows
open My_Portfolio/portfolio.html         # Mac
xdg-open My_Portfolio/portfolio.html     # Linux
```

---

## 🌿 Git Workflow Followed

This project follows a **Trunk-Based Development** strategy — the modern industry standard for CI/CD-ready codebases.

```
main (Production Ready)
 └── feature/add-gitignore  →  Merged via Pull Request
```

### Commit History Strategy

Every commit represents a **single logical unit of work** with professional imperative-verb messages:

| Commit | Message | Purpose |
|---|---|---|
| 1 | `Init: Add README to initialize project` | Project initialization |
| 2 | `Add: Add portfolio homepage with HTML structure` | Core content added |
| 3 | `Style: Extract CSS into separate style.css file` | Separation of concerns |
| 4 | `Add: Add internship experience section to portfolio` | Content enhancement |
| 5 | `Docs: Update README with project description and usage` | Documentation |
| 6 | `Add: Add .gitignore to exclude unnecessary files` | Repo hygiene via PR |

---

## 🔐 .gitignore Coverage

```
# OS Files
.DS_Store
Thumbs.db

# Editor Files
.vscode/
.idea/

# Log Files
*.log

# Temp Files
*.tmp
*.temp

# Environment Files
.env
.env.local
```

---

## 📋 Portfolio Sections

- 🎯 Hero — Introduction and designation
- 👤 About — Personal background
- 🚀 Projects — Showcase of work
- 🛠️ Skills — Technical skillset
- 🔧 Tools & Libraries — Technologies used
- 🏫 Workshops — Training attended
- 📜 Certificates — Achievements
- 🎓 Education — Academic background
- 💼 Internship Experience — DecodeLabs DevOps Intern
- 🌐 Languages — Programming & spoken languages
- 📬 Contact — Reach out information

---

## 🔁 CI/CD Pipeline

> This repository is the **active trigger** for **Project 3: CI/CD Pipelines**.

A GitHub Actions workflow will be added in Project 3 to:
- Automatically validate code on every `git push`
- Run build and test steps
- Deploy to a live web address

**Status:** 🔄 Coming in Project 3

---

## 📞 Contact

| Platform | Link |
|---|---|
| 💼 LinkedIn | [linkedin.com/in/lucky-abhinav](https://www.linkedin.com/in/lucky-abhinav/) |
| 🐙 GitHub | [github.com/Abhinav-lucky](https://github.com/Abhinav-lucky) |

---

## 📄 License

```
MIT License
Copyright (c) 2026 Abhinav Marrela
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software to use, copy, modify, merge, publish, and
distribute it, subject to the following conditions: The above copyright
notice shall be included in all copies or substantial portions of the software.
```

---

<div align="center">

**Built with 💻 by Abhinav Marrela | DecodeLabs DevOps Intern – Batch 2026**

⭐ Star this repo if you found it helpful!

</div>
