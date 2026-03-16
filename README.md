# Credit Card Consumption Prediction

## 1. Title

**Credit Card Consumption Prediction using Machine Learning**

This project focuses on predicting the future credit card spending behavior of customers using machine learning techniques. By analyzing historical transaction data, demographic details, and financial behavior, the model estimates the amount a customer is likely to spend on their credit card in the upcoming months.

Financial institutions generate large volumes of customer transaction data. By applying data analytics and machine learning to this data, organizations can gain valuable insights into customer behavior and make smarter financial decisions. This project demonstrates how predictive modeling can be used to forecast credit card consumption and support business decision-making.

---

## 2. Objective

The primary objective of this project is to develop a machine learning model capable of predicting the **average credit card consumption of customers for the next three months**.

The project aims to:

* Analyze customer demographic and behavioral data.
* Identify key factors influencing credit card spending.
* Build predictive models that estimate customer spending patterns.
* Evaluate model performance using appropriate regression metrics.
* Provide insights that can help financial institutions make data-driven decisions.

This prediction model can be used by banks to improve their understanding of customer behavior and enhance financial planning strategies.

---

## 3. Tech Stack

The following technologies and tools were used to build and analyze this project.

### Programming Language

* **Python**

### Data Analysis Libraries

* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations

### Data Visualization

* **Matplotlib** – Data visualization and plotting graphs
* **Seaborn** – Statistical data visualization

### Machine Learning Libraries

* **Scikit-learn** – Machine learning algorithms and model evaluation
* **XGBoost / LightGBM** – Advanced gradient boosting models for improved prediction accuracy

### Development Environment

* **Jupyter Notebook** – Interactive environment for coding, analysis, and visualization

### Version Control

* **Git & GitHub** – Project version control and portfolio hosting

---

## 4. Data Source

The dataset used in this project consists of **three separate datasets** that contain different aspects of customer information. These datasets were combined to create a unified dataset for analysis and model training.

### 1. Customer Demographics Data

This dataset contains basic information about customers, including:

* Age
* Gender
* Income level
* Account type
* Other demographic attributes

Demographic data helps in understanding the financial background and profile of customers.

### 2. Customer Behavior Data

This dataset captures customer financial activity and transaction behavior such as:

* Debit card transaction frequency
* Credit card transaction history
* Investment activities
* Loan information
* Monthly transaction patterns

These behavioral features play an important role in predicting customer spending behavior.

### 3. Credit Card Consumption Data

This dataset contains the **target variable**:

`cc_cons` – represents the average credit card consumption of customers.

The objective of the machine learning model is to predict this value using other available features.

### Data Integration

All datasets were merged using a **unique customer identifier (Customer ID)** to create a comprehensive dataset that includes both demographic and behavioral attributes for each customer.

---

## 5. Dashboard Previews

During the **Exploratory Data Analysis (EDA)** phase, several visualizations were created to understand patterns in the data and identify relationships between variables.

Some key visualizations include:

* **Distribution of Credit Card Spending**
  Shows how customer spending values are distributed and highlights potential skewness or outliers.

* **Income vs Credit Card Consumption**
  Helps identify the relationship between customer income levels and spending behavior.

* **Transaction Behavior Analysis**
  Visualizes patterns in debit and credit transactions.

* **Correlation Heatmap**
  Displays relationships between numerical features and helps identify the most important predictors.

## 6. Business Problem

Financial institutions handle millions of credit card transactions every day. Understanding how customers use their credit cards is essential for improving financial services and managing risk.

However, without predictive analytics, banks face several challenges:

* Difficulty identifying high-value customers
* Inefficient credit limit allocation
* Limited understanding of customer spending behavior
* Ineffective marketing and promotional strategies
* Increased financial risk due to poor forecasting

This project addresses these challenges by developing a machine learning model that predicts future credit card consumption based on historical customer data.

### Business Impact

By using predictive analytics, banks and financial institutions can:

* Identify **high-value customers** and provide personalized services
* Set **appropriate credit limits** based on spending behavior
* Design **targeted marketing campaigns** for different customer segments
* Improve **customer relationship management**
* Reduce financial risk and improve decisio

###Demo/Screenshort



