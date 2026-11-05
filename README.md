# Rezaul Islam — Academic Website

A free, static academic portfolio website prepared for GitHub Pages.

## Files
- `index.html` — main website (HTML, CSS and a small JavaScript snippet in one file)
- `robots.txt` — crawler instructions
- `sitemap.xml` — sitemap for search engines
- `assets/` — add your own profile photo, CV and (when approved for public release) thesis PDF here

## Publish at GitHub Pages
1. Sign in to GitHub as `rezaulislam`.
2. Create a **public** repository named exactly `rezaulislam.github.io`.
3. Upload the contents of this folder to the repository root (do not upload the outer folder itself).
4. In Settings → Pages, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Visit https://rezaulislam.github.io/ after deployment completes.

## Before publishing
1. Replace the generic Google Scholar, ORCID, ResearchGate and LinkedIn links with your own profile URLs.
2. Add your portrait as `assets/profile.jpg`. In `index.html`, find the profile placeholder and replace the `RI` text with:
   `<img src="assets/profile.jpg" alt="Portrait of Rezaul Islam">`
3. Add your current CV as `assets/cv.pdf`.
4. Only add a thesis PDF once it is approved for public release. The current thesis section correctly identifies the research as in progress.
5. Check all project descriptions, dates, institutional acknowledgements and roles for accuracy before publication.

## Updating later
Edit `index.html` directly on GitHub using the pencil icon, or edit locally and upload the changed file. Each commit to the `main` branch triggers a new GitHub Pages deployment.

## Search visibility
After publishing:
1. Open Google Search Console: https://search.google.com/search-console/
2. Add the URL-prefix property `https://rezaulislam.github.io/`.
3. Complete ownership verification.
4. Submit `https://rezaulislam.github.io/sitemap.xml`.
5. Use URL Inspection to request indexing of the homepage.

Indexing and ranking are controlled by Google and cannot be guaranteed. Keep the website public, accessible, accurate and updated. Link to it from your official academic profiles where possible.
