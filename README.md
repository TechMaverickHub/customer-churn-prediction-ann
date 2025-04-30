# Bank Customer Churn Prediction using Simple ANN

A simple Artificial Neural Network (ANN) model built using Keras and TensorFlow to predict whether a bank customer is likely to churn (leave the bank). The project includes data preprocessing, model training, and evaluation using classification metrics.

---

## 📊 Dataset

The dataset contains features such as:
- Customer demographics (Age, Gender, Geography)
- Account information (Balance, Tenure, Estimated Salary)
- Banking activity (Credit Score, Number of Products, Active Membership, etc.)

> 📁 Dataset is assumed to be preloaded or can be imported from Kaggle or other standard sources.

---

## ⚙️ Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow & Keras
- Matplotlib / Seaborn (for visualization)

---

## 🚀 Project Workflow

1. **Data Preprocessing**:
   - Handling categorical variables
   - Feature scaling
   - Splitting into training/test sets

2. **Model Building**:
   - Sequential ANN with Keras
   - Input, hidden, and output layers
   - Activation functions and optimizers

3. **Model Evaluation**:
   - Accuracy score
   - Confusion matrix
   - Classification report

---

## 🧪 Results

- Final Model Accuracy: **81.32%**
- Model performance evaluated using:
  - Confusion matrix
  - Precision, recall, F1-score

---

## 📂 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bank-churn-ann.git
   cd bank-churn-ann
