# Análisis de Datos COVID-19: Fase 2  

## Contexto  
El SARS-COV-2, responsable de la enfermedad COVID-19, es un virus de la familia de los coronavirus que apareció en China a finales del año 2019 y se expandió a gran velocidad a lo largo del globo, sorprendiendo a la mayoría de los países y causando una pandemia en 2020. Este proyecto busca analizar y visualizar los datos relacionados con los casos confirmados de contagio, utilizando herramientas de ciencia de datos.  

## Descripción del Proyecto  
En la Fase #2 de este proyecto, se utiliza el módulo `matplotlib` de Python para generar visualizaciones que permiten analizar y responder preguntas de interés sobre los datos preparados en la Fase #1. El objetivo es hacer que la información sea accesible y comprensible tanto para expertos como para personas del común, mediante gráficas claras y detalladas.  

### Preguntas de Interés  
1. **Variación de contagios mes a mes de los tres países con más casos reportados.**  
2. **Comparación del total de contagios de cinco países.**  
3. **Porcentaje de contagios de cada uno de los cinco países seleccionados respecto al total mundial.**  

## Dataset Utilizado  
El dataset usado es proporcionado por la Universidad Johns Hopkins y contiene información sobre los casos confirmados de COVID-19 en todo el mundo.  

- **Fuente del Dataset:**  
  [Johns Hopkins CSSE COVID-19 Dataset](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)  

- **Condiciones de Uso:**  
  Puedes consultar las condiciones de uso del dataset en el repositorio oficial de la Universidad Johns Hopkins:  
  [Condiciones de Uso](https://github.com/CSSEGISandData/COVID-19)  

## Herramientas Utilizadas  
- **Lenguaje:** Python  
- **Bibliotecas:**  
  - `pandas` para la preparación y manipulación de datos.  
  - `matplotlib` para la creación de gráficas.  

## Estructura del Proyecto  
1. **Fase #1:** [Preparación y limpieza de datos](https://github.com/andreacampog/analisis-covid-19)
2. **Fase #2:** Generación de gráficas utilizando los datos limpios de la Fase #1.  

### Archivos Clave  
- **Fase 2 - Visualizaciones:** Archivo Jupyter Notebook con la implementación de las gráficas.  
  - Nombre del archivo: `analisis-covid-19-fase-2.ipynb`  
- **Readme:** Este archivo (`README.md`), que contiene la documentación del proyecto.  

## Cómo Usar Este Proyecto  
1. Asegúrate de tener Python instalado en tu máquina.  
2. Instala las bibliotecas requeridas:  
   ```bash
   pip install pandas matplotlib
