# Personal Academic Website

My personal academic homepage built with Jekyll and [al-folio](https://github.com/alshedivat/al-folio).

**Visit**: [https://zeqiwu.com](https://zeqiwu.com)

---

**Wu, Zeqi (吴泽齐)**

## Site files

- `_pages/`: page content and navigation.
- `_bibliography/papers.bib`: publications and working papers.
- `_data/`: CV, talks, coauthors, and social links.
- `_layouts/`, `_includes/`, and `_sass/`: page templates and styling.
- `_cv/cv.tex`: LaTeX CV source; `assets/CV/Zeqi_CV.pdf`: downloadable PDF.
- `.github/workflows/deploy.yml`: GitHub Pages build and deployment.

## Project assets

- `assets/BNNW/`: balanced neural networks weighting project files.
- `assets/spatial-FD/`: spatial functional dependence paper, supplement, and slides.
- `assets/CV/`: downloadable CV PDF.

Keep all assets for the same project together. Local publication and CV file
paths are relative to `assets/`, such as `spatial-FD/FD_spatial_main.pdf` and
`CV/Zeqi_CV.pdf`. Shared CSS, JavaScript, fonts, and JSON keep their existing folders.

## Local preview

Install the gems with `bundle install`, then run `bundle exec jekyll serve`.
The generated `_site/` and local `vendor/` dependencies are ignored by Git.
