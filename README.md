# Williams Lab — website

A single-page static site. No build step, no server-side code. Just static files.

## Contents
- `index.html` — the whole site (HTML + CSS + JS in one file)
- `images/` — the figures and photos used on the page
- `favicon.svg` — browser-tab icon

## Fonts / internet
The page loads three fonts from Google Fonts (Instrument Serif, IBM Plex Sans,
IBM Plex Mono) over the internet. Everything else is local. If a host has no
outbound internet the page still works and falls back to system fonts.

## How to publish (pick one)

**MSU Domains / MSU web hosting (recommended for a lab):**
Upload the whole folder to the web space your college/IT gives you. The page
must be reachable as `index.html` at the folder root.

**Cloudflare Pages or Netlify (free, fastest):**
Drag this entire folder onto the dashboard's deploy area. It goes live in under
a minute with HTTPS. No configuration needed.

**GitHub Pages (free):**
Put these files in a repository, enable Pages on the default branch, root folder.

## Editing later
Open `index.html` in any text editor. The copy is plain HTML near the top of the
`<body>`. To swap a figure, replace the matching file in `images/` (keep the same
filename), or point the `<img src="...">` at a new filename.

## Still to add
- Lab logo (nav mark + footer lockup)
- ORCID/Scholar are linked; ZFIN allele/line link still marked "to add" in the footer
