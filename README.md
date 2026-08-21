# TP-Final-SIG

# Simulación del Monitoreo de una Entidad sobre un Mapa

Este trabajo consiste en una aplicación web interactiva utilizada para la simulación del viaje de un vehículo sobre un mapa. Permite la visualización, carga y análisis de rutas y datos espaciales, sea interactuando directamente sobre el mapa o importando datos de fuentes externas.


## Funcionalidades 

   - **Agregar Punto:** Permite agregar los puntos del recorrido clickeando sobre el mapa
   - **Mover Punto:** Permite editar las posiciones de los puntos agregados
   - **Limpiar Puntos:** Elimina el punto seleccionado junto con su ruta
   - **Simular Viaje:** Muestra el recorrido óptimo que seguría el vehículo
   - **Cargar Ruta:** Opción para importar rutas desde archivos 

## Características

   - Mapa base obtenido de **OpenStreetMap (OSM)**
   - Generación del trayecto óptimo consultando la API de **OSRM (Open Source Routing Machine)**
   - Organización en Capas Vectoriales
   - Lectura local de archivos **CSV** (`Latitud, Longitud`)
   - Lectura de archivos **GeoJSON / JSON**
   - Controles de **Iniciar**, **Pausar** y **Detener/Reiniciar** la simulación


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