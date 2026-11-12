
# Pra & Ankobra River Basins: Galamsey Turbidity & Mining Contamination Analytics
High level Report : https://docs.google.com/document/d/1T0uoGYIF0JT-P7an2wxcqvK-WTrwM1Bnrc2SP1su1Ug/edit?usp=sharing

An interactive geospatial investigation exploring how artisanal and small-scale gold mining (*galamsey*) within southwestern Ghana's Birimian gold belt has driven severe riverbed degradation, toxic mercury/arsenic mobility, and acute municipal water treatment shutdowns across the Pra and Ankobra catchments.

---

## Project Background

The Pra and Ankobra rivers drain Ghana's most prolific gold-mining districts (Tarkwa, Prestea, Bogoso, Obuasi, and Dunkwa-on-Offin). Over the past fifteen years, the mechanization of informal alluvial gold mining—utilizing heavy excavators and floating riverbed dredgers (*changfas*)—has severely altered fluvial geomorphology:
- **Extreme Turbidity:** Baseline river turbidity has surged from $<5\text{ NTU}$ to over $1,500–3,500\text{ NTU}$.
- **Municipal Water Outages:** The Ghana Water Company Limited (GWCL) has repeatedly suspended operations at major intakes, notably the **Daboase Treatment Plant** (supplying the 600,000+ residents of Sekondi-Takoradi) and the **Bunso Plant** (Birim River).
- **Toxic Heavy Metals:** Fluvial dispersal of elemental mercury ($\text{Hg}$) from gold amalgamation and dissolved arsenic ($\text{As}$) from oxidized arsenopyrite shear zones.

---

## Key Features of the Interactive Dashboard

- **High-Resolution Vector Hydrography:** Dedicated GeoJSON paths mapping the Pra mainstem, Offin, Birim, and Ankobra channels.
- **Deposit & Intake Layer Overlays:** Spatial correlation linking Birimian gold deposits with downstream municipal treatment intakes.
- **Water Quality & Turbidity Metrics:** Interactive visual comparison of baseline EPA drinking water thresholds versus post-galamsey field measurements.
- **Scale Resolution Analysis:** Demonstrating why global continental datasets (e.g., USGS/Natural Earth with 49 total African segments) prune these river systems out.

---

##  Data Sources & Credibility

1. **Mine Deposits & Exploration Sites:** USGS World Minerals Exploration Database (WMED) (`Mineral Exploration.csv`, `Mineral Deposits.csv`).
2. **Hydrographic Basins:** Ghana Water Resources Commission (WRC) Pra & Ankobra Basin Integrated Water Resources Management (IWRM) surveys; HydroSHEDS Level 8 drainage lines.
3. **Turbidity & Water Quality Data:** Ghana Environmental Protection Agency (EPA) surface water quality registers; Ghana Water Company Limited (GWCL) operational water intake bulletins.
4. **Scientific Field Studies:**
   - Kowalski, T., & Zielińska, K. (2025). *Sustainable sand mining practices and river morphological response in the Niger Basin.* IJGGE, 7(5), 41–45.
   - Heath, R., et al. (2004). *Water Related Impacts of Small Scale Mining.* Water Research Commission (WRC Report No. 1150/1/04).


## TOOLS used for this Project 
1. **leaflet.js, GeoJson, HTML and CSS, Vanilla Javascript, Jupyter Notebooks, SQL, Python

