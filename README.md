# 🏡 Nexter — Real Estate Website

A real estate landing page for **Nexter**, built to learn **CSS Grid** in depth. The whole layout, from the page structure to the photo gallery, is built with Grid and styled with **Sass**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

**🔗 Live demo:** [prasad-nexter.netlify.app](https://prasad-nexter.netlify.app/)

---

## ✨ Features

- **Page layout built entirely with CSS Grid**, including named grid lines and full-bleed sections
- **Sections:** sidebar, header with "seen on" logos, top realtors, features, story, home listings, image gallery and footer
- **Image gallery** laid out with a 14-item Grid composition
- **Home listing cards** built with Grid
- **Desktop-first responsive design** that adapts to tablets and phones
- Styled with Sass variables and partials

---

## 🧠 What I Learned

- CSS Grid fundamentals: `grid-template-columns/rows`, `fr`, `minmax()`, `repeat()`
- Named grid lines and placing items precisely
- Implicit vs explicit grids and `auto-fit`
- Aligning items and tracks
- Combining Grid with Flexbox where each fits best

---

## 🛠️ Tech Stack

- **HTML5** — structure
- **Sass (SCSS)** — styles
- **CSS3** — Grid layout
- **Autoprefixer + PostCSS** — vendor prefixes
- **npm scripts** — the CSS build process

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (for the Sass build)

### Installation

```bash
git clone https://github.com/prasad-k-s/Nexter.git
cd Nexter
npm install
```

### Build the CSS

| Script | What it does |
| --- | --- |
| `npm run watch:sass` | Recompiles `css/style.css` every time you save a Sass file (for development) |
| `npm run build:css` | Production build: compile Sass → add vendor prefixes (Autoprefixer) → compress |

Then open `index.html` in your browser.

---

## 📂 Project Structure

```
Nexter/
├── index.html
├── package.json
├── css/          # Compiled CSS
├── img/          # Images and logos
└── sass/
    ├── main.scss # Imports all partials
    ├── _base.scss
    ├── _typography.scss
    ├── _sidebar.scss
    ├── _header.scss
    ├── _features.scss
    ├── _story.scss
    ├── _homes.scss
    ├── _gallery.scss
    ├── _realtors.scss
    └── _footer.scss
```

---

## 🙏 Credits

The base project comes from [Jonas Schmedtmann's](https://twitter.com/jonasschmedtman) *Advanced CSS and Sass* course.
