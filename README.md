# CLASP Accessibility Demos

Interactive demo pages from TLDE's CLASP accessibility sessions (Captions, Links, Alt text, Structure, Palette). Every file is a standalone HTML page: no build step, no login, no data saved.

## The pages

- `index.html`: the landing page that links to the five demos.
- `clasp.html`: the one-stop page covering all five letters plus tables.
- `caption-check.html`: machine captions versus edited captions on a muted lecture clip.
- `link-list.html`: what a page's links sound like read aloud, plus a contrast checker.
- `alt-text-read-aloud.html`: three images read aloud with file names, then with real alt text.
- `heading-list.html`: the heading list from bold-text headings versus real ones.

## Good to know

- The read-aloud buttons use the browser's built-in speech. If a browser has none, the button says so.
- Fonts load from Google Fonts. Without a connection the pages fall back to system fonts and still work.
- Examples match the CLASP demo course (BIOL 205, Unit 4). The course is the source of truth if anything disagrees.

## Hosting

These pages are published with GitHub Pages from this repository's main branch, root folder. The landing page is `index.html`, and each demo has its own address that SharePoint can link to:

- Landing page: https://lmc-tlde.github.io/clasp-demos/
- CLASP page: https://lmc-tlde.github.io/clasp-demos/clasp.html

If the organization or repository name changes, both addresses change with it.
