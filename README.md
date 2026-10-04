# Daifeng Li's academic homepage

Live site: https://fengli1702.github.io/

An AcademicPages / Minimal Mistakes Jekyll site, adapted from
[Ran Yan's homepage](https://ran-yan-hk.github.io/). The original theme's MIT
license is preserved in `LICENSE`.

## Update the site

| Content | File |
| --- | --- |
| Name, affiliation, email, advisor, avatar | `_config.yml` |
| Navigation | `_data/navigation.yml` |
| Biography | `_pages/about.md` |
| Publications | `_data/publications.yml` |
| Education | `_data/education.yml` |
| Teaching | `_data/teaching.yml` |
| Awards | `_data/awards.yml` |
| Web CV | `_pages/cv.md` |
| Downloadable CV | `files/Daifeng_Li_CV.pdf` |
| Additional styling | `assets/css/custom.css` |

To add a photo, put it in `images/` and change `author.avatar` in `_config.yml`.
The current avatar is a neutral initials graphic. Only add verified social
profile URLs; unset fields are hidden.

The PDF is a public copy of the supplied pre-PhD CV, with the cognitive-diagnosis
project removed and the email written using AT/DOT without a mailto link.
The website includes the September 2026
PhD enrollment confirmed by Daifeng; replace the PDF when an updated CV is ready.

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/. GitHub Pages builds and publishes the `main`
branch from the repository root using its native Jekyll build.

The former Hugo site is retired. Its last version is preserved at the tag
`archive/pre-academic-homepage-2026-10-04` and in Git history.
