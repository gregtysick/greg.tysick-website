# Repository Agent Instructions

This repository contains Greg's personal link site for `greg.tysick.com`.

## Rules

- Treat `site/` as the only public deployable surface.
- Keep repository docs, migration notes, and agent instructions outside `site/`.
- Preserve the current static HTML snapshot unless Greg explicitly approves a redesign.
- Keep deployment target notes current while the WHC to Namecheap migration is in progress.

## Deployment

- Production target: Namecheap cPanel document root `/home/beaufgfv/greg.tysick.com`.
- Use `.cpanel.yml` to copy `site/` into the production document root when deploying through cPanel Git Version Control.

