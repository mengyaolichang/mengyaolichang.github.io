# Academic homepage

Source for [mengyaolichang.github.io](https://mengyaolichang.github.io), the personal
homepage of Liyao Chang.

Built with [Jekyll](https://jekyllrb.com/) and the
[al-folio](https://github.com/alshedivat/al-folio) theme, and deployed to GitHub
Pages by [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) on every
push to `main`.

## Where the content lives

| Path | Contents |
| --- | --- |
| `_pages/about.md` | Landing page: bio, photo, contact |
| `_bibliography/papers.bib` | Publications; `selected={true}` also lists a paper on the landing page |
| `_news/` | News items; add `date_display:` to show a month without a day |
| `_data/cv.yml` | CV page |
| `_data/socials.yml` | Profile links |
| `_config.yml` | Site settings |
| `_sass/_custom.scss` | Style overrides, kept out of the theme partials |
