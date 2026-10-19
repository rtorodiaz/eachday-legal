# takeform.app

Marketing site and legal pages for **Take Form**, the habit tracker for iPhone. Support mail: support@takeform.app.

Plain static HTML — no build step, no dependencies.

| File | What it is |
|---|---|
| `index.html` | One-page landing |
| `privacy-policy.html` | Privacy Policy (also served at `/privacy` on Vercel) |
| `terms-of-service.html` | Terms of Service (also served at `/terms` on Vercel) |
| `assets/site.css` | Shared styles (light + dark, tokens mirror the app) |
| `assets/site.js` | Scroll reveal, theme toggle |
| `assets/icon.svg` | App mark (the three discs) |

## Deploy

- **GitHub Pages**: serve from the `main` branch root. No configuration needed.
- **Vercel**: import the repo; `vercel.json` adds clean URLs and the `/privacy` and `/terms` rewrites. Point `takeform.app` at the project.

## Local preview

```sh
python3 -m http.server 8080
```
