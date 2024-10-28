# London Airbnb and Metro Accessibility Analysis 🌆🚇

**Description**: This project explores the distribution of Airbnb listings across various districts of London, focusing on accessibility to metro stations and how it impacts listing density, pricing, and cluster patterns. Through clustering models and geographic visualizations, the analysis aims to offer insights into travel and accommodation trends in London, particularly useful for potential investors, urban planners, and tourism managers.

---

## Table of Contents 📑

- [Introduction](#introduction)
- [Project Context](#project-context)
- [Analysis Overview](#analysis-overview)
- [Machine Learning Models](#machine-learning-models)
- [Insights and Findings](#insights-and-findings)
- [Files and Directory Structure](#files-and-directory-structure)
- [Contact](#contact)

---

## Introduction

The London Airbnb and Metro Accessibility project analyses the correlation between Airbnb listing density, metro accessibility, and district-specific features. This analysis leverages geographic data, listing metadata, and clustering algorithms to understand accommodation patterns in the city.

---

## Project Context

The data for this project includes Airbnb listings, metro station information, and district boundaries within London. The analysis includes weekday and weekend listing variations, price trends, and metro proximity, aiming to derive patterns that could guide stakeholders in the tourism and real estate sectors.

---

## Analysis Overview

This project explores several dimensions of Airbnb listings, such as:

1. **Metro Accessibility**: Investigating how proximity to metro stations affects listing density and average prices.
2. **Price Distribution by District**: Analysing average listing prices across different London districts.
3. **Cluster Analysis**: Using clustering algorithms to group neighbourhoods based on listing attributes, providing insights into distinct market segments.
4. **Attraction and Restaurant Indices**: Exploring the distribution of these indices across districts to determine their influence on listing patterns.

---

## Machine Learning Models

The following machine learning models and methods were used:

1. **K-Means Clustering**:
   - Applied to group neighbourhoods into clusters based on Airbnb listing features such as price, proximity to metro, and district indices.
   - Cluster visualizations provided insights into hotspots for listings and their distinct features.

2. **Geospatial Analysis**:
   - Folium maps with cluster overlays display the spatial distribution of Airbnb listings, illustrating clusters by density and district.
   - Geographic Information System (GIS) methods were used to compute the distance to metro stations and visualise listing distribution patterns.

3. **Predictive Modelling**:
   - Although not fully deployed in this analysis, initial steps towards using regression models to predict pricing based on location, metro accessibility, and neighbourhood characteristics were explored.

---

## Insights and Findings

1. **Metro Accessibility Impact**:
   - Districts closer to central metro stations, like the City of London and Westminster, tend to have denser listings and higher average prices. This suggests a premium associated with convenience in public transport access.
   - Outer districts like Lewisham and Greenwich, with fewer metro stations, show lower density and pricing, highlighting a potential gap in accessibility.

2. **Price Patterns**:
   - Premium pricing was observed in central areas with high attraction and restaurant indices, such as Westminster and the City of London.
   - Districts with fewer listings and amenities, such as Lewisham, recorded the lowest average prices.

3. **Clustering Analysis**:
   - The K-Means clustering revealed three primary types of neighbourhoods: high-density, mid-density, and low-density areas, each associated with specific price ranges and proximity to metro stations.
   - Neighbourhoods with similar tourist and dining attraction scores clustered together, indicating potential high-demand zones for Airbnb listings.

4. **Attraction and Restaurant Indices**:
   - Districts with higher attraction and restaurant indices tend to have more listings, as seen in areas like Camden and Westminster.
   - These indices correlated with price, demonstrating that amenities and attractions significantly influence Airbnb market dynamics.

---

## Files and Directory Structure

```
📁 Project Root
├── Airbnb.ipynb                  # Main Jupyter Notebook for data processing and analysis
├── Visualisations.ipynb          # Notebook dedicated to creating and fine-tuning visualisations
├── london_airbnb_clusters.html   # HTML output of Folium maps showing clustering results
├── london_airbnb_data.csv        # CSV containing Airbnb listing data for London
├── London_Ward.shp               # Shapefile for London district boundaries
├── london_weekdays.csv           # CSV for weekday-specific listing analysis
├── london_weekends.csv           # CSV for weekend-specific listing analysis
├── metro_access_analysis_sorted.csv  # CSV with metro accessibility metrics
├── README.md                     # Project README file
├── wards.csv                     # CSV with additional district-level data
└── 📁 Diagrams                   # Folder containing generated visualizations
    ├── Average attraction index.png
    ├── Average price per district.png
    ├── Avg metro distance.png
    └── Neighborhood and Airbnb Listing Counts by District.png
```

## Contact

For further inquiries or collaboration opportunities, please contact me via email: [vishalnavin@gmail.com](mailto:vishalnavin@gmail.com).

---
