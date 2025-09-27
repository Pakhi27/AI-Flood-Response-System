# AI-Flood-Response-System 

An AI-driven framework for **flood prediction, victim detection, and rescue route mapping**, with a case study in Valencia, Spain.  
The project integrates **machine learning, deep learning, and geospatial analysis** to enhance disaster preparedness, real-time response, and urban resilience.

---

## Features
- **Flood Prediction & Mapping**  
  - Uses Sentinel-1 SAR imagery & AEMET weather data  
  - Google Earth Engine (GEE) for large-scale flood extent & depth visualization  
- **Victim Detection**  
  - YOLOv8-based person detection on drone/satellite/CCTV imagery  
  - HSV-based water segmentation for identifying flood zones  
  - Real-time video processing (18–20 FPS on GPU)  
- **Rescue Route Mapping (Ongoing)**  
  - Dynamic routing using shortest-path algorithms  
  - Integration of flood maps & victim locations  

---

## 🛠️ Tools & Technologies
- **Data Sources**  
  - [AEMET API](https://opendata.aemet.es/centrodedescargas/inicio) – Meteorological data  
  - [Copernicus Sentinel-1 SAR](https://scihub.copernicus.eu/) – Flood imagery  
- **Libraries & Frameworks**  
  - Python, NumPy, Rasterio, Matplotlib, OpenCV  
  - TensorFlow / PyTorch  
  - [YOLOv8](https://github.com/ultralytics/ultralytics) for victim detection  
  - Google Earth Engine for flood mapping  

---

##  Results
- **Flood Extent & Depth Maps**: Classified shallow, medium, and deep water zones  
- **Victim Detection**: Bounding boxes + segmentation masks with YOLOv8  
- **Real-Time Monitoring**: Achieved ~20 FPS for live CCTV-like streams  

---

## Future Work
- Implement **rescue route optimization**  
- Expand flood modeling with **temporal prediction** for early warnings  
- Deploy as a **real-time web or mobile application**  

---

---

##  License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

