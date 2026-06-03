# Academic Webpage — Miri Stryjan

Static HTML academic website, ready for GitHub Pages.

## Setup

1. Create a new GitHub repository named `yourusername.github.io`
   (or any repo — then go to Settings → Pages to enable it)

2. Upload `index.html` (and any assets) to the repository root

3. If using a custom domain, add a `CNAME` file with your domain name

## Customising the page

| What to change | Where in index.html |
|---|---|
| Photo | Replace `<div class="photo-placeholder">` with `<img src="assets/photo.jpg" alt="...">` and add your photo to an `assets/` folder |
| CV PDF link | Replace `href="#"` on the two "Download CV" buttons |
| Papers | Edit the `<div class="paper">` blocks in `#research` |
| Courses | Edit the `<div class="course">` blocks in `#teaching` |
| CV rows | Edit the `<div class="cv-row">` blocks in `#cv` |
| Social links | Update the `href` values for Bluesky / Google Scholar / SSRN |

## File structure

```
your-repo/
├── index.html        ← main page
├── assets/
│   └── photo.jpg     ← your headshot
└── CNAME             ← optional: if using a custom domain
```

## Notes
- No build step required — pure HTML/CSS/JS
- Mobile responsive
- Abstracts expand/collapse on click
