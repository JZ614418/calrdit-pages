# Calrdit · GitHub Pages

Three static pages for the App Store review:

- `index.html` — landing
- `support.html` — required by App Store for the "Support URL" field
- `privacy.html` — required for the "Privacy Policy URL" field

## Deploy

Simplest: a brand-new repo dedicated to Pages.

```bash
cd /Users/jz/Desktop/Calrdit/docs/pages
git init
git add .
git commit -m "Initial pages"
gh repo create calrdit-pages --public --source=. --push
```

Then in the new repo:

- GitHub → Settings → Pages → Source: `main` / root
- Wait ~60s for the first build

The pages come up at:

- `https://<your-github-handle>.github.io/calrdit-pages/`
- `https://<your-github-handle>.github.io/calrdit-pages/support.html`
- `https://<your-github-handle>.github.io/calrdit-pages/privacy.html`

Once those are live, come back and we'll write the two URLs into App Store Connect.
