# Earthquake Visualizer 🌎

An interactive, standalone web application that visualizes recent earthquake data from around the world on a responsive map.

![Earthquake Visualizer Screenshot](https://raw.githubusercontent.com/jaysonragasa/vibe_earthquakevisual/refs/heads/main/Screenshot%202025-08-21%20232310.png) 

## ✨ Features

This application provides a rich, interactive experience for exploring seismic data with the following features:

-   **Interactive Global Map**: Pan and zoom around the globe to explore earthquake locations.
-   **Heatmap Layer**: Instantly identify areas with high concentrations of seismic activity.
-   **Magnitude Representation**:
    -   **Color-Coded Circles**: Individual earthquakes are marked with circles colored according to a neon scale, from red (minor) to magenta (major).
    -   **Dynamic Sizing**: The size of each circle is proportional to the earthquake's magnitude.
-   **Detailed Tooltips**: Hover over any earthquake marker to see its specific magnitude, location, and time of occurrence.
-   **Comprehensive Filtering**:
    -   **Date Range**: Select a custom start and end date. Defaults to the current month.
    -   **Magnitude Range**: Filter earthquakes by minimum and maximum magnitude.
    -   **Geographic Filtering**: Narrow down the search by selecting a specific country and city. The map automatically zooms to the selected country.
-   **Responsive Design**:
    -   **Desktop View**: A classic sidebar layout for larger screens.
    -   **Mobile View**: The control panel transforms into a sleek, collapsible bottom sheet to maximize map space.
-   **Customizable Map View**:
    -   Toggle between **Satellite** and **Terrain** base maps.
    -   **Dark/Light Mode**: Switch between themes for optimal viewing comfort.
    -   **Find My Location**: A dedicated button to pan and zoom to your current location.
-   **Real-Time Data**:
    -   **Refresh Button**: Manually fetch the latest earthquake data based on your current filters.
    -   **Smart Error Handling**: If a query returns too many results, the specific error message from the API is displayed to the user.

---

## 📊 Data Source

This visualizer uses the **U.S. Geological Survey (USGS) Earthquake Catalog API** for real-time and historical earthquake data.

-   [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/)

Country and city data for the dropdown filters is sourced from the [countries-states-cities-database](https://github.com/dr5hn/countries-states-cities-database) on GitHub.

---

## 💻 Technologies Used

-   **HTML5**
-   **CSS3** (with Tailwind CSS for styling)
-   **JavaScript** (ES6+)
-   **Leaflet.js**: An open-source JavaScript library for interactive maps.
-   **Leaflet.heat**: A plugin for creating heatmaps on Leaflet maps.
-   **OpenStreetMap & Esri**: For the base map tile layers.

