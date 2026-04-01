# Implementaciones de Chatbot (Discriminativo)

> Asignatura: Modelos de Inteligencia Artificial  
> Curso de Especialización en Inteligencia Artificial y Big Data

## 📌 Descripción
Esta unidad aborda la implementación práctica de chatbots discriminativos utilizando servicios cloud. Se desarrolla un chatbot bancario (BankerBot) desplegado en Amazon Web Services (AWS), utilizando Amazon Lex como motor de comprensión del lenguaje natural y AWS Lambda para la lógica de negocio. El enfoque discriminativo se centra en la clasificación de intenciones y la extracción de entidades para gestionar interacciones bancarias automatizadas.

## 🎯 Objetivos de Aprendizaje
- Diseñar e implementar un chatbot discriminativo en un entorno cloud.
- Configurar un bot conversacional en Amazon Lex con intenciones, slots y tipos de slots personalizados.
- Desarrollar funciones Lambda en Python para la lógica de negocio del chatbot.
- Implementar intenciones bancarias: consulta de saldo y transferencia de fondos.
- Gestionar el flujo de diálogo mediante slots y sesiones.
- Desplegar y probar un chatbot funcional en AWS.

## 🧠 Contenidos

### Amazon Lex: Chatbot as a Service
Se estudia Amazon Lex como plataforma para la construcción de interfaces conversacionales, incluyendo la configuración de intenciones, utterances, slots y fulfillment hooks.

### Función Lambda: Lógica de negocio
La función Lambda implementa tres intenciones principales:

1. **CheckBalance**: Consulta del saldo de una cuenta bancaria.
   - Recibe el tipo de cuenta como slot.
   - Genera un saldo aleatorio como demostración.
   - Devuelve respuesta formateada al usuario.

2. **FollowupCheckBalance**: Consulta de seguimiento del saldo.
   - Similar a CheckBalance pero como intención de continuación.

3. **TransferFunds**: Transferencia de fondos entre cuentas.
   - Gestiona tres slots: cuenta origen, cuenta destino y monto.
   - Implementa lógica de validación (1 de cada 10 transferencias denegada aleatoriamente).
   - Respuestas en español con confirmación de la operación.

### Arquitectura del sistema
- **Frontend**: Interfaz conversacional de Amazon Lex.
- **Backend**: AWS Lambda (Python) para procesamiento de intenciones.
- **Gestión de estado**: Atributos de sesión para mantener contexto entre turnos.

## 🛠️ Tecnologías y Librerías
| Herramienta | Uso en este tema |
|---|---|
| Amazon Lex | Motor de NLU y gestión del diálogo |
| AWS Lambda | Función serverless para la lógica de negocio |
| Python | Lenguaje de la función Lambda |
| JSON | Formato de comunicación entre Lex y Lambda |

## 📁 Archivos
| Archivo | Tipo | Descripción |
|---|---|---|
| `BotBanking/lamda_function.py` | Código Python | Función Lambda con la lógica del chatbot bancario (CheckBalance, TransferFunds) |
| `BotBanking/BankerBot.zip` | Archivo comprimido | Paquete de despliegue del bot para Amazon Lex |

## 🔗 Relación con otros temas
Esta unidad integra los conocimientos de NLP (UD6) y NLU (UD8) en una implementación real. El chatbot discriminativo utiliza conceptos de clasificación de intenciones y extracción de entidades vistos en unidades anteriores. Complementa la perspectiva ética y legal estudiada en UD5 y UD10.
