# Análisis de Airbnb CDMX
1. El precio típico en CDMX es ~$950 MXN/noche (mediana).
   El promedio está inflado por propiedades de lujo.

2. Condesa, Roma Norte y Polanco concentran la mayoría
   de los listings — zonas turísticas consolidadas.

3. Un departamento completo cuesta ~2.5x más que
   una habitación privada en la misma zona.

4. Las colonias más caras no siempre son las más conocidas —
   hay zonas residenciales que superan a Polanco en precio promedio.

5. La correlación precio-reseñas es negativa:
   listings más accesibles acumulan más reservas y reseñas.


   # 🏙️ Análisis de Airbnb — Ciudad de México

Análisis exploratorio de datos del mercado de Airbnb en la CDMX
usando Python. Incluye limpieza de datos, visualizaciones y un
mapa interactivo con más de 20,000 listings.

![Mapa de listings Airbnb CDMX](graficas/mapa_preview.png)

---

## 🛠️ Tecnologías

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-blue)
![Folium](https://img.shields.io/badge/Folium-0.14-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## ❓ Preguntas de negocio respondidas

| # | Pregunta | Hallazgo |
|---|----------|----------|
| 1 | ¿Cuál es la distribución de precios? | El 75% de los listings cuesta menos de $2,397 MXN/noche |
| 2 | ¿Qué colonias tienen más listings? | Cuauhtémoc , Miguel Hidalgo y Benito Juárez concentran el 30% |
| 3 | ¿Cómo varía el precio por tipo de cuarto? | Un depto completo cuesta 2.2x más que una habitación privada |
| 4 | ¿Cuáles son las colonias más caras? | Las colonias premium superan $10,913 MXN/noche en promedio |
| 5 | ¿Precio y reseñas tienen relación? | Correlación negativa débil — listings baratos acumulan más reseñas |

---

## 📊 Visualizaciones

### Distribución de precios
![Distribución de precios](graficas/01_distribucion_precios.png)

### Top 15 colonias con más listings
![Top colonias](graficas/02_top_colonias.png)

### Precio por tipo de cuarto
![Precio por tipo](graficas/03_precio_por_tipo.png)

### Top 10 colonias más caras
![Colonias caras](graficas/04_colonias_mas_caras.png)

### Precio vs número de reseñas
![Scatter precio reseñas](graficas/05_precio_vs_resenas.png)

---

## 🗂️ Estructura del proyecto