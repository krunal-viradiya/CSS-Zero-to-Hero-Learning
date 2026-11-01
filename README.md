# 🎨 CSS: Zero to Hero

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="70" height="70" />
</p>

<p align="center">
  <b>A comprehensive, practical repository mapping the transition from styling fundamentals to modern layouts, responsive design, and CSS architecture.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Standard-W3C%20Specs-264DE4?style=for-the-badge&logo=html5&logoColor=white" alt="W3C Specs" />
  <img src="https://img.shields.io/badge/Focus-Full%20Stack%20UI%20Mastery-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="Full Stack UI Mastery" />
  <img src="https://img.shields.io/badge/Author-krunal--viradiya-blue?style=for-the-badge&logo=github" alt="Author" />
</p>

---

## 📌 Overview

This repository documents a structured, module-by-module breakdown of pure CSS. Every module is standalone, designed to demonstrate visual layout concepts with clean code alongside technical inline notes covering:

- **Browser Rendering Engine:** How layout calculations, reflows, repaints, and compositing occur.
- **Architectural Reasoning:** Why modern layout specs (Flexbox & Grid) replace legacy float/table hacks.
- **Real-World Patterns:** Direct translation to responsive web apps, UI libraries, and production frontend systems.

---

## 🗺️ Roadmap & Curriculum

### 🟢 Phase 1: Core Fundamentals & Cascade Mechanics
| Module | File | Description |
| :--- | :--- | :--- |
| **01** | `01-intro-and-linking.html` | CSS kya hai, browser styling kaise apply karta hai, inline vs internal vs external linking. |
| **02** | `02-selectors-and-specificity.html` | Universal, element, class, id selectors, specificity score calculations, aur `!important` rule. |
| **03** | `03-cascade-and-inheritance.html` | Cascade algorithm, inheritance behavior, initial/inherit/unset values, aur browser default styles. |
| **04** | `04-colors-and-units.html` | Colors (`HEX`, `RGB`, `RGBA`, `HSL`), absolute vs relative units (`px`, `rem`, `em`, `vw`, `vh`, `%`). |
| **05** | `05-typography-and-fonts.html` | Font-family, system font stack, web fonts (Google Fonts), font-weight, line-height, aur letter-spacing. |

---

### 🟡 Phase 2: The Box Model & Display Essentials
| Module | File | Description |
| :--- | :--- | :--- |
| **06** | `06-box-model.html` | Content, padding, border, margin, margin collapsing mechanics, aur `box-sizing: border-box`. |
| **07** | `07-display-properties.html` | `block`, `inline`, `inline-block`, aur `none` vs `visibility: hidden` ke layout differences. |
| **08** | `08-backgrounds-and-borders.html` | Background color, image positioning, size (`cover`/`contain`), gradients, aur border-radius tricks. |
| **09** | `09-overflow-and-clipping.html` | `overflow: visible/hidden/scroll/auto`, text truncation with ellipsis, aur simple clipping masks. |

---

### 🟠 Phase 3: Layout Engines (Positioning, Flexbox & Grid)
| Module | File | Description |
| :--- | :--- | :--- |
| **10** | `10-positioning-deep-dive.html` | Document flow, `static`, `relative`, `absolute`, `fixed`, `sticky`, aur `z-index` stacking context. |
| **11** | `11-flexbox-container.html` | 1D layout model, `flex-direction`, `justify-content`, `align-items`, `flex-wrap`, aur `gap`. |
| **12** | `12-flexbox-items.html` | Flex item controls: `flex-grow`, `flex-shrink`, `flex-basis`, `align-self`, aur order property. |
| **13** | `13-css-grid-fundamentals.html` | 2D layout model, `grid-template-columns/rows`, `fr` unit, `repeat()`, `minmax()`, aur auto-fill/auto-fit. |
| **14** | `14-css-grid-areas.html` | Named grid lines, `grid-template-areas`, magazine layouts, aur complex nested dashboard grids. |

---

### 🔴 Phase 4: Responsive Design & Modern UI Patterns
| Module | File | Description |
| :--- | :--- | :--- |
| **15** | `15-media-queries.html` | Mobile-first approach, viewport meta tag, break points, aur dark mode with `prefers-color-scheme`. |
| **16** | `16-responsive-images-media.html` | Responsive images, aspect-ratio property, `object-fit: cover/contain`, aur video embed containers. |
| **17** | `17-css-variables.html` | Custom properties (`--primary-color`), scope levels, dynamic runtime updates, aur instant theming. |
| **18** | `18-pseudo-classes-elements.html` | States (`:hover`, `:focus-visible`, `:active`), structural pseudo-classes (`:nth-child`), aur `::before`/`::after`. |

---

### 🟣 Phase 5: Motion, 3D & Advanced Architecture
| Module | File | Description |
| :--- | :--- | :--- |
| **19** | `19-transitions-and-transforms.html` | Smooth state transitions, timing functions (`cubic-bezier`), translate, rotate, scale, aur skew. |
| **20** | `20-keyframe-animations.html` | Complex multi-step animations with `@keyframes`, animation iteration, direction, aur performance tips. |
| **21** | `21-modern-css-features.html` | CSS native nesting, modern pseudo-selectors (`:has()`, `:is()`, `:where()`), aur subgrid basics. |
| **22** | `22-css-architecture-bem.html` | Maintainable CSS patterns, BEM naming convention, modular files, aur avoiding specificity wars. |
| **23** | `23-ui-components-lab.html` | Production-ready components: accessible modals, floating labels, animated cards, aur navbars. |

---

## 🛠️ Execution & Local Setup

### Prerequisites
- Modern web browser (Google Chrome, Firefox, or Brave)
- Code editor like [Visual Studio Code](https://code.visualstudio.com/)
- Recommended: **Live Server** extension for VS Code

### Running Any Module Locally
Preview and inspect the CSS modules directly in your browser:

```bash
# Clone the repository
git clone https://github.com/krunal-viradiya/CSS-Zero-to-Hero-Learning.git

# Enter repository directory
cd CSS-Zero-to-Hero-Learning

# Open in VS Code
code .
```

- Right-click on any `.html` file (e.g., `01-intro-and-linking.html`) and select **"Open with Live Server"**.
- Press `F12` to inspect elements, experiment with properties live, and study the box model.

---

> *Note to self: Slow progress is still progress. Just don't stop.*