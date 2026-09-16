# Michael Christopher Giardullo — Personal Site

A zero-backend static one-page site built for GitHub Pages.

## Files

- `index.html` — page content and structure
- `styles.css` — complete responsive design
- `script.js` — tiny progressive-enhancement script for reveal transitions and the footer year
- `assets/favicon.svg` — monogram favicon
- `assets/headshot-placeholder.svg` — fallback image if the GitHub avatar is unavailable

## Run locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

Create a public repository named `mcgjpn.github.io`, put these files in the repository root, and enable GitHub Pages from the repository settings if it is not enabled automatically.

The site will be available at `https://mcgjpn.github.io/` before a custom domain is connected.

## Easy edits

### Replace the headshot

Add your photo as `assets/headshot.jpg` and change the portrait `src` in `index.html` to:

```html
src="assets/headshot.jpg"
```

### Add real Power BI work

Replace the stylized `.bi-visual` block with a screenshot image and wrap it in the relevant report/project link. Keep the explanatory copy short and describe the business question, model, and outcome rather than just the visuals.

### Add a public email later

Add a `mailto:` link in the footer/nav once you decide which address should be public.
