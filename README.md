# 🌳 PRODIGY_DS_03
## Customer Purchase Prediction Using Decision Tree Classifier

### 📌 Internship
**Prodigy InfoTech – Data Science Internship**

### 👨‍💻 Submitted By
**Rushiraj Arvind Kadam**

---

# 📖 Project Overview

This project focuses on building a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on demographic and behavioral information.

The Bank Marketing Dataset from the UCI Machine Learning Repository was used for this task. The project demonstrates the complete Machine Learning workflow including data preprocessing, feature encoding, model training, evaluation, and visualization.

---

# 🎯 Objective

The objective of this project is to:

- Build a Decision Tree Classification Model
- Predict customer subscription behavior
- Analyze customer demographic and campaign-related data
- Evaluate model performance using classification metrics
- Visualize the Decision Tree and feature importance

---

# 📂 Dataset Information

**Dataset:** Bank Marketing Dataset

**Source:** UCI Machine Learning Repository

**File Used:** `bank-full.csv`

### Target Variable

| Value | Meaning |
|---------|---------|
| Yes | Customer Subscribed |
| No | Customer Did Not Subscribe |

### Dataset Size

- Records: 45,211
- Features: 17
- Target Column: `y`

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 🔄 Machine Learning Workflow

### 1. Data Loading

- Loaded the Bank Marketing Dataset
- Explored dataset structure and features

### 2. Data Preprocessing

- Checked for missing values
- Encoded categorical variables using Label Encoding
- Prepared features and target variable

### 3. Train-Test Split

- 80% Training Data
- 20% Testing Data

### 4. Model Building

Algorithm Used:

**Decision Tree Classifier**

Parameters:

```python
DecisionTreeClassifier(
    max_depth=5,
    random_state=42
)
```

---

# 📊 Visualizations

The following visualizations were created:

### Customer Subscription Distribution

Shows the distribution of customers who subscribed and did not subscribe.

### Correlation Heatmap

Displays relationships among numerical features.

### Confusion Matrix

Evaluates model prediction performance.

### Decision Tree Visualization

Shows the decision-making process used by the model.

### Feature Importance

Identifies the most influential features affecting customer subscription decisions.

---

# 📈 Model Evaluation

Metrics Used:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

The model successfully classified customer purchasing behavior and achieved strong predictive performance.

---

# 🔍 Key Findings

✅ Decision Tree successfully classified customer subscription behavior.

✅ Campaign-related features significantly influenced customer decisions.

✅ Customer demographic attributes contributed to prediction accuracy.

✅ Feature importance analysis identified the most influential variables.

✅ Decision Trees provide interpretable business decision rules.

---

# 📁 Project Structure

```text
PRODIGY_DS_03
│
├── bank-full.csv
├── PRODIGY_DS_03.ipynb
├── screenshots
│   ├── target_distribution.png
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── decision_tree.png
│   └── feature_importance.png
│
├── PRODIGY_DS_03_Professional_Report.pdf
└── README.md
```

---

# 🚀 Future Scope

Future improvements can include:

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Cross Validation
- Ensemble Learning Techniques

---

# 📚 References

- UCI Machine Learning Repository
- Scikit-Learn Documentation
- Pandas Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

# 🎓 Internship Task

This project was completed as part of **Task-03** under the **Prodigy InfoTech Data Science Internship Program**.

---

⭐ If you found this project useful, consider giving it a star on GitHub!# PRODIGY_DS_03
