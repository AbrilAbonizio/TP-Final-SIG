# TP-Final-SIG

# Simulación del Monitoreo de una Entidad sobre un Mapa

Este trabajo consiste en una aplicación web interactiva utilizada para la simulación del viaje de un vehículo sobre un mapa. Permite la visualización, carga y análisis de rutas y datos espaciales, sea interactuando directamente sobre el mapa o importando datos de fuentes externas.


## Funcionalidades 

   - **Agregar Puntos:** Modo para agregar marcadores con clic sobre el mapa.
   - **Mover Puntos:** Permite editar las posiciones de los marcadores agregados.
   - **Limpiar Puntos:** Reinicia los puntos ingresados.

## Características

   - Mapa base obtenido de **OpenStreetMap (OSM)**
   - Generación del trayecto óptimo consultando la API de **OSRM (Open Source Routing Machine)**.
   - Organización en Capas Vectoriales
   - Lectura local de archivos **CSV** (`Latitud, Longitud`)
   - Lectura de archivos **GeoJSON / JSON**
   - Controles de **Iniciar**, **Pausar** y **Detener/Reiniciar** la simulación.  


## Tecnologías y Librerías Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript 
- **Librería SIG Web:** [OpenLayers v9.1.0](https://openlayers.org/)
- **Mapa Base:** [OpenStreetMap (OSM)](https://www.openstreetmap.org/)
- **Servicio de Ruteo:** [OSRM API](http://project-osrm.org/)


## Estructura del Repositorio

```text
.
├── index.html          # Interfaz de usuario y mapa
├── script.js            # Lógica principal, manejo de OpenLayers, OSRM y animación
├── styles.css           # Estilos visuales, layout y diseño responsivo
└── README.md            # Documentación del proyecto