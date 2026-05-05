# Coleman Bryant — Personal Portfolio Website

A single-page personal portfolio site built with plain HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no dependencies.

Live site: [cbryant6.github.io](https://cbryant6.github.io)

---

## How to Run

### Option 1 — Open directly in a browser (simplest)

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

That's it. No server, no installs required.

```bash
git clone https://github.com/GIX-Luyao/personal-web-cbryant6.git
cd personal-web-cbryant6
# Then open index.html in your browser
```

### Option 2 — Serve locally with Python (recommended for testing the GitHub activity fetch)

The GitHub contribution grid makes a live API fetch, which some browsers block on `file://` URLs. Serving locally avoids that.

```bash
# Python 3
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

### Option 3 — Serve locally with Node.js

```bash
npx serve .
```

Then visit the URL shown in your terminal (typically [http://localhost:3000](http://localhost:3000)).

---

## Project Structure

```
personal-web-cbryant6/
├── index.html      # Entire site — HTML, CSS, and JS in one file
├── PM Resume.pdf   # Resume (linked from the site)
└── README.md       # This file
```

---

## Features

- **Apple Liquid Glass aesthetic** — frosted glass panels, ambient blobs, specular highlights
- **Floating pill navigation** — sticky, smooth-scroll, active section highlight via IntersectionObserver
- **Featured Work section** — three project cards (Acoustic Dosimeter, ML Music Genre & Instrument Classifier, Motion Maven)
- **About section** — two-column bio + quick-fact cards
- **GitHub Activity grid** — live fetch from the GitHub contributions API with graceful static fallback
- **Contact panel** — dark glass panel with email and GitHub links
- **Fully responsive** — mobile-friendly down to 320px

---

## Customization

All placeholder links are clearly marked in `index.html` with comments. The site is self-contained — edit the single file and refresh your browser to see changes.

To deploy updates to GitHub Pages:

```bash
git add index.html
git commit -m "describe your change"
git push
```

GitHub Pages redeploys automatically within ~60 seconds.
