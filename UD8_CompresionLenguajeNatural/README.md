# Comprensión del Lenguaje Natural (NLU)

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Esta unidad profundiza en la Comprensión del Lenguaje Natural (NLU - Natural Language Understanding), un subárea del NLP que permite a las máquinas interpretar el significado y la intención detrás del lenguaje humano. Se estudia la arquitectura de un sistema NLU completo, incluyendo la detección de intenciones, la extracción de entidades y la gestión de slots, con una implementación práctica de un chatbot bancario funcional.

## 🎯 Objetivos de Aprendizaje
- Comprender la arquitectura y componentes de un sistema NLU.
- Implementar un clasificador de intenciones utilizando TF-IDF y Regresión Logística.
- Aplicar extracción de entidades con spaCy (NER) en texto en español.
- Diseñar y gestionar un sistema de slots para dialogar con el usuario.
- Crear una interfaz de chat interactiva con Gradio.
- Integrar los componentes de un NLU en un sistema funcional coherente.

## 🧠 Contenidos

### Fundamentos del NLU
Se estudian los componentes esenciales de un sistema de comprensión del lenguaje natural: clasificación de intenciones, extracción de entidades y relleno de slots.

### Laboratorio: Chatbot Bancario con NLU
El notebook implementa un chatbot bancario en español con los siguientes componentes:

1. **Modelo NLP**: Uso de spaCy con el modelo `es_core_news_sm` para procesamiento del español.
2. **Clasificación de intenciones**: Entrenamiento de un clasificador con 4 intenciones bancarias:
   - `consultar_saldo`: Consultar el saldo de la cuenta.
   - `transferir_dinero`: Realizar transferencias de dinero.
   - `pagar_factura`: Pagar facturas de servicios.
   - `hablar_con_agente`: Conectar con soporte humano.
3. **Extracción de entidades**: Uso de NER de spaCy (LOC, DATE, ORG, PER, MONEY) y expresiones regulares para detectar montos y cuentas.
4. **Sistema de respuestas**: Generación de respuestas contextuales basadas en la intención detectada y las entidades extraídas.
5. **Interfaz de chat**: Interfaz interactiva con Gradio que muestra la respuesta, la intención detectada, la confianza y las entidades extraídas.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| Python | Lenguaje de programación principal |
| spaCy | NER (Named Entity Recognition) con modelo español `es_core_news_sm` |
| scikit-learn | TfidfVectorizer y LogisticRegression para clasificación de intenciones |
| Gradio | Creación de la interfaz de chat interactiva |
| re | Expresiones regulares para extracción de entidades personalizadas |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `UT8. Comprensión del lenguaje natural.pptx` | Presentación | Material teórico sobre NLU y sus componentes |
| `UT8. Estructura de un NLU.ipynb` | Notebook | Laboratorio práctico: implementación de un chatbot bancario con NLU |

## 🔗 Relación con otros temas
Continúa directamente los conceptos de NLP (UD6) y se apoya en las técnicas de clasificación vistas en sistemas expertos (UD3). Los conocimientos de esta unidad son prerequisito para la implementación de chatbots discriminativos (UD9).
