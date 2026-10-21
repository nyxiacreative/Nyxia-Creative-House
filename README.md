# NYXIA Creative House — Interactive Landing Page

A ready-to-deploy, single-page portfolio website using plain HTML, CSS, and JavaScript. No build step, API keys, npm install, database, or paid dependencies required.

## Preview locally

Open `index.html` in your browser. For the most reliable preview (including all browser features), start a local static server:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Deploy via GitHub Pages

1. Create a new public GitHub repository (for example `nyxia-website`).
2. Upload **the contents of this folder** to the repository root (`index.html`, `styles.css`, `script.js`, `assets/`, `README.md`).
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
4. Once published, GitHub will provide the live website URL. You can connect a custom domain later.

## Deploy via Vercel

1. Push this folder's contents to a GitHub repository.
2. In Vercel, choose **Add New → Project → Import Git Repository**.
3. Framework preset: **Other**. No build command required. Output directory: `.` (root).
4. Deploy.

## Customize

- `script.js`: edit the **services** and **projects** arrays, partner notes, project details, and WhatsApp number (`WA`).
- `index.html`: edit section titles, Instagram URL, contact text, SEO metadata, and form options.
- `styles.css`: adjust colors, fonts, images, and animation.
- `assets/`: optimized versions of supplied original event photos, supporter reference images, and supplied NYXIA logos.

## Media and accuracy notes

- All event photos are from user-provided files. Site display is grayscale by CSS; full-color photos are visible on hover / in the gallery lightbox.
- The case studies use user-supplied details. The June 2026 month for Angon Jiwo is inferred from a supplied news clipping showing June 9; verify exact date before publishing if needed.
- Sponsor logos are shown as supplied composite images; individual sponsor marks were not reconstructed or implied to endorse NYXIA independently of their respective event.
- Verify use rights and credits for photographer photos and external logos before public launch.
- WhatsApp: +62 878-2347-1499. Instagram: @nyxiacreativehouse.
- Website's contact form does not collect or store data; it opens WhatsApp with a prepared text.
- The site is intentionally static and does not claim live ticketing or analytics.

## V3 — Art Direction & Motion

- Cinematic procedural abstract background on hero and philosophy sections (CSS only, no photo replacements elsewhere).
- Slow orbital sculpture, drifting silk/light beams and atmospheric grain.
- Scroll reveal, subtle interactive spotlight on desktop, premium card hover and project dialog entrance.
- Slim scroll-progress indicator.
- `prefers-reduced-motion` support; all copy, services, photos and portfolio data are unchanged.
- To deploy an update, replace the repository files with all contents of this folder and redeploy.

Note: Source and JavaScript syntax verified; automated visual browser testing was blocked in this environment. Please preview on your deployed site before publishing publicly.
