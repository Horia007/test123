# Basic Website

A simple static website built with plain HTML, CSS, and JavaScript.

## Files

- `index.html` — page structure and content
- `styles.css` — styling (responsive, with automatic dark mode)
- `script.js` — footer year and contact form handling

## Running locally

Install dependencies once, then start the dev server (auto-reloads on save):

```sh
npm install
npm run dev
```

Or, without Node.js, serve the folder with Python:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000. (`npm run build` creates a production build in `dist/`.)

> Note: the contact form only shows a confirmation message; it does not send data anywhere.
