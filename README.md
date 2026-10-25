# empirenetwork123.github.io

Source of my academic website, [empirenetwork123.github.io](https://empirenetwork123.github.io), built with Jekyll and served by GitHub Pages.

## Structure

| Path | Content |
|---|---|
| `_config.yml` | name, status, contact details and plugins |
| `_data/links.yml` | profile links shown under "Connect" |
| `_data/achievements.yml` | awards and scholarships (Background) |
| `_data/news.yml` | news items, newest first |
| `_data/publications.yml` | publications, newest first |
| `index.html` | profile, research interests, background and news |
| `publications.html` | publication list |
| `assets/` | stylesheet, favicon and profile photo |

Most updates only need a new entry in one of the files in `_data/`.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

The site is then available at http://localhost:4000.
