# gordofreemo.github.io

Personal site of Andrew Geyko, served by GitHub Pages from `master`.

Plain HTML and CSS with no build step. `.nojekyll` turns off GitHub's Jekyll build.

- `index.html`: the page
- `style.css`: styles, light and dark
- `404.html`: the not-found page
- `images/`: the profile photo
- `files/cv.pdf`: the CV, built from `cv/`
- `cv/`: LaTeX source of the CV (curve class). Rebuild with `latexmk -pdf Geyko_Andrew_CV.tex` inside `cv/`, then copy the PDF to `files/cv.pdf`

Preview locally with `python3 -m http.server 8000` and open http://localhost:8000.
