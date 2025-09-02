---
Fecha de creación: 2025-09-02 00:25
Fecha de Modificación: 2025-09-02 00:25
tags: 
Tema:
---


## 📚 Idea/Concepto 
La tokenización es el proceso de dividir texto en tokens, que se convierten en IDs enteros usados como entrada a la capa de embeddings. Los modelos modernos emplean algoritmos de subpalabras como Byte Pair Encoding (BPE), WordPiece o SentencePiece, que aprenden sus reglas a partir de un corpus para equilibrar el tamaño del vocabulario y la cobertura de palabras. Estos métodos permiten manejar vocabularios grandes, reducir el problema de palabras desconocidas (OOV) y representar palabras morfológicamente complejas. La granularidad de la tokenización afecta directamente el número de tokens producidos, impactando en el uso de la ventana de contexto, el costo computacional y la huella de memoria durante el procesamiento en lote. Tras la tokenización, los IDs se transforman en vectores que se combinan con codificaciones posicionales para preservar el orden en la secuencia. Finalmente, en la etapa de decodificación, los IDs generados se convierten de nuevo en texto legible, cerrando el ciclo completo de procesamiento.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 