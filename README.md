# Predicting Churn in a Telecom Company

## Project Overview
This project focuses on predicting customer churn in a telecom company using machine learning models. Churn prediction helps businesses retain customers by identifying high-risk customers and implementing targeted retention strategies. 

## Team Members
- **Jasvitha Vatsavaya**
- **Manasa Ramaka**
- **Sai Abhinav Mullapudi**
- **Vaikhari Tushar Kadam**

## Dataset
The project utilizes the **Telco Customer Churn** dataset, which contains customer demographics, account details, and service usage information for 7,043 telecom customers in California. The target variable is `Churn`, indicating whether a customer left the company.

## Features Used
Key features in the dataset include:
- **Customer Demographics**: Gender, Senior Citizen, Partner, Dependents
- **Service Subscriptions**: Phone Service, Multiple Lines, Internet Service, Streaming Services
- **Account Information**: Contract Type, Monthly Charges, Total Charges, Payment Method
- **Custom Features**: Total Services used, Monthly Charge Difference

## Methodology
The project follows a structured approach:
1. **Data Preprocessing & Feature Engineering**  
   - Converted categorical variables into numerical representations  
   - Created new features such as `Total Services` and `Monthly Charge Difference`  

2. **Modeling & Evaluation**  
   Several models were trained and evaluated based on their predictive performance:
   - **Logistic Regression**
   - **Decision Tree**
   - **Boosted Tree**
   - **Neural Network**
   - **Naïve Bayes**
   
   Models were compared using **AUC (Area Under Curve)** and **misclassification rates**. The **Neural Network model** achieved the highest validation AUC of **0.8426**, making it the best-performing model.

## Business Impact
Churn prediction allows telecom companies to:
- Identify high-risk customers early
- Implement targeted retention strategies such as customized plans and discounts
- Optimize marketing efforts to reduce acquisition costs
- Improve customer satisfaction and long-term loyalty

## Deployment
The model is designed for deployment in a telecom company’s CRM system, enabling:
- **Customer Segmentation**: Categorizing customers based on churn risk
- **Real-Time Insights**: Interactive dashboards for monitoring churn trends
- **Automation**: Integration with marketing campaigns for personalized retention strategies

## Tools & Technologies Used
- **Python (Pandas, NumPy, Scikit-learn, TensorFlow)**
- **JMP Predictive Modeling**
- **Tableau (Data Visualization)**
- **Flask (for potential deployment)**

## Ethical Considerations
- Ensuring fairness by auditing for bias in customer demographics
- Adhering to data privacy regulations (GDPR, CCPA)
- Providing transparency in churn predictions to business stakeholders

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telecom-churn-prediction.git
