# AI-Based Retail Customer Analytics, Data Warehouse & Churn Prediction System

### Turning Retail Transaction Data into Actionable Business Intelligence

## 📌 Project Overview

The **AI-Based Retail Customer Analytics, Data Warehouse and Churn Prediction System** is an end-to-end data analytics and machine learning project designed to transform raw retail transaction data into meaningful business insights.

The project focuses on data preprocessing, data quality management, data warehouse development using Star Schema, Online Analytical Processing (OLAP), multidimensional data cube generation, and machine learning-based customer churn prediction.

By analyzing historical retail transactions and customer purchasing patterns, this system aims to help businesses understand customer behaviour, identify potential customer loss, and make data-driven decisions.

## 🎯 Project Objectives

- Collect and understand real-world retail transaction data.
- Perform data cleaning and preprocessing.
- Handle missing values, duplicate records, and outliers.
- Integrate and transform retail data.
- Apply data reduction and discretization techniques.
- Perform data quality and consistency checks.
- Design and implement a data warehouse using Star Schema.
- Perform OLAP operations and generate data cubes.
- Predict potential customer churn using Machine Learning.
- Evaluate model performance and generate business insights.

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Core programming |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| Kaggle Notebook | Development and execution |

## 📊 Dataset

**Online Retail / E-Commerce Transaction Dataset**

The project uses historical transaction records from a UK-based online retail business.

Dataset: [E-Commerce Data – Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

The dataset contains information related to:
- Invoice Number
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## ⚙️ Project Workflow

### 1. Data Collection and Understanding
Loading the retail transaction dataset and exploring its structure, dimensions, data types, and statistical properties.

### 2. Data Cleaning and Preprocessing
Handling missing values, duplicate records, inconsistent entries, and invalid transactions.

### 3. Missing Value and Outlier Handling
Identifying missing data and detecting extreme values using statistical techniques such as the Interquartile Range (IQR).

### 4. Data Integration and Transformation
Preparing structured data, integrating relevant attributes, and creating analytical features such as Total Amount.

### 5. Data Reduction and Discretization
Reducing unnecessary data and converting continuous variables into meaningful categories.

### 6. Data Quality and Consistency Checking
Validating data completeness, accuracy, consistency, and uniqueness.

### 7. Data Warehouse Design
Developing a Star Schema consisting of:

- Fact Sales
- Dimension Customer
- Dimension Product
- Dimension Date

### 8. OLAP Operations
Implementing the five major OLAP operations:

- Roll-up
- Drill-down
- Slice
- Dice
- Pivot

### 9. Data Cube Generation
Generating multidimensional sales summaries to analyze business performance across different dimensions.

### 10. Customer Churn Prediction
Applying a Random Forest Classifier to identify customers who may stop purchasing based on their purchasing behaviour and derived churn labels.

### 11. Model Evaluation
Evaluating the machine learning model using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 12. Business Insights and Conclusion
Interpreting analytical results to identify customer purchasing trends, sales patterns, and potential customer retention opportunities.

## 🏗️ Data Warehouse Architecture

The project follows a Star Schema approach:

**Fact Table:**
- Fact_Sales

**Dimension Tables:**
- Dim_Customer
- Dim_Product
- Dim_Date

This structure supports efficient analytical queries and multidimensional reporting.

## 📈 Expected Outcomes

- Clean and structured retail transaction data.
- A well-organized retail data warehouse.
- Multidimensional sales analysis using OLAP.
- Customer purchasing behaviour insights.
- Machine learning-based churn prediction.
- Data-driven recommendations for customer retention.

## 💡 Business Impact

This project demonstrates how data warehousing, business intelligence, and machine learning can work together to support retail businesses.

The insights can help businesses understand customer behaviour, monitor sales performance, identify customers at risk of leaving, and develop better customer retention strategies.

## 🚀 How to Run the Project

1. Open the project notebook in Kaggle.
2. Add the required retail dataset.
3. Execute the notebook cells sequentially.
4. Review the preprocessing results, visualizations, and data warehouse tables.
5. Explore OLAP operations and data cube outputs.
6. Train and evaluate the customer churn prediction model.

## 👩‍💻 Author

**Nitu Rawat**

B.Tech – Computer Science and Engineering (Artificial Intelligence & Machine Learning)

Sanskriti University

GitHub: [nitu-rawat](https://github.com/nitu-rawat)

---

*This project is developed as an academic implementation of Data Warehousing, Data Mining, Business Intelligence, and Machine Learning concepts.*
