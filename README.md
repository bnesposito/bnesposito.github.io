# bnesposito.github.io

Personal academic website, served by GitHub Pages at https://bnesposito.github.io.

The site is plain HTML and CSS, so there is no build step (`.nojekyll` tells GitHub Pages to serve the files as they are).

| File | What it is |
| --- | --- |
| `index.html` | The whole website: intro, papers, teaching |
| `style.css` | All styling (colors are set at the top, including dark mode) |
| `files/Esposito_Bruno_CV.pdf` | CV. Replace it and keep the file name so links keep working |
| `images/` | Profile photo and favicon |
| `research/`, `teaching/` | Redirects from the old site's pages to the matching section |
| `404.html`, `sitemap.xml`, `google…html` | Not-found page, sitemap, Google Search Console verification |

## Common edits

- **Add a paper:** in `index.html`, copy one `<li>…</li>` block inside a `<ul class="papers">` list and edit it. Delete the `<button class="toggle">` and `<p class="abstract">` lines if there is no abstract.
- **Add a link under a paper** (slides, appendix, replication package): add an `<a href="…">…</a>` inside that paper's `<span class="links">`.
- **Preview locally:** open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.
