# Significant Earthquakes, 1965-2016

Este proyecto analiza y visualiza datos de terremotos significativos entre 1965 y 2016 utilizando técnicas de análisis y visualización de datos.

## Autor
**Angel Patiño - KMeans**

## Conjunto de datos
El conjunto de datos utilizado se puede encontrar en [Kaggle - USGS Earthquake Database](https://www.kaggle.com/datasets/usgs/earthquake-database).

## Descripción
Este código analiza los datos de terremotos para identificar patrones mediante técnicas de agrupación (KMeans). Se incluyen visualizaciones interactivas de los resultados utilizando herramientas como Matplotlib, Plotly, Seaborn y Folium.

## Requisitos
- Pandas
- Matplotlib
- Plotly
- Seaborn
- NumPy
- Folium
- Geopy

## Funcionalidades principales
- Carga de datos desde un archivo CSV.
- Análisis de valores faltantes en el conjunto de datos.
- Eliminación de outliers utilizando Z-score.
- Transformación de datos para mejorar la distribución.
- Aplicación de KMeans para agrupar terremotos según características geoespaciales y sísmicas.
- Visualización de resultados mediante gráficos y mapas interactivos.

## Uso
Para ejecutar el código, asegúrate de tener instaladas todas las bibliotecas mencionadas en los requisitos y ejecuta el script principal.

## Ejemplo de salida
El código produce visualizaciones como histogramas, gráficos de dispersión y mapas interactivos que muestran la distribución geográfica y las características de los terremotos agrupados.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, por favor envía una solicitud de extracción.

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
