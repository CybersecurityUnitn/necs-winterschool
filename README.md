# NeCS PhD Winter School

This is the standalone Hugo source for the NeCS PhD Winter School website.

## Local development

Run `hugo server` and open the local address printed by Hugo. Create a production build with `hugo --minify`.

## Editing

- Site-wide dates, venue, contact address, and menu live in `hugo.yaml`.
- Each page is an editable Markdown file in `content/`.
- The homepage is `content/_index.md`; its presentation is in `layouts/index.html`.
- Images are stored locally in `static/images/`.
- Shared page chrome is in `layouts/_default/baseof.html`; styling is in `assets/css/site.css`.

The WordPress export is retained at the repository root as the migration source archive.
