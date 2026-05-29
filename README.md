# Vela Textile DPP Prototype

One-page static Digital Product Passport prototype for the TraceWeave practical case.

## Files

- `index.html` — complete one-page scroll prototype with embedded CSS and JavaScript.
- `vercel.json` — Vercel configuration to serve the site cleanly and avoid 404s.
- `README.md` — this guide.

## GitHub upload instructions

Upload the three files directly in the root of your GitHub repository:

```text
your-repository/
  index.html
  vercel.json
  README.md
```

Do not upload them inside another nested folder unless your Vercel Root Directory points to that folder.

## Vercel settings

Use these settings in Vercel:

```text
Framework Preset: Other
Build Command: leave empty
Output Directory: leave empty or .
Root Directory: leave empty, unless your files are inside a subfolder
```

After pushing to GitHub, redeploy the Vercel project and open the main deployment URL.
