# Portfolio Website — Task 1, Project 1

A single-page personal portfolio built with **HTML and CSS only** (no JavaScript, no
frameworks, no build step), as required by the task brief.

## Design direction

Two-ink risograph print: federal blue and fluorescent pink on pale blue stock, with a
deliberate misregistration on the display type — the pink copy of the name sits a few
pixels off from the blue one, the way a real two-pass print does. A halftone dot screen
sits over the whole page.

## Requirements from the brief

| Requirement | Where |
|---|---|
| Single-page portfolio, HTML + CSS only | `index.html` + `style.css`, zero JS |
| Sections: About, Skills, Projects, Contact | `#about`, `#skills`, `#projects`, `#contact` |
| Clean layout, modern colour scheme | Two-ink palette defined as CSS custom properties |
| Responsive for mobile and desktop | Fluid `clamp()` type, `auto-fit` grids, breakpoints at 62rem and 34rem |
| Hover effects and transitions | Nav underlines, card lift + hard shadow, plate colour shift, e-mail fill sweep |

## Files

```
index.html    markup
style.css     all styling, organised by section
```

## Run it

Open `index.html` in any browser. Nothing to install.

## Things worth pointing out

- The three project thumbnails are **pure CSS** — `conic-gradient`, `radial-gradient` and
  `repeating-linear-gradient`, no image files at all.
- Smooth scrolling comes from `scroll-behavior: smooth` in CSS, not from a script.
- `prefers-reduced-motion` is respected: all animation is switched off for anyone who
  has asked their system for less movement.
- Focus is visible on every interactive element, so the page can be used with a keyboard.

## Before you submit

Replace the placeholder name, e-mail, phone number and social links with your own,
and swap the three project write-ups for real ones.
