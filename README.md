# Análisis de Regresión Lineal Simple

Este repositorio contiene un análisis detallado de regresión lineal simple realizado en Python utilizando bibliotecas como NumPy, Pandas, Matplotlib, Statsmodels y Seaborn. El análisis se centra en la relación entre las puntuaciones SAT y los promedios universitarios de calificaciones (GPA).

## Contenido del Repositorio

El repositorio contiene los siguientes archivos:

- `1.01. Simple linear regression.csv`: Este archivo CSV contiene los datos utilizados en el análisis. Contiene dos columnas: SAT (puntuaciones SAT) y GPA (promedios universitarios de calificaciones).
- `regression_analysis.ipynb`: Este es el cuaderno de Jupyter utilizado para realizar el análisis. Contiene el código Python junto con explicaciones detalladas y visualizaciones del proceso de regresión lineal.

## Requisitos

Para ejecutar el código en el cuaderno de Jupyter, se requieren las siguientes bibliotecas de Python:

- NumPy
- Pandas
- Matplotlib
- Statsmodels
- Seaborn

Se pueden instalar estas bibliotecas mediante el gestor de paquetes pip.

## Ejecución del Análisis

Para ejecutar el análisis, simplemente abre el cuaderno de Jupyter `regression_analysis.ipynb` en tu entorno de Jupyter Notebook y ejecuta las celdas secuencialmente. Asegúrate de tener el archivo CSV `1.01. Simple linear regression.csv` en el mismo directorio que el cuaderno.

## Detalles del Análisis

El análisis sigue los siguientes pasos:

1. Importación de bibliotecas y lectura de datos desde el archivo CSV.
2. Visualización de los datos mediante un gráfico de dispersión.
3. Ajuste de un modelo de regresión lineal utilizando statsmodels.
4. Visualización de la línea de regresión en el gráfico de dispersión.
5. Comparación de diferentes modelos de regresión lineal.
6. Resumen detallado de los resultados del análisis.

## Resultados

El análisis revela una relación positiva entre las puntuaciones SAT y los promedios universitarios de calificaciones. Proporciona coeficientes de regresión que pueden utilizarse para predecir el GPA en función de las puntuaciones SAT.

## Objetivo del Análisis

El objetivo de este análisis de regresión lineal simple es investigar la relación entre las puntuaciones SAT y los promedios universitarios de calificaciones (GPA). Al realizar este análisis, buscamos:

- Comprender la naturaleza de la relación entre las puntuaciones SAT y los GPA de los estudiantes universitarios.
- Determinar si existe una relación lineal significativa entre estas dos variables.
- Estimar la fuerza y la dirección de la relación mediante el coeficiente de determinación (R-cuadrado) y los coeficientes de la regresión.
- Proporcionar una herramienta predictiva para predecir el GPA de un estudiante en función de su puntuación SAT.
- Explorar visualmente la relación entre las variables mediante gráficos de dispersión y líneas de regresión.

Este análisis tiene aplicaciones potenciales en la predicción del desempeño académico de los estudiantes universitarios y en la identificación de factores que influyen en el rendimiento académico. Los resultados obtenidos pueden ser útiles para educadores, asesores académicos y estudiantes que deseen comprender mejor cómo las puntuaciones SAT pueden relacionarse con el éxito académico en la universidad.
