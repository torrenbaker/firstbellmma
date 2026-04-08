# First Bell MMA — Website

## Deploy to GitHub Pages

1. Create a new repo on GitHub called `firstbellmma`
2. Drop all files into `~/firstbellmma/`
3. Run:

```bash
cd ~/firstbellmma
git init
git add .
git commit -m "initial launch"
git branch -M main
git remote add origin https://github.com/torrenbaker/firstbellmma.git
git push -u origin main
```

4. Go to Settings → Pages → Deploy from branch → main → / (root) → Save
5. Site live at: `https://torrenbaker.github.io/firstbellmma/`

## TODO

- [ ] Add social media links (YouTube, Instagram, TikTok, X) — replace all `#` placeholder hrefs
- [ ] Add featured interview thumbnail image to `assets/`
- [ ] Add fighter interview thumbnails to `assets/`
- [ ] Replace placeholder email addresses if needed
- [ ] Add logo image when ready (replace the red dot in nav)
- [ ] Custom domain: buy `firstbellmma.com`, add DNS records pointing to GitHub Pages

## File Structure

```
├── index.html      ← Homepage (hero, interviews, events)
├── about.html      ← About page
├── contact.html    ← Contact page
├── privacy.html    ← Privacy policy
├── style.css       ← Shared stylesheet
├── assets/         ← Images (thumbnails, logos)
└── README.md       ← This file
```

## Iterate with Claude Code

```bash
cd ~/firstbellmma
code .
```

Use Claude Code in VS Code to make changes, then push:

```bash
git add . && git commit -m "update" && git push
```
