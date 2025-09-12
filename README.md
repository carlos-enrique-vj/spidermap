# 🌍 Map demo: https://carto.mx/webmap/spoke/
# 🚇 Nearest Metro Stations (CDMX)

This project is an interactive web map built with **Mapbox GL JS**, **Turf.js**, and **D3.js**, which allows you to visualize the **five closest Mexico City Metro stations** to any location on the map.  

The application dynamically recalculates the nearest stations as the user moves the map, drawing connecting lines from the map’s center to the nearest stations.

---

## 🌍 Features
- Interactive map using **Mapbox GL JS** with 3D globe projection.  
- Calculates and displays the **five nearest Metro stations** to the current center of the map.  
- Visual connection lines from the user’s location (or map center) to nearby stations.  
- **Custom markers and labels** for better visualization.  
- Geolocation button to center the map on the user’s real-time position.  
- Links to:
  - An external **Spider Map** visualization.  
  - The official **CDMX Metro map**.  

---

## 🛠️ Technologies Used
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/)  
- [Mapbox Geocoder](https://github.com/mapbox/mapbox-gl-geocoder)  
- [Turf.js](https://turfjs.org/) (geospatial analysis)  
- [D3.js](https://d3js.org/) (data handling)  

---

## 📂 Project Structure
├── index.html              # Archivo principal de la aplicación
├── /data
│   ├── metro.geojson       # GeoJSON con estaciones del Metro
│   ├── precision.png       # Imagen del marcador central
│   ├── spider-map2.png     # Logo de Spider Map
│   ├── metro_cdmx.png      # Logo oficial del Metro


# ESPAÑOL
# 🚇 Estaciones del Metro más cercanas (CDMX)

Este proyecto es un mapa web interactivo construido con **Mapbox GL JS**, **Turf.js** y **D3.js**, que permite visualizar las **cinco estaciones del Metro de la Ciudad de México más cercanas** a cualquier ubicación en el mapa.  

La aplicación recalcula dinámicamente las estaciones más cercanas conforme el usuario mueve el mapa, trazando líneas desde el centro hasta las estaciones más próximas.

---

## 🌍 Funcionalidades
- Mapa interactivo con **Mapbox GL JS** en proyección 3D tipo globo.  
- Calcula y muestra las **cinco estaciones más cercanas** al centro actual del mapa.  
- Líneas de conexión desde la ubicación del usuario (o centro del mapa) hacia estaciones cercanas.  
- **Marcadores y etiquetas personalizadas** para mejor visualización.  
- Botón de geolocalización para centrar el mapa en la posición del usuario en tiempo real.  
- Enlaces a:
  - Una visualización externa de **Spider Map**.  
  - El **mapa oficial del Metro CDMX**.  

---

## 🛠️ Tecnologías usadas
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/)  
- [Mapbox Geocoder](https://github.com/mapbox/mapbox-gl-geocoder)  
- [Turf.js](https://turfjs.org/) (análisis geoespacial)  
- [D3.js](https://d3js.org/) (manejo de datos)  

---

## 📂 Estructura del proyecto
├── index.html # Archivo principal de la aplicación
├── /data
│ ├── metro.geojson # GeoJSON con estaciones del Metro
│ ├── precision.png # Imagen del marcador central
│ ├── spider-map2.png # Logo de Spider Map
│ ├── metro_cdmx.png # Logo oficial del Metro
