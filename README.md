# LUMIÈRE Dental

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222?style=flat-square&logo=github)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen?style=flat-square)

A luxury cosmetic and restorative dental practice marketing website built as a single, zero-dependency HTML file. LUMIÈRE Dental is a high-end, fully responsive front-end project that showcases services, the clinical team, patient testimonials, and an appointment booking form — all powered by vanilla HTML, CSS, and JavaScript with no build step required.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [Usage / How to Run](#usage--how-to-run)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Features

- ✅ **Hero section** with animated statistics and dual call-to-action buttons
- ✅ **Services grid** showcasing five core treatments in a masonry-style layout
- ✅ **Interactive before/after slider** — drag or touch to reveal smile transformations
- ✅ **Animated counters** that count up from zero when scrolled into view
- ✅ **Auto-scrolling testimonials carousel** that pauses on hover
- ✅ **5-step treatment process** with hover highlight effects
- ✅ **Team section** with specialist profiles and role badges
- ✅ **Appointment booking form** with client-side validation and success feedback
- ✅ **Custom animated cursor** that responds to interactive elements
- ✅ **Scroll-triggered fade-in animations** using the IntersectionObserver API
- ✅ **Fully responsive** layout for desktop, tablet, and mobile
- ✅ **Mobile hamburger menu** for small-screen navigation
- ✅ **Parallax and GPU-accelerated CSS animations** for smooth 60 fps performance
- ✅ **Zero external dependencies** — works straight from the file system

---

## Tech Stack

| Category | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Grid, Flexbox, `clamp()`) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Cormorant Garamond, DM Sans, DM Mono |
| Animations | CSS transitions + `requestAnimationFrame` |
| Scroll detection | IntersectionObserver API |
| Hosting | GitHub Pages |
| Build tools | None |

---

## Project Structure

```
dentl3/
└── index.html      # Entire application — markup, styles, and scripts in one file
```

Everything lives in `index.html`. The file is organised in this order:

| Section | Description |
|---|---|
| `<head>` | Meta tags, Google Fonts import, and all embedded CSS (~480 lines) |
| `<nav>` | Fixed navigation bar with logo and scroll links |
| `#hero` | Full-viewport hero with headline, stats, and CTA buttons |
| `#services` | Masonry grid of five treatment cards |
| `#results` | Drag-to-compare before/after smile transformation slider |
| `#process` | Numbered five-step treatment journey |
| `#team` | Specialist profiles with SVG avatar placeholders |
| `#counters` | Animated key-stats strip |
| `#testimonials` | Infinitely scrolling patient review carousel |
| `#booking` | Appointment request form with validation |
| `<footer>` | Links, contact details, and social media icons |
| `<script>` | All JavaScript (~150 lines) at bottom of `<body>` |

---

## Prerequisites

No package manager, runtime, or compiler is required. You only need:

- A **modern web browser** that supports ES6+ (Chrome 61+, Firefox 60+, Safari 12+, Edge 79+)

Optionally, for local development with live reload:

- **Python 3** (ships with every macOS/Linux) — used to spin up a simple HTTP server

---

## Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/engrmaziz/dentl3.git

# 2. Enter the project directory
cd dentl3
```

That's it. There is nothing to install or build.

---

## Usage / How to Run

### Option 1 — Open directly in a browser

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows (PowerShell)
start index.html
```

### Option 2 — Serve locally with Python

```bash
python -m http.server 8000
# Then visit: http://localhost:8000
```

### Option 3 — Live site (GitHub Pages)

The project is deployed and publicly accessible at:

**https://engrmaziz.github.io/dentl3/**

---

> **Screenshot placeholder** — add a screenshot of the live site here:
> `![LUMIÈRE Dental homepage](./screenshot.png)`

---

## Contributing

Contributions are welcome! Here's the standard flow:

1. **Fork** the repository on GitHub
2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** in `index.html`
4. **Commit** with a clear message
   ```bash
   git commit -m "feat: describe what you changed"
   ```
5. **Push** your branch
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a pull request** against `main` and describe what you changed and why

Please keep pull requests focused and avoid bundling unrelated changes.

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

```
MIT License

Copyright (c) 2026 Musharraf Aziz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Author

**Musharraf Aziz**

- GitHub: [@engrmaziz](https://github.com/engrmaziz)
