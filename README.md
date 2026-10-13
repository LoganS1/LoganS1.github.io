# logansinclair.me

Personal site. Static HTML and CSS, no JavaScript, no build step. Published by
GitHub Pages from `main` at `/` (mirrored there from Forgejo on every push).

| Path | What |
|---|---|
| `index.html`, `css/style.css`, `favicon.svg` | The site |
| `resume.pdf` | Resume, linked from the site |
| `CNAME` | Custom domain for Pages |
| `_archive/` | The previous site. Underscore folder, so Pages does not publish it |

Design notes: the "blueprint" skin since 2026-10-13. A blueprint-blue ground with a faint grid,
a drawing title block beside the intro, IBM Plex Mono labels with Source Serif 4 body text, and
safety yellow as the only accent. Everything is in `css/style.css`, with colours as custom
properties on `:root`. The one animation (the title block's reveal) sits behind
`prefers-reduced-motion`. The previous string-lights design (shared with `..\TheNookPeep`)
is in git history before that date.
