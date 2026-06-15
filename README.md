# Nearest Grocery Stores

A single-page web app that shows walking routes from your home address to nearby grocery stores, powered entirely by open source mapping data — no API keys required.

**Live demo:** https://petterir.github.io/nearest-maps/

## Features

- Enter any home address and search radius (500 m – 3 km)
- Finds nearby supermarkets, grocery stores, and convenience stores via OpenStreetMap
- Draws a separate walking route to each store on the map
- Shows walking distance and estimated time for each route
- Click a store in the sidebar or on the map to highlight its route

## Data sources

| Purpose | Service |
|---|---|
| Map tiles | [OpenStreetMap](https://www.openstreetmap.org/) via Leaflet.js |
| Address geocoding | [Nominatim](https://nominatim.openstreetmap.org/) |
| Store locations | [Overpass API](https://overpass-api.de/) |
| Walking routes | [Valhalla](https://valhalla1.openstreetmap.de/) (pedestrian profile) |

## Usage

Open `index.html` in any browser — no build step, no dependencies to install.
