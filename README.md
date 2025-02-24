# Over-the-Air Updates Repository

This repository hosts the update bundles and configuration for the Over-the-Air update demo app.

## Structure

- `updates/` - Contains the update bundles (zip files)
- `capacitor.config.json` - Configuration file specifying the current version and bundle URL

## Versions

- 0.0.0: Initial version (white background)
- 0.0.1: First update (light green background)

## Update Process

1. Build new version of the app
2. Create update bundle
3. Update capacitor.config.json with new version
4. Push changes to this repository
5. App users can download the update through the app
