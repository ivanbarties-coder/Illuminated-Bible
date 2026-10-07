# Illuminated Word — A KJV Bible Website

A colourful, illuminated-manuscript-styled website presenting the King James Version (KJV) Bible, book by book, with full chapter text, chapter navigation, and original artwork for each book.

## Live site

Once published with GitHub Pages, your site will be available at:

**[https://ivanbarties-coder.github.io/Illuminated-Bible/](https://ivanbarties-coder.github.io/Illuminated-Bible/)**

## How to publish this site with GitHub Pages

1. Create a new repository on GitHub named `Illuminated-Bible`. Do not initialise it with a README (you already have one here).
2. Upload all the files from this folder into the repository — either by dragging them into the GitHub web uploader, or via git:
  ```bash
   git init
   git add .
   git commit -m "Initial site upload"
   git branch -M main
   git remote add origin https://github.com/ivanbarties-coder/Illuminated-Bible.git
   git push -u origin main
  ```
3. In the repository, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`.
5. Set **Branch** to `main` and folder to `/ (root)`, then click **Save**.
6. Wait 1–2 minutes. GitHub will show your live URL at the top of the Pages settings screen.
7. Open that link — `index.html` will load automatically as your homepage.

## Folder contents

- `index.html` — homepage / book index
- `styles.css` — shared site styling
- One summary page and one or more chapter-read pages per Bible book (e.g. `genesis.html`, `genesis-read.html`, `genesis-read-2.html`, …)
- Book artwork images (e.g. `genesis-painting.png`)

## Notes

- All Scripture text is from the King James Version (KJV), which is in the public domain.
- No build step, server, or database is required — this is a static site, which is exactly what GitHub Pages hosts for free.

