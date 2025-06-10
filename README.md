# Amazon-Basin-LiDAR-Vegetation-Anomaly-Analysis



This project aims to uncover previously undocumented archaeological sites in the Amazon Basin by fusing advanced geospatial analysis, unsupervised machine learning, and AI-generated insights. It demonstrates a powerful and scalable pipeline for archaeological discovery from digital elevation and vegetation data.

---

## 🌍 Project Overview

We developed an end-to-end AI-augmented geospatial pipeline to:

- Analyze LiDAR-derived Digital Elevation Models (DEMs)
- Integrate simulated vegetation indices (NDVI)
- Detect terrain anomalies using unsupervised learning
- Interpret results using GPT-4 to generate scientifically grounded hypotheses

---

## 🗂️ Data Sources

- **Amazon Basin DEM**: High-resolution terrain elevation data  
- **Simulated NDVI Index**: Proxy for vegetation density (to simulate satellite vegetation patterns)

> 💡 *Note: NDVI values are simulated. In practice, multispectral satellite imagery would be used.*

---

## 🧪 Methodology

### 1. Terrain Feature Extraction
- Derived slope, aspect, and curvature from DEM
- Captures terrain signatures relevant to ancient earthworks

### 2. Multi-Feature Clustering
- Applied `DBSCAN` clustering to combined features (elevation, slope, curvature, NDVI)
- Identifies terrain clusters potentially related to anthropogenic patterns

### 3. Anomaly Detection
- Used `Isolation Forest` to highlight rare terrain-vegetation combinations
- Focuses attention on subtle archaeological indicators

### 4. AI Interpretations (GPT-4)
- Custom prompts were crafted to allow GPT-4 to:
  - Analyze geospatial patterns
  - Cite scientific literature
  - Suggest hypotheses and field validation steps

### 5. Interactive Visualization
- Real-time sliders for DBSCAN parameters
- Live geospatial map plots for easy exploration

---

## 🔍 Key Findings

- Terrain clusters align with known patterns of Amazonian geoglyphs and settlement mounds.
- Anomaly detection revealed isolated, subtle patterns that resemble anthropogenic structures.
- GPT-generated insights support interpretations grounded in archaeological research.

---

## ✨ Innovation & Impact

- 🧠 **AI-Augmented Discovery**: GPT-4 interprets and contextualizes data with scientific reasoning  
- 🌐 **Multimodal Fusion**: Combines elevation and vegetation features for richer insights  
- 🧭 **Unsupervised Learning**: No labels required — ideal for unknown or underexplored terrain  
- 📊 **Interactive & Reproducible**: Built using notebooks and widgets for full transparency

---

## 📈 Future Work

- Replace simulated NDVI with real satellite or hyperspectral data
- Test other clustering algorithms (e.g., HDBSCAN, UMAP)
- Validate high-interest areas with archaeologists or drone surveys
- Automate narrative generation using GPT for large-scale archaeological reconnaissance

---

## 📚 References

- Schaan, D.P. (2019). *Amazonian Geoglyphs and Anthropogenic Landscapes.*
- Levis, C., et al. (2017). *Archaeology and Ecosystem Engineering in the Amazon.*
- Canuto, M.A., et al. (2020). *Ancient Amazonian Peoples Revealed by Lidar.*
- Fernández-Díaz, J.C., et al. (2018). *Advanced Airborne Lidar for Archaeology.*
- Opitz, R.S., & Cowley, D.C. (2013). *Interpreting Archaeological Lidar Data.*
- ... *(Full list in report)*

---
