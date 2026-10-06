# Naturome

Holding page for Naturome — softgel supplements.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | Live holding page: development notice and build status |
| `styles.css` | Styles for the holding page |
| `full-site.html` | Full marketing site, kept for the launch |
| `full-site.css` | Styles for the full site |
| `favicon.svg` | Icon — softgel with a leaf, vector |
| `favicon.ico` | Icon — 32px fallback |
| `favicon-180.png` | Apple touch icon |
| `Naturome_Logo_Transparent.png` | Wordmark |

Static files only — no build step. Open `index.html` in a browser, or serve the
folder from any static host.

## Brand

| Token | Value | Use |
| --- | --- | --- |
| Paper | `#F6F4EE` | Background |
| Ink | `#15180F` | Body text |
| Forest | `#1F3D2B` | Accent — active status, icon |
| Rule | `#D7D3C7` | Dividers |

Typefaces: Fraunces (headings), Inter (body), both loaded from Google Fonts.

## Updating the status

The development phases live in the `.status` table in `index.html`. Move the
`current` class to the row in progress and change the `Complete` / `In progress`
/ `Pending` labels alongside it.
