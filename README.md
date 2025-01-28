# Análisis de Ventas de Alcohol en Iowa - Power BI y Python

## Descripción del Proyecto

Este proyecto, basado en un dataset descargado de Kaggle, analiza las ventas de alcohol en todos los establecimientos de Iowa. La idea principal es crear un reporte interactivo en Power BI para identificar patrones de ventas, resaltar los condados y ciudades con mayores ingresos, y proporcionar herramientas dinámicas para la toma de decisiones.

## Objetivos

- Procesar y limpiar datos utilizando Python para optimizar su carga en Power BI.
- Implementar un modelo de datos eficiente con tablas de hechos y dimensiones.
- Diseñar un reporte interactivo que facilite el análisis de ventas mediante gráficos, tablas, KPIs y Time Intelligence.

### Proceso del Proyecto

**1. Preparación de Datos en Python**
- Carga del dataset completo: Utilizamos Python para cargar y explorar el dataset original de ventas de alcohol.
- División en tablas de hechos y dimensiones:
- Tabla de hechos: Ventas.
- Tablas de dimensiones: Artículo y Tienda.
- Rellenado de datos faltantes: Aplicamos funciones de Python para imputar valores ausentes de manera eficiente.
- Segmentación de la tabla de hechos: Dividimos la tabla de ventas por trimestres y años, lo que permite cargar solo los datos necesarios mediante parámetros y carpetas en Power BI, optimizando así el rendimiento del reporte.
- Eliminación de columnas innecesarias: Mantuvimos únicamente las columnas relevantes para el análisis.
- Exportación final: Guardamos los datos procesados en una carpeta estructurada para su posterior carga en Power BI.

**2. Procesamiento en Power BI**
- Limpieza adicional y tipificación: Ajustamos el tipo de datos de las columnas y realizamos limpieza final.
- Creación de una tabla de calendario: Basada en la columna de fechas de la tabla de ventas, permite que los nuevos datos se integren automáticamente en el modelo y reporte.
- Modelado de datos: Establecimos relaciones entre las tablas de hechos y dimensiones.
- Cálculo de medidas DAX: Creamos las métricas necesarias para el análisis, incluyendo ventas totales, beneficios, y métricas basadas en Time Intelligence.

**3. Diseño del Reporte**
Visualizaciones Interactivas:
- Tablas y gráficos dinámicos para mostrar las ventas totales por condado, ciudad y tienda.
- Tarjetas y KPIs para visualizar rápidamente métricas clave como ventas totales, actuales y beneficios.
- Análisis de tendencias: Usamos Time Intelligence para comparar ventas entre años.
- Simulaciones dinámicas: Incorporamos un slider que permite analizar el impacto de descuentos o aumentos de precios en las ventas.
- Interfaz de usuario atractiva: Diseñamos un reporte visualmente agradable y funcional, utilizando imágenes y recursos gráficos de Pixabay.

## Recursos Utilizados

Datos: [Kaggle](https://www.kaggle.com/datasets/residentmario/iowa-liquor-sales)

Imágenes: 
- [Logo Marca](https://pixabay.com/es/vectors/perro-logo-resumen-animal-canino-8576035/)
- [Logos Bookmarks](https://pixabay.com/users/inspire-studio-22128832/)

Herramientas:
- Python: Limpieza y preprocesamiento de datos.
- Power BI: Modelado, visualización y análisis interactivo.

## Instrucciones de Uso

Requisitos previos:
- Tener Python instalado con las siguientes bibliotecas: pandas, os.
- Tener Vs Code con Jupyter
- Power BI Desktop para cargar y explorar el reporte.
- Navega por los diferentes gráficos y tablas interactivas.
- Usa los filtros y sliders para personalizar tu análisis.
- El que quiera disponer del proyecto .pbix contacteme en mi Email: georgianrucareanu@gmail.com

## Resultados

El reporte final proporciona:
- Un análisis claro de los condados y ciudades con mayores ventas.
- KPIs clave para entender métricas como ventas totales y beneficios.
- Comparativas de ventas entre años con Time Intelligence.
- Herramientas para simular escenarios de descuentos o cambios de precio.

## Agradecimientos

Quiero agradecer a:
- Los creadores del dataset en Kaggle por compartir los datos.
- Pixabay por proporcionar imágenes gratuitas para enriquecer el diseño del reporte.

## Aclaración
- Este proyecto es un ejercicio educativo creado con fines de aprendizaje y exploración. Su objetivo es practicar y demostrar conceptos específicos del Analisis de Datos aprendidos por mi. No está destinado a ser una solución definitiva o una práctica recomendada.
