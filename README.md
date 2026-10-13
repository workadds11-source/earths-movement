# Earth's Movement

A responsive global map dashboard inspired by Apple's Liquid Glass visual language. Built with plain HTML, CSS, JavaScript and Leaflet.

## Features
- Interactive global map, place search, map-style switcher and responsive layout.
- Public air traffic states from OpenSky Network (subject to API availability, coverage and rate limits).
- Mapped tree features and road geometry from OpenStreetMap's Overpass API (zoom in to query local data).
- Wildlife and marine observations from GBIF. These are observation records, not live animal movement.
- Public world-event headlines from GDELT.
- Live refresh controls and clear notes about source coverage.

## Run locally
Open `index.html` in a modern browser. Internet access is required for the map and public data feeds.

## GitHub Pages
The site is configured to publish from the `main` branch root.

## Data sources
- OpenSky Network: https://openskynetwork.github.io/opensky-api/rest.html
- OpenStreetMap: https://www.openstreetmap.org/
- Overpass API: https://overpass-api.de/
- GBIF occurrence API: https://www.gbif.org/developer/occurrence
- GDELT DOC API: https://blog.gdeltproject.org/gdelt-doc-2-0-api-debuts/
- Nominatim search: https://nominatim.org/release-docs/latest/api/Search/
- Leaflet: https://leafletjs.com/

## Limitations
There is no single open API that provides complete, real-time global data for every requested category. Coverage, licensing, freshness, rate limits and browser access vary by provider. Some requested categories require specialized providers, credentials or curated historical datasets and are not represented as complete live layers here. This dashboard is informational only and should not be used for emergency or navigation decisions.

Respect each data provider's usage policy, rate limits, attribution requirements and license.
