# Replyora website

A complete vanilla HTML/CSS/JavaScript marketing site for Replyora, an AI customer support agent.

## Run locally

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173/`.

## Deploy

Upload this folder to Vercel, Netlify, Cloudflare Pages, or GitHub Pages. Routes are folder-based and use clean URLs. The included `vercel.json`, `sitemap.xml`, and `robots.txt` are ready to edit with the production domain.

## Included routes

- `/`, `/features`, `/pricing`, `/use-cases`, `/about`, `/contact`, `/faq`
- `/blog` plus three complete articles
- `/tool` — public Reply Composer
- `/login`, `/register`, `/verify`, `/forgot-password`, `/loading`
- `/privacy`, `/terms`, `/cookies`, and `/404.html`

## Brand assets

Add the final `logo.png` and `icon.png` to `public/` when they are ready. The current text wordmark keeps the site usable before those assets are added.

## Notes

- No framework or build step is required.
- Internal links use clean root-relative paths without `.html`.
- Auth pages are frontend-only experiences and do not store passwords.
- The public Reply Composer is the only interactive output tool.
