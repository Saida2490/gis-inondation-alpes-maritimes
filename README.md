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
## Data selection & methodology update

### Initial approach and limitations

The initial analysis relied on the CORINE Land Cover (CLC) dataset to identify urban areas exposed to flood risk.
However, during exploratory analysis, major inconsistencies were observed in highly urbanized coastal cities such as Cannes, Nice, Monaco and Menton.

Due to its coarse spatial resolution (minimum mapping unit of 25 hectares), CORINE Land Cover significantly under-represents dense urban fabrics, especially in Mediterranean coastal contexts.
As a result, key urban areas affected by recent flood events (notably in 2015 and 2017 in the Alpes-Maritimes) were either poorly represented or entirely missing.

This dataset was therefore deemed unsuitable for an accurate assessment of urban exposure to flood risk at the departmental scale.

### Methodological pivot

To ensure a more realistic and fine-grained analysis, the project methodology was updated to use the **OCS GE (Occupation du Sol à Grande Échelle)** dataset provided by IGN.

OCS GE offers a high spatial resolution (10 m) and a detailed classification of built-up areas, allowing for:
- accurate representation of dense and discontinuous urban fabrics,
- better alignment with real-world urban morphology,
- more reliable intersection with flood risk zones.

This methodological adjustment improves the robustness and relevance of the analysis, particularly for densely urbanized coastal territories such as the Alpes-Maritimes.

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
