
# Masun Technology — Official Website

> **Built by first-year students. Shipping apps that actually work.**  
> Est. 2026 · Bhubaneswar, India

---

## 🚀 About

This is the official website for **Masun Technology**, a student-founded startup building clean, fast, and purposeful software. The site showcases the company's products, values, and mission — all packed into a single, zero-dependency HTML file.

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| **Structure** | HTML5 (Semantic) |
| **Styling** | CSS3 — Custom Properties, Flexbox, Grid, Animations, `@keyframes`, `clip-path` |
| **Scripting** | Vanilla JavaScript (ES5/ES6) — No frameworks, no libraries |
| **Fonts** | Google Fonts — `Bebas Neue`, `IBM Plex Mono`, `Syne` |
| **Graphics** | Inline SVG (all illustrations hand-coded) |
| **AI Integration** | Google Gemini AI (used inside the Label Truth mobile app) |
| **Deployment** | Static HTML — deployable on GitHub Pages, Netlify, Vercel, or any static host |

---

## ✨ Features & Techniques

- **Single-file architecture** — entire site lives in `index.html` (HTML + CSS + JS in one file)
- **Custom preloader / boot screen** with animated progress bar and glitch effects
- **Canvas-based particle background** rendered via the HTML5 `<canvas>` API
- **Scroll-based reveal animations** using the `IntersectionObserver` API
- **Text scramble / glitch effect** built in pure JavaScript
- **Animated marquee cycler** for keyword looping
- **Mouse-tracking crosshair** with live coordinate display
- **Contact overlay modal** with form handling in vanilla JS
- **Hover-triggered video playback** for product cards
- **Grain/noise texture overlay** via inline SVG `feTurbulence` filter
- **Fully responsive** layout using CSS `clamp()`, Flexbox, and Grid
- **No external JS dependencies** — zero npm, zero build step, zero bundler

---

## 📦 Products Featured

### 1. ScreenSync *(App 01 · Android)*
Instantly sync your phone display with your PC — no cables, no lag.

### 2. Label Truth *(App 02 · Android & iOS)*
Point your camera at any food, supplement, or medicine label — Gemini AI breaks down every ingredient instantly with color-coded safety ratings, health scores, and warnings.

---

## 📁 Project Structure

```
masun-website/
├── index.html          # Entire website (HTML + CSS + JS)
├── labeltruth.mp4      # Product demo video (loaded lazily on hover)
└── README.md           # You're reading this
```

> **Note:** `labeltruth.mp4` is lazy-loaded on product card hover — place it in the same directory as `index.html`.

---


## 👥 Team

**Masun Technology** was founded by two first-year college students with a passion for shipping things that matter. Age is not a barrier — good ideas and consistent building always win.

---

## 📬 Contact

Reach out via the **Get In Touch** button on the website, or open an issue in this repo.

---

*Built with no frameworks. Just HTML, CSS, and a lot of intent.*
