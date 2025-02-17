# ARC-GIS-AQI(Air Quality Index)-Prediction-and-analysis
📊 Air Quality and Urban Development – Data Analysis & Prediction

🔍 Project Overview

"Air Quality and Urban Development" explores the relationship between urbanization and environmental health by analyzing air pollution trends using Python for ArcGIS. This project utilizes geospatial data and machine learning to identify pollution hotspots and predict air quality levels. The analysis focuses on two critical air pollutants: PM2.5 and Carbon Monoxide (CO), applying interpolation techniques and GIS-based analysis for enhanced decision-making.

🏗️ Tech Stack

Programming Language: Python
GIS Tools: ArcGIS, ArcGIS Notebooks
Data Processing: Pandas, NumPy, FME (Feature Manipulation Engine)
Visualization: Matplotlib, ArcGIS Dashboard
Machine Learning: Spatial Interpolation (IDW, Natural Neighbor)
📌 Key Features

Data Collection: Extracted air quality data from EPA's Air Quality System (AQS).
Geospatial Analysis: Used ArcGIS Maps and Python scripts for spatial data processing.
Hotspot Identification: Applied point interpolation techniques to locate areas with high pollution levels.
Dashboard Implementation: Developed an interactive ArcGIS Dashboard to visualize real-time pollution trends.
Statistical Analysis: Conducted MAX Density Aggregation to detect pollution hotspots in the U.S.
🚀 Results & Insights

Identified key pollution hotspots across urban centers in the U.S.
PM2.5 and CO levels were analyzed and visualized using FME solutions.
ArcGIS Dashboard provides interactive air quality monitoring.
📌 Interpolation Techniques Used

Inverse Distance Weighted (IDW): Assigns values to unknown points based on the values of nearby known points, giving more weight to closer observations.
Natural Neighbor Interpolation: Uses triangulation to estimate unknown values based on the nearest data points.
⚠️ Challenges Faced

Data Cleansing: Required interpolation and Excel-based preprocessing for missing values.
Dataset Limitations: The original dataset lacked full U.S. coverage, requiring additional data sources.
Layer Integration: Some geospatial layers did not integrate correctly within ArcGIS.
🔮 Future Enhancements

Scalability: Expand the study area to more urban centers globally.
Automated Data Cleansing: Improve data accuracy through automated preprocessing.
Advanced Interpolation: Experiment with more spatial analysis techniques.
Expanded Parameters: Incorporate additional pollutants for a broader air quality assessment.
🌐 Resources

📌 ArcGIS Dashboard
https://umass-amherst.maps.arcgis.com/apps/dashboards/d5ad22362ce149f0a880437cce098a5a

📌 ArcGIS Notebooks & Data Layers
Filter 1: https://umass-amherst.maps.arcgis.com/home/item.html?id=1f1ee25259ca4d6291bcd3c0b40c89cb

Filter 2: https://umass-amherst.maps.arcgis.com/home/item.html?id=fc6ab13d6b284daf86b7ce35f4c16b54

Interpolation Filter: https://umass-amherst.maps.arcgis.com/home/item.html?id=92c1e1cf04474dd981d48705e8bbedab

Max Density Filter: https://umass-amherst.maps.arcgis.com/home/item.html?id=22d98cbe7ed54403b21ed8ea19acd290

Final Notebook: https://umass-amherst.maps.arcgis.com/home/notebook/notebook.html?id=c1d80286d3d348209b6c9a836bcd8e23

👨‍💻 Author

Shravan Sundar Ravi – Data Analyst & Geospatial Data Enthusiast
