# Neural Network Fundamentals and Training Behavior Analysis

## Objective

The objective of this project is to build and analyze a feed-forward neural network model for a supervised learning problem using a customer churn dataset.

The project demonstrates:

- Data preprocessing
- Neural network training
- Forward propagation
- Loss calculation
- Backpropagation
- Hyperparameter experimentation
- Model evaluation

---

# Dataset Information

Dataset Used:
`customer_churn_nn.csv`

Target Variable:
`churn`

- 0 → Customer did not churn
- 1 → Customer churned

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

# Tasks Performed

## Task 1: Dataset Understanding

- Dataset exploration
- Missing value analysis
- Statistical summary
- Target variable distribution

## Task 2: Data Preprocessing

- Handling missing values
- Label encoding categorical columns
- Feature scaling
- Train-test splitting

## Task 3: Neural Network Model Building

- Feed-forward neural network
- Hidden layers with ReLU activation
- Sigmoid output layer
- Binary crossentropy loss
- Adam optimizer

## Task 4: Training and Evaluation

- Training loss and accuracy
- Testing loss and accuracy
- Confusion matrix
- Classification report

## Task 5: Hyperparameter Experimentation

Three experiments were conducted by changing:

- Hidden layers
- Neurons
- Learning rate
- Batch size
- Epochs
- Activation functions

## Task 6: Final Reflection

Conceptual understanding of:

- Weights and biases
- Activation functions
- Learning rate behavior
- Underfitting and overfitting

---

# Results Summary

The neural network achieved strong performance in predicting customer churn.

The best-performing model used:

- 2 hidden layers
- ReLU activation
- Adam optimizer
- Learning rate = 0.001
- Batch size = 32

The model demonstrated good generalization with balanced training and testing accuracy.