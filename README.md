# 🥦 Bust the Myths — Vegan Awareness Campaign

A bold, colorful, three-page website that debunks common misconceptions about plant-based eating. Built with pure HTML, CSS, and vanilla JavaScript — no external libraries or frameworks.

## 🔗 Live Site

[dbusch-developer.github.io/bust-the-myths](https://dbusch-developer.github.io/bust-the-myths/)

---

## 📁 File Structure
```
├── index.html   — Homepage
├── myths.html   — 8 interactive flip cards
├── start.html   — Getting started tips with accordion
├── style.css    — All styles
├── script.js    — All JavaScript
└── README.md    — This file
```

## 📄 Pages

- **index.html** — Homepage with hero, stats bar, myth previews, and a why it matters section
- **myths.html** — 8 flip cards, click a card to flip it and reveal the bust. Counter tracks progress, celebration appears when all 8 are flipped
- **start.html** — 5 accordion tips that expand on click, plus a table of easy food swaps

## ⚙️ JavaScript Features

- **Flip Cards** — Clicking a card toggles a flipped class. CSS uses rotateY(180deg) to animate. Counter increments on each new flip. Hidden celebration message reveals at 8.
- **Accordion** — Clicking a button toggles an open class on the parent item. CSS shows/hides the body and rotates the + icon.
- **Mobile Nav** — Hamburger toggles an open class on the nav links list.
- **Footer Year** — Sets .yr elements to new Date().getFullYear().

## 🛠 Built With

- HTML5
- CSS3 (custom properties, grid, flexbox, 3D transforms, keyframe animations)
- Vanilla JavaScript