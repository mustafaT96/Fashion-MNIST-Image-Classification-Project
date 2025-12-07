# 🧵 Fashion-MNIST Image Classification  
### A Feedforward Neural Network Exploration

This repository contains the implementation and analysis of a Feedforward Neural Network (FNN) trained on the Fashion-MNIST dataset. The project focuses on understanding model behavior, improving performance through regularization, and visualizing learned representations.

---

## 📂 What This Project Includes

- Feedforward Neural Network (FNN) built using TensorFlow/Keras  
- Complete data preprocessing pipeline (normalization, reshaping, splitting)  
- Baseline model training with evaluation on validation and test sets  
- Regularization experiments:
  - Dropout  
  - Batch Normalization  
  - L2 Regularization  
  - Learning Rate Scheduling  
- Training callbacks (EarlyStopping, TensorBoard, LR Scheduler)  
- UMAP visualizations of layer embeddings across training stages  
- Model checkpoints saved at different stages of training  
- Comparison of training/validation curves to study overfitting  

All detailed results, graphs, and analysis are available inside the notebook.

---

## 📦 Files Included

### 📦 fashion-mnist-ffnn  
│  
├── Image_Classification.ipynb # Main notebook with full analysis  
├── Image_Classification.pdf # Exported PDF version  
├── checkpoints/ # Saved model weights  
└── logs/ # TensorBoard logs  

---

## 🚀 How to Use

Run the notebook to reproduce:

- Baseline training  
- Regularization experiments  
- Embedding visualizations  
- Performance comparisons  

---

## 📌 Note  
This README summarizes only the key components.  
**All methodology, code, figures, and explanations are documented inside the notebook.**
