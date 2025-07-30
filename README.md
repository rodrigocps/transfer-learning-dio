# Desafio DIO: Transfer Learning com VGG16

Este projeto demonstra e compara a eficácia de um modelo de classificação de imagens de cães e gatos treinado do zero contra um modelo pré-treinado, utilizando a arquitetura VGG16. O principal objetivo é evidenciar a superioridade e a eficiência do **Transfer Learning** no desenvolvimento de redes neurais.

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)]([SEU_LINK_AQUI](https://colab.research.google.com/drive/1tSECefzJA2-5e1BnVsBhvTol04kRpCV7?usp=sharing))

---

### **Objetivo**

O projeto visa demonstrar e comparar a performance de duas abordagens de treinamento para um modelo de classificação de imagens, utilizando o problema de diferenciação entre cães e gatos. O foco é provar que a técnica de *transfer learning* oferece uma performance superior em relação a um modelo treinado do zero.

---

### **Metodologia**

A implementação seguiu duas abordagens principais:

* **Modelo de Referência (Treinado do Zero):** Uma **Rede Neural Convolucional (CNN)** sequencial foi construída do zero, servindo como uma linha de base para a comparação.
* **Modelo de Transfer Learning (VGG16):** Foi utilizada a arquitetura **VGG16**, um modelo pré-treinado no vasto *dataset* ImageNet. As camadas convolucionais da VGG16 foram congeladas, e apenas uma nova camada classificadora foi adicionada e treinada para a tarefa específica.

A performance de ambos os modelos foi analisada com base em métricas de `loss` (perda) e `accuracy` (precisão).

---

### **Tecnologias Utilizadas**

- `Python`
- `TensorFlow / Keras`
- `NumPy`
- `Matplotlib`
- `Google Colab`
