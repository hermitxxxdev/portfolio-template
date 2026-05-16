<div align="center">

<img src="https://hermitxxx.github.io/portfolio-hermit/assets/logo.jpg" width="100px" style="border-radius: 50%" />

# 隠者 · HERMIT — Portfolio

**A dark, minimal personal portfolio for a Frontend Developer.**

[![Live Site](https://img.shields.io/badge/🌐_Live_Site-hermitxxx.github.io-dc2626?style=for-the-badge)](https://hermitxxx.github.io/portfolio-hermit/)
[![Personal Site](https://img.shields.io/badge/🧑‍💻_Website-thehermit.tech-dc2626?style=for-the-badge)](https://thehermit.tech)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hermitdev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hermitdev/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-portfolio--hermit-181717?style=for-the-badge&logo=github)](https://github.com/Hermitxxx/portfolio-hermit)
[![HTML](https://img.shields.io/badge/HTML-100%25-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/Hermitxxx/portfolio-hermit)

</div>

---

## 📖 Overview

**Hermit's Arena** is a single-page personal portfolio website built with pure **HTML, CSS, and JavaScript** — no frameworks, no build tools, no dependencies beyond a CDN icon library. It presents a Japanese-inspired dark aesthetic with red accents, animated particle effects, and smooth scroll interactions. The site showcases the developer's skillset, social links, and a contact form in a clean, immersive layout.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Structure & semantic markup |
| **CSS3** | All styling — animations, layout, responsiveness |
| **Vanilla JavaScript** | Interactivity — particles, scroll animations, mobile menu |
| **Font Awesome 6.5.1** | Icon library (via CDN) |
| **GitHub Pages** | Hosting & deployment |

---

## ✨ Features

- **Animated Particle Background** — 50 floating red particles rendered dynamically via JavaScript
- **Glowing Hero Section** — Pulsing neon text-shadow animation with Japanese typography (隠者)
- **Skills Arsenal** — Progress bar cards with scroll-triggered fill animations using `IntersectionObserver`
- **Social Connect Section** — Links to GitHub, Telegram, Instagram, and Facebook with hover effects
- **Contact Form** — Name, email, and message fields with live character counter (2000 char limit)
- **Responsive Design** — Fully mobile-friendly with hamburger navigation menu for smaller screens
- **Scroll-to-Top Button** — Fixed button that appears after scrolling 300px down
- **Smooth Scrolling** — Native smooth scroll behavior across all internal anchor links
- **Glassmorphism Navbar** — Fixed top navigation with `backdrop-filter: blur`

---

## 📦 Dependencies

This project has **zero npm/build dependencies**. The only external resource is loaded via CDN:

| Library | Version | Source |
|---|---|---|
| Font Awesome | `6.5.1` | `cdnjs.cloudflare.com` |

No `package.json`, no Node.js, no bundler required.

---

## 🚀 Running Locally

Since this is a static HTML project, setup is dead simple:

### Option 1 — Open directly in browser

```bash
# Clone the repository
git clone https://github.com/Hermitxxx/portfolio-hermit.git

# Navigate into the folder
cd portfolio-hermit

# Open in your default browser
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

### Option 2 — Serve with VS Code Live Server (Recommended)

1. Open the project folder in **VS Code**
2. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
3. Right-click `index.html` → **"Open with Live Server"**
4. Visit `http://127.0.0.1:5500` in your browser

### Option 3 — Serve with Python

```bash
# Python 3
python -m http.server 8080

# Then open: http://localhost:8080
```

> **Note:** Opening directly via `file://` works fine too, but using a local server ensures all assets load correctly.

---

## 📁 Project Structure

```
portfolio-hermit/
├── index.html        # Entire site — HTML, CSS, and JS in one file
├── CNAME             # Custom domain config for GitHub Pages
└── assets/
    └── logo.jpg      # Profile/logo image
```

---

## 🔗 Links

| | Link |
|---|---|
| 🌐 **Live Portfolio** | [hermitxxx.github.io/portfolio-hermit](https://hermitxxx.github.io/portfolio-hermit/) |
| 🧑‍💻 **Personal Website** | [thehermit.tech](https://thehermit.tech) |
| 💻 **GitHub Repository** | [github.com/Hermitxxx/portfolio-hermit](https://github.com/Hermitxxx/portfolio-hermit) |
| 🐙 **GitHub Profile** | [github.com/Hermitxxx](https://github.com/Hermitxxx) |
| 💼 **LinkedIn** | [linkedin.com/in/hermitdev](https://www.linkedin.com/in/hermitdev/) |
| ✈️ **Telegram** | [t.me/gabimaru_op](https://t.me/gabimaru_op) |
| 📸 **Instagram** | [@_nothermit](https://www.instagram.com/_nothermit/) |

---

<div align="center">
  <sub>© 2025 HERMIT · 隠者開発者 · All rights reserved</sub>
</div>
