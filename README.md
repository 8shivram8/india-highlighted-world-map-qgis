# 🌍 India Highlighted on World Map (QGIS Project)

This repository contains a QGIS project showing a world map with India highlighted using a Mapnik Grayscale style inside India and a light gray background for the rest of the world.

---

## 🖼 Preview

![Map Preview](preview/india_world_map_preview.png)

---

## 📁 Repository Structure

india-world-map/
│
├── india_world_map.qgz → QGIS project file
│
├── GeoPackage/
│ └── all files.gpkg → GeoPackage containing:
│ - india
│ - world_borders
│ - mapnik_clip_mask
|
├── preview/
│ └── india_world_map_preview.png
│
└── README.md

---

## 🗺 Map Features

- 🌍 World borders
- 🇮🇳 India highlighted
- 🎨 Mapnik Grayscale style inside India
- 🌫 Light gray background for rest of the world
- Clean cartographic focus effect

---

## 🛠 Requirements

- QGIS 3.x (Recommended latest version)
  Download: https://qgis.org

- Internet connection (for XYZ tile layers like Mapnik)

---

## ▶ How to Use

1. Download or clone this repository.
2. Open `india_world_map.qgz` in QGIS.
3. Ensure internet is connected (for basemap layers).
4. The map will load automatically with styling preserved.

---

## 🌐 Coordinate Reference System (CRS)

Project CRS:  
EPSG:3857 — WGS 84 / Web Mercator

---

## 📦 Data Format

Vector layers are stored in a single GeoPackage file:

`all files.gpkg`

This format:

- Keeps multiple layers in one file
- Is portable and efficient
- Is fully supported by QGIS

---

## 📄 Data Sources

- Natural Earth (World boundaries)
- OpenStreetMap (Mapnik tiles)
- CartoDB Light (Background tiles)

---

## 📌 License

This project is shared for educational and GIS demonstration purposes.

Basemap data © OpenStreetMap contributors.
