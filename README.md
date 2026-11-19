# Hisham’s personal website

A personal portfolio for Md Hasibul Husain Hisham, a Computer Science PhD student at the University of Utah. Professional content is based on `Hisham_profile.pdf` (November 2026); personal interests are retained from the original website. The layout uses system fonts, muted green accents, a personal introduction, a small project grid, and readable publication and experience lists.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://localhost:8000>. You can also open `index.html` directly. No package installation, build step, or external font service is required. If you have npm, `npm run dev` starts the same server and `npm run check` checks the JavaScript syntax.

## Edit the site

- `index.html`: profile, research, seven publications, experience, education, projects, service, awards, skills, and contact links.
- `css/style.css`: responsive layout, typography, mobile styles, and print styles.
- `js/main.js`: updates the footer year. All content and navigation work without JavaScript.
- `files/Hisham_profile.pdf`: the current downloadable CV. Replace this file when updating the CV, then update the page to match.
- `img/hisham-casual.jpg`: optimized version of the existing `img/hisham.jpg` photograph.

Publications are a plain list, ordered from newest to oldest. Entries without a paper URL are displayed without a paper link; add the official URL when available.

The original template assets in `vendor/`, `scss/`, and `css/resume*` / `js/resume*` are retained for reference. The rewritten page does not load them. The obsolete Gulp pipeline, Travis configuration, and npm dependencies have been removed.

## GitHub Pages

The site is static and can be served directly by GitHub Pages from the repository root. Changes are ready for review locally; publishing requires pushing them to the branch configured for Pages.

The original template’s license is retained in `LICENSE`.
