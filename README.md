# uskyblock.github.io

Static homepage for the uSkyBlock project.

This repository contains the canonical landing page for:

- the official project homepage
- download and release links
- documentation entry points
- project metadata for search and social previews

## Structure

- `index.html` - homepage markup and metadata
- `styles.css` - site styles and responsive layout
- `assets/` - homepage image assets
- `robots.txt` - crawler directives
- `sitemap.xml` - sitemap for the published site

## Local preview

This is a plain static site. For a quick local preview, open `index.html` in a browser.

If you want to serve it over HTTP locally, one simple option is:

```sh
python3 -m http.server
```

Then open `http://localhost:8000`.

## Deployment

This repository is published via GitHub Pages at:

`https://uskyblock.github.io/`

Changes to `main` are intended to update the live site.

## Notes

- The hero image is served as responsive WebP in-page.
- Open Graph and Twitter metadata currently use the PNG asset for crawler compatibility.
- Structured data is defined directly in `index.html`.
- The metadata in `index.html` is intentional: title, description, Open Graph, Twitter tags, canonical URL, and JSON-LD should be kept aligned when editing the homepage.
- The JSON-LD graph is part of the site's SEO setup and should not be removed casually.
