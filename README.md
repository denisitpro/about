# about

Personal one-page site for Denis Larkin, published via GitHub Pages at
https://denisitpro.github.io.

Plain static HTML + CSS — no build step, no framework, no dependencies.
Bilingual (English / Russian) with a small vanilla-JS language switcher;
English is the default and the page works with JavaScript disabled.

## Editing content

The copy on this page is not written here first. It is drafted and approved
in a separate private repo, `claude-edu/resume/github-pages/content.md`, and
then ported into `index.html` verbatim. To change what the page says, edit
the copy there first, then update `index.html` to match.

## Files

- `index.html` — the page (EN + RU markup in one file; language choice is
  persisted in `localStorage`)
- `style.css` — all styling
- `.nojekyll` — disables GitHub Pages' Jekyll processing
- `assets/` — screenshots and other static files referenced by the page
