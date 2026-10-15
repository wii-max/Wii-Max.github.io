# Wei Quan's Homepage

Personal academic homepage of Wei Quan (Full Professor, School of Electronic and Information Engineering, Beijing Jiaotong University), built with the [Academic Pages](https://academicpages.github.io/) template (Jekyll + GitHub Pages).

## How to update

- **News / Bio / Awards / Services**: edit [`_pages/about.md`](_pages/about.md)
- **Publications**: add one Markdown file per paper under [`_publications/`](_publications/) (front matter: `title`, `category` = `books` / `standards` / `papers`, `date`, `venue`, `citation`), then commit and push
- **Site info / sidebar links**: edit [`_config.yml`](_config.yml)
- **Navigation**: edit [`_data/navigation.yml`](_data/navigation.yml)

## Local preview

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Notes

- Content migrated from the previous single-page HTML version (see git history).
- Deployment: GitHub Actions builds on push (repo Settings → Pages → Source: GitHub Actions).
