<!-- Hero -->
<h1 align="center">Port Summaries</h1>

<p align="center">
  <strong>The go-to-place for any investor interested on a Barkel portfolio opportunity.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/stage-completed-success?style=flat-square" alt="Stage">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/sergiobk201/port_summaries?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/tech-HTML5%20%2F%20CSS3-orange?style=flat-square" alt="Tech">
</p>

<p align="center">
  <!-- TODO: add hero image at assets/images/hero.png -->
  <img src="assets/images.hero.png" alt="Port Summaries Preview" width="720">
</p>

---

## ✨ Overview

**Port Summaries** is a sleek, professional "menu" designed for potential investors, family, and friends to explore diverse investment strategies managed by Barkel Group. It provides a high-signal overview of the **Vector**, **Legend**, and **Renda** portfolios, allowing users to make informed decisions before diving into the live performance data.

Built as a learning project focused on high-quality frontend fundamentals, it emphasizes a **"Quant" aesthetic**—combining high-precision typography (DM Mono) with narrative-driven headers (Source Serif 4) and a sophisticated dark mode interface.

## 🚀 Features

- 📊 **Strategic Comparison** — Side-by-side view of Quant, Value, and Dividend strategies.
- 📐 **Clean Architecture** — Fully responsive layout built with CSS Grid and Flexbox.
- 📑 **Semantic Precision** — Structured with accessible HTML5 elements (`<article>`, `<header>`, `<section>`).
- 🎨 **Visual Polish** — Interactive hover effects and entry animations for a professional feel.
- ⚡ **Zero JS** — Optimized performance using only vanilla CSS transitions and variables.

## 📸 Demo

> 🔗 **Live Performance Tracking:** [Barkel Portfolio Dashboard](https://barkel-portfolio.streamlit.app/)

## 🏁 Quick Start

To view the gallery locally, simply clone the repository and open `index.html` in any modern browser:

```bash
git clone https://github.com/sergiobk201/port_summaries.git
cd port_summaries
open index.html
```

## 📦 Installation

### Requirements

- A modern web browser (Chrome, Firefox, Safari, or Edge).
- No web server or runtime required (Pure static files).

### Setup

```bash
# Clone the repository
git clone https://github.com/sergiobk201/port_summaries.git

# Navigate to the folder
cd port_summaries
```

## 🛠 Usage

The project is structured to be easily customizable. All styles are controlled via CSS variables in `style.css`:

```css
:root {
  /* Quant Theme Palette */
  --bg-dark: #0f1115;
  --card-bg: #1a1d23;
  --accent-blue: #4a90e2;
  --text-main: #e2e8f0;
}
```

To add a new portfolio, simply duplicate a `<article class="card">` block in `index.html` and update the content.

## 🏗 Architecture

The project follows a **Single-Page Application (SPA)** layout without the overhead of a framework.

- **`index.html`**: Semantic structure and content.
- **`style.css`**: Layout (CSS Grid), typography, and animations.
- **`assets/`**: Local images and visual markers.

## 🗺 Roadmap

- [x] Define semantic HTML structure.
- [x] Implement global CSS variables.
- [x] Create responsive Grid layout.
- [x] Add interactive hover effects.
- [ ] Host the gallery on GitHub Pages or Vercel.

## 📝 Changelog

- **2026-05-17** — Completed full implementation of all strategy cards and responsive layout.
- **2026-05-01** — Project initialization and semantic structural planning.

## 🤝 Contributing

This is a personal learning project. While contributions aren't actively sought, feel free to fork the repo and experiment with your own portfolio strategies.

## 📄 License

[MIT](LICENSE) © 2026 Sergio Barrientos

## 🙏 Acknowledgments

- Inspired by the investment philosophies of Warren Buffett and Luiz Barsi.
- Built with a focus on Quant Finance presentation standards.
