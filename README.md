# Análisis ConnectaTel

## Objetivo

Analizar el comportamiento de los clientes de ConnectaTel a partir de información de usuarios, planes y uso de servicios, con el fin de identificar patrones de consumo, valores atípicos y segmentos de clientes que permitan generar recomendaciones para el negocio.

## Datasets utilizados

- `plans.csv`: información de los planes disponibles.
- `users_latam.csv`: información de los clientes.
- `usage.csv`: información del uso de llamadas y mensajes.

## Etapas del análisis

1. Carga y exploración de los datos.
2. Identificación de valores nulos e inconsistencias.
3. Limpieza y estandarización de los datos.
4. Agrupación del uso por cliente.
5. Análisis estadístico.
6. Visualización de distribuciones.
7. Identificación de outliers.
8. Segmentación de clientes por edad y nivel de uso.
9. Elaboración de conclusiones y recomendaciones.

## Principales hallazgos

La mayor cantidad de clientes se concentra en el grupo de edad `Adulto` y en el segmento de `Uso medio`.

Se encontraron valores atípicos en la cantidad de mensajes, llamadas y minutos de llamada. Estos valores se mantuvieron debido a que pueden representar comportamientos reales de clientes con un nivel de consumo elevado.

También se identificaron problemas de calidad en los datos, como valores nulos, valores sentinels y fechas fuera de rango, los cuales fueron revisados y tratados durante el proceso de limpieza.

## Recomendaciones

Se recomienda crear ofertas diferenciadas según el nivel de uso de los clientes, ofrecer mayores beneficios a los usuarios de alto consumo e incentivar a los clientes de uso medio a migrar hacia planes con mayores capacidades.

También se recomienda mantener opciones ajustadas para clientes de bajo uso y realizar seguimiento a los usuarios con consumos extremos para evaluar la creación de planes específicos.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

## Cómo ejecutar el notebook

1. Descarga o clona este repositorio.
2. Abra el archivo `version final sprint7.ipynb` en Jupyter Notebook, JupyterLab o Google Colab.
3. Verificar el tener disponibles las librerías utilizadas: Python, Pandas, NumPy, Seaborn y Matplotlib.
4. Ejecuta las celdas del notebook en orden, desde la primera hasta la última.

## Guía de reproducción

Para reproducir el análisis, se deben utilizar los datasets `plans.csv`, `users_latam.csv` y `usage.csv`. El notebook realiza la carga y exploración de los datos, limpieza y tratamiento de valores inválidos, agrupación de métricas por usuario, análisis estadístico, visualización de distribuciones, identificación de outliers, segmentación de clientes y elaboración de conclusiones y recomendaciones.
