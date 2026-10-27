# Tailwind Responsive Navbar

A responsive landing page in React and Tailwind, built around a navigation bar that collapses into a mobile menu.

## Sections

| Component | Section |
|---|---|
| `src/components/header/` | Navbar with the mobile hamburger menu |
| `src/components/hero/` | Above-the-fold hero |
| `src/components/slider/` | Content slider |
| `src/components/about-us/` | About block |
| `src/components/faqs/` | FAQ accordion |
| `src/components/footer/` | Footer with links |

Composed in `src/App.jsx`.

## Stack

React 18 · Vite · Tailwind CSS

## Running

```bash
npm install
npm run dev
```

Serves on `http://localhost:5173`. The responsive breakpoints are pure Tailwind (`sm:`, `md:`, `lg:`), so resizing the window is enough to check the menu behaviour.

## Notes

A layout exercise: every section is static markup, which makes it a clean starting point to drop content and a router into.
