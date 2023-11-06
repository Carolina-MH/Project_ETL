# Project_ETL

![head](https://github.com/Carolina-MH/Project_ETL/blob/main/img/head.gif)

El análisis de datos de turismo es una herramienta poderosa para comprender mejor el comportamiento de los viajeros y su impacto en las regiones. Para este proyecto, he seleccionado el conjunto de datos:

✈️ `Viajeros y Pernoctaciones por Provincias` proporcionado por el Instituto Nacional de Estadística (INE). La elección se basa en la importancia del turismo en la economía española y la riqueza de información que este conjunto de datos ofrece.

☀️ `Datos climáticos` mensuales por provincia de 2022 de la `AEMET` para enriquecer la tabla de la INE. Esto me permite investigar si el clima influye en las pernoctaciones y viajes.

🏙️ Además, he incorporado datos de `población` por provincia en 2022 desde `Wikipedia`, lo que me proporciona un contexto fundamental para entender cómo la cantidad de residentes en cada provincia puede influir en los patrones de turismo y pernoctaciones.


# Objetivos 🎯

El objetivo principal radica en la extracción de datos limpios y coherentes de las fuentes ya mencionadas. A través de este proceso ETL, pretendo transformar y estructurar estos datos de manera óptima para su posterior análisis. 

Además, el almacenamiento de los datos en una BD adecuada permitirá que estos estén disponibles y listos para futuros proyectos de investigación y análisis, lo que enriquecerá la comprensión de cómo el turismo, el clima y la población se interrelacionan en las provincias de España.


# Métodos de extracción de datos aplicados

En el transcurso de este proyecto, he desplegado una serie de técnicas de extracción de datos, cada una adaptada a las fuente de información. 

🔍 [Extracción de datos a través de Archivos CSV (INE)](notebook/INE_2022.ipynb):  inicié el proyecto aplicando la extracción a través de archivos CSV.

🔍 [Extracción de datos a través de API (AEMET)](notebook/API(AEMET).ipynb): simultáneamente, opté por emplear una API para obtener los datos climáticos. Esta elección me proporcionó acceso inmediato a los datos climáticos mensuales por provincia en 2022, asegurandome la precisión y actualización de los mismos.

🔍 [Extracción de datos mediante Webscraping (Wikipedia)](notebook/Webscraping_población.ipynb):por último, para incorporar datos de población desde Wikipedia, hemos implementé esta técnica. Con esto, he logrado extraer datos específicos de manera automática y los he mantenido coherentes con las necesidades del proyecto.



# Acciones realizadas

✔️ Importación de datos

✔️ Limpieza de datos

✔️ Reorganización

✔️ Creación de un nuevo DB en Mongo

✔️ Exportación al nuevo DB estableciendo colecciones


# Conclusión 💡


A lo largo de este proyecto, he aplicado diversas técnicas para extraer datos esenciales de turismo, clima y población. Estos datos se encuentran ahora limpios y estructurados, listos para impulsar futuros análisis e investigaciones. 

Con esta base sólida en mis manos, podrá continuar explorando las  relaciones entre turismo, clima y población en las provincias de España.

![tail](https://github.com/Carolina-MH/Project_ETL/blob/main/img/tail.gif)
