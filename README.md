# Desafío Alura Store - Análisis de Datos Latam

## Descripción del Proyecto

Este repositorio contiene el análisis de datos realizado como parte del desafío "Alura Store" propuesto por Alura Latam. El objetivo principal fue analizar el rendimiento de cuatro tiendas ficticias (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) basándose en métricas clave de ventas, para ayudar al "Sr. Juan" a decidir cuál tienda vender con el fin de optimizar sus recursos e invertir en nuevos negocios.

## Objetivo del Análisis

Evaluar las cuatro tiendas según los siguientes criterios:
1.  Facturación Total (Ingresos por ventas)
2.  Ventas por Categoría de Producto (Popularidad)
3.  Calificación Promedio otorgada por los clientes
4.  Productos Más y Menos Vendidos (por cantidad)
5.  Costo Promedio de Envío

El objetivo final es recomendar qué tienda presenta el menor rendimiento general y, por lo tanto, es la candidata más adecuada para la venta.

## Herramientas Utilizadas

* **Lenguaje:** Python 3
* **Bibliotecas Principales:**
    * Pandas: Para la manipulación y análisis de datos.
    * Matplotlib y Seaborn: Para la visualización de datos.
* **Entorno:** Google Colaboratory (Colab)

## Estructura del Repositorio

* `Analisis_AluraStore.ipynb`: Notebook de Google Colab que contiene todo el proceso de carga de datos, limpieza (si fue necesaria), análisis paso a paso, visualizaciones y la recomendación final.

## Resultados y Recomendación

Tras analizar las métricas clave, se obtuvieron los siguientes hallazgos principales:

* **Facturación:** La Tienda 4 presentó la menor facturación total ($1,038,376,000).
* **Calificaciones:** La Tienda 1 tuvo la calificación promedio más baja (3.976685), mientras que la Tienda 3 tuvo la más alta (4.048326). La Tienda 4 se situó en un nivel intermedio-bajo (3.995759).
* **Costos de Envío:** La Tienda 1 tuvo el costo promedio más alto.
* **Categorías y Productos:** Si bien todas las tiendas mostraron actividad en categorías similares, la baja facturación de la Tienda 4 sugiere menor valor promedio por venta.

**Recomendación Final:** Se recomienda vender la **Tienda 4** debido a su combinación de la menor facturación general y un desempeño que no destaca positivamente en otras áreas clave, lo que la convierte en la opción más estratégica para desinvertir y optimizar recursos.

## Cómo Utilizar

1.  Descarga el archivo `Analisis_AluraStore.ipynb`.
2.  Súbelo y ábrelo en Google Colab ([colab.research.google.com]([https://colab.research.google.com/](https://colab.research.google.com/drive/1h895XSZYJnV6E8oHX1ollairmw5JAUz9)) o en un entorno local compatible con Jupyter Notebooks (como Anaconda).
3.  Ejecuta las celdas en orden para replicar el análisis. Los datos se cargan directamente desde las URLs proporcionadas por Alura Latam en el desafío.

---

