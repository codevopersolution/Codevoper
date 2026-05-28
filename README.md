# Codevoper

A static landing page for Codevoper — a digital agency offering web development, UI/UX design, graphic design, e-commerce, social media management, and SEO optimization.

## Project Structure

- `index.html` — main landing page HTML file.
- `logo.svg`, `logo.png` — brand logo assets.
- `footer logo.svg` — footer graphic asset.
- `final.svg` — additional graphic asset used by the page.

## Description

This project is a polished static website for a digital agency. It includes:

- responsive hero section with animated visual elements
- agency services and portfolio presentation
- custom cursor and animated background effects
- modern dark theme styling using inline CSS
- no external build tools required; ready to deploy as static files

## How to Use

1. Open `index.html` in a browser.
2. Ensure the asset files (`logo.svg`, `logo.png`, `footer logo.svg`, `final.svg`) remain in the same folder as `index.html`.

## Deployment

Since this is a static website, you can deploy it by serving the `dist` folder with any static hosting provider, such as:

- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting
- Azure Static Web Apps

## Git Push Instructions

To push this folder to a Git repository, run these commands from the `dist` directory:

```bash
cd path/to/dist
git init
git add .
git commit -m "Add Codevoper static site"
git remote add origin https://github.com/codevopersolution/Codevoper.git
git branch -M main
git push -u origin main
```
