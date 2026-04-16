# AGENTS.md

## Project Purpose

This repository is a Hugo site for `dominikstrasser.dev`.
The site should function as a simple portfolio and CV website that clearly explains what Dominik does.

## Design Rules

- Keep the visual system minimal and text-led.
- Restrict the palette to black, dark gray, light gray, and white.
- Use `Outfit` as the default sans-serif font.
- Keep typography plain and document-like.
- Use whitespace for visual separation; avoid cards, panels, and boxed section treatments.
- Prefer container `gap` for layout spacing over ad-hoc margins between repeated elements.
- Avoid bright accent colors, complex gradients, and heavy animations unless the user explicitly asks for them.

## Key Files

- `assets/css/global.css`: global styling and shared design tokens.
- `layouts/_default/baseof.html`: global shell and stylesheet loading.
- `layouts/_default/list.html`: homepage and section list layouts.
- `layouts/_default/single.html`: single-content layout.
- `content/`: authored portfolio, CV, and section content.
- `public/`: generated output only; do not hand-edit.

## Working Rules

- Prefer Hugo templates and Markdown content over adding JavaScript.
- Keep copy concise and clear; the site should explain work quickly.
- When adding new sections, make them easy to scan on both desktop and mobile.
- Verify layout or content changes with `hugo`.
