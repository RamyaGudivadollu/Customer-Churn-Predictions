
# Customer Churn Prediction using Artificial Neural Networks (ANN)

**Project Overview:**
This project predicts whether a customer will **churn** (leave) or **stay** with a company using an **Artificial Neural Network (ANN)**. Customer churn prediction is crucial for businesses to **retain customers**, **increase revenue**, and reduce **loss due to customer attrition**.

---

**Dataset:**

* The dataset contains information about customer demographics, account details, and service usage.
* Key features include:

  * `Gender`, `SeniorCitizen`, `Partner`, `Dependents`
  * `Tenure`, `MonthlyCharges`, `TotalCharges`
  * Services like `OnlineSecurity`, `TechSupport`, `StreamingTV`, etc.
* Target variable: `Churn` (0 = No, 1 = Yes)

---

**Preprocessing Steps:**

1. **Handle missing values** in `TotalCharges` and other numeric columns.
2. **Encode categorical features** using label encoding or one-hot encoding.
3. **Feature scaling** using `MinMaxScaler` for numerical columns.
4. **Split dataset** into training and testing sets (`train_test_split`).

---

**Modeling with ANN:**

* Built a **feedforward neural network** using **TensorFlow/Keras**.
* Input layer → Hidden layers → Output layer (sigmoid activation).
* **Loss function:** Binary crossentropy
* **Optimizer:** Adam
* **Metrics:** Accuracy

---

**Evaluation Metrics:**

* **Confusion Matrix:** To visualize correct and incorrect predictions.
* **Accuracy:** Percentage of correct predictions.
* **Precision, Recall, F1-score:** For better insight into class-wise performance.

---

**Key Results:**

* The ANN model achieved **~80% accuracy** on the test data.
* Confusion matrix shows the model’s performance in predicting churn vs non-churn customers.

---

**Conclusion:**

* ANN is effective in predicting customer churn.
* Companies can use this model to **identify high-risk customers** and implement **retention strategies**.

---

**Technologies Used:**

* Python, Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn (for preprocessing, train-test split, evaluation)
* TensorFlow/Keras (for ANN model)

---

