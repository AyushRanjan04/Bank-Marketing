# Bank Dataset Analysis Project

## Overview
This project involves analyzing a bank dataset to derive meaningful insights and answer various business-related questions. The dataset includes information about customers' demographics, financial behavior, and past interactions with the bank. The goal is to explore the data, perform statistical analysis, and improve decision-making processes.

## Dataset
The dataset contains the following columns:
- `age`: Age of the customer
- `job`: Job type of the customer
- `marital`: Marital status of the customer
- `education`: Education level of the customer
- `default`: Whether the customer has credit in default
- `balance`: Average yearly balance in euros
- `housing`: Whether the customer has a housing loan
- `loan`: Whether the customer has a personal loan
- `contact`: Contact communication type
- `day`: Last contact day of the month
- `month`: Last contact month of the year
- `duration`: Last contact duration in seconds
- `campaign`: Number of contacts performed during this campaign
- `pdays`: Number of days since the customer was last contacted from a previous campaign
- `previous`: Number of contacts performed before this campaign
- `poutcome`: Outcome of the previous marketing campaign
- `deposit`: Whether the customer subscribed to a term deposit

## Objectives
1. **Descriptive Analysis**: Understand the distribution and characteristics of the data.
2. **Customer Segmentation**: Segment customers based on their demographics and financial behavior.
3. **Campaign Analysis**: Evaluate the effectiveness of marketing campaigns and identify factors contributing to their success.

## Key Questions
1. What is the age distribution of the customers?
2. What are the most common job types among customers?
3. What is the distribution of marital status among customers?
4. What are the education levels of the customers?
5. What is the average account balance?
6. What percentage of customers have defaulted on their loans?
7. How many customers have housing loans?
8. How many customers have personal loans?
9. What are the most common methods of contact (phone, email, etc.)?
10. How many contacts were made during each campaign?
11. What is the success rate of each campaign in terms of deposits made?
12. What is the average account balance for each month?
13. What is the total account balance for customers in each job category?
14. For each marital status category, how many customers have taken a loan?

## Tools and Libraries
- **Python**: For data manipulation and analysis
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical computations
- **Matplotlib**: For data visualization
- **Seaborn**: For statistical data visualization
- **Scikit-learn**: For machine learning and predictive modeling
- **Statsmodels**: For statistical modeling
- **MS Excel**: For data analysis and visualization
- **SQL**: For database querying and manipulation
- **Power BI**: For interactive data visualization and business intelligence

## MS Excel Analysis
### Key Questions and Solutions:
1. **Calculate the average account balance**:
   ```excel
   =AVERAGE(D2:D100)
   ```
2. **Create a bar chart to show the distribution of job types**:
   - Select the job type column.
   - Go to `Insert` > `Bar Chart`.
3. **Use a pivot table to summarize the number of customers by marital status**:
   - Select your data range.
   - Go to `Insert` > `PivotTable`.
   - Drag `marital` to Rows and `customer ID` to Values.
4. **Filter the dataset to show only customers with housing loans**:
   - Use the filter option on the housing loan column.
5. **Sort the dataset by age in ascending order**:
   - Select the age column.
   - Go to `Data` > `Sort A to Z`.

## SQL Analysis
### Key Questions:
1. What is the age distribution of the customers?
2. What are the most common job types among customers?
3. What is the distribution of marital status among customers?
4. What are the education levels of the customers?
5. What is the average account balance?
6. What percentage of customers have defaulted on their loans?
7. How many customers have housing loans?
8. How many customers have personal loans?
9. What are the most common methods of contact (phone, email, etc.)?
10. How many contacts were made during each campaign?
11. What is the success rate of each campaign in terms of deposits made?
12. What is the average account balance for each month?
13. What is the total account balance for customers in each job category?
14. For each marital status category, how many customers have taken a loan?

### Advanced SQL Questions:
1. Using a CTE, find the average balance for each job category.
2. Using a CTE, calculate the total number of contacts made during each campaign.
3. Using a CTE, determine the percentage of customers with housing loans for each marital status.
4. Using a CTE, find the average duration of contact for customers who made a deposit.
5. Using `ROW_NUMBER()`, rank customers based on their account balance.
6. Using `RANK()`, find the rank of each customer within their job category based on balance.
7. Using `DENSE_RANK()`, determine the dense rank of customers based on the duration of contact.

## Power BI Analysis
### Key Questions:
1. Create a dashboard to visualize the age distribution of customers.
2. Create a bar chart to show the most common job types among customers.
3. Create a pie chart to show the distribution of marital status among customers.
4. Create a line chart to show the trend of account balances over different months.
5. Create a scatter plot to analyze the relationship between contact duration and the likelihood of a deposit.

### Steps to Create Visualizations:
1. **Import Data**:
   - Load your dataset into Power BI.
2. **Create Visualizations**:
   - Use the visualization pane to create charts and graphs.
3. **Build Dashboards**:
   - Combine multiple visualizations into a single dashboard for comprehensive analysis.
4. **Publish Reports**:
   - Share your reports and dashboards with stakeholders.

## Conclusion
This project aims to provide a comprehensive analysis of the bank dataset, uncovering valuable insights and building meaningful data to support business decisions. By understanding customer behavior and the effectiveness of marketing campaigns, the bank can improve its strategies and enhance customer satisfaction.
