Análisis de Regresión Lineal Múltiple en OXXO

Este proyecto muestra el flujo completo de un análisis de regresión lineal múltiple aplicado a datos simulados de sucursales OXXO. El objetivo es predecir la ganancia de cada tienda a partir de diferentes inversiones y la ubicación geográfica, enfrentando el reto de datos faltantes y variables categóricas.

Descripción del flujo de trabajo

1. Importación de librerías
Se utilizan pandas y numpy para manipulación de datos, matplotlib para visualización y scikit-learn para preprocesamiento, modelado y evaluación.

2. Preparación de la base de datos
Se carga el dataset OXXO_Regresion_Multiple.csv y se separan las variables independientes (inversiones y estado) de la variable dependiente (ganancia).

3. Imputación de valores faltantes
Se rellenan los valores faltantes en las variables numéricas usando la media de cada columna, asegurando la integridad del modelo.

4. Codificación de variables categóricas
La columna de estado se transforma mediante OneHotEncoding para que el modelo pueda interpretar correctamente la información categórica.

5. Entrenamiento del modelo
Se divide el dataset en conjuntos de entrenamiento y prueba, y se entrena un modelo de regresión lineal múltiple para aprender la relación entre las inversiones, el estado y la ganancia.

6. Evaluación del modelo
Se comparan las predicciones del modelo con los valores reales del conjunto de prueba, mostrando los resultados lado a lado para evaluar el desempeño.

¿Por qué es relevante este proyecto?

Manejo de datos reales: incluye imputación de valores faltantes y codificación de variables categóricas.
Modelado robusto: utiliza regresión lineal múltiple, técnica fundamental en ciencia de datos.
Flujo reproducible y modular, fácil de adaptar a otros problemas de negocio.
Enfoque y herramientas estándar en proyectos de analítica avanzada y machine learning.
