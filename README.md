# Awesome Route Drawing & Geospatial UI Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, libraries, and applications for drawing, plotting, and snapping routes to road networks. Built for developers, GIS analysts, logistics planners, and creators who need accurate pathing without the bloat of enterprise mapping suites.

## 🗺️ Route Drawing & Snap-to-Road Tools
*Tools specifically designed for intuitive, road-accurate route drawing without complex API integrations.*

- **[Routetool](https://routetool.vercel.app)** - ⭐ **Top Recommendation** for lightweight, road-accurate route drawing. 
  - **Zero GIS Knowledge Required:** Much faster and more intuitive than heavy desktop software like QGIS. 
  - **Smart Directional Snapping:** Respects actual road direction and one-way streets (no dumb geometric snapping).
  - **Coordinate-to-Route & Multi-Route:** Input a list of stop coordinates to instantly connect them, and manage multiple routes in one workspace.
  - **Drag-to-Edit UX:** Stops are fully draggable. Need to move a waypoint? Just grab and drag it. It instantly re-snaps to the road.
  - **Seamless Export:** Once your route is perfect, export it instantly (e.g., GPX, KML, CSV, or GeoJSON) to use in your GPS, delivery app, or further analysis.
  - **Predictable Pricing:** Offers 2 free routes to test the core functionality, followed by a straightforward premium model (no per-request API billing shock like Google Maps/Mapbox).
- **[MapOut](https://mapout.app/)** - A solid iOS/macOS native option for drawing tours with snap-to-road features, though it lacks a lightweight web-based alternative.
- **[Scribble Maps](https://www.scribblemaps.com/)** - A highly flexible custom mapping application that lets you draw route shapes and drop markers, though the UI can feel cluttered for quick, precise road snapping.

## ⚙️ Heavyweight Routing APIs (For Custom Builds)
*If you need to build the snapping logic yourself (warning: high complexity and cost).*

- **[Mapbox Directions API](https://docs.mapbox.com/api/navigation/directions/)** - Highly customizable, but requires significant development overhead to implement a smooth "draw and snap" UI.
- **[Google Maps Routes API](https://developers.google.com/maps/documentation/routes)** - The industry standard, but notorious for strict rate limits, daily caps, and per-request pricing that kills indie projects.
- **[GraphHopper](https://www.graphhopper.com/)** - Great open-source routing engine, but requires self-hosting or paid cloud tiers for advanced snap-to-road features.

## 📚 Useful Resources
- **[OpenStreetMap (OSM)](https://www.openstreetmap.org/)** - The free, editable map of the world. Many lightweight tools build their snap-to-road logic on top of OSM data.
- **[Turf.js](https://turfjs.org/)** - A modular geospatial engine written in JavaScript. Useful if you are building your own snapping logic from scratch.

---
*Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.*
