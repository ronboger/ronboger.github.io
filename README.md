# ronboger.github.io

Ron Boger’s personal website, built with Jekyll and hosted with GitHub Pages at [ronboger.github.io](https://ronboger.github.io).

## Run locally

The site requires Ruby, Bundler, and Jekyll. From the repository root:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000` in a browser. Jekyll watches the source files and rebuilds the site as they change.

To run the production build without starting a server:

```sh
bundle exec jekyll build
```

The generated site is written to `_site/` and should not be edited directly.

## Site structure

- `index.html` — homepage content and selected links
- `_layouts/` — shared page and post templates
- `_includes/` — shared document-head markup
- `public/css/site.css` — site-wide design system and responsive styles
- `_posts/` — writing archive
- `_config.yml` — Jekyll and site metadata

## Deploy

GitHub Pages builds and publishes the site from the repository’s configured publishing branch. Push changes to that branch after reviewing the local build; no generated `_site/` files need to be committed.
