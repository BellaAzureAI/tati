# Lyric Project

Minimal GitHub Pages template for publishing lyrics using the Minima theme.

## Included

- Minima configuration in `_config.yml`
- Home page in `index.md`
- Two sample lyric pages: `song-one.md`, `song-two.md`
- Lightweight style overrides in `assets/main.scss`

## Publish On GitHub Pages

1. Push this folder to a GitHub repository.
2. Open repository settings.
3. Go to Pages.
4. Set Source to `Deploy from a branch`.
5. Select `main` branch and `/(root)` folder.
6. Save and wait for deployment.

## Edit Lyrics

- Add one Markdown file per song.
- Use front matter like this:

```md
---
layout: page
title: Song Title
permalink: /song-title/
---
```

- Link songs from `index.md`.

## Optional Local Preview

If you have Ruby and Bundler installed:

1. Add a `Gemfile` with `gem "github-pages", group: :jekyll_plugins`.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve --source . --destination ./_site`.

### Build Folders

- `_site` is generated HTML output from Jekyll.
- `.sass-cache` is a temporary Sass cache folder and can be deleted safely.