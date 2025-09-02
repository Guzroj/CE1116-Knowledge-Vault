---
Fecha de creación: 2025-09-02 00:23
Fecha de Modificación: 2025-09-02 00:23
tags: 
Tema:
---


## 📚 Idea/Concepto 
La ventana de contexto de un modelo de lenguaje es el número máximo de tokens que puede procesar de forma simultánea al generar texto. Funciona como una memoria a corto plazo: el modelo solo considera la información dentro de esa ventana y descarta lo que queda fuera. Esta restricción surge del costo computacional O(n²·d) del mecanismo de autoatención, lo que la convierte en un recurso finito y un cuello de botella. Para preservar el orden de los tokens, se añaden codificaciones posicionales a los embeddings, incorporando la información de posición directamente en sus vectores. En modelos generativos, se aplica un enmascaramiento causal, que bloquea los tokens futuros antes del softmax para mantener la naturaleza autorregresiva. Además, la atención multi-cabeza aprovecha la ventana dividiendo el espacio de representación en subespacios independientes, lo que permite capturar simultáneamente relaciones sintácticas y semánticas más complejas. En la práctica, se distingue entre la ventana fija del modelo y las estrategias de gestión de sesión, que permiten aprovechar de manera más eficiente este límite en aplicaciones reales.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 