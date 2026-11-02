# Mandip Yadav — Premium AI/ML Portfolio
Responsive portfolio with a premium navy-and-gold visual theme, interactive project case studies, skills, GitHub activity and AWS Academy certificate previews. Built with HTML, CSS and vanilla JavaScript; no build step or backend required.

## Deploy
Push to `mandip000/mandip-portfolio`, then Settings → Pages → Deploy from branch `main` / root.

## Before publishing
- Replace the canonical/OG URL in `index.html` if the Pages URL differs (`https://mandip000.github.io/mandip-portfolio/`).
- Add `assets/images/og.png` (1200×630) for social previews.
- Add the Aquarius AI repo link in the `projects` array in `script.js` (`gh`) once you have it.
- Add certificate images to `assets/certificates/` if you want to show them.

## Shortcuts
`Ctrl/Cmd + K` opens the command menu (sections, project case studies, links, copy email).


### Certificates
The Certifications section includes four AWS Academy badge previews. Each preview links to its original PDF in `assets/certificates/`.


## Advanced portfolio update

This version adds refined interaction styling and dedicated email, phone, and Facebook contact cards while preserving the existing project and certificate assets.

### Publish on GitHub Pages
1. Extract the ZIP and copy the contents of `mandip-portfolio` into your repository root.
2. Keep the `.git` folder in your existing repository; do not replace it.
3. Run `git add .`, `git commit -m "Polish portfolio design and contact section"`, and `git push origin main`.
4. Confirm GitHub Pages is configured for the correct branch and folder.
