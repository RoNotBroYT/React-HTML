# Map Explorer

## Overview

Map Explorer is a browser-based interactive weather map.  
It allows users to click anywhere on the map to view live weather data, toggle radar overlays, and jump to their current location.

The application runs entirely in the browser and does not require installation or a build system.

---

## Features

- Interactive zoomable map
- Click-to-view live weather data
- Temperature and wind speed display
- Rain detection
- Radar overlay toggle
- Radar playback animation
- Current location detection
- Clear all markers button
- Responsive user interface

---

## How It Works

When the page loads:

1. The map initializes and centers on a default location.
2. A base map layer is displayed.
3. The user can interact with the map immediately.

When the user clicks on the map:

- A marker is placed at the selected location.
- Weather data for that location is retrieved.
- Weather details are displayed in the information panel.
- A popup appears on the marker with key weather information.

If the user enables radar:

- A radar layer is displayed over the map.
- The radar animation cycles through recent radar frames when playback is activated.

If the user chooses to show their location:

- The browser requests location permission.
- The map centers on the detected position.
- Weather data loads automatically for that location.

---

## How To Use

### View Weather at a Location
1. Click anywhere on the map.
2. Wait briefly for the weather data to load.
3. View the results in the weather panel.

### Show Your Current Location
1. Click **Show My Location**.
2. Allow location access when prompted.
3. The map will center on your position and display local weather.

### Toggle Radar
- Use the **Radar ON/OFF** button to enable or disable radar.
- Use **Play Radar** to animate recent radar movement.

### Clear Markers
Click **Clear Markers** to remove all markers from the map.

---

## Requirements

- A modern web browser (Chrome, Edge, Firefox, Safari)
- Internet connection
- Location permission (optional)

---

## Running The Project

This project runs as a standalone HTML file.

To use:

1. Download or clone the repository.
2. Open the `index.html` file in your browser.

No installation steps are required.

---

## Project Structure

```
index.html
```

All functionality is contained within this single file.

---

## Summary

Map Explorer is a lightweight, fully browser-based weather mapping tool that provides real-time weather information and radar visualization through an interactive interface.
