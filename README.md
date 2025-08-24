Landslide Damage Analysis – Idukki

This project focuses on mapping and analyzing landslide-affected areas in Idukki, Kerala using Remote Sensing (RS) and GIS techniques. The analysis is carried out on Google Earth Engine (GEE), leveraging multi-source satellite data and machine learning classifiers to identify and quantify terrain changes caused by landslides.

🌍 Project Overview

Landslides pose a major hazard in the Western Ghats, especially in districts like Idukki and Wayanad. This project uses a combination of digital elevation models (DEMs), Sentinel-1 SAR, and Sentinel-2 optical imagery to detect changes in land cover and slope stability, and to estimate the extent of landslide-affected areas.

🔑 Objectives

Identify landslide-affected vs. non-affected regions.

Quantify land cover changes (e.g., forest loss, barren land increase).

Use Random Forest classification for improved accuracy.

Provide damage percentage statistics for different land cover types.

🛰️ Datasets Used

Sentinel-1 SAR – Radar backscatter for surface deformation.

Sentinel-2 – Optical imagery for vegetation and land cover.

DEM (SRTM / ALOS) – Slope and elevation data for terrain analysis.

Study Area – Idukki district boundary shapefile/ROI.

⚙️ Methodology

Data Collection – Load Sentinel-1, Sentinel-2, and DEM data in GEE.

Preprocessing – Apply cloud masking, filtering, and terrain correction.

Feature Extraction – Generate indices (NDVI, slope, backscatter features).

Classification – Apply Random Forest classifier to distinguish affected vs. unaffected areas.

Change Detection – Compare pre- and post-event land cover.

Damage Assessment – Compute % changes in forest, barren, built-up, etc.

📊 Results

Landslide-affected zones mapped across Idukki.

Forest cover reduction and increase in barren land identified.

Damage assessment reports in percentage values per land cover type.

Visual outputs: classified maps, before/after comparisons, charts.

🖥️ Tools & Technologies

Google Earth Engine (GEE)

Random Forest Machine Learning

QGIS (optional for visualization)

Python (for post-analysis, if used)
