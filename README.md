# NYC Public Cameras

A simple, self-contained web app to find publicly available traffic cameras near any address in New York City (starting with strong coverage in Manhattan and other boroughs).

**Live app:** https://richthequick.github.io/nyc-public-cameras/

## Features
- Enter any address or place name in NYC
- Or use your device location
- Shows nearby NYC DOT / Traffic Management Center cameras with live still images
- Automatically expands search radius (from ~0.3 mi up to 10 mi) until useful results are found
- Displays distance from the requested point
- Images auto-refresh every 15 seconds
- Responsive design — works on phone or computer
- Prioritizes the highest-coverage public source (NYC TMC has ~900+ cameras across the city)

## How to use
1. Open the live app link above (or this `index.html` locally).
2. Enter an address (e.g. "Times Square", "Brooklyn Bridge", "1 World Trade Center") and click Search.
3. Or click "Use My Location".

No installation required. All data is fetched live from public endpoints:
- Camera list & images: `https://webcams.nyctmc.org/api/cameras`
- Geocoding: Nominatim (OpenStreetMap)

## Notes
- Best coverage in Manhattan and major corridors; expands automatically elsewhere in the five boroughs.
- Images are still frames that update frequently (not continuous video streams for most cameras).
- For rough weather checks, look for nearby highway/arterial cameras.
- Public data only. Always verify critical conditions with official sources.

Data courtesy of NYC DOT Traffic Management Center.
