# scho.ai — personal site

Plain static HTML, served by GitHub Pages from the `master` branch root. No build step, no framework.

- `index.html` is the whole site; styles are inline in its `<style>` block.
- `CNAME` holds the custom domain (scho.ai). Don't delete it.
- `.nojekyll` stops GitHub from running Jekyll. Keep it.

## Style rules
- Minimal and typographic: one column, serif body, no cards, gradients, icons, emoji or animations.
- Keep copy short and plain. First person. British spelling.
- Never write the email address in plain text in the HTML. It is assembled in the script at the bottom.

## Common edits
- New publication: add an `<li>` at the top of "Selected publications" (title link, then `<span class="meta">Authors · Venue, Year</span>`). Keep it to ~5 entries; Scholar has the rest.
- New project: same pattern under "Building".

## Deploy
Commit and push to `master`. The site updates about a minute later.
