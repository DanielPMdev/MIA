# Servicios de Voz (Text-to-Speech)

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Esta unidad se centra en los servicios de voz, específicamente en la conversión de texto a voz (TTS - Text-to-Speech) y en la transcripción automática de voz a texto (ASR - Automatic Speech Recognition). Se estudian las tecnologías que permiten a las máquinas sintetizar voz a partir de texto, reconocer el habla y traducirla, cubriendo tanto los fundamentos teóricos como la implementación práctica mediante laboratorios guiados.

## 🎯 Objetivos de Aprendizaje
- Comprender los fundamentos de la síntesis de voz (TTS) y el reconocimiento de voz (ASR).
- Conocer y aplicar etiquetas SSML para controlar la síntesis de voz.
- Implementar la conversión texto a voz utilizando servicios gratuitos (gTTS, edge-tts).
- Transcribir audio a texto mediante reconocimiento automático del habla.
- Traducir textos transcritos a otros idiomas.
- Evaluar los costes asociados a servicios de voz en entornos cloud.
- Trabajar con diferentes acentos y variantes del español (España, México).

## 🧠 Contenidos

### Fundamentos de Text-to-Speech
Se estudian los conceptos básicos de la síntesis de voz, los motores TTS neuronales y las diferentes voces disponibles para cada idioma.

### Etiquetas SSML
Se cubren las etiquetas SSML (Speech Synthesis Markup Language) que permiten controlar aspectos como la velocidad, el tono, las pausas y la pronunciación en la síntesis de voz.

### Laboratorio 1: Texto a SSML
Laboratorio introductorio donde se practica la conversión de texto plano a marcado SSML y se generan archivos de audio de ejemplo (18 archivos MP3).

### Laboratorio 2: Cálculo de Costes
Laboratorio orientado a la evaluación de costes de los servicios TTS en plataformas cloud, fundamental para entender la viabilidad económica de los proyectos.

### Laboratorio 3: Síntesis y Traducción
Laboratorio práctico completo que integra múltiples tecnologías:
- **Síntesis con gTTS**: Uso de Google Text-to-Speech para generar audio en español (España) y español (México).
- **Síntesis con edge-tts**: Uso de Microsoft Edge TTS con voces neurales (AlvaroNeural para España, GerardoNeural para México).
- **Transcripción ASR**: Conversión de audio MP3 a texto usando SpeechRecognition de Google.
- **Traducción automática**: Traducción del texto transcrito al inglés usando deep-translator.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| Python | Lenguaje de programación principal |
| gTTS | Síntesis de voz con Google Text-to-Speech |
| edge-tts | Síntesis de voz con Microsoft Edge TTS (voces neurales) |
| SpeechRecognition | Reconocimiento automático del habla (ASR) |
| pydub | Manipulación y conversión de archivos de audio (MP3 a WAV) |
| deep-translator | Traducción automática de texto (Google Translator) |
| ffmpeg | Procesamiento multimedia de archivos de audio |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `UT7. Texto a voz_.pptx` | Presentación | Material teórico sobre servicios de voz y TTS |
| `etiquetas_ssml.pdf` | Apuntes | Referencia de etiquetas SSML para síntesis de voz |
| `Laboratorio N1/` | Directorio | Laboratorio 1: Texto a SSML con archivos MP3 de ejemplo |
| `Laboratorio N2/` | Directorio | Laboratorio 2: Cálculo de costes de servicios TTS |
| `Laboratorio N3/Lab3_Sintesis_gTTS.ipynb` | Notebook | Laboratorio 3: Síntesis TTS con gTTS, transcripción ASR y traducción |
| `Laboratorio N3/Lab3_Sintesis_EdgeTTS.ipynb` | Notebook | Laboratorio 3: Síntesis TTS con edge-tts y voces neurales |

## 🔗 Relación con otros temas
Los servicios de voz se conectan directamente con el procesamiento del lenguaje natural (UD6) y la comprensión del lenguaje natural (UD8). Las capacidades de TTS y ASR son componentes esenciales en la construcción de chatbots con interfaz de voz (UD9).
