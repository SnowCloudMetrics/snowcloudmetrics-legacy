# SnowCloudMetrics-Legacy

This repository preserves the legacy Google Earth Engine scripts that were used to build
the SnowCloudMetrics workflow and the supporting app interface.

Website: https://www.snowcloudmetrics.app/

It is intentionally lightweight and archival:

- `archive/v1/snow_metrics_2020_toAsset.js` is the original global SnowCloudMetrics workflow.
- `app/snowcloudmetrics_app_ui.js` is the Earth Engine script that supported the app UI/backend.

## What this repo is for

- Preserve the original Earth Engine source code in a readable form
- Document how the scripts were used
- Keep the legacy implementation separate from the newer canonical `snowcloudmetrics` repository

## Recommended starting points

1. Read `app/README.md` for the legacy website/app backend script
2. Read `archive/v1/README.md` for the publication-era workflow
3. Read `docs/version-history.md`
4. Read `docs/methodology.md`
5. Read `docs/app-notes.md`

## Notes

- These scripts are designed for the Google Earth Engine code editor.
- They depend on Earth Engine assets and collections that may no longer be public.
- The scripts are preserved for historical reference and reproducibility.
