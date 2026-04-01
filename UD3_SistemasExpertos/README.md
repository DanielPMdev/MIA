# Sistemas Expertos

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Esta unidad estudia los sistemas expertos como una de las aplicaciones más clásicas y fundamentales de la Inteligencia Artificial. Se abordan los principios de los sistemas basados en reglas y se introduce la aplicación práctica de modelos probabilísticos, específicamente las redes bayesianas y el clasificador Naive Bayes, como herramientas de razonamiento bajo incertidumbre utilizadas en la toma de decisiones automatizada.

## 🎯 Objetivos de Aprendizaje
- Comprender la arquitectura y componentes de un sistema experto.
- Conocer los mecanismos de inferencia basados en reglas.
- Implementar un clasificador Naive Bayes utilizando scikit-learn.
- Evaluar el rendimiento de un modelo de clasificación mediante métricas estándar.
- Comparar diferentes variantes de Naive Bayes (Multinomial vs Bernoulli).
- Manejar datos faltantes mediante técnicas de imputación y eliminación.

## 🧠 Contenidos

### Fundamentos de los sistemas expertos
Se estudian los componentes fundamentales de un sistema experto: la base de conocimiento, el motor de inferencia, la interfaz de usuario y el módulo de explicación. Se analizan las estrategias de encadenamiento hacia adelante y hacia atrás.

### Redes bayesianas y Naive Bayes
Se introduce el framework probabilístico para la toma de decisiones, centrándose en las redes bayesianas y el clasificador Naive Bayes como herramienta de clasificación supervisada.

### Laboratorio práctico: Clasificación con Naive Bayes
El laboratorio implementa un pipeline completo de clasificación:
1. Análisis descriptivo de los datos (dataset de votaciones del Congreso).
2. Tratamiento de valores missing mediante imputación por moda.
3. División de datos en conjuntos de entrenamiento (75%) y test (25%).
4. Entrenamiento con MultinomialNB y evaluación con métricas de precisión (0.90).
5. Experimentación con diferentes proporciones de datos (50/50).
6. Comparación con BernoulliNB (precisión: 0.92).
7. Evaluación del impacto de eliminar datos faltantes vs. imputación.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| Python | Lenguaje de programación principal |
| scikit-learn | Implementación de MultinomialNB y BernoulliNB, métricas de evaluación |
| pandas | Carga y manipulación del dataset |
| numpy | Operaciones numéricas |
| matplotlib | Visualización de datos |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `Copia de UT3 - Sistemas expertos .pdf` | Apuntes | Material teórico sobre sistemas expertos y redes bayesianas |
| `Lab_1_Modelos_de_Redes_Bayesianas_Naive_Bayes.ipynb` | Notebook | Laboratorio práctico de clasificación con Naive Bayes usando dataset de votaciones |

## 🔗 Relación con otros temas
Continúa la progresión desde los tipos de IA (UD2) hacia aplicaciones específicas. Los conceptos de clasificación y métricas de evaluación son fundamentales para entender el análisis de sentimientos (UD6) y la comprensión del lenguaje natural (UD8).
