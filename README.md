# 🇮🇳 SMART INDIA HACKATHON 2026 — LANDSLIDE AI

> **Problem Statement ID:** `SIH26001`  
> **Problem Statement Title:** AI-Based Early Warning and Landslide Risk Monitoring System in NER  
> **Theme:** Disaster Management  
> **Category:** Software  
> **Team ID:** `AMP2026017`  
> **Team Name:** `Landslide AI`  

---

## 📌 Proposed Solution (Slide 2)
**Landslide AI** is a smart disaster-management platform that combines:
- **Rainfall** (IMD weather and precipitation APIs)
- **Soil-Moisture** (IoT geotechnical ground sensors)
- **Terrain / Slope** (Digital Elevation Models & gradient analysis)
- **Historical Landslide Data** (Past occurrence mapping across the North Eastern Region)

to estimate real-time landslide risk and support life-saving early warnings.

### How It Addresses The Problem:
* **Continuous Risk Monitoring:** 24/7 telemetry tracking across critical NER corridors.
* **AI-Based Risk Level:** Simple, actionable categorization: **Low / Moderate / High**.
* **Early Alerts for Vulnerable Areas:** Triggered before slope shear thresholds fail.
* **Dashboard for Authorities & Response Teams:** Unified portal for SDMA, NDRF, and District Commissioners.
* **Location-Based Warnings & Evacuation Support:** GIS-guided safe evacuation perimeters.

### Innovation & Uniqueness:
1. **Combines Multiple Risk Signals in One Platform:** Fuses weather, terrain physics, and historical catalogs.
2. **Converts Raw Data into an Easy-to-Understand Risk Map:** Color-coded GIS map for instant situational awareness.
3. **Supports Prevention, Preparedness, and Response in One Workflow:** From early warning to citizen field reporting.

---

## 🏛️ Designed for Both Authorities and Communities (Slide 5)

The platform is architected around **6 Core Modules**:

1. **`01 - AI Risk Assessment`**: Multi-factor model calculating real-time Risk Score (0–100), Risk Class (Low / Mod / High), and Confidence Score.
2. **`02 - Interactive Risk Map`**: Visualizes vulnerable zones across the **North Eastern Region (Meghalaya, Assam, Sikkim, Arunachal Pradesh, Mizoram)**.
3. **`03 - Early-Warning Alerts`**: Location-based siren and SMS alert dispatch when rainfall/moisture thresholds are exceeded.
4. **`04 - Authority Dashboard`**: Real-time HUD command center for disaster response forces and district administrations.
5. **`05 - Citizen Reporting`**: Geo-tagged community field reporting tool allowing local residents to submit photos and reports of ground cracks.
6. **`06 - Explainable View`**: Transparent SHAP feature attribution bars showing the exact percentage breakdown (Rainfall, Soil Moisture, Slope, History) behind each prediction.

---

## ⚙️ Technologies & Architecture (Slide 3 & 4)

| Layer | Technologies Defined in PPT |
| :--- | :--- |
| **Backend API Framework** | Flask, FastAPI (Python) |
| **Frontend UI** | HTML5, CSS3, JavaScript (Tailwind CSS, Leaflet.js) |
| **Predictive Intelligence** | Scikit-Learn, PyTorch, XGBoost |
| **Data Ingestion** | Weather / Rainfall & Sensor APIs (IMD, CWC) |
| **Database** | PostgreSQL, PostGIS, TimescaleDB |
| **Spatial / Mapping Layer**| Leaflet.js, Mapbox, PostGIS |

---

## 🗺️ What We Will Build First (Slide 6 Roadmap)

- [x] **PROTOTYPE (MVP):** Dashboard + Interactive GIS Map + Historical NER sample dataset *(Completed!)*
- [ ] **AI MODEL:** Train and validate multi-factor XGBoost & PyTorch models using Geological Survey of India (GSI) historical datasets.
- [ ] **INTEGRATION:** Connect live IMD rainfall APIs and TimescaleDB streaming sensor tables.
- [ ] **PILOT:** Deploy field pilot with local NER disaster management teams (Meghalaya & Sikkim SDMA).

---

## 🎯 Target Audience & Impact (Slide 7)
* **Target Audience:** Local administrations, Emergency responders (NDRF / SDRF), and communities in landslide-prone hill tracts.
* **Social Impact:** Earlier awareness, faster coordination, safer evacuation planning, and improved community preparedness.
* **Environmental Impact:** Supports monitoring of vulnerable slopes to prioritize bio-engineering slope stabilization and retaining walls.

---

## 🚀 How to Run the Website Locally
Open File Explorer, go to your Desktop folder:
`C:\Users\Admin\Desktop\landslide-ai-hackathon\`
Double click **`index.html`**!
