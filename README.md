# All About IT — GitHub Pages package

Free IT learning site for students: an in-site course (8 modules with full
lessons and self-checks), a Hello, World! first-code page, a guide, cheat
sheets, a glossary, IT careers, and a free PDF course guide.

## Files in this package

- `index.html` — the whole site in one file (this is the file GitHub Pages serves)
- `it-course-guide.pdf` — the free 10-page PDF guide the site links to
- `.nojekyll` — tells GitHub Pages to serve the files exactly as-is

## How to publish (about 3 minutes)

1. Go to github.com and create a free account if you don't have one yet.
2. Click **New repository**. Name it `itcourse` (or any name you like).
   Keep it **Public**, then click **Create repository**.
3. Click **uploading an existing file**, then drag in ALL the files from
   this package (`index.html`, `it-course-guide.pdf`, `.nojekyll`).
   Click **Commit changes**.
4. Open **Settings → Pages**. Under "Build and deployment", choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`, then **Save**.
5. Wait about a minute. Your site is live at:
   `https://<your-username>.github.io/itcourse/`

## Updating the site later

Upload a new `index.html` (same filename) to the repository and commit —
GitHub Pages updates itself within a minute or two. Nothing else changes.

## Custom domain (later, optional)

When `itcourse.eu.org` is approved and its DNS is ready, add a file named
`CNAME` containing only `itcourse.eu.org`, then set the DNS records GitHub
shows under **Settings → Pages**. Until then, the github.io address above
works on its own.

The current site at itcourse.neocities.org stays live — this is an
additional home for the same files, not a replacement you have to rush.
