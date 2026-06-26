# Customer Churn Analysis using Python, SQL and Machine Learning

## Project Overview

Customer churn is a major challenge for telecom companies because losing existing customers directly impacts revenue.
In this project, I analyzed customer data to understand why customers leave the service, 
identified important churn patterns, and built machine learning models to predict customer churn.

The complete analysis was done using Python for data cleaning and visualization, SQL for business analysis, 
and Machine Learning for churn prediction.

---

## Dataset

- IBM Telco Customer Churn Dataset
- Total Records: 7,043
- Features: 24

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- MySQL

---

## Project Workflow

### Data Cleaning

- Converted `TotalCharges` to numeric values
- Handled missing values
- Checked duplicate records
- Created additional features such as Revenue Per Month, Tenure Group, and Charge Segment

### Exploratory Data Analysis

Performed analysis to understand:

- Customer churn distribution
- Contract type analysis
- Internet service analysis
- Payment method analysis
- Monthly charges
- Customer tenure
- Correlation between different features

### SQL Analysis

Using MySQL, I answered business-related questions such as:

- What is the overall churn rate?
- How much revenue is lost because of churn?
- Which contract type has the highest churn?
- Which payment method is associated with the highest churn?
- Which internet service customers are more likely to churn?

### Machine Learning

Built two classification models:

- Logistic Regression
- Random Forest Classifier

The models were evaluated using Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

---

## Results

### Business Insights

- Overall churn rate: **26.54%**
- Revenue lost due to churn: **₹2.86 Million**
- Customers with Month-to-Month contracts showed the highest churn rate.
- Customers using Electronic Check had the highest churn among payment methods.
- Fiber Optic customers were more likely to churn than DSL customers.

### Model Performance

**Logistic Regression**

- Accuracy: 81.12%
- Precision: 67.20%
- Recall: 56.03%
- F1 Score: 61.11%

**Random Forest**

- Accuracy: 79.77%
- Precision: 65.83%
- Recall: 49.06%
- F1 Score: 56.22%

---

---

## What I Learned

While working on this project, I improved my understanding of:

- Data cleaning and preprocessing
- SQL queries for business analysis
- Exploratory Data Analysis (EDA)
- Classification models
- Feature engineering
- Converting analysis into business insights

---

