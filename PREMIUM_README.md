#Credit Card Fraud Detection Project

---

#Executive Summary
This project applies machine learning techniques to identify fraudulent credit card transactions. 
Fraud detection is a high-impact business problem in banking and fintech,
where missed fraud can cause direct financial loss and false positives can frustrate customers.

The model was developed to detect suspicious activity accurately while balancing precision and recall.

---

#Business Context
Banks process millions of transactions daily. Manual fraud review is expensive and slow. Intelligent fraud detection systems help organizations:

- Reduce financial losses  
- Improve customer trust  
- Strengthen risk controls  
- Increase operational efficiency  

---

#Tech Stack

Category | Tools 
----------------------------------------
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn | Jupyter Notebook|GitHub |

---

#Dataset
This project uses an anonymized credit card transaction dataset containing legitimate and fraudulent transactions.

Main target column:

- `Class = 0` → Legitimate Transaction  
- `Class = 1` → Fraudulent Transaction  

---

#Project Workflow

```text
Data Loading
   ↓
Data Inspection
   ↓
Exploratory Data Analysis
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Business Insights
```

---

#Exploratory Data Analysis

Visualisations included:

- Fraud vs Non-Fraud Distribution (Pie Chart)
- Transaction Amount Histogram
- Correlation Heatmap
- Confusion Matrix

---

#Machine Learning Model

#Random Forest Classifier

Why Random Forest?

- Strong baseline model
- Handles complex patterns
- Works well on structured data
- Resistant to overfitting

---

#Evaluation Metrics

This project uses metrics suited for imbalanced fraud datasets:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

> Recall is especially important in fraud detection because missed fraud can be costly.

---

#Key Insights

- Fraudulent transactions represent a very small percentage of total transactions.
- Dataset imbalance makes accuracy alone unreliable.
- High recall is more valuable than high accuracy in fraud detection.
- Machine learning can significantly improve fraud monitoring efficiency.

---

#Future Improvements

- Compare XGBoost / Logistic Regression
- Hyperparameter tuning
- Threshold optimization
- Feature importance dashboard
- Power BI reporting layer

---

#Repository Structure

```text
Fraud_Detection_Project/
│── Fraud_Detection_Project.ipynb
│── README.md
│── creditcard.csv


#How to Run

#1. Clone Repository

   bash
git clone <your-repo-link>


### 2. Install Requirements

   bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook


#3. Start Jupyter

  bash
jupyter notebook

#4. Open Notebook

  text
Fraud_Detection_Project_Professional.ipynb


#Skills Demonstrated

- Data Cleaning  
- Exploratory Data Analysis  
- Data Visualisation  
- Machine Learning  
- Model Evaluation  
- Business Storytelling  
- GitHub Project Documentation  

