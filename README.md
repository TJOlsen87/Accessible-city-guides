# Accessible City Guides by TJ Olsen

Static, accessibility-first neighborhood and travel guides built from research, local knowledge, and firsthand experience.

## Current guides

- `ridgewood/` — working Ridgewood, Queens guide with filters and TJ notes.
- `new-orleans/` — legacy New Orleans restaurant/bar notes imported from TJ's last text version.
- `austin/` — 2026 NFB Austin restaurant guide.

## Hosting

The site is deliberately plain HTML/CSS/JavaScript so it can be hosted directly by Tiiny Host with no build process. The repository root is the site root and `index.html` is the landing page.

## Editorial conventions

- Alcohol is useful metadata, not a requirement for inclusion.
- Fast food and delis are included only when distinctive, unusually good, or practically useful.
- Firsthand TJ notes are kept separate from general descriptive information.
- Ridgewood uses `recommended`, `situational`, `research`, and `caution` rather than star ratings.
- Aunt Ginny's X I Like Food should be named exactly that. I Like Food is Fernando's independent pop-up housed at Aunt Ginny's.
- Do not describe I Like Food as "stoner food."
- Do not publish TJ's home address or coordinates. Future home-origin sorting should expose only derived distance/time.

## Updating

Ridgewood entries currently live in `ridgewood/data.js`. New Orleans is intentionally a legacy-source import for now so TJ can add firsthand notes before a more structured rebuild.
