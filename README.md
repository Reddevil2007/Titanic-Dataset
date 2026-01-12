
# 🚢 Titanic Survival Prediction using Logistic Regression (From Scratch)

# 📌 Overview
This project implements a logistic regression model from scratch to predict passenger survival on the Titanic dataset. The objective is to understand the mathematical and algorithmic foundations of logistic regression without using machine learning libraries such as scikit-learn.

# Features Used
- Passenger Class (Pclass)
- Sex
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Fare
- Embarked Port

# ⚙️ Data Preprocessing
- Handled missing values in Age and Embarked
- Dropped Cabin as it had excessive missing values
- Encoded categorical features (Sex, Embarked)
- Applied feature scaling for numerical stability
-Split data into 80% training and 20% testing

# 🧠 Model Implementation
## Core components:
- Linear combination of features
- Sigmoid activation function
- Binary cross-entropy (log loss)
- Gradient descent optimization


# 📈 Training
- Model trained over multiple epochs
- Training loss recorded at each epoch
- Loss vs Epochs plot used to verify convergence

# 📊 Evaluation Metrics
- Confusion Matrix
- Accuracy
- ROC Curve
- Area Under Curve (AUC)

# ✅ Results
The model successfully learned patterns from the data and achieved reasonable predictive performance on the test set. The results demonstrate the effectiveness of logistic regression for binary classification tasks.
