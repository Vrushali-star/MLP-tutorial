# Multilayer Perceptrons: Architecture, Training, and Real-World Applications

## Overview
This project presents a comprehensive study of Multilayer Perceptrons (MLPs), a fundamental type of artificial neural network. It covers the architecture, training process, and real-world applications, along with a practical implementation for loan approval prediction.

The project is developed as part of a machine learning assignment.

---

## Introduction
Machine Learning is a branch of artificial intelligence that enables systems to learn from data and make predictions. Neural networks, inspired by the human brain, are powerful tools for modelling complex relationships.

A Multilayer Perceptron (MLP) is a feedforward neural network consisting of:
- Input layer  
- One or more hidden layers  
- Output layer  

MLPs are widely used for classification and regression tasks.

---

## MLP Architecture
- Fully connected (dense) network  
- Each neuron is connected to the next layer  
- Uses weights and bias for computation  
- Activation functions introduce non-linearity  

---

## Core Concepts
- Weights and Bias  
- Activation Functions (ReLU, Sigmoid)  
- Forward Propagation  
- Backpropagation  
- Gradient Descent  

---

## Implementation (Finance Example)

### Dataset
A synthetic dataset of 200 samples was generated with:
- Income  
- Credit Score  
- Loan Amount  
- Employment Years  

Target:
- 1 = Loan Approved  
- 0 = Loan Rejected  

---

### Data Preprocessing
- Train-test split (80:20)  
- Feature scaling using StandardScaler  

---

### Model
- Algorithm: Multilayer Perceptron (MLPClassifier)  
- Hidden layers: (16, 8)  
- Activation: ReLU  
- Optimizer: Adam  

---

## Results
- Accuracy: **92.5%**  

### Confusion Matrix

### Key Insights
- High precision (1.00) → reliable approvals  
- Good F1-score (0.87)  
- Some approved cases missed (recall = 0.77)  

---

## Visualisations
- Loss curve showing training convergence  
- Income vs Credit Score decision boundary  
- Class distribution plot  

---

## Overfitting and Improvements
- Overfitting occurs when model memorises training data  
- Techniques used:
  - Dropout  
  - L2 Regularisation  
  - Early Stopping  

---

## Applications
### Healthcare
- Disease prediction (e.g., diabetes)  
- Medical diagnosis  

### Finance
- Loan approval  
- Fraud detection  
- Credit scoring  

### Image Recognition
- Classification tasks  
- Feature-based prediction  

---

## Conclusion
MLPs are powerful neural networks capable of learning complex patterns. With proper training and regularisation, they provide strong performance across multiple domains such as healthcare, finance, and computer vision.

---

## References
- Goodfellow et al., *Deep Learning*  
- Chollet, *Deep Learning with Python*  
- Scikit-learn Documentation  
- TensorFlow Research Papers  
- UCI Machine Learning Repository  

---

## Author
**Vrushali Patel**

---

## License
This project is licensed under the MIT License.
