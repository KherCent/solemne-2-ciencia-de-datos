# Solemne II: Introducción a la Ciencia de Datos

Este repositorio contiene el desarrollo de la Evaluación Solemne II para la asignatura **Introducción a la Ciencia de Datos** (Universidad San Sebastián - Advance).

**Estudiante:** Jorge Kevin Herrera Centellas

## Contenido del Repositorio
* **`Solemne_II_JorgeHerrera.ipynb`**: Notebook con la implementación de los modelos paso a paso utilizando la metodología CRISP-DM.
* **`german.data.C.csv`**: Dataset de entrada (versión C de German Credit Data, con 11 atributos).
* **`german_credit_procesado.csv`**: Dataset de salida preparado y discretizado para el análisis de reglas de asociación.

## Descripción del Proyecto
Se implementó un modelo de clasificación basado en **Árbol de Decisión** y un análisis de **Reglas de Asociación (Algoritmo Apriori)** para la predicción de riesgo de crédito en clientes financieros, aplicando secuencialmente las fases de la metodología **CRISP-DM**:
1. **Comprensión del Negocio (Business Understanding):** Definición de metas para reducir el riesgo de impago en préstamos bancarios.
2. **Comprensión de los Datos (Data Understanding):** Exploración descriptiva inicial y visualización de la distribución de montos, plazos e histogramas.
3. **Preparación de los Datos (Data Preparation):** Codificación dummy de categóricas, balanceo de clases mediante sobremuestreo con **SMOTE** (para corregir el desbalance 70/30) y discretización de variables numéricas continuas en categorías.
4. **Modelado (Modeling):** Entrenamiento del clasificador de árbol de decisión y minería de reglas de asociación usando `mlxtend`.
5. **Evaluación (Evaluation):** Análisis de métricas (precisión global, recall, feature importances) y filtrado de las reglas de asociación más fuertes por soporte, confianza y lift.
6. **Despliegue (Deployment):** Propuesta de estrategias comerciales e implicaciones de negocio a partir de los hallazgos de ambos modelos.
