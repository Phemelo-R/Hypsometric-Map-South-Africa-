# 🌍Hypsometric Map of South Africa

This repository contains an R script for creating a detailed **Hypsometric Map of South Africa**. The map visualizes various geographical features, including elevation data, rivers, mountain ranges, provincial boundaries, and coastal features such as the Agulhas Bank and Benguela Upwelling. Additionally, it incorporates ocean currents and the Great Escarpment line. 🧑‍💻👾

## Features
- **Elevation Data**: Visualized using vibrant hypsometric colors ranging from deep ocean depths to the highest peaks.
- 🔵**Rivers and Provinces**: Includes South African rivers and provincial boundaries.
- 🌊**Coastal Features**: Highlights the Agulhas Bank and Benguela Upwelling regions.
- 🌊**Ocean Currents**: Displays the Agulhas and Benguela currents with directional arrows.
- 🗻**Mountain Ranges**: Marks major mountain ranges with labeled points.
- 🗻**The Great Escarpment**: Shown as a dashed red line.
- 📍**Neighboring Countries**: Includes labels and borders for neighboring countries.
- 📍**Annotations**: Labels for the Atlantic and Indian Oceans.

## Libraries Used
The following R libraries are used in this script:
- `tidyverse` for data manipulation and visualization
- `scales` for scaling functions
- `ggspatial` for spatial visualization
- `rnaturalearth` and `rnaturalearthdata` for Natural Earth map data
- `sf` for handling spatial features
- `raster` for raster data manipulation
- `elevatr` for elevation data
- `ggrepel` for repulsive text and label geoms
- `rnaturalearthhires` for high-resolution map data
- `ggnewscale` for multiple scales in `ggplot2`

## Script Overview
The script consists of the following sections:
- **Data Preparation**: Defines bounding boxes, retrieves spatial data, and formats it for visualization.
- **Map Construction**: Uses `ggplot2` to layer various map elements, including hillshade, elevation, rivers, and annotations.
- **Visualization**: The final map is displayed and can be saved as a high-resolution PDF.

## Example Output
The final map includes:
- Elevation data with hillshade for 3D-like topography.
- Labeled mountain ranges and rivers.
- Ocean features with currents labeled and arrows indicating direction.
- Neighboring country borders and labels.

## Credits
This map was created by **Phemelo Mojalefa Rutlokoane** as part of a bonus task for geographic data visualization.

---
**Sources**:
- NASA SRTM Elevation Data via the `elevatr` package
- Natural Earth Data for geographic features
