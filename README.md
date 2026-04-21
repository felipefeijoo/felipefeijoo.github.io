# Felipe Feijoo — Personal academic website

Source for [felipefeijoo.github.io](https://felipefeijoo.github.io), the personal academic website of Felipe Feijoo, Ph.D. — Associate Professor at the School of Industrial Engineering, Pontificia Universidad Catolica de Valparaiso (PUCV), IPCC WGIII Lead Author (Energy Systems), and researcher on energy systems modeling, decarbonization pathways, and the energy-water-food nexus.

The site is built with [Jekyll](https://jekyllrb.com/) on top of the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template (which is itself a fork of the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme) and hosted on GitHub Pages.

## How it's organized

* `_config.yml` — site-wide settings (name, bio, sidebar links, author metadata).
* `_data/navigation.yml` — top navigation bar.
* `_pages/` — static pages (about, cv, grants, publications, talks, teaching).
* `_publications/` — one markdown file per paper; rendered on the Publications page.
* `_talks/` — one markdown file per talk/conference appearance.
* `_teaching/` — one markdown file per course.
* `files/` — downloadable assets, including `CV_Felipe_Feijoo.pdf`.
* `images/` — profile photo (`profile.png`), favicons, and other images.

## Adding a new publication, talk, or course

Create a new markdown file in the corresponding `_publications/`, `_talks/`, or `_teaching/` folder. Use an existing entry as a template — the filename should start with a date (`YYYY-MM-DD-slug.md`) and the YAML front matter drives the rendering.

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.

## Credits

Template: [Academic Pages](https://github.com/academicpages/academicpages.github.io) by the Academic Pages community, forked from [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose. Released under the MIT license.
