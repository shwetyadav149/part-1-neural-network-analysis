# Customer Churn Prediction using Neural Networks

## Project Objective

The objective of this project is to build a Feed Forward Neural Network (FFNN) to predict customer churn using supervised learning.

The project demonstrates:
- Forward propagation
- Backpropagation
- Neural network training
- Loss calculation
- Hyperparameter experimentation
- Model evaluation

---

## Dataset Information

Dataset contains customer-related features such as:
- Region
- Plan Type
- Payment Method
- Tenure
- Monthly Charges
- Satisfaction Score
- Data Usage

Target Variable:
- churn
  - 1 = Customer Churned
  - 0 = Customer Retained

Dataset Size:
- Rows: 2000
- Columns: 17

---

## Data Preprocessing

The following preprocessing steps were performed:
- Removed customer_id column
- Encoded categorical variables
- Feature scaling using StandardScaler
- Train-test split

---

## Neural Network Architecture

The neural network contains:
- Input Layer
- Hidden Layer with ReLU activation
- Output Layer with Sigmoid activation

Optimizer:
- Adam

Loss Function:
- Binary Crossentropy

---

## Model Performance

### Final Results

- Test Accuracy: 98.25%
- Test Loss: 0.068

### Important Observation

The dataset was highly imbalanced.
The model predicted majority class effectively but struggled to identify churned customers.

---

## Hyperparameter Experiments

Three different experiments were performed:
- Different hidden layers
- Different neuron counts
- Different activation functions
- Different batch sizes

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Conclusion

The neural network successfully learned customer behavior patterns and achieved high accuracy.

The project demonstrated:
- Neural network fundamentals
- Forward propagation
- Backpropagation
- Hyperparameter tuning
- Model evaluation

Future improvements may include:
- SMOTE balancing
- Dropout regularization
- Deep neural networks