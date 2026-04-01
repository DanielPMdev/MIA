# Procesamiento del Lenguaje Natural

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Esta unidad introduce el Procesamiento del Lenguaje Natural (NLP), una de las ramas más activas de la Inteligencia Artificial que permite a las máquinas comprender, interpretar y generar lenguaje humano. Se abordan los desafíos fundamentales del NLP y se realiza un laboratorio práctico de análisis de sentimientos utilizando datos reales de Twitter con técnicas de aprendizaje automático.

## 🎯 Objetivos de Aprendizaje
- Comprender los fundamentos y desafíos del Procesamiento del Lenguaje Natural.
- Implementar un pipeline completo de preprocesamiento de texto (limpieza, tokenización, eliminación de ruido).
- Aplicar la técnica TF-IDF para la vectorización de texto.
- Entrenar un modelo de Regresión Logística para análisis de sentimientos.
- Evaluar el rendimiento de un modelo de clasificación de texto mediante métricas estándar.
- Visualizar resultados mediante nubes de palabras y matrices de confusión.
- Analizar problemas de desbalanceo de datos y ambigüedad semántica.

## 🧠 Contenidos

### Fundamentos del NLP
Se cubren los conceptos esenciales del procesamiento del lenguaje natural, incluyendo los retos principales: trabajar con texto desordenado, implementar preprocesamiento eficiente, manejar ambigüedad semántica y desbalanceo de datos.

### Laboratorio: Análisis de sentimientos en Twitter
El notebook práctico implementa un pipeline completo de clasificación de sentimientos:
1. **Carga de datos**: Dataset de Twitter con 31,962 tweets etiquetados (0 = no odio, 1 = odio/racismo/sexismo).
2. **Preprocesamiento**: Limpieza de menciones (@usuario), URLs, caracteres especiales y conversión a minúsculas.
3. **Análisis del desbalanceo**: 29,720 tweets clase 0 vs 2,242 tweets clase 1.
4. **Vectorización TF-IDF**: Transformación del texto en representación numérica con 5,000 características.
5. **Modelo de Regresión Logística**: Accuracy del 95%, con precisión 0.92 para tweets de odio pero recall de solo 0.33.
6. **Visualización**: Nubes de palabras para ambas clases de sentimiento.
7. **Interpretación detallada**: Análisis completo de precision, recall, F1-score, macro y weighted averages.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| Python | Lenguaje de programación principal |
| scikit-learn | TfidfVectorizer, LogisticRegression, métricas de clasificación |
| pandas | Manipulación del dataset de tweets |
| numpy | Operaciones numéricas |
| matplotlib | Visualización de resultados |
| seaborn | Gráficos estadísticos |
| wordcloud | Generación de nubes de palabras |
| re | Expresiones regulares para preprocesamiento de texto |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `UT6. Procesamiento del Lenguaje Natural.pptx` | Presentación | Material teórico sobre los fundamentos del NLP |
| `Desafíos en el NLP.ipynb` | Notebook | Laboratorio práctico de análisis de sentimientos en tweets de Twitter |

## 🔗 Relación con otros temas
Los conceptos de NLP son fundamentales para las unidades posteriores: servicios de voz (UD7) que trabajan con texto y voz, comprensión del lenguaje natural (UD8) que profundiza en el NLU, e implementación de chatbots (UD9). Las técnicas de clasificación conectan con los fundamentos vistos en sistemas expertos (UD3).
