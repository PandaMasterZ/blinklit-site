# BlinkLit — website

Marketing landing page + legal pages for **BlinkLit**, a hybrid reading app
(normal reader + RSVP speed reading) by Sr. Crema de Coco.

Static site — plain HTML/CSS/JS, no build step. Hosted on GitHub Pages.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page (hero with live RSVP demo, features, pricing) |
| `privacy.html` | Privacy Policy (required by Google OAuth / Play / Lemon Squeezy) |
| `terms.html` | Terms of Service |
| `style.css` | Shared brand tokens, animations, hover states, legal-page styles |

The only external dependency is Google Fonts. Everything else is self-contained.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000   # then visit http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push this folder to a **public** repo.
2. Repo → **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.
3. Site goes live at `https://<user>.github.io/<repo>/`.

## TODO before going live

- Replace the contact email `blinklitofficial@gmail.com` once the real address exists.
- Point the **Buy Pro** / **Start free** buttons to the real store/app links.
