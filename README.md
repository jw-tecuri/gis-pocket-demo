# GIS Pocket Demo

**Live demo:** https://jw-tecuri.github.io/gis-pocket-demo/

An interactive map of one city area – Frankfurt, about 9.4 × 9.4 km – during one evening rush hour (17:00–18:30 UTC), running entirely in your browser. No server and no account are needed.

- **GPS readings:** 361,715 readings of 6,881 vehicles, shown as a grid, heatmap or 3D columns, coloured by speed, and as single readings when you zoom in. Click a reading for its details and its vehicle's trip.
- **Live traffic:** the vehicles drive on the map with short trails; play, pause, change the speed or drag the time slider. Click a vehicle to follow it.
- **Readings in view:** exact counts by vehicle class and speed for what the map shows, or for an area you select.
- **How it works:** « beside the map buttons opens a short explainer with small interactive figures: the grid, the Morton key, the count pyramid, cells or readings, counting with bounds, interpolated traffic.

All vehicle data is **synthetic** (generated), not recorded from real vehicles.

## Download and use offline

The whole demo is also available as one HTML file: download `gis-pocket-demo.zip` from the [latest release](https://github.com/jw-tecuri/gis-pocket-demo/releases/latest), unzip it and open `gis-pocket-demo.html` in a browser. It works without an internet connection.

## Browsers

Current Chrome, Edge, Firefox and Safari (it needs Chrome/Edge 94+, Safari 16.4+ or Firefox 113+) on desktop and mobile. A computer with a graphics card handles the 3D views best.

## About this repository

This repository holds only the published demo: `index.html`, `app.js` (the program, minified) and `pack.bin` (the map and traffic data). It is replaced with every update (one commit, one release).

## Credits and licences

- Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors (ODbL), map tiles and style by [Protomaps](https://protomaps.com).
- Built with [MapLibre GL JS](https://maplibre.org) and [deck.gl](https://deck.gl). The licence notices of all open-source packages in the program are included at the end of `app.js`.
