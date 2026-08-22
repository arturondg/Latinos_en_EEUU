# 🗺️ Geospatial Analysis: US Hispanic Demographics (Decennial Census)

An end-to-end exploratory data analysis (EDA) and geospatial mapping project analyzing the geographical distribution, population density, and demographic concentration of Hispanic and Latino communities across the United States.

---

## 📌 Project Overview

This project processes raw demographic data from the **US Decennial Census** and blends it with state and county shapefiles. Using Python's geospatial stack (`GeoPandas`, `Shapely`, `Folium`), the raw census variables were cleaned, standardized, and projected to uncover regional demographic concentrations and settlement patterns.

### Key Objectives:
* Clean and transform raw decennial census datasets.
* Join demographic metrics with US spatial boundaries (TIGER/Line shapefiles).
* Build choropleth maps and spatial visualizations to analyze geographic distribution at state and county levels.

---

## 🛠️ Tech Stack & Libraries

* **Data Processing & Manipulation:** `Python`, `Pandas`
* **Geospatial & GIS:** `GeoPandas`, `Shapely`
* **Visualization & Mapping:** `Folium`, `Matplotlib`, `Seaborn`
* **Environment:** `Jupyter Notebook`

---

## 🗂️ Data Pipeline & Methodology

1. **Data Ingestion:**
   * Raw population and ethnicity tables extracted from the US Decennial Census.
   * Spatial geometry datasets (Shapefiles / GeoJSON) for US administrative divisions.

2. **Data Cleaning & Spatial Preprocessing:**
   * Standardized FIPS codes across tabular and geospatial datasets.
   * Handled missing spatial records and normalized population totals into percentage densities.
   * Re-projected coordinate reference systems (CRS) to standard geographic projections (e.g., `EPSG:4326` and `EPSG:3857`).

3. **Geospatial Modeling & Visualization:**
   * Choropleth mapping by demographic density brackets.
   * Interactive layer generation with pop-ups and custom colormaps using `Folium`.

---

## 📊 Visualizations & Maps


### Hispanic Population Distribution (Choropleth)
<div align="center">
  <!-- Reemplaza esta ruta con la ubicación real de tu captura de mapa -->
  <img src="Assets/Texas_Latinos.png" width="850" alt="US Hispanic Demographics Map" />
</div>

## 🗺️ Live Interactive Maps (GitHub Pages)

Explore the county-level interactive choropleth maps directly in your browser without cloning or running the code:

### 🌟 Featured States (High Hispanic Density)

| State | Interactive Map Demo | Focus / Key Observation |
| :--- | :---: | :--- |
| **California** | [🔗 Open Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_California.html) | High urban & agricultural corridor density |
| **Texas** | [🔗 Open Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Texas.html) | Borderlands and major metro cluster analysis |
| **Florida** | [🔗 Open Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Florida.html) | Southeast coastal population concentration |
| **New York** | [🔗 Open Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_New%20York.html) | Tri-state metropolitan distribution |
| **Illinois** | [🔗 Open Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Illinois.html) | Midwest industrial & urban concentration |

---

<details>
<summary><b>📍 Click here to view all 50 State Interactive Maps (A–Z)</b></summary>
<br>

| State | Live Map Link | State | Live Map Link |
| :--- | :---: | :--- | :---: |
| **Alabama** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Alabama.html) | **Montana** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Montana.html) |
| **Alaska** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Alaska.html) | **Nebraska** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Nebraska.html) |
| **Arizona** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Arizona.html) | **Nevada** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Nevada.html) |
| **Arkansas** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Arkansas.html) | **New Hampshire** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_New%20Hampshire.html) |
| **California** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_California.html) | **New Jersey** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_New%20Jersey.html) |
| **Colorado** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Colorado.html) | **New Mexico** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_New%20Mexico.html) |
| **Connecticut** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Connecticut.html) | **New York** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_New%20York.html) |
| **Delaware** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Delaware.html) | **North Carolina** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_North%20Carolina.html) |
| **District of Columbia** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_District%20Of%20Columbia.html) | **North Dakota** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_North%20Dakota.html) |
| **Florida** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Florida.html) | **Ohio** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Ohio.html) |
| **Georgia** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Georgia.html) | **Oklahoma** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Oklahoma.html) |
| **Hawaii** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Hawaii.html) | **Oregon** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Oregon.html) |
| **Idaho** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Idaho.html) | **Pennsylvania** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Pennsylvania.html) |
| **Illinois** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Illinois.html) | **Rhode Island** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Rhode%20Island.html) |
| **Indiana** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Indiana.html) | **South Carolina** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_South%20Carolina.html) |
| **Iowa** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Iowa.html) | **South Dakota** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_South%20Dakota.html) |
| **Kansas** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Kansas.html) | **Tennessee** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Tennessee.html) |
| **Kentucky** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Kentucky.html) | **Texas** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Texas.html) |
| **Louisiana** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Louisiana.html) | **Utah** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Utah.html) |
| **Maine** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Maine.html) | **Vermont** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Vermont.html) |
| **Maryland** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Maryland.html) | **Virginia** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Virginia.html) |
| **Massachusetts** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Massachusetts.html) | **Washington** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Washington.html) |
| **Michigan** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Michigan.html) | **West Virginia** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_West%20Virginia.html) |
| **Minnesota** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Minnesota.html) | **Wisconsin** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Wisconsin.html) |
| **Mississippi** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Mississippi.html) | **Wyoming** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Wyoming.html) |
| **Missouri** | [View Map](https://arturondg.github.io/Latinos_en_EEUU/Mapas_Counties_States/Latinos_en_Missouri.html) | | |

</details>
---

## 💡 Key Analytical Findings

* **Regional Clustering:** High concentration indices remain prominent in historical Southwestern gateway states (California, Texas, Arizona, New Mexico), alongside distinct urban nodes in Florida, New York, and Illinois.
* **Emerging Hubs:** Notable relative growth in suburban and mid-sized metropolitan areas across non-traditional settlement states.
* **Spatial Density vs. Absolute Count:** Normalizing absolute counts by county population reveals high-density rural agricultural corridors that standard aggregated state maps obscure.

---

