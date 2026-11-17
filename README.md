# Getvia NFC Landing Page

Static page opened when someone taps a Getvia NFC card. Plain HTML/CSS with no build step, no framework and no backend.

## Update the links

Open `index.html` and find the `EDIT YOUR LINKS HERE` comment. Change each `href`, plus the title and description text if needed:

| Card | Current link |
|------|--------------|
| Visit Our Website | `https://home.getvia.in/` |
| Follow Us on Instagram | `https://www.instagram.com/getviaofficial` |
| Get Started with Getvia | `https://getvia.in/` (the app; use `https://getvia.in/business/signup` to send businesses straight to signup) |

## Deploy (GitHub Pages)

1. Push this folder's contents to the root of a GitHub repository.
2. In the repository, go to **Settings → Pages → Deploy from a branch** and pick `main` / `/ (root)`.
3. Write the resulting URL (or your custom domain) to the NFC card.

All asset paths are relative, so the page works on `username.github.io/repo/` and on a custom domain. `.nojekyll` turns off Jekyll processing.

## Contents

```
index.html              page (styles inline)
assets/img/             Getvia logo + app icons (from frontend/public)
assets/fonts/           Inter 400/600/800, self-hosted (from @fontsource/inter)
```

Preview locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
