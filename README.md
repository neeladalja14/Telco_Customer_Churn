# Telco Customer Churn Analysis

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)

## 📌 Project Overview
This project aims to analyze customer churn in a telecommunications company using machine learning techniques. The goal is to identify key factors contributing to customer churn and build a predictive model to help the company retain customers.

## 📂 Dataset
The dataset used for this project contains customer information, including demographics, account details, and service usage. The key features include:

- **Customer ID**
- **Gender**
- **Senior Citizen (Yes/No)**
- **Partner (Yes/No)**
- **Dependents (Yes/No)**
- **Tenure (Months with the company)**
- **Phone Service (Yes/No)**
- **Multiple Lines (Yes/No/No phone service)**
- **Internet Service (DSL/Fiber optic/No)**
- **Online Security, Online Backup, Tech Support, Streaming Services**
- **Contract Type (Month-to-month/One year/Two year)**
- **Paperless Billing (Yes/No)**
- **Payment Method (Electronic check, Mailed check, etc.)**
- **Monthly Charges**
- **Total Charges**
- **Churn (Yes/No - Target Variable)**

## 🔧 Data Preprocessing
The following steps were performed to clean and prepare the data for modeling:

- Handling missing values in the **Total Charges** column.
- Encoding categorical variables using one-hot encoding and label encoding.
- Feature scaling using standardization.
- Exploratory Data Analysis (EDA) to understand churn trends and key customer behaviors.

## 📊 Exploratory Data Analysis (EDA)
Various visualizations and statistical analyses were conducted to extract insights, including:

- Churn distribution analysis.
- Correlation heatmaps to identify relationships between features.
- Bar plots and histograms for categorical and numerical feature analysis.
- Box plots to detect outliers in numerical data.

## 🤖 Machine Learning Models
Several machine learning models were trained and evaluated to predict customer churn:

1. **Logistic Regression**
2. **Random Forest Classifier**
3. **Gradient Boosting (XGBoost, LightGBM)**
4. **Support Vector Machine (SVM)**
5. **Neural Networks**

### 📈 Model Evaluation
The models were evaluated using various performance metrics:

- **Accuracy**
- **Precision, Recall, F1-score**
- **ROC-AUC Score**
- **Confusion Matrix**

## 🔍 Key Findings

- Customers with month-to-month contracts had the highest churn rates.
- Fiber optic internet users had a higher churn rate than DSL users.
- Customers with paperless billing and electronic payment methods were more likely to churn.
- Longer tenure customers were less likely to churn.
- Adding additional services like online security and tech support reduced churn probability.

## 🚀 Deployment
A final predictive model was deployed using **Flask** for creating a web application where users can input customer details and predict the likelihood of churn.

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning Algorithms** (Logistic Regression, Random Forest, XGBoost, etc.)
- **EDA & Data Visualization** (Seaborn, Matplotlib)
- **Flask** (for model deployment)
- **Jupyter Notebook**

## 🔮 Future Improvements

- Incorporate deep learning models (LSTMs) to improve predictions.
- Gather more data on customer interactions and complaints.
- Develop a real-time churn monitoring system.

## 🏁 Conclusion
The project successfully identified key factors influencing customer churn and built predictive models to assist the telecom company in reducing churn. The insights gained from the analysis can help improve customer retention strategies.

## 👨‍💻 Author
[Neel Adalja]

## 🎖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgment
Thanks to the open-source community and telecom datasets available for analysis.

