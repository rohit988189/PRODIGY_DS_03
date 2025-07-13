# 🌳 Customer Purchase Prediction using Decision Tree Classifier

This project implements a **Decision Tree Classifier** to predict whether a bank customer will subscribe to a term deposit, based on their **demographic**, **financial**, and **campaign interaction** data. The analysis uses the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## 🎯 Objective

Build a classification model to assist banks in identifying potential customers who are likely to purchase financial products — enabling better targeted marketing.

---

## 📁 Dataset

- **Source**: [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Filename**: `bank-additional-full.csv`
- **Target Variable**: `y`  
  - `yes` → Customer subscribed  
  - `no` → Customer did not subscribe  

---

## 🔍 Features Overview

The dataset includes:
- **Personal details**: `age`, `job`, `marital`, `education`
- **Financial indicators**: `default`, `housing`, `loan`
- **Campaign data**: `contact`, `month`, `day_of_week`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`
- **Economic indicators**: `emp.var.rate`, `cons.price.idx`, `euribor3m`, `nr.employed`

---

## 🧰 Tools & Libraries Used

| Tool/Library       | Purpose                         |
|--------------------|----------------------------------|
| Python             | Programming                     |
| Pandas             | Data loading & cleaning         |
| Matplotlib & Seaborn| Data visualization             |
| scikit-learn       | Machine learning & evaluation   |

---

## 🛠️ Steps Performed

1. ✅ **Dataset loading** from local CSV  
2. 🧼 **Cleaning and encoding** of categorical features using `LabelEncoder`  
3. 🔀 **Splitting data** into training and testing sets  
4. 🌳 **Training** a `DecisionTreeClassifier` model  
5. 🧠 **Evaluating** performance using metrics  
6. 📊 **Visualizing** the trained decision tree  

---

## 📈 Evaluation Results

Example model performance:
✅ Accuracy : 88.89%
✅ Precision: 50.36%
✅ Recall : 54.20%
✅ F1 Score : 52.21%


**Confusion Matrix**:
[[8528 616]
[ 528 625]]

The model has high accuracy but moderate recall and precision for the "yes" class, suggesting room for improvement with balancing or boosting techniques.

---

## 🌳 Decision Tree Visualization

The decision tree shows:
- Feature splits at each node
- Gini impurity
- Class distribution
- Leaf node outcomes

It helps in understanding **which features are most important** in making the final decision.

---

## ▶️ How to Run This Project

### 🧪 Option 1: Google Colab
1. Upload the notebook and `bank-additional-full.csv`
2. Run all cells

### 💻 Option 2: Run Locally
1. Place `bank-additional-full.csv` in the same directory
2. Run the script in VS Code or Jupyter Notebook
3. Install required packages:

```bash
pip install pandas matplotlib seaborn scikit-learn
💡 Use Cases
Marketing campaign planning

Customer profiling

Lead prioritization

Upselling financial products

🙋‍♂️ Author
Rohit Chavan
Machine Learning Intern | Data Science & AI/ML Enthusiast


