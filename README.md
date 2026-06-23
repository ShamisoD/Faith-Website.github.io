# Rooted & Tested

A single-page faith resource site listing the Bible study, discernment, and music
resources you personally use and trust.

## Files

- `index.html` — the page content and structure
- `style.css` — all colors, fonts, and layout

## How to open this in VS Code

1. Unzip the folder you downloaded.
2. Open VS Code.
3. Go to **File → Open Folder…** and select the unzipped `rooted-and-tested` folder.
4. Open `index.html` in the editor.

## How to view it in a browser

You don't need a server for this — it's a plain static page.

- **Easiest:** right-click `index.html` in VS Code's file explorer and choose
  **"Reveal in File Explorer / Finder,"** then double-click the file to open it
  in your browser.
- **Live preview while editing:** install the free **"Live Server"** extension
  in VS Code (search for it in the Extensions panel), then right-click
  `index.html` and choose **"Open with Live Server."** It will reload
  automatically every time you save.

## How to edit the content

Open `index.html` and look for the `<section class="resources">` blocks —
each resource (Life Bible Ministry, BSF, the podcast, Heliocentric, and the
four music artists) is one `<div class="resource">` block. Inside each one:

- `<h3>` — the name of the resource
- `<p class="desc">` — the description
- `<div class="note">` — your personal note on why you trust it (or a disclaimer)
- `href="..."` inside `<a class="visit">` — the link it opens

To add a new resource, copy one whole `<div class="resource">...</div>` block,
paste it where you want it, and edit the text and link inside.

## How to edit the look

Open `style.css`. The top of the file has a `:root` block with all the colors
and fonts named as variables (e.g. `--oxblood`, `--gold`, `--parchment`).
Changing a value there updates it everywhere on the page.

## Publishing it for free

Once you're happy with it, you can put this online for free with any of these:

- **GitHub Pages** — push the folder to a GitHub repo, then turn on Pages in
  the repo settings.
- **Netlify or Vercel** — drag and drop the folder onto their site in a
  browser; it gives you a live link in seconds.
