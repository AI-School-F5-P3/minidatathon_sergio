# Análisis de Datos de COVID-19 en Estados Unidos

Este proyecto analiza los datos diarios de COVID-19 en Estados Unidos, obtenidos a través de la API de [COVID Tracking Project](https://covidtracking.com/data/api). El análisis incluye la visualización de la evolución de casos, hospitalizaciones, uso de ventiladores y muertes a nivel estatal, así como el estudio de correlaciones entre estas variables.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Visualizaciones](#visualizaciones)

## Descripción

El objetivo de este proyecto es proporcionar un análisis exploratorio de los datos relacionados con el COVID-19 en Estados Unidos. A través de diversas visualizaciones y cálculos de correlación, se busca entender mejor la evolución de la pandemia y la relación entre diferentes variables como casos positivos, hospitalizaciones, uso de respiradores y muertes.

## Tecnologías Utilizadas

El proyecto se desarrolló utilizando las siguientes tecnologías:

- **Python 3**
- **Google Colab** para el desarrollo y ejecución del código.
- **Pandas** para la manipulación y análisis de datos.
- **Seaborn** y **Matplotlib** para la creación de visualizaciones.
- **Bokeh** para la creación de gráficos interactivos.
- **Requests** para la obtención de datos desde la API.

## Instalación

Para ejecutar este proyecto en tu entorno local, sigue estos pasos:

1. **Clona el repositorio**:

   ```bash
   git clone https://github.com/AI-School-F5-P3/minidatathon_sergio.git
   cd tu_repositorio
   ```

2. **Instala las dependencias**:

   ```bash
   pip install pandas seaborn matplotlib bokeh requests
   ```

3. **Ejecuta el notebook**:

   Puedes abrir el archivo `.ipynb` en Google Colab o en Jupyter Notebook y ejecutar las celdas para ver el análisis.

## Uso

Para utilizar el proyecto:

1. **Obtener los datos**: Los datos se obtienen automáticamente desde la API de COVID Tracking Project.

2. **Explorar el análisis**: El notebook incluye celdas que realizan el análisis y generan visualizaciones, como la evolución temporal de casos positivos, la distribución de casos por estado, y las correlaciones entre diferentes variables.

3. **Interactividad**: Utiliza las visualizaciones interactivas de Bokeh para explorar los datos de forma más dinámica.

## Visualizaciones

El proyecto incluye diversas visualizaciones, tales como:

- **Evolución temporal de casos positivos de COVID-19 por estado**: Gráfica de línea.
- **Distribución de casos positivos por estado**: Gráfico de caja (boxplot).
- **Matriz de correlación entre diferentes variables**: Heatmap.
- **Relación entre casos positivos y negativos**: Gráfico de dispersión interactivo con Bokeh.
