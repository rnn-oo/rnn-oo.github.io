# All About IT — GitHub Pages package (with is-a.dev domain)

Files in this package:
- `index.html` — the full site (latest build)
- `it-course-guide.pdf` — the free 10-page course guide the site links to
- `CNAME` — sets the custom domain to `itcourse.is-a.dev` (the is-a.dev PR was merged; DNS already points to GitHub Pages)
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## What to do (repo `rnn-oo/rnn-oo.github.io` already exists)

1. Open the repo on github.com → **Add file → Upload files**.
2. Upload ALL files in this package (drag the whole folder contents), including `CNAME` and `.nojekyll`.
   - `index.html` will be overwritten with the newest version — that is intended.
3. Commit the changes.
4. Go to **Settings → Pages**. Under "Custom domain" it should now show `itcourse.is-a.dev`
   (the CNAME file sets this automatically). If it is empty, type `itcourse.is-a.dev` and Save.
5. Wait for GitHub to verify the domain and issue the HTTPS certificate (a few minutes up to ~24h).
   Once the certificate is ready, tick **Enforce HTTPS** on the same page.
6. Visit **https://itcourse.is-a.dev** — the site should load there. `https://rnn-oo.github.io` keeps working too.

## Updating the site later

Replace `index.html` (and the PDF if it changed) with a fresh export and commit. Keep `CNAME` and `.nojekyll` as they are.
