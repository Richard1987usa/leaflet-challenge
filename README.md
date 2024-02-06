Overview of the Project

This project stems from the initiative of the United States Geological Survey (USGS), renowned for their comprehensive research on natural hazards, ecosystem health, and the effects of climatic and land-use changes. At the forefront of scientific innovation, USGS seeks to develop a suite of tools for the effective visualization of their extensive global earthquake data, which is collected daily but currently lacks a compelling presentation method.

Introducing an interactive dashboard designed to delve into the "USGS All Earthquakes from the Past 7 Days" dataset. This platform is equipped with a map feature that not only enhances the visualization of USGS data but also aims to augment public and governmental awareness about environmental challenges. The ultimate goal is to bolster funding and support for planetary issues.

Technological Stack

The dashboard is crafted using:

Leaflet
HTML
CSS
JavaScript
D3
Getting Set Up

To get started, ensure the following are installed on your development system:

A preferred code editor (like VScode)
A preferred web browser (such as Google Chrome or Firefox)
A Mapbox API key
Installation Steps

Clone the repository to your local machine using:

bash
Copy code
Open the repository in your code editor to review the codebase.

Store your Mapbox API key in a config.js file located in the static/js/ directory:

javascript
Copy code
export const API_KEY = <your API key>
Access the dashboard by navigating to localhost:5000 in your browser.

Key Features

Interactive Map: Centered on the GeoCoordinates [37.6000, -95.6650] (USA), with a zoom level of 2.5. Markers represent earthquake incidents, while orange lines depict tectonic plate boundaries. The map offers zoom and pan capabilities.

Layer Control: Choose from 3 base maps – outdoor, satellite (default), and grayscale. Two overlays, Earthquakes and Tectonic Plates, allow for enhanced visualization.

Markers: Marker sizes correlate with earthquake magnitudes, and colors vary with depth. Tooltips provide details like Magnitude, Location, and Depth.

Legend: A legend illustrates the correlation between depth and color.
