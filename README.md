# Geospatial Analysis of US Infrastructure

## 📈 Overview
This project undertakes a detailed geospatial analysis of the United States, focusing on two critical infrastructure elements: power plants and railways. By integrating various datasets, including state boundaries, power plant locations, and railway lines, this analysis provides valuable insights into the infrastructure's distribution and potential impacts on regional development.

## 🛠️ Features
◆ Data Integration

Combines multiple data sources to create a comprehensive geospatial dataset.

Uses GeoJSON for state boundaries and CSV files for power plant data.

◆ Geospatial Analysis

Analyzes the spatial distribution of power plants and railway lines across different states.

Utilizes Python geospatial libraries like GeoPandas and Shapely for spatial operations.

◆ Visualization

Generates maps and charts to visualize the density and distribution of infrastructure.

Provides interactive maps using Folium for enhanced user engagement.

## 📊 Data Sources

**State Boundaries:** GeoJSON format to delineate the boundaries of U.S. states.

**Power Plants:** CSV file detailing power plant locations, capacities, and operational statuses.

**Railways:** Shapefiles obtained from the Bureau of Transportation Statistics, detailing comprehensive railway networks across North America.

## 📚 Project Structure

Geospitalanalysis_enhanced.ipynb: Jupyter Notebook containing the complete analysis workflow.

us-states.json: GeoJSON file for U.S. state boundaries.

global_power_plant_database2.csv: Dataset containing details on power plants across the U.S.

North_American_Rail_Network_Lines.shp: Shapefile containing detailed information about railway lines. {You can download the railway data here: https://geodata.bts.gov/datasets/usdot::north-american-rail-network-lines/about We suggest downloading the shape file, which is 60MB vs the hundreds of MB of GeoJSON and CSV.}

## 💾 Installation

Clone the Repository
```bash

git clone https://github.com/yourusername/geospatial-analysis-us-infrastructure.git
cd geospatial-analysis-us-infrastructure
```

Install Dependencies

Ensure Python 3.6+ is installed and then run:
```bash
pip install pandas geopandas matplotlib folium
```

## 🚀 Usage

Start the Notebook
Launch JupyterLab or Jupyter Notebook.
Navigate to the project directory.
Open Geospitalanalysis_enhanced.ipynb.
Execute the Analysis
Run the cells sequentially to load the data, perform spatial joins, and generate visualizations.

## 🌟 Contributing

Contributions to enhance the analysis or extend the datasets are highly encouraged:

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -am 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a pull request.

## 📜 License

This project is distributed under the MIT License - see the LICENSE.md file for details.

## 🙌 Acknowledgments

**GeoPandas Community:** For the robust geospatial analysis tools.

**Bureau of Transportation Statistics:** For providing access to detailed railway data.

**Energy Information Administration (EIA)**: For the comprehensive power plant data.
