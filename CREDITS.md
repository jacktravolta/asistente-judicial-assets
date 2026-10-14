# Image credits

The four landing-page photos live in this repository and are served to the
`asistente-judicial` app through GitHub Pages:

    https://jacktravolta.github.io/asistente-judicial-assets/<file>.webp

Each file was downloaded from Unsplash, resized (max 1600 px), stripped of
metadata, and re-encoded as WebP (`-quality 78`) with ImageMagick (~187 KB
total). The app's landing hotlinks these URLs, so **do not rename this
repository or its files** — the production site depends on these paths.

All images are free to use under the [Unsplash License](https://unsplash.com/license)
(free for commercial and non-commercial use, no permission needed; attribution
appreciated but not required). The attribution below is provided as good practice.

| File | Source (Unsplash page) | Author | License |
| --- | --- | --- | --- |
| `hero-signing-document.webp` | https://unsplash.com/photos/man-writing-on-paper-OQMZwNd3ThU | Scott Graham (@amstram) | Unsplash License |
| `desk-workspace.webp` | https://unsplash.com/photos/person-holding-pencil-near-laptop-computer-5fNmWej4tAA | Scott Graham (@amstram) | Unsplash License |
| `documents-organized.webp` | https://unsplash.com/photos/person-holding-paper-near-pen-and-calculator-xoU52jUVUXA | Kelly Sikkema (@kellysikkema) | Unsplash License |
| `calm-planning.webp` | https://unsplash.com/photos/white-ceramic-mug-with-coffee-on-top-of-a-planner-aQfhbxailCs | Estée Janssens (@esteejanssens) | Unsplash License |

Direct image URLs used for the downloads (before conversion):

- `hero-signing-document` — https://images.unsplash.com/photo-1450101499163-c8848c66ca85
- `desk-workspace` — https://images.unsplash.com/photo-1454165804606-c3d57bc86b40
- `documents-organized` — https://images.unsplash.com/photo-1554224155-6726b3ff858f
- `calm-planning` — https://images.unsplash.com/photo-1506784983877-45594efa4cbe

## Notes

- Photos were chosen for a calm, trustworthy legal-services tone: documents,
  desks, hands, and quiet workspaces. None of them implies a legal result or a
  judicial outcome.
- Testimonials on the landing page remain speech bubbles without faces.
- If a photo is ever replaced, keep the same filename (URL stability), update
  this table, and preserve the `loading="lazy"` + descriptive `alt` conventions
  in the landing markup.
