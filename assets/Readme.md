# Lara Grogan — Website

A simple, professional 3-page static website (Home / About / Tales & Legends), designed for bookers, managers, cultural partners, and press.

## Pages
- `index.html` — Home
- `about.html` — About
- `tales-legends.html` — Tales & Legends in Song

## Folder structure
- `assets/css/` — stylesheets
- `assets/js/` — JavaScript (menu, small UI behavior)
- `assets/img/` — images (portrait, OG image)
- `assets/docs/` — PDFs (optional: presenter pack, tech rider, etc.)
- `content/` — working materials (Word docs, drafts; not required for hosting)

## Run locally (recommended)
### Option A: VS Code Live Server (easiest)
1. Install the VS Code extension **Live Server** (by Ritwick Dey).
2. Open this folder in VS Code.
3. Right-click `index.html` → **Open with Live Server**.

### Option B: Simple local server (no extensions)
If you have Python installed:
- Windows PowerShell:
  - `py -m http.server 5500`
Then open:
- `http://localhost:5500`

## Deploy (static hosting)
This is a static site — no backend required.

### Deploy to GitHub Pages (fast)
1. Create a GitHub repository (e.g. `lara-grogan-website`)
2. Push this folder to GitHub (see steps below)
3. In GitHub:
   - **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/(root)**
4. Your site will be published at the URL GitHub gives you.

### Deploy to Netlify (also fast)
1. Go to Netlify and choose **Add new site → Import from Git**
2. Pick your GitHub repo
3. Build settings:
   - Build command: (leave empty)
   - Publish directory: `/`
4. Deploy.

## Content updates
- Website text is based on the Word docs stored in `content/source-word/`.
- When updating copy, edit the HTML pages directly (or update drafts in `content/` first, then paste into HTML).

## Notes
- Replace `assets/img/portrait.jpg` with the official portrait.
- Update booking contact email wherever it appears (Home + project page).
- Replace placeholder video link/embed on `tales-legends.html`.
