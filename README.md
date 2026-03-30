# Flood Vulnerability Assessment – Sonitpur District

## Project Structure

```
Flood Vulnerability Assessment/
│
├── report/
│   └── Assam Watershed Report.pdf
│
└── README.md

```
## What This Project Is About
 
This project analyzes flood vulnerability in the **Sonitpur district of Assam, India** using QGIS (Quantum GIS). Assam is one of India's most flood-prone states — nearly 40% of its land is at risk, about four times the national average. The Brahmaputra river and its 50+ tributaries are the main cause of recurring floods that have displaced millions of people.
 
This study focuses on Sonitpur's two major watersheds and uses spatial data to answer: *which areas are most at risk, and why?*
 
---
 
## What Was Done
 
### 1. Watershed Delineation
Two major watersheds in Sonitpur were mapped using a Digital Elevation Model (DEM). Each was further divided into sub-watersheds to understand how water drains through the region.
 
- Watershed 1 — 128.85 sq km (3 sub-watersheds)
- Watershed 2 — 176.32 sq km (3 sub-watersheds)
 
### 2. Stream Network Analysis
Streams within each watershed were extracted and classified using Strahler's stream order system. Total stream lengths were calculated.
 
- Watershed 1 total stream length: ~34,357 m
- Watershed 2 total stream length: ~33,679 m
 
### 3. Flood Vulnerability Assessment
Villages and towns within each watershed were identified and cross-referenced with the Government of Assam's official Flood Contingency Report to find which settlements fall in flood-prone zones.
 
| | Watershed 1 | Watershed 2 |
|---|---|---|
| Total villages/towns | 71 | 111 |
| Flood-vulnerable | 12 | 17 |
| Total flooded area | 14.74 sq km | 15.03 sq km |
 
---
 
## Key Findings
 
- Most flood-prone areas are near **river outlets**, where silt and sand deposits reduce the river's water-carrying capacity.
- Areas near **river bends** (e.g. Tengabasti, Karaina, Nirai Ati, Kathalguri) are especially vulnerable due to weak infrastructure.
- The hilly terrain causes fast-moving water during heavy rain, increasing flood risk in downstream plains.
- Historical floods in 2004, 2017, and 2020 confirm these are **recurrent high-risk zones**.
 
---
 
## Tools & Data Used
 
- **QGIS** with SAGA toolbox - spatial analysis
- **SRTM DEM** - elevation data
- **India ADM Shapefiles** - administrative boundaries
- **Census of India 2011** - population data
- **Government of Assam Flood Contingency Plan 2024–25** - flood zone reference
- **OpenStreetMap** - base map
 
---
 
## References
 
1. [Flood & Erosion Problems - Government of Assam](https://waterresources.assam.gov.in/portlets/flood-erosion-problems)
2. [What's Really Behind Assam's Worsening Floods? - PreventionWeb (2024)](https://www.preventionweb.net/news/india-whats-really-behind-assams-worsening-floods)
3. [A Historical Understanding of Assam's Floods - EPW (2022)](https://www.epw.in/engage/article/historical-understanding-assams-floods)
4. [District Disaster Management Authority, Sonitpur](https://sonitpur.assam.gov.in/departments/ddma)
5. [Flood Contingency Plan 2024–25 — Government of Assam](https://sonitpur.assam.gov.in/sites/default/files/public_utility/Flood%20Contigency%20Plan%202024-25_2.pdf)

---
_PRANAV SHARMA | BS IN ANALYTICS AND SUSTAINABILITY STUDIES | SEM III SEM IV_
---
