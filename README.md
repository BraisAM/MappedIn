# MappedIn
# Draw Areas on the Map to Find LinkedIn Job Listings by Location

## Overview

**MappedIn** is an interactive web application designed to help job seekers explore LinkedIn job listings by selecting custom areas on a map of Switzerland. By drawing polygons over the map, users can visually define their preferred job search regions. The app then identifies major Swiss cities within the selected area and provides direct links to LinkedIn job searches for those locations, streamlining the job hunting process.

---

## Features

- **Interactive Map:** Built with [Leaflet](https://leafletjs.com/), the app provides a smooth, zoomable, and pannable map of Switzerland.
- **Polygon Drawing Tool:** Powered by [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw), users can draw custom polygon shapes on the map to define their job search zones.
- **City Detection:** The app contains a dataset of Swiss cities with geographical coordinates and detects which cities fall inside the drawn polygon.
- **LinkedIn Job Links:** For each detected city, the app generates clickable buttons linking directly to LinkedIn job listings filtered by location.
- **User-Friendly Interface:** The detected cities and corresponding job links appear dynamically below the map for easy access.

---

## How It Works

1. Open the app to see an interactive map centered on Switzerland.
2. Use the polygon drawing tool to mark your desired job search area.
3. After completing the polygon, the app calculates which major Swiss cities lie within the selected area.
4. The app displays the list of these cities with buttons linking to LinkedIn job searches specific to each city.
5. Click on the buttons to open LinkedIn job listings for your selected locations.

---

## Technologies Used

- **Leaflet:** For rendering the interactive map.
- **Leaflet.draw:** To enable polygon drawing on the map.
- **JavaScript, HTML, CSS:** Frontend application development.
- **GeoJSON & Geospatial Calculations:** To handle city locations and polygon intersections.

---

## Future Improvements

- Add filters for job categories, keywords, or experience levels.
- Extend coverage to other countries or regions.
- Enable saving, sharing, or exporting drawn areas.
- Integrate job listings from other platforms besides LinkedIn.
- **Add geolocation support** to allow users to quickly center the map on their current location.
- **Automatic city detection** without relying on a hardcoded list, by dynamically fetching or detecting cities within the drawn area.

---

## Try MappedIn

[MappedIn](https://braisam.github.io/MappedIn/)

