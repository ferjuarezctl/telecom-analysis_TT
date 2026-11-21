# telecom-analysis_TT

# Análisis de Clientes - ConnectaTel

## Descripción del proyecto

El objetivo es analizar los datos de clientes de ConnectaTel para identificar patrones de consumo, problemas de calidad en los datos y segmentos de usuarios que ayuden a entender mejor su comportamiento y encontrar oportunidades de mejora en los planes de telefonía.

## Datasets utilizados

Se trabajó con tres archivos CSV:

- `users_latam.csv`: información de clientes, edad, ciudad, plan contratado y fechas de registro.
- `usage.csv`: registros de llamadas y mensajes de los usuarios.
- `plans.csv`: información de los planes disponibles, precios y beneficios.

## Etapas del análisis

1. **Exploración inicial:** revisión de estructura, tipos de datos y estadísticas descriptivas.
2. **Limpieza de datos:** identificación y tratamiento de valores nulos, edades inválidas y fechas inconsistentes.
3. **Análisis exploratorio:** estudio de distribuciones de edad, llamadas, mensajes y minutos de uso.
4. **Detección de outliers:** identificación de valores atípicos mediante el método IQR.
5. **Segmentación:** clasificación de clientes por edad y nivel de consumo.
6. **Conclusiones:** interpretación de resultados y recomendaciones para ConnectaTel.

## Herramientas utilizadas

- Python
- Pandas y NumPy
- Matplotlib y Seaborn
- Jupyter Notebook / Google Colab

## Principales hallazgos

- Se encontraron inconsistencias en edades, ciudades y fechas de registro.
- El segmento de adultos concentra la mayor cantidad de usuarios.
- La mayoría de los clientes se encuentra en el segmento de uso medio.
- Se identificaron algunos usuarios con consumos de llamadas considerablemente superiores al promedio.

## Cómo ejecutar el proyecto

1. Descarga el notebook `.ipynb` del repositorio.
2. Ábrelo en [Google Colab](https://colab.research.google.com/) o Jupyter Notebook.
3. Carga los tres datasets utilizados.
4. Ajusta las rutas de lectura de los archivos CSV según su ubicación.
5. Ejecuta las celdas en orden para reproducir el análisis.
