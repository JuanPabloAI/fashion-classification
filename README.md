# 👕 Fashion Classification (Fashion-MNIST)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Proyecto de **clasificación de prendas de ropa** usando **redes neuronales convolucionales (CNNs)** sobre el dataset **Fashion-MNIST**.  

El objetivo es construir un modelo capaz de identificar correctamente el tipo de prenda (camisetas, zapatos, bolsos, etc.) a partir de imágenes en escala de grises de 28x28 píxeles.  

---

## 📂 Contenido del repositorio

- `notebooks/Fashion_classification.ipynb` → Notebook principal con todo el flujo del proyecto.
- `requirements.txt` → Dependencias necesarias para ejecutar el proyecto.
- `.gitignore` → Archivos y carpetas ignoradas en el control de versiones.
- `README.md` → Documentación principal.

---

## ⚙️ Instalación y uso

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/<tu-usuario>/fashion-classification.git
   cd fashion-classification

python -m venv .venv
# Activar entorno:
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt

jupyter notebook
