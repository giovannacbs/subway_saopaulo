# 🗺️ São Paulo: Access to Metro and Job Shifts 

## 🔍 What this project explores

The visual narrative investigates:
- How job density shifted across São Paulo over time
- Which areas became more or less accessible by foot from metro stations
- How infrastructure and economic changes reshaped the geography of work

## 📊 Data sources

- **Origin-Destination Survey (Pesquisa OD):**  
  [Transparência Metrô SP](https://transparencia.metrosp.com.br/dataset/pesquisa-origem-e-destino)

- **Metro stations shapefile:**  
  [GeoSampa - Estações do Metrô](https://geosampa.prefeitura.sp.gov.br/PaginasPublicas/_SBC.aspx)

- **Sidewalk network (for walkability analysis):**  
  Extracted using [Pyrosm](https://pyrosm.github.io/pyrosm/) and OpenStreetMap data with `network_type="walking"`

## 🧮 Methodology

- Calculated walking distances from each metro station using **QGIS Service Area (from layer)** tool  
  ([QGIS network analysis tutorial](https://docs.qgis.org/3.40/en/docs/training_manual/vector_analysis/network_analysis.html))
- Limited the analysis to sidewalks and pedestrian-accessible streets from OpenStreetMap
- Exported walking buffer areas and job data maps as **SVG files** from QGIS

## 🎨 Design & Storytelling

- Edited layers and visual layout in **Adobe Illustrator**
- Used **[ai2html](https://github.com/newsdev/ai2html)** to export Illustrator artwork as responsive HTML
- Integrated scrollytelling behavior using **[Scrollama.js](https://github.com/russellgoldenberg/scrollama)**

## 🌐 Live project

📎 [**View the live site**](https://giovannacbs.github.io/subway_saopaulo/)  

## 👤 Author

Project made for the **Lede Program** by [Giovanna Serafim](https://github.com/giovannacbs)

---

