# Joe's GitHub Pages Portfolio (Starter)

This repo is a **ready-to-deploy** GitHub Pages portfolio for **Albert Joseph (Joe)**.

## What it includes (matches Week 13 requirements)

- **Main page** with your **name**, **tagline**, and links to:
  - `bio.html` (Your bio)
  - `portfolio.html` (Your portfolio & team pitch links)
  - `pitch.html` (Elevator pitch placeholder — video comes later in Week 15)
- **Skills** badges to showcase your backend stack
- **Contact** link (email) + placeholders for GitHub & LinkedIn

## Quick Start (Deploy in Minutes)

### 1) Create the repository
- Go to GitHub → **New repository**.
- **Name** it exactly: `YOUR-USERNAME.github.io` (replace with your GitHub username).
- Choose **Public**. Create repo.

### 2) Add the files
Option A — **Upload via the web** (easiest):
- Click **Add file → Upload files**.
- Drag-and-drop all files/folders from this starter into your repo.
- **Commit**.

Option B — **VS Code / Git**:
```bash
# clone (replace with your username)
git clone https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io
cd YOUR-USERNAME.github.io

# copy the starter files into this folder, then:
git add .
git commit -m "Add starter portfolio"
git push
```

### 3) Visit your site
- Open: `https://YOUR-USERNAME.github.io`

## Customize (Do This Next)

Open these files and edit placeholders:

- `index.html`
  - Change **name** and **tagline**.
  - Update **Featured Work** links.
- `bio.html`
  - Replace the bio text with your Week 12 bio.
  - Update GitHub + LinkedIn URLs.
- `portfolio.html`
  - Add your **portfolio PDF** to `assets/portfolio.pdf` OR replace the button link with Google Slides.
  - Add links for your **Team Pitch Video** and **Team Slides**.
  - (Optional) Embed your slides by putting your **Google Slides embed URL** into the iframe.
- `pitch.html`
  - Leave as a placeholder for Week 13.
  - **Week 15**: Embed your video — replace the `about:blank` with your **YouTube/Drive embed URL**.

## How to embed a YouTube video

Replace the `iframe` in `pitch.html` with:

```html
<iframe
  src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
  title="Elevator Pitch"
  allowfullscreen
></iframe>
```

## How to embed a Google Slides deck

Publish your Slides to the web (File → Share → Publish to web) and copy the **Embed** link (looks like `/embed?start=false...`). Replace the `iframe src` in `portfolio.html` with that URL.

## Notes

- This starter uses **Bootstrap 5** + a small custom CSS file for a clean, modern look.
- You can add more pages or sections anytime.
- Everything is **static** and loads fast on GitHub Pages.
