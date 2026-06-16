# Neha Nayak — Developer Portfolio

A clean, responsive personal portfolio website built with vanilla HTML, CSS, and JavaScript.

## Live Preview

> Deploy on GitHub Pages, Netlify, or Vercel — drop in the files and you're live.

## Features

- **Dark mode** with localStorage persistence — remembers the user's preference across visits
- **Scroll reveal animations** — sections fade in as you scroll down
- **Active nav highlighting** — nav link glows as its section enters the viewport
- **Responsive mobile nav** — hamburger menu with outside-click dismiss
- **Zero dependencies** — no frameworks, no build step, just three files

## Tech Stack

- HTML5 & semantic markup
- CSS3 — custom properties, grid, flexbox, `IntersectionObserver`-driven animations
- Vanilla JavaScript — no libraries
- [Tabler Icons](https://tabler-icons.io/) (icon webfont via CDN)
- [DM Sans + DM Serif Display](https://fonts.google.com/) (Google Fonts)

## Project Structure

```
portfolio/
├── index.html        # Markup and content
├── style.css         # All styles and dark mode variables
├── script.js         # Dark mode, mobile nav, scroll reveal
└── Neha_Resume_SE.pdf  # Linked for download in the hero section
```

## Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/aknneha/portfolio.git
   ```
2. Open `index.html` in your browser — no build step needed.

## Deploying on GitHub Pages

1. Push all files to the `main` branch of your repository.
2. Go to **Settings → Pages**.
3. Set source to `main` branch, root folder.
4. Your site will be live at `https://aknneha.github.io/<repo-name>/`.

## Customisation

| What to change | Where |
|---|---|
| Name, bio, links | `index.html` — hero and contact sections |
| Colors and fonts | `style.css` — `:root` variables block at the top |
| Sections / content | `index.html` — each `<section>` block |
| Resume file | Replace `Neha_Resume_SE.pdf` in the root folder |

## License

Open source under the [MIT License](LICENSE). Feel free to use this as a base for your own portfolio.
