# 🧠 CNN com Keras para Classificação de Imagens

Este código implementa a **arquitetura** de uma Rede Neural Convolucional (CNN) em **Keras/TensorFlow** para classificação de imagens.

- **Pré-processamento:** Normaliza valores de pixels de 0-255 para 0-1.  
- **Modelo:** Camadas `Conv2D`, `MaxPooling2D`, `Dropout`, `Flatten` e `Dense` (Softmax na saída).  
- **Treinamento:** Otimizador Adam, perda `categorical_crossentropy`, métrica `accuracy` e `ReduceLROnPlateau` para ajuste dinâmico da learning rate.  
- **Saída:** Gráfico de acurácia de treino e validação.

> ⚠ Necessário fornecer os dados (`x_train`, `x_test`, `y_train`) no formato `(28,28,1)`.

---

[Meu LinkedIn](https://www.linkedin.com/in/pedro-rodrigues-salom%C3%A3o-55a0ab310/)
