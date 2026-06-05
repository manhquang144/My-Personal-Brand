# Manh Quang Dau — CV Website

## Files
- `index.html` — your CV. This is the file you edit. (Renamed from "CV Website.html" so hosts serve it as the homepage.)
- `tweaks-panel.jsx` — powers the live theme panel. Keep it next to index.html.

## Edit locally in VS Code
1. Open this folder in VS Code.
2. Edit `index.html`:
   - **Text** (jobs, contact, etc.) — plain HTML in the page body.
   - **Styling** — the `<style>` block in the `<head>`.
   - **Theme presets & Tweaks** — the `<script type="text/babel">` block near the bottom.
3. Preview: install the **Live Server** extension (Ritwick Dey), then right-click `index.html` → "Open with Live Server".
   - Opening the file directly (file://) mostly works too, but Live Server avoids browser quirks with the .jsx file.

## Host it (free)
This folder is a complete static site. Pick one:
- **Netlify Drop** — netlify.com/drop — drag this whole folder in.
- **GitHub Pages** — push the folder to a repo, enable Pages.
- **Cloudflare Pages / Vercel** — drag-and-drop or connect a repo.

Because there are two files (html + jsx), upload the **whole folder**, not just the html.

## Note on the "bundled" file