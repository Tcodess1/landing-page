# Landing Page Demo

This repository contains a small demo landing page built as a visual example and learning exercise. It shows a typical landing page layout (header, hero, feature/info cards, testimonial/quote, wide CTA, and footer) and uses a small, focused set of CSS styles based on a simple design guide.

## What this is

- A static HTML/CSS demo — no build tools or frameworks required.
- Meant to demonstrate layout, typography, color tokens, and responsive behavior for a landing page.

## Files

- `index.html` — the sample page markup with header, hero, info section, quote/testimonial, wide CTA, and footer.
- `style.css` — styles used by the page. Uses CSS variables for the palette and contains responsive rules.

## Design tokens (from the guide)

- Dark background (hero & footer): `#1F2937`
- Hero main text: `#F9FAF8` — 48px, weight 900
- Hero secondary text: `#E5E7EB` — 18px
- Logo text: 24px, `#F9FAF8`
- CTA color: `#3882F6`
- Info header: 36px, `#1F2937`, weight 900
- Quote section background: `#E5E7EB` and quote text: 36px, `#1F2937`, weight 300 (italic)
- Font: Roboto (weights 300, 400, 900)

## How to view locally

You can open the page directly in your browser by double-clicking `index.html`, or serve it with a tiny local server (useful if you want proper file/asset behavior):

```bash
# from this repo folder
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Notes & next steps

- The layout uses simple CSS grid and flexbox patterns. The `style.css` includes a `.container` helper, hero grid, feature cards, quote block, and a wide CTA box.
- Accessibility: links and buttons are basic — consider adding keyboard focus styles and aria attributes for production use.
- Assets: the demo uses placeholders for illustrations; replace the `.placeholder` and `.icon` blocks with real images and alt text.
- License: none specified — add a LICENSE file if you plan to publish or reuse this.

If you'd like, I can:

- Add example images and alt text into the markup.
- Make the header responsive with a mobile menu toggle.
- Generate a small set of sample content or a component library for reuse.

Enjoy experimenting with the demo! 🎨
