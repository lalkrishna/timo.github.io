# Timo — website and privacy policy

GitHub Pages site for **Timo — Days Counter & Reminder** (Android, `app.philtre.timo`).

| Page | Path | Live URL |
|---|---|---|
| Home | `index.html` | https://lalkrishna.github.io/timo.github.io/ |
| Privacy policy | `privacy/index.html` | https://lalkrishna.github.io/timo.github.io/privacy/ |

Use the privacy policy URL in Google Play Console → **App content → Privacy policy**.

## Publish

1. Commit and push to `main`.
2. In the repo on GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`** → Save.
3. Wait a minute, then open the URLs above.

Plain HTML and CSS, no build step. `.nojekyll` tells Pages to serve the files as they are.

## Keep in step with the app

- The privacy policy describes v0.1: no `INTERNET` permission, no analytics, cloud backup excluded.
  **Update it (and its effective date) before any release that adds network access**, e.g. the v0.3 opt-in anonymous upload or accounts/sync.
- Play Console **Data safety** for v0.1: no data collected, no data shared.
- When the Play listing is public, swap the "Coming soon to Google Play" pill in `index.html` for a link (instructions are in a comment above it).

## Files

```
index.html            Home page (live widget numbers are computed in the browser)
privacy/index.html    Privacy policy
assets/styles.css     Shared styles; colours mirror the app's Timo tokens
assets/img/           Icon, favicon, Timo artwork, share image
```
