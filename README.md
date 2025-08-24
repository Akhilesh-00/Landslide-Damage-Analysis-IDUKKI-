IDUKKI: https://code.earthengine.google.com/42257442a95b7b7d5b64c01bc8517664

WAYANAD: https://code.earthengine.google.com/28523f855cff81a9d57bad3d67f4b364

Landslide Damage Analysis – Idukki & Wayanad

Landslide Damage Analysis in Idukki and Wayanad – A remote sensing and GIS-based study using Google Earth Engine (GEE) with Sentinel-1 SAR, Sentinel-2, and DEM data. This project applies a Random Forest classifier to detect landslide-affected regions, quantify terrain changes, and assess land cover damage percentages across the highly landslide-prone districts of Idukki and Wayanad, Kerala.

🌍 Project Overview

The Western Ghats region of Kerala, particularly Idukki and Wayanad, is highly vulnerable to landslides due to steep terrain, heavy monsoons, and unregulated land use. This project leverages satellite-based remote sensing and machine learning classification techniques to:

Map landslide-affected areas.

Detect pre- and post-event land cover changes.

Quantify the extent of damage to forests, agricultural lands, and settlements.

🔑 Objectives

Detect and map landslide-affected vs. non-affected zones.

Perform land cover change analysis (e.g., forest loss, barren land increase).

Provide damage percentage statistics for each district.

Compare landslide patterns between Idukki and Wayanad.

🛰️ Datasets Used

Sentinel-1 SAR – Radar backscatter for surface deformation detection.

Sentinel-2 – Optical imagery for vegetation and land cover monitoring.

DEM (SRTM / ALOS) – Elevation and slope analysis.

ROI Boundaries – District shapefiles for Idukki and Wayanad.

⚙️ Methodology

Data Collection – Sentinel-1, Sentinel-2, and DEM loaded in GEE.

Preprocessing – Cloud masking, terrain correction, and filtering.

Feature Extraction – Indices such as NDVI, slope, and SAR backscatter.

Classification – Random Forest model to separate affected/unaffected areas.

Change Detection – Comparative analysis of pre- and post-event conditions.

Damage Assessment – Computation of land cover change percentages.

📊 Results

Generated landslide susceptibility maps for Idukki & Wayanad.

Identified forest cover reduction and increase in barren land in affected regions.

Produced damage percentage reports for each land cover type in both districts.

Created visual outputs: maps, before/after comparisons, and charts.

🖥️ Tools & Technologies

Google Earth Engine (GEE)

Random Forest Classifier

QGIS (for visualization)

