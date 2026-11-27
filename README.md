# Loopsii Landing Page

A pixel-perfect, light, single-page website reproducing the look, feel, animations, and typography of [loopsii.com](https://loopsii.com) ("Loopsii: the all-in-one app for freelancers").

## How to Run

### Option 1: Direct in Browser
Double-click `index.html` or open it with your favorite browser:
```bash
start index.html
```

### Option 2: Local Web Server
Run using `serve` or Python:
```bash
# With npm/npx
npm start
# or
npx serve -l 3000 .

# Or with Python
python -m http.server 3000
```
Then visit [http://localhost:3000](http://localhost:3000).

## Features Included
- **All 14 Sections** in the exact sequence from the reference.
- **Glassmorphism surfaces & layered depth shadows**.
- **Interactive Pricing Switch**: Monthly ($12/mo) and Yearly ($10/mo, billed $120/yr, 17% savings) with color transition (`#c4f041` / `#bce6fa`).
- **Interactive FAQ Accordion**: Expandable and collapsible questions with smooth CSS grid transition.
- **⌘K Quick Search Modal**: Press `Cmd+K` / `Ctrl+K` or click the search action pill to trigger navigation search.
- **All Exact Custom Properties & Colors**: `#c4f041`, `#bce6fa`, `#f3bd77`, `#aac2aa`, `#e0f661`, `#fa8e66`, etc.
- **Complete SVG Graphics and Typography**: Includes all folder SVGs, dashboard mockups, and typography.
