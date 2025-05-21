# 🩺 Skin Cancer Detection (CNN-based App)

This folder contains code for detecting skin cancer using deep learning. The model processes dermatoscopic images to classify lesions, making it a foundation for building real-world medical screening tools.

---

## 📄 Contents

| File                          | Description |
|------------------------------|-------------|
| `skinCancer.ipynb`           | Step-by-step classification pipeline using a CNN for skin lesion diagnosis. Includes data preprocessing, training, and evaluation. |
| `mvip_cancer_detection.ipynb`| A project variant (possibly optimized) used for presentation or deployment in the MVIP context. May include augmented visualizations or modular design. |

---

## 🧠 Features

- Data loading from HAM10000 dataset
- Preprocessing: resizing, normalization, augmentation
- CNN architecture using Keras/TensorFlow
- Training with performance monitoring
- Accuracy, loss plots, and confusion matrix for evaluation
- Optional deployment hooks (can be extended to Flask/Streamlit app)

---

## 🚀 To Run

Open the notebook and run all cells sequentially:

```bash
jupyter notebook skinCancer.ipynb
pip install tensorflow matplotlib seaborn scikit-learn
```