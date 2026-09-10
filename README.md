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

## Research files

- `research/BNNW/`: balanced neural networks weighting project files.
- `research/spatial-FD/`: spatial functional dependence paper, supplement, and slides.
- `research/NTU/`: pentad minimality verification script.

Keep all files for the same research project together. Local publication file
paths in `_bibliography/papers.bib` are relative to `research/`, such as
`spatial-FD/FD_spatial_main.pdf`. The CV PDF stays in `assets/CV/`; its path in
`_pages/cv.md` remains relative to `assets/`. Shared CSS, JavaScript, fonts, and
JSON keep their existing folders.

## Local preview

Install the gems with `bundle install`, then run `bundle exec jekyll serve`.
The generated `_site/` and local `vendor/` dependencies are ignored by Git.
