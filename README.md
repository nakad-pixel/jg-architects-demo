# JG+ Architects — Demo Website

**DEMO / REFERENCE.** Every project, service and image here is placeholder content. Nothing is verified JG+ Architects work until the client supplies it.

## Replace content (no layout edits needed)
All content lives in `data/content.json`.

- **Project photo:** put a file at `images/projects/{slug}/hero.webp`, then set `"image"` for that project to that path. Same for `gallery` (array of paths).
- **Mark a project real:** set `"status": "REAL"` — the DEMO label disappears.
- **Services:** set `"verified": true`, or delete unverified ones.
- **Social:** set `"url"` and `"verified": true`; unverified links render disabled.
- **Contact:** fill `contact.email`, `contact.phone`, `contact.whatsapp`.
- **Logo:** edit `brand` in the JSON or swap in an SVG.

## Not yet built
Floor-plan zoom viewer, fullscreen/horizontal gallery modes, FAQ, image comparison, a form backend, sitemap. The page is set to `noindex` so the demo doesn't rank under the firm's name — remove the robots meta in `index.html` before launch.
