# Resource Allocation in 5G Network Using Machine Learning

This project explores the application of machine learning (ML) to optimize bandwidth management in 5G networks. A comparative analysis of regression algorithms and neural networks is conducted to identify the most effective models for resource allocation, ensuring high Quality of Service and network efficiency. Key evaluation metrics include **Mean Square Error (MSE)** and **R-Squared**.

# Project Report

https://drive.google.com/file/d/1rsk-dxSwd8PK9Nxl_2OK9N5gxwjEN4yl/view?usp=sharing

## Requirements

### Software:
- **Python**  
- **Python Libraries**:
  - Numpy  
  - Pandas  
  - Matplotlib  
  - Plotly  
  - Scikit-learn  
  - TensorFlow  

### IDEs:  
- Google Colab  
- VS Code  

---

## Methodology

### 1. Data Acquisition and Preprocessing:
- **Dataset**: A 400-row dataset from Nokia with features like signal strength, required bandwidth, latency, and allocated resources.
- **Data Augmentation**: Created an 800-row dataset by applying augmentation techniques to enhance model performance.
- **Feature Engineering**:  
  - Case 1: Combine signal strength and required bandwidth into a single feature, and resource allocation as another feature.  
  - Case 2: Combine latency and latency-signal interaction into a single feature and resource allocation into another feature.  
- **Data Split**: Divided datasets (400 and 800 rows) into training, validation, and test sets using a 70/20/10 split.

### 2. Model Training and Evaluation:
- **Models Implemented**:  
  - Linear Regression  
  - Polynomial Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosting Regressor  
  - Support Vector Machine  
  - K-Nearest Neighbors (KNN)  
  - Neural Networks (tested with 100, 200, and 300 epochs)  

- **Evaluation Metrics**:  
  - **Mean Squared Error (MSE)**: Measures average squared difference between predicted and actual resource allocation.  
  - **R-Squared**: Measure variance in actual resource allocation explained by the model.  

---

## Results

### Key Findings:
- **400-row Dataset**:  
  - Best models: **Random Forest** and **Neural Network (300 epochs)**.  
- **800-row Dataset**:  
  - Best models: **Gradient Boosting Regressor** and **Neural Network (200 epochs)**.  

### Observations:
- Neural Networks demonstrated performance improvement with more epochs but tended to overfit, emphasizing the need for careful epoch selection.

