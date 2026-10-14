# asistente-judicial-assets

Static image assets for the **Asistente Judicial** landing page, served as a
tiny static site through GitHub Pages.

## Why

The production app runs on shared hosting with a monthly transfer quota. The
landing's four hero photos are hotlinked from here so their bandwidth does not
count against the app's quota, and the app's deploy set stays smaller (~187 KB
less, 4 fewer files).

## Files

| File | Served URL |
| --- | --- |
| `hero-signing-document.webp` | https://jacktravolta.github.io/asistente-judicial-assets/hero-signing-document.webp |
| `desk-workspace.webp` | https://jacktravolta.github.io/asistente-judicial-assets/desk-workspace.webp |
| `documents-organized.webp` | https://jacktravolta.github.io/asistente-judicial-assets/documents-organized.webp |
| `calm-planning.webp` | https://jacktravolta.github.io/asistente-judicial-assets/calm-planning.webp |

## Rules

- **Do not rename this repository, its branch, or the files.** Production URLs
  depend on these exact paths.
- Replace a photo only by keeping the same filename and updating `CREDITS.md`.
- Images are WebP (q78, max 1600 px). The source JPEGs remain in the app
  repository's git history.
