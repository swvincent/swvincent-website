# Project

Personal landing page for www.swvincent.com. HTML + vanilla JavaScript only — no frameworks, no build tools, no external dependencies.

## Style

- Monochromatic greyscale design
- CSS lives in `css/site.css`; do not use inline styles
- Social link icons use inline SVG (no icon libraries)
- Colors are custom properties on `:root`, overridden in the `prefers-color-scheme: dark` block. Add new colors to both palettes rather than hardcoding hex values, or they will break one of the two themes
- `404.html` shares the same stylesheet and card layout as `index.html`; keep the two consistent

## Deployment

GitHub Pages. `master` is the live branch.

The canonical URL is `https://www.swvincent.com/`. The `rel=canonical` link, Open Graph tags and JSON-LD in `index.html` must all use it.
