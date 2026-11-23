# Kainat Anam — Portfolio website

Static site (HTML, CSS, vanilla JS). No build step.

## Deploy on Vercel
1. Upload this folder to a GitHub repo, then Import it in Vercel.
   Framework Preset: Other. Build Command: leave empty. Output Directory: leave empty (root).
2. Or from this folder run: `npx vercel --prod`

## Edit content
- Everything lives in `index.html` (text, links).
- Images are in `assets/img/`. Replace a file with the same name to update it.
- After you get your live domain, change `og:image` in `index.html` to the full URL,
  e.g. https://your-site.vercel.app/assets/og.png
