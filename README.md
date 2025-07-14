# Road Network and Healthcare Accessibility Analysis in Sukabumi City  
**Using OpenStreetMap and OSMNX**

![Geospatial](https://img.shields.io/badge/type-geospatial-blue) ![Status](https://img.shields.io/badge/status-completed-green)

This repository contains the final project for the course *Analisis Data Tidak Terstruktur* (Unstructured Data Analysis) at Universitas Indonesia. The project focuses on analyzing the road network and accessibility to healthcare facilities in Sukabumi City using open geospatial data and Python libraries such as OSMNX, NetworkX, Geopandas, and Folium.

---

## 📌 Project Objectives

- To analyze the structure of Sukabumi's road network using geospatial data from OpenStreetMap.
- To evaluate node importance using multi-centrality measures: Degree, Betweenness, Closeness, and Eigenvector Centrality.
- To assess spatial accessibility of healthcare facilities from road networks.
- To identify *healthcare deserts*—areas with poor access to healthcare services.
- To provide recommendations for optimal locations of new healthcare facilities based on the integrated analysis.

---

## 🧰 Tools and Libraries

- **Python 3.10+**
- `osmnx`
- `networkx`
- `geopandas`
- `folium`
- `matplotlib`, `seaborn`
- `scikit-learn` (for clustering)

---

## 📈 Key Findings

- Sukabumi's road network has **4,439 nodes** and **10,329 edges**, with average edge length of 76 meters.
- Using multi-centrality analysis, **3,022 strategic nodes** were identified.
- **599 strategic nodes** were found to be more than 3 km away from any healthcare facility, indicating underserved key locations.
- **53 nodes** were identified as *healthcare deserts* (>5 km away from any facility).
- Recommendations were made for **new facility placements** at high-centrality but underserved nodes.

---

## 📍 Visualizations

- Centrality-based road network maps
- Interactive maps showing strategic nodes and healthcare facilities
- Distribution of distance from each road node to nearest healthcare point
- Scatterplots showing relation between centrality and accessibility

---

## 📖 Final Report

The full analysis, discussion, and recommendations can be found in [`Laporan_UAS_Maryesta_Apriliani_Sihombing.pdf`](./Laporan_UAS_Maryesta%20Apriliani%20Sihombing_2206051531%20(1).pdf). *(Bahasa Indonesia)*

---

## 🧑‍💻 Author

**Maryesta Apriliani Sihombing** 
Course: Analisis Data Tidak Terstruktur  
