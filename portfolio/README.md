# Rahaf Melhem — Portfolio

A responsive English/Arabic portfolio for Rahaf Melhem, a front-end developer and Computer Systems Engineering student at Palestine Technical University – Kadoorie.

## Features

- Responsive desktop and mobile layouts.
- English/Arabic switching with LTR/RTL layouts.
- Light and dark themes with saved browser preferences.
- Project filters for React and JavaScript.
- Esham explicitly marked **in progress**, expected completion **January 2027**.
- English proficiency correctly listed as **Intermediate**.
- Printable résumé (`resume.html`); use Print / Save as PDF.
- Working GitHub, LinkedIn and email links.
- Keyboard focus styles and reduced-motion support.

## Run locally

No installation or build step is required. Open `index.html`, or run:

```sh
python -m http.server 8000
```

Then visit http://localhost:8000.

## Files

- `index.html`: Page structure and English content.
- `style.css`: Visual design, responsiveness and print styles.
- `script.js`: Arabic translation, theme switching and project filters.
- `resume.html`: Text résumé with print / PDF support.
- `assets/`: Favicon and public illustrated GitHub avatar.

## GitHub Pages

This is a plain static site compatible with GitHub Pages. In a dedicated repository, enable **Settings → Pages → Deploy from a branch**, select the default branch and **/(root)**. If placed in another repository's `portfolio/` folder, enable Pages on that repository and append `/portfolio/` to the published site URL.

## Updating

Edit English content in `index.html` and matching Arabic translations in `script.js`. Keep `resume.html` in sync. Project visuals are CSS illustrations, not screenshots. The small illustrated avatar is the public GitHub profile image for `rahafOM`.

## External resources

Google Fonts supplies Manrope, DM Sans and Noto Sans Arabic with system-font fallbacks. No analytics, contact-form backend, or tracking scripts are included. Contact opens the visitor's email client.
