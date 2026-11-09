# 🧠 Deep Learning & Deep Neural Networks Portfolio (TensorFlow & Keras)

[![Course](https://img.shields.io/badge/Curso-Deep_Learning_de_la_Neurona_a_la_Red-blue?style=for-the-badge&logo=udemy)](https://www.udemy.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)

¡Bienvenido a mi repositorio de **Deep Learning y Redes Neuronales Profundas**! Este espacio recopila las implementaciones prácticas, algoritmos desde cero, laboratorios de visión por computador, procesamiento de audio/texto y componentes personalizados desarrollados a lo largo del curso impartido por el profesor **Santiago Hernández**.

El objetivo de este portafolio es demostrar la comprensión matemática y la implementación en código de arquitecturas que van desde el Perceptrón básico hasta Redes Neuronales Multicapa (MLP), Optimización Avanzada y Tuning de Hiperparámetros.

---

## 📜 Certificación

* **Curso:** Curso completo de Deep Learning: de la neurona a la red
* **Instructor:** Santiago Hernández
* **Estado:** Completado 
* **Certificado:** *[Enlace al certificado de finalización de Udemy]*

---

## 🛠️ Tecnologías y Entorno

* **Lenguaje:** Python 3.10+
* **Frameworks de DL:** TensorFlow 2.x, Keras
* **Optimización & Tuning:** Keras Tuner, Adam, RMSprop, Momentum, SGD
* **Procesamiento & Data Science:** NumPy, Pandas, Scikit-Learn
* **Visualización & Audio:** Matplotlib, Seaborn, Librosa / Keras Audio Processing

---

## 📁 Estructura del Repositorio (`notebooks/`)

Los cuadernos están organizados por bloques temáticos abarcando desde las bases matemáticas y límites de decisión hasta personalización avanzada en TensorFlow:

```text
.
├── datasets/                                   # Archivos de datos (.csv, audio, imágenes)
├── notebooks/
│   ├── 01_Fundamentos_y_Perceptron/
│   │   ├── Implementando una RNA con Keras.ipynb
│   │   ├── Implementando la Neurona M-P.ipynb
│   │   ├── Visualización del límite de decisión del Perceptrón.ipynb
│   │   ├── Diagnóstico de cáncer de mama con el Perceptrón.ipynb
│   │   ├── ¿Por qué utilizar una función de activación_.ipynb
│   │   └── Visualización de las funciones de activación.ipynb
│   │
│   ├── 02_Perceptron_Multicapa_y_Aplicaciones/
│   │   ├── Clasificación de imágenes con el Perceptrón Multicapa.ipynb
│   │   ├── Visualizando el límite de decisión del Perceptrón Multicapa.ipynb
│   │   ├── Clasificación+de+imágenes+con+el+Perceptrón.ipynb
│   │   ├── Clasificación de audio con el Perceptrón Multicapa I.ipynb
│   │   ├── Clasificación de audio con el Perceptrón Multicapa II.ipynb
│   │   └── Clasificación de audio con Keras.ipynb
│   │
│   ├── 03_Optimizacion_y_Procesamiento_de_Texto/
│   │   ├── Tensores y operaciones con tensores.ipynb
│   │   ├── Clasificación de texto con Stochastic Gradient Descent.ipynb
│   │   ├── Clasificación de texto con Mini-Batch Gradient Descent.ipynb
│   │   ├── Clasificación de texto con Momentum Gradient Descent.ipynb
│   │   ├── Clasificación de texto con RMSprop.ipynb
│   │   ├── Clasificación de texto con Adam.ipynb
│   │   ├── Exponentially weighted moving average.ipynb
│   │   ├── Clasificación de sentimientos.ipynb
│   │   └── Clasificación de Tweets de desastres naturales.ipynb
│   │
│   └── 04_Componentes_Personalizados_y_Tuning/
│       ├── Creación de capas personalizadas con Tensorflow.ipynb
│       ├── Creación de otros componentes personalizados con Tensorflow.ipynb
│       ├── Regresión con Keras.ipynb
│       ├── Limite de decisión de una RNA profunda.ipynb
│       ├── Selección de hiperparámetros con Keras Tuner.ipynb
│       └── Selección de hiperparámetros y clasificación de texto.ipynb
│
├── models/                                     # Modelos exportados (.h5)
│   ├── modelo_boston_housing.h5
│   └── modelo_mnist.h5
├── README.md
└── LICENSE
