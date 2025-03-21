# Bayesian Optimization on ResNet50 for Recyclable Object Classification

This repository contains the implementation and analysis of a **Comparative Study of Bayesian Optimization Effectiveness on ResNet50 for Recyclable Object Classification**. The study explores how Bayesian Optimization improves the performance of the ResNet50 convolutional neural network in classifying recyclable objects.

## 📌 Project Overview
Efficient waste classification is crucial for sustainable recycling. This project utilizes **ResNet50**, a deep learning model, to classify recyclable materials (cardboard, glass, metal, paper, plastic) and applies **Bayesian Optimization** for hyperparameter tuning to improve accuracy and efficiency.

## 🔬 Research Objectives
1. **Dataset Balancing**: Mitigate dataset imbalance using Simple Random Sampling.
2. **Optimization**: Compare ResNet50 model performance with and without Bayesian Optimization.
3. **Performance Evaluation**: Analyze the impact of Bayesian Optimization on classification accuracy, validation loss, and computational efficiency.

## 🛠️ Tech Stack & Tools
- **Language**: Python
- **Deep Learning Framework**: TensorFlow & Keras
- **Optimization**: Bayesian Optimization (Gaussian Process)
- **Dataset**: Kaggle's Garbage Dataset
- **Visualization**: Matplotlib, Seaborn

## 📂 Repository Structure
```
├── garbage-dataset/              # Dataset used for training
├── notebook/            # Jupyter notebooks for training and analysis
├── README.md             # Project description
├── requirements.txt      # Dependencies
```

## 🚀 How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/akinomaria/bayesian-optimization-resnet50.git
   cd bayesian-optimization-resnet50
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook "notebook/RESNET50 WITH BAYESIAN OPTIMIZATION.ipynb"
   ```
4. Train the model and compare results.
