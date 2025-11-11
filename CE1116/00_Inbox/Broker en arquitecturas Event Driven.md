---
Fecha de creación: 2025-11-11 16:27
Fecha de Modificación: 2025-11-11 16:27
tags: 
Tema:
---


## 📚 Idea/Concepto 
Un Broker en una arquitectura Event Driven es el componente central del Event Backbone, responsable de recibir, almacenar y distribuir eventos de forma asíncrona entre productores y consumidores mediante el modelo Publish/Subscribe (Pub/Sub).
Existen dos variantes principales: el Message Broker, que gestiona colas transitorias de mensajes (como RabbitMQ), y el Event Broker, que mantiene un registro inmutable de eventos (Event Log) para garantizar persistencia, reproducibilidad y trazabilidad (como Apache Kafka).
El Event Log actúa como la fuente principal de verdad del sistema, permitiendo reconstruir estados, habilitar patrones como Event Sourcing y CQRS, y servir como base de datos de flujo continuo para procesamiento de streams en tiempo real y analítica de IA/ML.
En este contexto, el Broker no solo desacopla servicios, sino que también impulsa la evolución hacia sistemas distribuidos, reactivos y centrados en los datos.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 