# LJT-Homepage

This is the source of [Junteng Liu](https://gustahiaho.github.io)'s academic homepage: bio, education, research experience, publications, skills and contact information.

The site is built with the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) (which is itself forked from the [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)). All content lives in Markdown and YAML files:

| File | What it contains |
| --- | --- |
| `_config.yml` | Site-wide settings and the author/sidebar information |
| `_pages/about.md` | The front page: bio, education, research experience, honors, skills, publications and contact |
| `_pages/cv.md` | Curriculum vitae, built from the `site.publications` collection |
| `_pages/publications.html` | Publication archive |
| `_publications/*.md` | One page per publication |
| `_data/navigation.yml` | Links shown in the header |
| `_data/authors.yml` | Author profiles used by the author sidebar |

## Running locally

1. Install the Jekyll dependencies:

   ```bash
   bundle install
   ```

2. Serve the site locally and open <http://localhost:4000>:

   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

The site is hosted on GitHub Pages: enable it in the repository settings ("Pages" section, source branch `master`). Because the repository is not named `username.github.io`, the site is served at <https://gustahiaho.github.io>.
