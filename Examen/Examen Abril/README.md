# Examen Abril — Segundo Parcial

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Material de preparación y estudio para la convocatoria de abril (segundo parcial), que abarca las unidades UD6 a UD10 de la asignatura. Incluye apuntes interactivos sobre SSML y componentes de asistentes de voz (Alexa), ejercicios prácticos sobre intenciones y slots, y múltiples quizzes de autoevaluación centrados en la UD10 (IA y Ética), con especial énfasis en la clasificación de niveles de riesgo del Reglamento UE 2024/1689.

## 🎯 Objetivos de Aprendizaje
- Dominar las etiquetas SSML y sus atributos para controlar la síntesis de voz
- Comprender el flujo completo de un asistente de voz: ASR → NLU → DM → TTS
- Identificar y diferenciar intenciones y slots en frases del usuario
- Clasificar correctamente sistemas de IA según su nivel de riesgo (inaceptable, alto, limitado, mínimo)
- Conocer el marco regulatorio español de IA: AESIA, ENIA, OBISAL, Sandbox regulatorio y sanciones
- Evaluar el dominio global de la UD10 mediante simulaciones de examen interactivas

## 🧠 Contenidos

### SSML y Componentes de Alexa
Apuntes interactivos organizados en pestañas que cubren las principales etiquetas SSML (`<break>`, `<lang>`, `<emphasis>`, `<p>/<s>`, `<prosody>`, `<say-as>`, `<amazon:effect>`), cada una con ejemplos de código, valores posibles y casos de uso. Se explica el flujo completo de un asistente de voz a través de sus cuatro componentes: **ASR** (voz → texto), **NLU** (texto → intención + slots), **DM** (gestor del diálogo, decide acción o pregunta) y **TTS** (texto → voz). También se detallan los conceptos de **Elicit Slot** y **Fulfillment**, el flujo técnico de AWS Lambda y el modelo de facturación de servicios AWS (Lex, Polly, Transcribe).

### Intenciones y Slots
Ejercicios prácticos de identificación de intenciones y extracción de slots a partir de frases del usuario, con ejemplos aplicados a dominios como reservas de restaurantes, consultas meteorológicas y gestión de alarmas.

### IA y Ética — Niveles de Riesgo (UD10)
Tres recursos de evaluación interactivos que cubren en profundidad los contenidos de la UD10:
- **Niveles de riesgo del Reglamento UE 2024/1689**: clasificación de sistemas de IA según el Art. 5 (prácticas prohibidas), Anexo III (alto riesgo), Art. 50 (transparencia) y riesgo mínimo. Incluye escenarios trampa donde el contexto de uso determina la clasificación.
- **Marco regulatorio español**: ENIA, AESIA (sede en A Coruña), OBISAL, Sandbox regulatorio, Sello IA Confiable, España Digital 2025/2026, Carta de Derechos Digitales (Art. XXV y XXVI) y régimen sancionador.
- **Ética y robótica**: Leyes de Asimov, principios del Parlamento Europeo para robots, dilema del trolley / Moral Machine, neurotecnología y Spain Neurotech.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| HTML / CSS / JavaScript | Aplicaciones web interactivas de estudio (apuntes con pestañas y quizzes con retroalimentación) |
| DM Sans / Playfair Display | Tipografías de Google Fonts utilizadas en los quizzes |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `Ejercicios Examen Abril _ SSML, Alexa, Intenciones, Slots... .pdf` | Ejercicios | Ejercicios prácticos sobre etiquetas SSML, componentes de Alexa, intenciones, slots y flujos de conversación |
| `apuntes_ssml_alexa_intenciones.html` | Apuntes interactivos | Aplicación web con pestañas que cubre etiquetas SSML, componentes de Alexa (ASR/NLU/DM/TTS), intenciones y slots, Lambda y costes AWS |
| `audio_apuntes_ssml_alexa_intenciones.mpeg` | Audio | Versión en audio de los apuntes de SSML, Alexa e intenciones para estudio auditivo |
| `examen_ud10_ia_etica.html` | Quiz interactivo | Simulación de examen de la UD10 con 25 preguntas sobre niveles de riesgo, transparencia, marco español, neurotecnología, ética y robótica |
| `quiz_completo_ud10.html` | Quiz interactivo | Quiz completo de la UD10 con 25 preguntas que cubren todos los bloques temáticos de la unidad, incluyendo escenarios trampa |
| `quiz_niveles_riesgo_ia.html` | Quiz interactivo | Quiz especializado con 15 preguntas trampa centradas exclusivamente en la clasificación de niveles de riesgo del Reglamento UE 2024/1689 |

## 🔗 Relación con otros temas
Este material de estudio cubre los contenidos del segundo parcial y se apoya directamente en las siguientes unidades ya documentadas:
- **UD7_ServiciosVoz**: Etiquetas SSML, síntesis de voz (TTS) y reconocimiento (ASR)
- **UD8_CompresionLenguajeNatural**: Comprensión del lenguaje natural (NLU), extracción de intenciones y slots
- **UD9_ImplementacionesChatbot(Discriminativo)**: Implementación de bots con Amazon Lex y AWS Lambda
- **UD10_IA&Etica**: Ética en IA, niveles de riesgo del Reglamento europeo, marco regulatorio español

Es la continuación natural del material de **Examen Enero**, que cubría las unidades UD1 a UD5 (primer parcial).
