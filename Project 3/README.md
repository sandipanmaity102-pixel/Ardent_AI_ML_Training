
[README (1).md](https://github.com/user-attachments/files/25435135/README.1.md)
# 🚀 Sandipan Maity — AI & Python Portfolio

A modern, fully responsive personal portfolio website built with pure HTML, CSS, and vanilla JavaScript — showcasing AI/ML projects, skills, workshops, and contact information for **Sandipan Maity**, a B.Sc (CSE) student at Haldia Institute of Management.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sandipan%20Maity-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/sandipan-maity-35447839a)
[![GitHub](https://img.shields.io/badge/GitHub-programmer--sandipan-181717?style=flat&logo=github)](https://github.com/programmer-sandipan)

---

## 🌐 Live Preview

> Open `index.html` directly in your browser — no build tools, no dependencies, no server required.

---

## ✨ Features

- **Animated Hero Section** — Gradient text, animated typing effect cycling through AI/ML topics, and a live blinking cursor
- **Particle Canvas Background** — Smooth floating particles with connecting lines rendered via the HTML5 Canvas API
- **Glassmorphism UI** — Frosted-glass cards and panels with layered gradient overlays and soft box shadows
- **Scroll Progress Bar** — A thin accent-colored bar at the top that tracks reading progress
- **Scroll Reveal Animations** — Cards and sections fade and slide in as they enter the viewport using IntersectionObserver
- **Sticky Navigation** — Blurred, semi-transparent header that stays fixed on scroll with smooth anchor navigation
- **Responsive Mobile Menu** — Collapsible drawer for small screens, fully accessible
- **Stats Panel** — Quick-read metrics: projects completed, focus area, ML model used, and tools
- **Dynamic Footer Year** — Auto-updates the copyright year via JavaScript

---

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Complete single-file portfolio (HTML + CSS + JS)
└── README.md           # Project documentation
```

> All styles and scripts are embedded directly in `index.html` — no external files needed beyond the Font Awesome CDN for icons.

---

## 🗂️ Page Sections

| Section | Description |
|---------|-------------|
| **Hero** | Introduction, animated typing effect, quick-stats panel, and CTA buttons |
| **About** | Who I am, what I'm learning, and my mentorship journey |
| **Skills** | Python Foundations, Data Handling (Pandas), and Visualization (Matplotlib) |
| **Projects** | EDA Dashboard (Titanic) and House Price Prediction (Linear Regression) |
| **Workshops** | Ardent AI/ML Workshop and Code_ScholarEU learning experience |
| **Contact** | Email, LinkedIn, GitHub, and mentor information |

---

## 🛠️ Tech Stack

| Technology | Role |
|------------|------|
| HTML5 | Page structure and semantic markup |
| CSS3 | Custom properties, glassmorphism, animations, responsive grid |
| Vanilla JavaScript | Typing effect, particle canvas, scroll reveal, smooth navigation |
| Font Awesome 6.5 | Icons throughout the UI (via CDN) |
| HTML5 Canvas API | Animated particle network background |
| IntersectionObserver API | Scroll-triggered reveal animations |

---

## 🎨 Design System

The portfolio uses a dark, space-inspired theme with a consistent CSS custom property system:

| Variable | Value | Usage |
|----------|-------|-------|
| `--accent` | `#7C4DFF` | Primary purple accent |
| `--accent2` | `#00E5FF` | Cyan accent / gradients |
| `--good` | `#00E676` | Success / green highlights |
| `--bg0` | `#070A12` | Deep dark background |
| `--bg1` | `#0A1022` | Slightly lighter background |
| `--radius` | `22px` | Card border radius |

---

## 🚀 Getting Started

### View Locally

No installation needed. Simply clone and open:

```bash
git clone https://github.com/programmer-sandipan/portfolio.git
cd portfolio
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Customize Your Links

All external links are defined in one central `LINKS` object at the bottom of `index.html`:

```javascript
const LINKS = {
  githubProfile:    "https://github.com/programmer-sandipan",
  linkedin:         "https://linkedin.com/in/sandipan-maity-35447839a",
  project1Repo:     "https://github.com/programmer-sandipan/AI-ML-Workshop-2025",
  project2Repo:     "https://github.com/programmer-sandipan/AI-ML-Workshop-2025",
  project1Notebook: "#",   // Add your Colab/notebook link
  project2Notebook: "#",   // Add your Colab/notebook link
  email:            "student@email.com"
};
```

Simply update these values and save — all buttons and links on the page update automatically.

---

## 📌 Featured Projects

### 1. 📊 EDA Dashboard — Titanic Dataset
> Exploratory Data Analysis with visual insights

- Loaded and explored real-world dataset using **Pandas**
- Handled missing values with mean/mode imputation
- Created charts: survival count, gender vs. survival, age distribution
- Summarized key insights in a presentation-ready format

**Tools:** Pandas · Matplotlib · Google Colab

---

### 2. 🏠 House Price Prediction
> Supervised Machine Learning with Linear Regression

- Performed train-test split to evaluate on unseen data
- Trained a **LinearRegression** model using scikit-learn
- Evaluated with **RMSE** and **R² score**
- Visualized Actual vs. Predicted values and residual errors

**Tools:** scikit-learn · Matplotlib · Google Colab

---

## 🎓 Education & Workshops

- **B.Sc in Computer Science** — Haldia Institute of Management, 2nd Year (4th Semester)
- **Ardent AI & ML Workshop** — 3-day hands-on workshop covering EDA and ML foundations in Google Colab
- **Code_ScholarEU** — Ongoing learning in AI development, automation workflows, and LLM applications under mentorship of **SK Sahil**

---

## 📬 Contact

| Platform | Link |
|----------|------|
| 📧 Email | Update in `LINKS.email` inside `index.html` |
| 💼 LinkedIn | [sandipan-maity-35447839a](https://linkedin.com/in/sandipan-maity-35447839a) |
| 🐙 GitHub | [programmer-sandipan](https://github.com/programmer-sandipan) |
| 📸 Mentor (Instagram) | [@code_scholar_eu](https://www.instagram.com/code_scholar_eu/) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *Portfolio built with HTML, CSS & JavaScript — Responsive · Animated · Ready for GitHub Pages*
