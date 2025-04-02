# Metadatos del Dataset de Metabolómica

Este archivo contiene una descripción de los metadatos asociados al dataset `human_cachexia.csv`, el cual se utiliza en el análisis de metabolómica para estudiar la cachexia.

## Contenido de los metadatos

- **Patient ID:** Identificador único de cada muestra.
- **Muscle loss:** Indica el grupo experimental al que pertenece la muestra (e.g., "cachexic" o "control").
- **Valores de expresión de los metabolitos:** Las demás columnas del dataset contienen los valores de expresión de cada uno de los 63 metabolitos medidos en las muestras.

## Fuente

Los metadatos fueron extraídos del archivo original `human_cachexia.csv` disponible en el repositorio [metaboData](https://github.com/nutrimetabolomics/metaboData/tree/79036d1897db72955c0aa0634c1a6aa06d0532fa/Datasets/2024-Cachexia).

## Notas adicionales

- El dataset fue procesado para eliminar valores perdidos y estructurado en un objeto *SummarizedExperiment*.
- Los nombres de las columnas se utilizan para representar los nombres de los metabolitos en el análisis.