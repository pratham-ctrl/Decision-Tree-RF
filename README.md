# Decision Trees and Random Forests - Heart Disease Classification

## 📌 Overview
This project demonstrates the use of **Decision Trees** and **Random Forests** for classification tasks.  
Dataset used: **Heart Disease Dataset** (Kaggle).  
Objective: Predict whether a patient has **Heart Disease (1)** or **No Disease (0)**.

---

## 📂 Project Structure


---

## ⚙️ Steps Performed
1. **Dataset Loading** – Heart Disease dataset.
2. **Data Splitting** – Train-test split (80:20).
3. **Decision Tree Classifier** – trained with controlled depth to prevent overfitting.
4. **Random Forest Classifier** – ensemble of 100 trees.
5. **Evaluation** – Accuracy, Precision, Recall, F1-score, Confusion Matrix.
6. **Visualization** – Decision Tree, Feature Importance, Confusion Matrix heatmap.
7. **Cross-Validation** – 5-fold cross-validation to check model stability.

---

## 📊 Results
- **Decision Tree Accuracy:** ~78%  
- **Random Forest Accuracy:** ~85%  
- **Random Forest CV Accuracy:** ~84%  
- Random Forest performed better due to reduced variance and ensemble learning.

---

## 📷 Sample Outputs
### Decision Tree
![Decision Tree](tree_visualization.png)

### Feature Importance
![Feature Importance](feature_importance.png)

---

## 💡 Key Learnings
- Decision Trees are easy to interpret but prone to overfitting.
- Random Forests use **bagging** (Bootstrap Aggregation) to reduce overfitting and improve accuracy.
- Feature Importance highlights the most influential features (e.g., Age, Cholesterol, Max Heart Rate).

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/DecisionTree-RandomForest-Task.git
   cd DecisionTree-RandomForest-Task
