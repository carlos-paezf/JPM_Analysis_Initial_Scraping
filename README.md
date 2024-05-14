# Proyecto de Procesamiento de Datos

Este proyecto consiste en un conjunto de scripts y funciones diseñados para el procesamiento y preparación de datos en un entorno de análisis. Se proporciona una serie de herramientas para la extracción, transformación y carga (ETL) de datos, así como para la normalización y conversión a formatos adecuados para su posterior análisis o almacenamiento en una base de datos.

## Contenido del Repositorio

- `scripts/`: Contiene los scripts principales para la manipulación de datos.
- `csv/`: Carpeta de almacenamiento para archivos CSV generados durante el proceso.
- `json/`: Carpeta de almacenamiento para archivos JSON generados durante el proceso.
- `normalize-json/`: Carpeta de almacenamiento para archivos JSON normalizados.
- `sql/`: Carpeta de almacenamiento para archivos SQL generados a partir de los datos normalizados.
- `README.md`: Este archivo, que proporciona una visión general del proyecto y su contenido.

## Uso

1. Clona el repositorio a tu entorno local:

    ```txt
    $: git clone https://github.com/carlos-paezf/JPM_Analysis_Initial_Scraping.git
    ```

2. Instala las dependencias necesarias:

    ```txt
    $: pip install -r requirements.txt
    ```

3. Ejecuta los scripts necesarios según tus necesidades de procesamiento de datos.

## Scripts Principales

- `extract_data`: Extrae datos de un archivo Excel y los convierte en archivos CSV y JSON.
- `transform_data`: Normaliza y transforma los datos extraídos en archivos JSON.
- `load_data`: Carga los datos normalizados en una base de datos SQL.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema, tienes alguna sugerencia o te gustaría añadir una nueva funcionalidad, no dudes en abrir un issue o enviar un pull request.
