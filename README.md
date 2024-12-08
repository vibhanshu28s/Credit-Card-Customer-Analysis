**Credit Card Customer Churn Analysis**


**Overview**
  This project focuses on analyzing a dataset of credit card customers to understand customer demographics, segment customers, and predict customer churn. The analysis    includes preprocessing, exploratory data analysis (EDA), customer segmentation using clustering, and churn prediction using machine learning models.


**Key Objectives**
  Analyze customer demographics and their relationship with credit card usage.
  Segment customers based on demographic and usage patterns.
  Predict customer churn using multiple machine learning models.
  Provide actionable insights for targeted marketing strategies.


**Dataset**
  The dataset used for this analysis is Credit Card Customers, containing information about customer demographics, credit card usage, and churn status.

**Key Features:**
  Customer_Age, Gender, Marital_Status.
  Credit_Limit, Total_Trans_Amt, Avg_Utilization_Ratio.
  Attrition_Flag (Target Variable: Churn Status).



**How to Run the Project**

  1. Clone the Repository.
  2. Install Dependencies. Ensure you have Python 3.8+ installed. Install the required libraries.
  3. Execute the Scripts.
  4. View Outputs.

**Findings and Insights**

  **Demographics Analysis**
  Customer Age: Majority of customers are between 30–50 years old.
  Marital Status: The largest group is married individuals (~50%).
  
  **Segmentation**
  Customers were segmented into 3 clusters:
  **High-Value Customers**: High credit limit, high transaction amounts.
  **Moderate Users**: Average credit limit and transaction volume.
  **Low-Value Customers**: Low credit utilization and transactional activity.
  Churn Prediction
  
  **Models Used:**
  **Logistic Regression**: Simple and interpretable.
  **Random Forest**: Highly accurate with complex feature interactions.
  **MultinomialNB**: Effective after preprocessing but less robust for continuous features.
  **Performance**: Random Forest outperformed others with perfect scores.

**Actionable Insights**
  Focus retention efforts on Cluster 3 customers, as they are most likely to churn.
  Offer personalized rewards to High-Value Customers (Cluster 1) to maintain loyalty.
  Monitor usage patterns to predict potential churn proactively.
