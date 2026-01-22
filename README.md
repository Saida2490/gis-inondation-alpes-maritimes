# Urban areas exposure to flood risk – Alpes-Maritimes

## Context
Flood risk is a major issue in territorial planning, especially in Mediterranean areas.
The Alpes-Maritimes department is particularly exposed due to its coastal areas, river valleys,
and increasing urban pressure.

This project aims to analyze the exposure of urbanized areas to flood risk
using open spatial data and GIS tools.

## Objectives
- Identify urbanized areas exposed to flood risk
- Quantify the proportion of urban land located in flood-prone zones
- Compare exposure levels between communes within the department

## Study area
- Department: Alpes-Maritimes (France)
- Scale: departmental / communal

## Data sources
All datasets come from official open data sources:
- Administrative boundaries (communes): IGN / INSEE
- Urban areas: CORINE Land Cover
- Flood-prone areas: Flood Risk Atlas / PPRI (DREAL, data.gouv.fr)

## Methodology
The analysis was conducted using QGIS and includes:
- Data preparation and reprojection (Lambert-93)
- Selection of urban land use classes
- Spatial intersection between urban areas and flood zones
- Calculation of surfaces and exposure ratios
- Production of thematic maps

## Tools
- QGIS
- Open data (IGN, Copernicus, data.gouv.fr)

## Outputs
- Maps showing flood-prone areas
- Maps of urbanized areas exposed to flood risk
- Choropleth map by commune

## Limitations
- Regulatory flood data may vary in precision depending on areas
- The analysis is static and does not include temporal evolution
- Results depend on data scale and classification choices

## Status
Work in progress
