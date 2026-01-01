# 🌊 Flood Susceptibility Mapping Using Weighted Overlay Analysis  
## Kaziranga National Park, Assam (2017)

---

## 📌 Project Overview

Flooding is a recurring natural hazard in the Brahmaputra floodplain, particularly affecting **Kaziranga National Park**, a UNESCO World Heritage Site. Seasonal monsoon rainfall, low-lying alluvial terrain, dense river networks, and soil characteristics contribute to frequent inundation, posing serious threats to wildlife habitats, infrastructure, and conservation efforts.

This project applies **Weighted Overlay Analysis** to identify and spatially classify flood-prone areas in and around Kaziranga National Park using multiple geospatial and hydrological parameters.

---

## 🎯 Objective

- To assess flood susceptibility using a **Multi-Criteria Decision Analysis (MCDA)** approach  
- To integrate key flood-influencing parameters through **Weighted Overlay Analysis**  
- To classify the study area into **Very Low, Low, Moderate, High, and Very High** flood susceptibility zones  
- To support **disaster preparedness, conservation planning, and sustainable management** of Kaziranga National Park  

---

## 📍 Study Area

Kaziranga National Park is located in **Assam, India**, along the southern bank of the **Brahmaputra River**, between approximately **26°20′N–26°50′N latitude and 93°10′E–93°40′E longitude**.

The park lies in a **low-lying alluvial floodplain**, making it highly vulnerable to annual monsoon floods. A **5 km buffer zone** was created around the park boundary to capture hydrological influences from surrounding terrain and river systems.

---

## 🗺️ Flood Susceptibility Map

![Flood Susceptibility Map](Flood%20Susceptibility.jpg)

---

## 🧾 Data Sources

| Parameter | Data Source | Description |
|--------|------------|------------|
| Digital Elevation Model (DEM) | SRTM | Elevation data for terrain analysis |
| Slope | Derived from DEM | Indicates terrain steepness |
| Flow Accumulation | Derived from DEM | Represents surface runoff concentration |
| Distance from River | HydroRIVERS (HydroSHEDS) | Euclidean distance from Brahmaputra & tributaries |
| Land Use / Land Cover (LULC) | Landsat 5 & 8 | Land cover classification |
| Rainfall | CHIRPS / IMD Pune | Annual rainfall data (2017) |
| Soil Type | SWAR | Soil characteristics influencing infiltration |
| Streams | DIVA-GIS | River and drainage network |

---

## 🛠️ Tools & Software

- **ArcMap 10.8**
- **Google Earth Engine (GEE)**

---

## ⚙️ Methodology

1. All input datasets were projected to **WGS 1948 UTM Zone 46N**.
2. Raster layers were clipped to the study area and **5 km buffer zone**.
3. Each parameter was **reclassified into 5 classes** based on flood influence.
4. Relative **weights were assigned** to each thematic layer.
5. **Weighted Overlay Analysis** was performed to generate a composite flood susceptibility index.
6. The final map was classified into:
   - Very Low
   - Low
   - Moderate
   - High
   - Very High flood susceptibility zones

---

## 📊 Key Input Parameters

- 🗺️ Digital Elevation Model (DEM)  
- ⛰️ Slope  
- 🌊 Flow Accumulation  
- 🏞️ Euclidean Distance from River  
- 🌾 Land Use / Land Cover (LULC)  
- 🌧️ Annual Rainfall (2017)  
- 🧱 Soil Type  

---

## 📈 Results & Interpretation

- **High and Very High flood susceptibility zones** are mainly concentrated along river corridors and low-lying floodplains.
- **Moderate zones** occur in transitional areas with mixed land cover and moderate terrain.
- **Low and Very Low susceptibility zones** are found in relatively elevated and well-drained areas.

The results emphasize the dominant influence of **river proximity, rainfall intensity, terrain, and soil characteristics** on flooding patterns in Kaziranga National Park.

---

## 📚 What I Learned

- Application of **Multi-Criteria Decision Analysis (MCDA)** in flood hazard mapping  
- Importance of **data standardization and reclassification**  
- Integration of **Google Earth Engine** for rainfall data processing  
- Understanding spatial relationships between hydrological and environmental factors  

---

## 🔮 Future Improvements

- Incorporation of **Sentinel-1 SAR flood extent data** for validation  
- Use of **Analytical Hierarchy Process (AHP)** for weight determination  
- Inclusion of **river discharge and water level data**  
- Long-term flood trend analysis using multi-year datasets  
- Accuracy assessment using historical flood records  

---

## 📌 Conclusion

This study demonstrates the effectiveness of **Weighted Overlay Analysis** in flood susceptibility mapping and provides valuable insights for **disaster risk reduction and conservation planning** in Kaziranga National Park.

---


**Hemungshew Borgohain**  
B.Sc. Geography | GIS & Remote Sensing  
