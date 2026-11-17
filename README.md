# Parkly – Smart Parking Tashkent (prototype)

Single-page prototype (React + Leaflet via CDN, no build step).

- Interactive map of Tashkent with per-spot status: available / occupied / unconfirmed
- Dashboard, search, filters, user reports with a 2-step confirmation
- Clicking a spot opens it in Google Maps
- **All parking data is simulated demo data.** Locations are approximate.

Future sensor/camera integration: `window.parklyIngest({id:"3-7", status:"occupied", source:"sensor", ts:Date.now()})`

## Run locally
Open `index.html` in a browser, or `npx serve .`

## Credits
Map data © OpenStreetMap contributors. District outlines from akbartus/GeoJSON-Uzbekistan (GPL-3.0), based on OpenStreetMap.
