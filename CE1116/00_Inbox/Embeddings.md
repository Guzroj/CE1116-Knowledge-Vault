---
Fecha de creación: 2025-09-02 00:25
Fecha de Modificación: 2025-09-02 00:25
tags: 
Tema:
---


## 📚 Idea/Concepto 
Un embedding es una representación vectorial densa de tokens aprendida durante el entrenamiento, que captura similitudes semánticas y contextuales. En Transformers, los embeddings se combinan con codificaciones posicionales y luego se proyectan en vectores Query, Key y Value (WQ, WK, WV) para alimentar el mecanismo de autoatención. La similitud entre Q y K se escala por \(\sqrt{d_k}\) antes del softmax, y las salidas ponderadas de cada cabeza se concatenan y proyectan mediante W\_O para formar la representación contextual final. Tras la atención, los embeddings pasan por redes feed-forward (FFN), envueltas en conexiones residuales y normalización de capa, lo que asegura estabilidad en el entrenamiento y permite construir representaciones semánticas más profundas.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 