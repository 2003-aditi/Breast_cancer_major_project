# Breast_cancer_major_project

##  Overview
This project applies **neural networks** to classify breast tumors as **benign (0)** or **malignant (1)** using medical features such as radius, texture, and smoothness. The goal is to support early detection and improve diagnostic accuracy in oncology.

##  Objectives
- Analyze medical datasets for tumor classification  
- Build a neural network model for prediction  
- Achieve high accuracy and generalization on unseen data  

##  Dataset
- Features: **Radius, Texture, Smoothness**  
- Target: **Benign (0), Malignant (1)**  
- Preprocessing: Feature scaling, normalization, median imputation, train-test split  

## Tools & Technologies
- Python  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib  

##  Methodology
1. **Data Preprocessing**  
   - Normalization to balance feature scales  
   - Median imputation for missing values  
   - Train-test split for generalization  

2. **Neural Network Architecture**  
   - Input Layer: 3 medical features  
   - Hidden Layers: ReLU activation for non-linear relationships  
   - Output Layer: Sigmoid activation for binary classification  
   - Loss Function: Binary Crossentropy  
   - Optimizer: Adam  

3. **Training Framework**  
   - Epochs and batch size tuning  
   - Validation data evaluation to prevent overfitting  

##  Evaluation
- **Accuracy Curves**: Rapid improvement in early epochs, plateau near 90–95%  
- **Loss Curves**: Smooth decline, stable convergence without spikes  
- **Confusion Matrix**: Demonstrates reliable classification of benign vs malignant cases  

##  Results
- High accuracy achieved  
- Strong generalization on unseen data  
- Reliable diagnostic support tool  

##  Clinical Utility
- **Objective Pattern Recognition**: Detects subtle correlations in medical features  
- **Scalable Consistency**: Maintains precision across large datasets  
- **Computational Efficiency**: Provides near-instant classification for faster diagnosis  

##  Future Scope
Integration into **Electronic Health Record (EHR) systems** for real-time diagnostic support, enabling proactive oncology interventions and improved patient outcomes.
