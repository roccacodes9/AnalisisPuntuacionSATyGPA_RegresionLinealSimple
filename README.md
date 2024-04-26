**Análisis de Regresión Lineal Simple y \( R^2 \)**

**Contenido del Repositorio:**
1. **Jupyter Notebook (Archivo Python):**
   - Contiene el código para realizar un análisis de regresión lineal simple utilizando el conjunto de datos proporcionado en el archivo "real_estate_price_size.csv".
   - Importa las bibliotecas relevantes, carga los datos, realiza la regresión lineal simple y muestra un resumen de los resultados, incluido el \( R^2 \) ajustado.
   - Visualiza los datos con un gráfico de dispersión y muestra la línea de regresión lineal ajustada.

2. **Archivo CSV:**
   - "real_estate_price_size.csv": El conjunto de datos utilizado para el análisis, que contiene las variables "price" y "size" (precio y tamaño de la propiedad).

3. **README.md:**
   - Proporciona una descripción general del repositorio y cómo utilizar el código proporcionado.

**Requisitos de Ejecución del Análisis:**
- Python 3.x
- Bibliotecas:
  - numpy
  - pandas
  - matplotlib
  - statsmodels

**Detalles del Análisis:**
- Se realiza un análisis de regresión lineal simple para predecir el precio de una propiedad (variable dependiente) utilizando el tamaño de la propiedad (variable independiente).
- Se ajusta un modelo de regresión lineal simple y se muestra un resumen de los resultados utilizando la biblioteca statsmodels.
- Se calcula y muestra el coeficiente de determinación (\( R^2 \)) para entender qué proporción de la variabilidad en el precio de la propiedad se explica por el tamaño de la propiedad.
- Se visualizan los datos con un gráfico de dispersión y se muestra la línea de regresión lineal ajustada para una mejor comprensión de la relación entre el tamaño y el precio de la propiedad.

**Resultado del Análisis:**
- El análisis revela que el coeficiente de determinación \( R^2 \) del modelo de regresión lineal simple es aproximadamente 0.745, lo que indica que alrededor del 74.5% de la variabilidad en el precio de la propiedad se explica por el tamaño de la propiedad incluido en el modelo.
- Se muestra un gráfico de dispersión con la línea de regresión lineal ajustada, lo que proporciona una visualización clara de la relación entre el tamaño y el precio de la propiedad.
