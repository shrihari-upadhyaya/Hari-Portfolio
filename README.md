# Shrihari Upadhyaya — Product Manager Portfolio

A bold, product-led static portfolio website built with plain HTML, CSS, and a little JavaScript. Designed to impress recruiters and showcase PM work clearly.

## Sections

- **Hero** — Headline, value proposition, key stats
- **About Me** — Your story, strengths, and approach
- **Case Studies** — 9 PM documents (PRDs, RCAs, user research, growth strategy) linked as cards
- **Skills** — Six categories with visual skill chips
- **CV / Resume** — Timeline + PDF download
- **Contact** — Direct links: email, phone, LinkedIn

## Project structure

```
index.html
styles.css
script.js
assets/
├── hari-cv.pdf              # Your CV (downloadable)
├── shrihari-photo-web.jpg   # Optimised photo
└── case-studies/            # 9 PM case study PDFs
```

## How to customise

1. Open `index.html` and edit text directly.
2. Replace `assets/shrihari-photo-web.jpg` with a new photo (keep the same name, ideally under 300 KB).
3. Replace `assets/hari-cv.pdf` with an updated CV.
4. Add or remove case study cards in the Case Studies section — copy an existing `<article class="case-card">` block and point its link to a PDF in `assets/case-studies/`.
5. Update contact links in the Contact section.

## How to deploy on GitHub Pages

1. Create a new repository on GitHub.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo.
4. Under "Build and deployment", select **Deploy from a branch** and choose `main` / `root`.
5. Your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## Local preview

Open `index.html` directly in your browser, or run:

```bash
npx serve .
```

## Fonts

Uses [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts.
