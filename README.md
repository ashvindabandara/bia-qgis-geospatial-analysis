# BIA QGIS Geospatial Analysis

## Project Overview

This project focuses on the application of **Geographic Information Systems (GIS)** and geospatial analysis techniques to support radar deployment suitability assessment at **Bandaranaike International Airport (BIA), Sri Lanka**.

The project was developed as part of the **CIS6008 – Analytics and Business Intelligence** academic assessment and demonstrates how geospatial data, spatial analysis and visualization can support informed decision-making in the civil aviation sector.

## Objectives

- Georeference aerial imagery of the BIA area.
- Digitize relevant airport and surrounding geographic features.
- Create and manage spatial vector datasets.
- Apply QGIS geoprocessing techniques to identify suitable radar deployment areas.
- Analyse suitability for **Primary Surveillance Radar (PSR)**, **Secondary Surveillance Radar (SSR)** and **Surface Movement Radar (SMR)**.
- Identify buildings and other spatial constraints affecting radar deployment.
- Produce professional geospatial maps for decision-making.
- Demonstrate the business intelligence value of GIS in aviation infrastructure planning.

## Geospatial Analysis

The project includes spatial analysis involving:

- Airport runway and taxiway areas
- Buildings
- Trees and vegetation
- Water bodies
- Airport and administrative areas
- Radar suitability zones
- Spatial buffers and exclusion areas
- Intersection and difference operations
- Final suitable-area identification

### Radar Suitability Assessment

The analysis evaluates potential locations for:

**PSR – Primary Surveillance Radar**

Assessment of suitable areas considering spatial constraints and surrounding airport features.

**SSR – Secondary Surveillance Radar**

Identification of appropriate areas while considering relevant airport infrastructure and surrounding constraints.

**SMR – Surface Movement Radar**

Analysis of suitable areas around the airport environment while considering features such as taxiways, buildings and other spatial limitations.

## Tools & Technologies

- **QGIS** – Georeferencing, digitization, spatial analysis and cartographic visualization
- **Shapefile** – Spatial vector data management
- **GeoPackage** – Spatial data and analysis outputs
- **KML/KMZ** – Geographic visualization and data exchange
- **Google Earth Pro** – Geospatial visualization and validation
- **EPSG:5234** – Coordinate Reference System used for the analysis

## Repository Structure

```text
bia-qgis-geospatial-analysis/
│
├── Map/
│   ├── Final PSR and SSR Suitable Area Map
│   ├── Final Radar Deployment Suitability Map
│   ├── Final SMR Suitable Area Map
│   ├── Georeferenced Digitized Map of Bandaranayake International Airport
│   └── Radar Deployment Suitability Map
│
├── Shapefiles/
│   ├── SMR suitability layers
│   ├── PSR/SSR suitability layers
│   ├── Runway
│   ├── Taxiway
│   ├── Trees
│   └── Water Bodies
│
├── Task C
│   └── QGIS Project
│
└── README.md
