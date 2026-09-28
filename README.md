# 🧠 Deep Learning Architectures: From Fundamentals to Sparse MoE

Este repositorio contiene la implementación modular y progresiva en **PyTorch** de las principales arquitecturas de Aprendizaje Profundo e Inteligencia Artificial, abarcando desde modelos convolucionales y recurrentes hasta redes de atención avanzada y modelos de lenguaje dispersos.

---

## 📌 Arquitecturas e Implementaciones Incluidas

* **Visión por Computadora (CNN):** Redes Convolucionales para extracción de características espaciales y clasificación de imágenes.
* **Procesamiento Secuencial (RNN):** Redes Recurrentes (RNN/LSTM) para el modelado de datos temporales y secuencias.
* **Mecanismos de Atención:** Implementación paso a paso de *Self-Attention* y *Scaled Dot-Product Attention*.
* **Transformers:** Arquitectura completa de *Multi-Head Attention* y bloques *Transformer Encoder*.
* **Mixture of Experts (MoE):** Capa *Sparse MoE* condicional con enrutamiento Top-$k$, pérdida auxiliar de balanceo de carga (Switch Transformer) y benchmarking de rendimiento/VRAM en GPU CUDA.

---

## 🛠️ Tecnologías y Herramientas

* **Lenguaje:** Python 3.10+
* **Framework Principal:** PyTorch (CUDA 12.1)
* **Entorno:** Jupyter Notebooks (`.ipynb`) y scripts ejecutables (`.py`)
* **Visualización:** Matplotlib y Seaborn