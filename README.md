# DIO Challenge: Transfer Learning with VGG16

This project demonstrates and compares the effectiveness of a dog and cat image classification model trained from scratch against a pre-trained model, using the VGG16 architecture. The main goal is to highlight the superiority and efficiency of **Transfer Learning** in neural network development.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tSECefzJA2-5e1BnVsBhvTol04kRpCV7?usp=sharing)

---

### **Objective**

The project aims to demonstrate and compare the performance of two training approaches for an image classification model, using the problem of differentiating between dogs and cats. The focus is to prove that the *transfer learning* technique offers superior performance compared to a model trained from scratch.

---

### **Methodology**

The implementation followed two main approaches:

* **Reference Model (Trained from Scratch):** A sequential **Convolutional Neural Network (CNN)** was built from scratch, serving as a baseline for comparison.
* **Transfer Learning Model (VGG16):** The **VGG16** architecture, a pre-trained model on the vast ImageNet dataset, was used. The convolutional layers of VGG16 were frozen, and only a new classifier layer was added and trained for the specific task.

The performance of both models was analyzed based on `loss` and `accuracy` metrics.

---

### **Technologies Used**

-   `Python`
-   `TensorFlow / Keras`
-   `NumPy`
-   `Matplotlib`
-   `Google Colab`
