# Shan-Jyun Wu — CV site

A single-page CV built with Jekyll, served via GitHub Pages.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Structure

* `_pages/cv.md` — the CV content, served at `/`.
* `_config.yml` — site + author metadata (name, bio, links shown in the sidebar).
* `images/profile.jpg`, `files/Profile.pdf` — profile photo and downloadable PDF resume.
* `_layouts/`, `_includes/`, `_sass/`, `assets/` — vendored theme (unmodified).

## Attribution

Theme vendored from [ktliao/ktliao.github.io](https://github.com/ktliao/ktliao.github.io)
(generated from the [AcademicPages](https://github.com/academicpages/academicpages.github.io)
template, itself built on [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)
by Michael Rose), MIT licensed — see `LICENSE`. All personal content has been replaced;
only the Jekyll theme/layout code was reused.
