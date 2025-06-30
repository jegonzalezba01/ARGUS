# 🌎 ARGUS

## 🔬 **ARGUS: Análisis Geoespacial para la Gestión Ambiental y Territorial**

**ARGUS** es una herramienta avanzada de análisis geoespacial que integra procesamiento satelital, grafos, clustering y machine learning para el monitoreo ambiental, con especial enfoque en la **deforestación y la ganadería ilegal en Colombia**. Diseñada para apoyar la toma de decisiones basadas en datos, busca contribuir a la conservación de ecosistemas y el fortalecimiento de la gestión territorial.

---

## 🚀 **Características principales**

✅ Procesamiento y clasificación de imágenes satelitales
✅ Análisis de redes y grafos de veredas y municipios
✅ Clustering geoestadístico para detección de patrones
✅ Visualizaciones interactivas y generación de geometrías clasificadas
✅ Arquitectura modular y escalable

---

## 🛠️ **Módulos incluidos**

### 1. **Grafos.ipynb – Extracción y Visualización de Veredas**

* Procesa y limpia datos de veredas para análisis ganadero.
* Construye grafos con *networkx* para representar relaciones territoriales.
* Genera visualizaciones interactivas con *pyvis* y gráficas estáticas con *plotly* y *matplotlib*.

---

### 2. **Clustering.ipynb – Herramienta Geoestadística para el Seguimiento de la Deforestación (HGESD-PGN)**

* Realiza clustering espacial para identificar áreas críticas de deforestación.
* Utiliza *geopandas*, *shapely* y *pandas* para generar geometrías y análisis geoestadístico.
* Produce visualizaciones y salidas gráficas para la gestión ambiental.

---

### 3. **ARGUS3.ipynb – Procesamiento Satelital**

* Procesa imágenes raster mediante *rasterio* y *numpy*.
* Integra capas vectoriales y raster para extraer información espacial.
* Prepara datos para clasificación y análisis posterior.

---

### 4. **Clasificador.ipynb – Clasificación Supervisada de Coberturas**

* Implementa modelos de machine learning (e.g. Random Forest) para clasificar imágenes en **Bosque**, **No Bosque** y **Sin Información**.
* Convierte resultados en geometrías vectoriales para análisis y visualización.
* Genera mapas temáticos de cobertura terrestre.

**Principales librerías:**

* pandas
* geopandas
* rasterio
* numpy
* shapely
* networkx
* pyvis
* plotly
* matplotlib
* joblib

---

## 💻 **Uso**

Cada notebook contiene celdas bien estructuradas con su flujo lógico y explicaciones. Se recomienda:

1. Ejecutar `Ganaderia.ipynb` para análisis de redes de veredas.
2. Procesar datos satelitales con `ARGUS3.ipynb`.
3. Realizar clasificación con `Clasificador.ipynb`.
4. Generar clustering y análisis geoestadístico con `Clustering.ipynb`.

---

## 🎯 **Objetivo**

Transformar el análisis ambiental tradicional mediante tecnología avanzada, contribuyendo a:

* Monitoreo de deforestación y actividades ilegales.
* Conservación de ecosistemas estratégicos.
* Generación de insumos técnicos para decisiones informadas.

---

## 🤝 **Contribuciones**

¡Las contribuciones son bienvenidas! Abre un *issue* o un *pull request* para mejorar funcionalidades, añadir nuevas metodologías o ampliar la aplicabilidad de ARGUS.


## ✨ **Autor**

**Jonatan E. González Balaguera**
Desarrollador principal – ARGUS
*Análisis de datos | Geoespacial | Machine Learning | Sostenibilidad*
