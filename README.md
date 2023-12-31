PROYECTO DE CIENCIA DE DATOS
CLASIFICACIÓN BINARIA
predicción de aceptación crediticia

Por: Julio A. Lazarte - Tucumán, Arg. - Dic/2023


![Captura de pantalla 2023-12-27 082217](https://github.com/JulioLaz/credit_scoring_predict/assets/108642139/8bfa0a4e-d04b-4108-b7ca-ace98449e24c)

Análisis de datos de un conjunto de datos crediticios alemanes, a partir de una DDBB cuya fuente es:
Profesor Dr. Hans Hofmann
Instituto de Estadística y Econometría
Universidad de Hamburgo
Departamento de Economía
Parque Von Melle 5, 2000 Hamburgo 13

El objetivo del proyecto es determinar mediante clasificación binaria el DEFAULT, es decir si es confiable o no para otorgar un crédito, utilizando los modelos:
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.ensemble import RandomForestClassifier
from sklearn.naive_bayes import GaussianNB
Tareas que se realizaron
1. Preprocesamiento de Datos: limpieza de datos, manejar valores faltantes, codificación de variables categóricas y normalización/escalado de datos.
2. Exploración de Datos: Analizar y comprender el conjunto de datos proporcionado, identificar variables claves y realizar visualizaciones para entender las relaciones entre las variables y seleccionar las características relevantes.
3. Construcción de Modelos: Experimentar con algunos algoritmos de machine learning como Regresión Logística, Árboles de Decisión, Random Forest, Naive Bayes, entre otros.
4. Evaluación y Selección del Modelo: Evaluar los modelos utilizando métricas como precisión, recall, área bajo la curva ROC, y F1-score. Seleccionar el modelo con el mejor rendimiento para la predicción de la solvencia crediticia.
