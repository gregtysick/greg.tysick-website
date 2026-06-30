# Deployment Notes

## Production

- Domain: `greg.tysick.com`
- Host: Namecheap shared hosting / cPanel
- Document root: `/home/beaufgfv/greg.tysick.com`
- SSL status on 2026-06-30: installed and live

## Source

The initial site snapshot was restored from:

`D:\Dropbox\Obsidian\Executive Function\Greg Tysick\Projects\greg.tysick.com\greg.tysick.com.zip`

## Deploy Flow

Use cPanel Git Version Control to deploy `main`. The `.cpanel.yml` file copies everything in `site/` to the production document root.

