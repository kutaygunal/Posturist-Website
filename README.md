<div align="center">

# 🦴 Posturist — Improve Your Posture

A modern marketing website for **Posturist**, a 21-day guided posture training app with daily workouts, progress tracking, and shareable milestones.

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Jekyll](https://img.shields.io/badge/Jekyll-CC0000?style=for-the-badge&logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 📖 Overview

A clean, responsive landing site for **Posturist** — a posture training app built around a structured **21-day challenge**. The site showcases the product's core value: guided daily workouts, clear exercise guidance, progress tracking, and shareable milestones.

**What it does:**
1. Presents the 21-day posture program and its benefits
2. Shows real app screenshots across the challenge, workout, and progress flows
3. Provides localized pages in **English, Türkçe, Deutsch, and Español**
4. Includes contact, privacy, and terms pages

---

## 🛠️ What's Inside

| File | Purpose |
|------|---------|
| `index.html` | Main landing page (English) |
| `tr.html` / `de.html` / `es.html` | Localized landing pages |
| `contact*.html` | Contact page (all languages) |
| `privacy*.html` | Privacy policy (all languages) |
| `terms*.html` | Terms of service (all languages) |
| `styles.css` | Shared design system & responsive layout |
| `assets/` | App screenshots, icons, and localized images |
| `_config.yml` | Jekyll site configuration |

---

## 🚀 Getting Started

### Prerequisites
- A static file server (or just open `index.html` in a browser)
- [Jekyll](https://jekyllrb.com/) *(optional, for GitHub Pages)*

### 1. Clone the repo

```bash
git clone https://github.com/kutaygunal/Posturist-Website.git
cd Posturist-Website
```

### 2. Open the site

Just open `index.html` in your browser, or serve it locally:

```bash
# Python
python -m http.server 8000

# Or with Jekyll (GitHub Pages)
jekyll serve
```

You'll see:

```
🦴 Posturist — Improve Your Posture
🌐 Language selector: English / Türkçe / Deutsch / Español
```

---

## 🌐 Pages

| Page | Description |
|------|-------------|
| `index.html` | Hero, features, program, gallery, and CTA |
| `contact.html` | Contact form / info |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |

Each page is also available in **Türkçe**, **Deutsch**, and **Español** via the language selector.

---

## 🎨 Design Notes

- **Responsive layout** — adapts cleanly from mobile to desktop
- **Dark, premium UI** — bold progress visuals and a modern card-based design
- **Localized assets** — screenshots are provided per language (`assets/en`, `assets/tr`, `assets/de`, `assets/es`)
- **No build step** — plain HTML + CSS, easy to host anywhere

---

## 🔒 Security

- No server-side code or user data is stored — this is a static marketing site.
- Contact, privacy, and terms pages are provided for transparency.

---

## 📄 License

MIT

---

<div align="center">
  Made with ❤️ for better posture
</div>
