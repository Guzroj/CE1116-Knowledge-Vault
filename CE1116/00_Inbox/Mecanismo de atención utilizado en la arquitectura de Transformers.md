---
Fecha de creación: 2025-09-02 00:23
Fecha de Modificación: 2025-09-02 00:23
tags: 
Tema:
---


## 📚 Idea/Concepto 
El mecanismo de atención en Transformers calcula la relevancia entre tokens para construir representaciones contextuales. Los embeddings se proyectan en Query (Q), Key (K) y Value (V); la similitud entre Q y K se obtiene con un producto punto escalado ($\frac{1}{\sqrt{d_k}}$
), normalizado con softmax, y se usa para ponderar los Values. El resultado se combina con el embedding original mediante conexión residual y normalización de capa, asegurando estabilidad. En Multi-Head Attention, cada cabeza tiene proyecciones lineales independientes; sus salidas se concatenan y se proyectan nuevamente para mantener la dimensión del modelo. Este mecanismo se complementa con embeddings posicionales para capturar el orden de los tokens y con redes feed-forward (FFN) que amplían la capacidad representacional. Se aplica como auto-atención (self-attention) dentro del encoder y como atención cruzada (cross-attention) en el esquema encoder-decoder, mientras que en el decodificador autorregresivo se usa un enmascaramiento para impedir que un token acceda a posiciones futuras.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[ ]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 