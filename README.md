This project was completed by Emmitt Hasty and Kenny Phan.
# Florida Population and Land Use Analysis

This GitHub repository houses a comprehensive project analyzing Florida's population, land use, and elevation data. The primary objective is to explore the spatial distribution of the population, types of land use, and evaluate the potential impact of sea-level rise. The culmination of this project is an interactive map, viewable at (https://www.arcgis.com/apps/dashboards/a53ce4e6d8bd44ffb9456d407f720c1c) which visualizes our findings.


## Project Overview

The analysis involves several key steps:

### Data Loading and Cleaning
- **Sources**: Included above in the Data/Raw_Data folder.
- **Processing**: Data are loaded into pandas and geopandas DataFrames.
- **Cleaning**: Renaming columns, handling missing values, and standardizing data formats.

### Data Merging and Transformation
- **Merging**: Land use data is combined with population data.
- **Calculations**: Future population projections for 2150 and adjustments for potential sea-level rise.

### Data Visualization
- **Mapping**: Creation of color-coded maps using matplotlib.
- **Graphical Representation**: Plots to visually summarize data distributions.

### Risk Scoring and Analysis
- **Scoring System**: Development of a scoring system based on urban and built-up land use.
- **Integration with Income Data**: Adding income data to analyze socio-economic factors.

### Final Data Output
- **CSV Export**: The final processed data is exported as a CSV file, used in the ArcGIS interactive map. This CSV is the output of the `risk_refinement.ipynb` notebook.

## Features
- **Holistic Analysis**: Covers demographic, topographic, and economic factors.
- **Future Projections**: Includes long-term trends and risks assessment.
- **Spatial Analysis Focus**: Emphasis on understanding geographic patterns.

## Enhancements
- **Interactive Visualizations**: (Future work) To extend the data to new coastal areas, to allow new states to understand their risks.
- **Advanced Statistical Analysis**: (Potential) For deeper insights.
- **Documentation**: Ensuring transparency and reproducibility.

## Contact
emhrv3@umsystem.edu

---

This repository offers a rich and insightful analysis of Florida's population dynamics, land use patterns, and potential future risks. The interactive map serves as a powerful tool to visualize and understand these complex spatial relationships. For more detailed information, please refer to the individual files and folders within this repository.

