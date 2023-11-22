# Geospatial Data Exploration and Visualization Project

![Alt text](https://editor.analyticsvidhya.com/uploads/95012geospatial.png)

## Overview

This project focuses on exploring and visualizing geospatial data for the city of Youssoufia. We leverage open-source data from OpenStreetMap to create points of interest (POIs) on a map, representing various locations like cafes, YouCode, etc. The visualization is done using Geopandas for data processing and Matplotlib for creating static maps.

## Project Architecture

The project is structured as follows:

```
├── data/
│ ├── youssoufia_geospatial_data.geojson # Geospatial data file
├── notebooks/
│ ├── geospatial_data_exploration.ipynb # Jupyter notebook for data exploration
├── README.md # Project README file

```

- **data/**: This directory contains the geospatial data file (`youssoufia_geospatial_data.geojson`) obtained from OpenStreetMap or GeoJSON.

- **notebooks/**: This directory contains the Jupyter notebook (`geospatial_data_exploration.ipynb`) where the geospatial data is processed and explored.

- **README.md**: This file provides an overview of the project, its architecture, and instructions for running and understanding the code.

## Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install geopandas matplotlib
```

## Clone the repository:
```
git clone https://github.com/yourusername/geospatial-project.git
```