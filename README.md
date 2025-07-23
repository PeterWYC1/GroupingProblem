# 🚢 Caso 3 - Agrupamiento de Desempeño de Barcos en una Naviera

 **Computación Científica** (Semestre 2025-II) aplicaci'on de **ASUM-DM** para el desarrollo de un modelo de agrupamiento (clustering) que permita identificar diferencias operacionales entre los barcos de una naviera.

##  Objetivo del Caso

La naviera sospecha que sus barcos pueden dividirse subjetivamente en **dos grupos definidos** según su comportamiento operativo. El propósito es validar esta afirmación a través de técnicas de agrupamiento para poder:

- Mejorar el desempeño operacional.
- Optimizar las condiciones de trabajo del personal.
- Mejorar la experiencia del cliente.

## Metodología

Se siguieron los pasos de la metodología **ASUM-DM**, una adaptación de metodologías de minería de datos, para resolver el caso de forma estructurada:

1. **Entendimiento del negocio**  
2. **Entendimiento de los datos**  
3. **Preparación de los datos**  
4. **Modelado**  
5. **Evaluación**  
6. **Despliegue (conclusiones)**

## Diccionario de Variables

El conjunto de datos incluye variables como:

- `Ship_Type`, `Route_Type`, `Engine_Type`
- `Speed_Over_Ground_knots`, `Engine_Power_kW`, `Distance_Traveled_nm`
- `Draft_meters`, `Cargo_Weight_tons`, `Operational_Cost_USD`, `Reveneu_per_Voyage_USD`
- `Efficiency_nm_per_kWh`, `Tournaround_Time_hours`, `Average_Load_Percentage`
- Entre otras relacionadas con operación, clima y mantenimiento

## Herramientas utilizadas

- Python 3
- Pandas, NumPy, Matplotlb, Seaborn
- Scikit-learn (KMeans, PCA, Silhouette Score)
- Jupyter Notebook

## Resultados

- Se realizó un análisis exploratorio de los datos.
- Se aplicó reducción de dimensionalidad con PCA para visualización.
- Se entrenaron modelos de agrupamiento (KMeans) con diferentes valores de *k*.
- La métrica **Silhouette Score** indicó que **dos clústeres** representaban una segmentación razonable de los barcos.
- Se interpretaron los grupos formados, confirmando diferencias operacionales significativas.

## Archivos

- `caso3.ipynb`: Notebook con todo el desarrollo del proyecto paso a paso.
- `CASO 3 - AGRUPAMIENTO.pdf`: Documento guía del caso de negocio.
- `datos_caso_3.csv`: .csv con los datos del negocio.


## Conclusión

N/A

