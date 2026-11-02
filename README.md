# UDOT Transportation System Risk Map

- Old URL(s):
  - https://products.highstreet.work/exb_udot_rip_apps/rip_explorer/
  - https://products.highstreet.work/exb_udot_rip_apps/systemriskmap/
  - https://products.highstreet.work/exb_udot_rip_apps/Transportation%20System%20Risk%20Map/
- New URL: https://high-street-consulting.github.io/udot-system-risk-map/
- Migrated: 2026-11-02
- Source: IIS wwwroot folder `wwwroot\exb_udot_rip_apps\rip_explorer`
- Framework: ArcGIS Experience Builder 1.16, build 5

## Changes from original

- `web.config` dropped (IIS-only MIME/cache/rewrite rules; GitHub Pages does not use it)
- `*.map` source maps dropped (0 files)
- empty `.nojekyll` added (skip the Jekyll build on GitHub Pages)

No application code was changed.
