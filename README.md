# Customer Churn Prediction

Predicting telecom customer churn using **Python (Random Forest Classifier)** and visualizing insights in **Power BI**.

---

## **Project Overview**
This project analyzes customer data from a telecom company to predict churn (customers leaving the service) and provides interactive dashboards for business insights.

- **Objective:** Identify customers likely to churn and understand key churn drivers.
- **Tools Used:** Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Power BI.

---

## **Project Structure**

Customer_Churn_Prediction/
│
├─ Python/
│ └─ Customer_Churn_Prediction.ipynb # Google Colab notebook with ML model
│
├─ PowerBI/
│ └─ Churn_Dashboard.pbix # Interactive dashboard
│
├─ data/
│ └─ telco_customer_churn.csv # Sample dataset (anonymized)
│
└─ README.md # Project documentation
---

## **Key Features**

### **Python (Google Colab)**
- Loaded and cleaned dataset, handled missing values, and converted data types  
- Encoded categorical variables and split data into training/testing sets  
- Built **Random Forest Classifier** to predict customer churn  
- Evaluated model with **accuracy, classification report, and confusion matrix**  
- Identified important features driving churn using feature importance  

### **Power BI Dashboard**
- **KPI Cards:** Total Customers, Churn Rate, Average Monthly Charges, Average Tenure  
- **Bar & Donut Charts:** Churn distribution by Contract Type, Payment Method, Gender  
- **Scatter Plot:** Monthly Charges vs Tenure colored by Churn  
- **Slicers:** Interactive filtering by Contract Type, Payment Method, Internet Service  
- **DAX Measures:** Dynamic calculations for metrics like Churn Rate and Average Charges  

---

## **Tech Stack**
- **Python Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
- **Data Visualization & Dashboard:** Power BI, DAX for measures  
- **Machine Learning:** Random Forest Classifier, Train/Test Split, Accuracy & Confusion Matrix  

---

## **How to Run**
1. Open `Python/Customer_Churn_Prediction.ipynb` in **Google Colab**.  
2. Run each cell to preprocess data, train the model, and evaluate results.  
3. Open `PowerBI/Churn_Dashboard.pbix` in **Power BI Desktop**.  
4. Use slicers and interactive visuals to explore churn trends.

---

## **Insights / Outcome**
- Customers with **short tenure** and **high monthly charges** are more likely to churn.  
- Certain **contract types and payment methods** have higher churn rates.  
- The dashboard allows stakeholders to **quickly identify at-risk customers** and take action to retain them.  
- Feature importance analysis highlights **top factors influencing churn**, helping businesses focus retention strategies.  

---

## **Skills & Learnings**
- Python, Machine Learning, Data Analysis, Data Visualization, Power BI, DAX, Customer Analytics, Predictive Modeling, Business Intelligence  

---
