Análisis de Regresión Lineal Simple

Este repositorio contiene un análisis detallado de regresión lineal simple realizado en Python utilizando bibliotecas como NumPy, Pandas, Matplotlib, Statsmodels y Seaborn. El análisis se centra en la relación entre las puntuaciones SAT y los promedios universitarios de calificaciones (GPA).
Contenido del Repositorio

El repositorio contiene los siguientes archivos:

    1.01. Simple linear regression.csv: Este archivo CSV contiene los datos utilizados en el análisis. Contiene dos columnas: SAT (puntuaciones SAT) y GPA (promedios universitarios de calificaciones).

    regression_analysis.ipynb: Este es el cuaderno de Jupyter utilizado para realizar el análisis. Contiene el código Python junto con explicaciones detalladas y visualizaciones del proceso de regresión lineal.

Requisitos

Para ejecutar el código en el cuaderno de Jupyter, se requieren las siguientes bibliotecas de Python:

    NumPy
    Pandas
    Matplotlib
    Statsmodels
    Seaborn

Se puede instalar estas bibliotecas mediante el gestor de paquetes pip. Por ejemplo:

pip install numpy pandas matplotlib statsmodels seaborn

Ejecución del Análisis

Para ejecutar el análisis, simplemente abre el cuaderno de Jupyter regression_analysis.ipynb en tu entorno de Jupyter Notebook y ejecuta las celdas secuencialmente. Asegúrate de tener el archivo CSV 1.01. Simple linear regression.csv en el mismo directorio que el cuaderno.
Detalles del Análisis

El análisis sigue los siguientes pasos:

    Importación de bibliotecas y lectura de datos desde el archivo CSV.
    Visualización de los datos mediante un gráfico de dispersión.
    Ajuste de un modelo de regresión lineal utilizando statsmodels.
    Visualización de la línea de regresión en el gráfico de dispersión.
    Comparación de diferentes modelos de regresión lineal.
    Resumen detallado de los resultados del análisis.

Resultados

El análisis revela una relación positiva entre las puntuaciones SAT y los promedios universitarios de calificaciones. Proporciona coeficientes de regresión que pueden utilizarse para predecir el GPA en función de las puntuaciones SAT.
