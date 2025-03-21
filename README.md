# Bayesian Optimization on ResNet50 for Recyclable Object Classification

This repository contains the implementation and analysis of a **Comparative Study of Bayesian Optimization Effectiveness on ResNet50 for Recyclable Object Classification**. The study explores how Bayesian Optimization improves the performance of the ResNet50 convolutional neural network in classifying recyclable objects.
<br><br>

## 📌 Project Overview
Efficient waste classification is crucial for sustainable recycling. This project utilizes **ResNet50**, a deep learning model, to classify recyclable materials (cardboard, glass, metal, paper, plastic) and applies **Bayesian Optimization** for hyperparameter tuning to improve accuracy and efficiency.
<br><br>

## 🔬 Research Objectives
1. **Dataset Balancing**: Mitigate dataset imbalance using Simple Random Sampling.
2. **Optimization**: Compare ResNet50 model performance with and without Bayesian Optimization.
3. **Performance Evaluation**: Analyze the impact of Bayesian Optimization on classification accuracy, validation loss, and computational efficiency.
<br><br>

## 🛠️ Tech Stack & Tools
- **Language**: Python
- **Deep Learning Framework**: TensorFlow & Keras
- **Optimization**: Bayesian Optimization (Gaussian Process)
- **Dataset**: Kaggle's Garbage Dataset
- **Visualization**: Matplotlib, Seaborn
<br><br>

## 📂 Repository Structure
```
├── garbage-dataset/      # Dataset used for training
├── notebook/             # Jupyter notebooks for training and analysis
├── README.md             # Project description
├── requirements.txt      # Dependencies
```
<br><br>

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
5. **Set the dataset path:** Before running the notebook, update the dataset path in the code to match where your dataset is stored. Locate the following line in the notebook:
   ```python
   dataset_path = r"C:\Users\User\Desktop\UMS\FYP\FYP 1\dataset\archive\garbage-dataset"
   ```
   Replace it with the actual path where you saved your dataset.
6. **Run the notebook:** Execute each cell sequentially to preprocess the dataset, train the ResNet50 model, apply Bayesian Optimization, and evaluate results.
