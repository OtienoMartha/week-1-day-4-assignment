# Week 1 Day 4 Assignment — Portfolio Enhancement

A personal portfolio with a skills section using animated CSS progress bars,
smooth-scrolling navigation, fully responsive layout, and a CSS-only dark/light
theme toggle.

## 📁 Files

| File | Purpose |
|---|---|
| `index.html` | Full portfolio: About, Skills, Projects, Contact |
| `styles.css` | Stylesheet with theme variables and responsive rules |

## 🚀 Live Demo (GitHub Pages)

https://OtienoMartha.github.io/week-1-day-4-assignment/

## 📸 Screenshots

### Desktop — Light Theme

![Desktop light](screenshots/portfolio.png)

## 🎨 What I Built

### Task 1 — Skills Section with CSS Progress Bars

Two categories (Technical and Soft Skills) with eight skills total. Each bar
animates from 0% to its target width using `@keyframes growBar` — no JavaScript.

### Task 2 — Smooth Scrolling Navigation

The `html` element uses `scroll-behavior: smooth` and `scroll-padding-top` so
clicking a nav link scrolls smoothly and the section heading lands below the
sticky navbar.

### Task 3 — Fully Responsive Portfolio

Tested at three breakpoints:
- **Desktop (1024px+):** two-column skills grid, multi-column projects
- **Tablet (768–1023px):** reduced type and padding
- **Mobile (below 768px):** single column, stacked buttons, 44px+ tap targets

### Bonus — CSS-Only Theme Toggle

A hidden `<input type="checkbox">` sits before the `.page` wrapper. The
`:checked ~ .page` sibling selector swaps CSS custom properties for dark mode.
No JavaScript needed.

## 🧠 What I Practiced

- CSS custom properties (variables) and theming
- `@keyframes` animation for progress bars
- `scroll-behavior` and `scroll-padding-top`
- Sticky positioning with `position: sticky`
- CSS Grid and Flexbox for responsive layout
- Media queries at 1023px, 767px, and 479px
- The `:checked ~` sibling selector for CSS-only interactivity

## 🛠️ How to View Locally

```bash
git clone https://github.com/OtienoMartha/week-1-day-4-assignment.git
cd week-1-day-4-assignment