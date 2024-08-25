# 📊 Credit Card and Customer Data Analysis

## 🎯 Project Objective
The objective of this project is to perform an in-depth analysis of credit card and customer data to derive actionable insights. This includes examining credit card usage, customer satisfaction, and various demographic factors. The analysis combines data from credit card transactions and customer profiles to provide a comprehensive view of customer behavior and financial patterns.

## Data Sources
- **Credit Card Data**: Contains detailed information on credit card transactions and usage.
- **Customer Data**: Provides demographic and personal details of customers.

---

## 🗂 Dataset Overview

### Credit Card Data
The dataset contains the following columns:

| Column Name              | Description                                           |
|--------------------------|-------------------------------------------------------|
| **Client_Num**           | Unique identifier for each client                    |
| **Card_Category**        | Category of the credit card (e.g., Blue, Gold, etc.) |
| **Annual_Fees**          | Annual fees charged for the credit card              |
| **Activation_30_Days**   | Indicator of activation within 30 days               |
| **Customer_Acq_Cost**    | Cost of acquiring the customer                       |
| **Week_Start_Date**      | Start date of the week for the transaction           |
| **Week_Num**             | Week number of the transaction                       |
| **Qtr**                  | Quarter of the year for the transaction              |
| **current_year**         | Current year of the transaction                      |
| **Credit_Limit**         | Credit limit for the card                            |
| **Total_Revolving_Bal**  | Total revolving balance on the card                  |
| **Total_Trans_Amt**      | Total transaction amount                            |
| **Total_Trans_Vol**      | Total transaction volume                            |
| **Avg_Utilization_Ratio**| Average utilization ratio of the credit card         |
| **Use Chip**             | Indicator if a chip is used for the card             |
| **Exp Type**             | Type of expenditure on the card                      |
| **Interest_Earned**      | Interest earned on the credit card                   |
| **Delinquent_Acc**       | Number of delinquent accounts                        |

### Customer Data
The dataset includes the following columns:

| Column Name               | Description                                           |
|---------------------------|-------------------------------------------------------|
| **Client_Num**            | Unique identifier for each client                    |
| **Customer_Age**          | Age of the customer                                  |
| **Gender**                | Gender of the customer                               |
| **Dependent_Count**       | Number of dependents                                 |
| **Education_Level**       | Education level of the customer                      |
| **Marital_Status**        | Marital status of the customer                       |
| **state_cd**              | State code of the customer                           |
| **Zipcode**               | Zipcode of the customer                              |
| **Car_Owner**             | Indicator if the customer owns a car                 |
| **House_Owner**           | Indicator if the customer owns a house               |
| **Personal_loan**         | Indicator if the customer has a personal loan        |
| **contact**               | Contact information of the customer                 |
| **Customer_Job**          | Job title of the customer                            |
| **Income**                | Income of the customer                               |
| **Cust_Satisfaction_Score**| Customer satisfaction score                         |

---

## 🛠 Tools Used
- **SQL**: For querying and data analysis
- **Python**: For data manipulation and visualization
- **Pandas**: Data processing and manipulation
- **Seaborn & Matplotlib**: Data visualization libraries

---

## 📈 Analysis and Findings

### 1. 🎓 Average Credit Limit by Education Level
- **Finding**: Customers with "Uneducated" and "Graduate" backgrounds tend to have higher average credit limits compared to other education levels.

### 2. 💼 Credit Card Usage by Customer Job Type
- **Finding**: Businessmen and white-collar workers show higher total transaction amounts and volumes compared to other job types.

### 3. 👫 Gender Distribution in Credit Card Categories
- **Finding**: Both genders have a higher preference for "Blue" cards, with female customers showing higher counts in the "Blue" and "Silver" categories compared to males.

### 4. 🏠 House Ownership and Credit Utilization
- **Finding**: House ownership has a marginal effect on credit utilization, with house owners showing a slightly higher utilization ratio.

### 5. 💳 Credit Limit by Personal Loan Status
- **Finding**: Customers with a personal loan have a slightly lower average credit limit compared to those without.

### 6. 🚨 Delinquency Rate by Income
- **Finding**: Delinquency rates vary by income, with higher incomes showing increased delinquency rates.

### 7. 🌟 Customer Satisfaction and Credit Card Features
- **Finding**: Satisfaction varies by card category, with "Silver" cards showing the highest average satisfaction.
### 8. 📈 Activation Rate and Credit Limit
Examines the relationship between credit limit and activation rate within 30 days.
- **Findings**: Higher credit limits generally lead to a higher activation rate within 30 days. Specifically:
  - For a credit limit of 1438.3, the activation rate is 58.42%.
  - For a credit limit of 1440.0, the activation rate is 100%.
  - Lower credit limits or a credit limit of 1439.0 result in lower or zero activation rates.
- **Implication**: Offering higher credit limits may incentivize quicker activation of credit cards, potentially increasing customer engagement.

  ### 9. 👴 Credit Card Category Distribution Across Age Groups
Analyzes the distribution of credit card categories among different age groups.
- **Findings**: 
  - The "Blue" card is most popular across all age groups, with the highest usage among ages 36-45 and 46-55.
  - "Gold" and "Platinum" cards are less common, with "Gold" being used slightly more by older age groups.
  - "Silver" cards are used less frequently but still present in all age groups.
- **Implication**: Credit card companies might focus marketing "Blue" cards to younger and middle-aged clients while offering "Gold" and "Platinum" options to older clients.

### 10. 🗺️ State-wise Credit Card Usage
Breaks down credit card usage metrics by state.
- **Findings**:
  - States like TX, NY, and CA have the highest total transaction amounts and volumes, indicating high credit card usage.
  - States with lower transaction amounts include AR, HI, and OR.
- **Implication**: Marketing and promotional strategies may need to be tailored based on state-specific usage patterns to maximize impact.

### 11. 👩‍🎓 Average Customer Satisfaction Score by Gender
Analyzes average customer satisfaction scores by gender.
- **Findings**:
  - Female customers have a slightly higher average satisfaction score (3.20) compared to male customers (3.18).
- **Implication**: Gender-specific factors might influence customer satisfaction, and tailored approaches could enhance overall satisfaction levels.

### 12. 📚 Average Customer Satisfaction Score by Education Level
Examines satisfaction scores across different education levels.
- **Findings**:
  - "High School" graduates have the highest average satisfaction score (3.24).
  - "Doctorate" holders have the lowest average satisfaction score (3.13).
  - The scores vary slightly but are generally close across different education levels.
- **Implication**: Educational background has a modest impact on customer satisfaction, which could guide targeted improvements in service delivery.
---

## 💡 Recommendations
- **Credit Limit Management**: Consider the impact of education and job type when setting credit limits.
- **Customer Segmentation**: Tailor marketing strategies based on job type and card preferences.
- **Financial Strategies**: Monitor delinquency rates and credit utilization to adjust financial strategies.

---

**George Zacharia**



---

## 📝 Conclusion
This comprehensive analysis provides valuable insights into credit card usage and customer behavior. By examining various factors such as education level, job type, and satisfaction scores, we can derive actionable recommendations for improving customer engagement and financial strategies.

---

**George Zacharia**
