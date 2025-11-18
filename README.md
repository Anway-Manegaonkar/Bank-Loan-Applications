# Bank-Loan-Applications
This project focuses on cleaning and analyzing a 25,000-record bank loan dataset using Python, Pandas, and Matplotlib.

Overview:
This project focuses on cleaning and analysing a 25,000-record bank loan dataset using Python, Pandas, and Matplotlib. The dataset contained multiple real-world issues like missing values, incorrect formats, inconsistent categories, and invalid numeric entries.
The goal was to clean the data end-to-end, exploring important patterns, and prepare insights.

Dataset:
The dataset includes the following key fields:
•	Application_ID
•	Gender, Age, Education, Marital_Status
•	Employment_Type
•	Monthly_Income
•	Loan_Amount
•	Loan_Term
•	Credit_Score
•	Existing_Debt
•	Approval_Status
•	Application_Date

Data Issues Identified:
•	Mixed casing and extra spaces
•	Messy numeric values (commas, strings like “50k”)
•	Invalid ages & credit scores
•	Missing values across multiple columns
•	Invalid or missing dates

Tools Used:
•	Python
o	Pandas
o	NumPy
o	Matplotlib
•	Jupyter Notebook
•	Gamma App (for creating a clean summary PPT)

Steps Performed:
Data Loading
•	Loaded the CSV file using Pandas
•	Converted date columns to datetime format
•	Performed initial inspection of data shape, types, and missing values

Data Cleaning
•	Standardized categorical fields (gender, education, marital status, employment type)
•	Removed commas & converted messy numeric values into proper numbers
•	Fixed invalid ages (<18 or >100) and credit scores (<300 or >850)
•	Cleaned loan term and existing debt
•	Handled missing values:
o	Numeric columns → median
o	Categorical columns → mode
•	Filled missing Application_ID and Application_Date
•	Ensured all columns were properly cleaned and consistent

Feature Engineering:
•	Created an EMI field using a simple interest formula

Exploratory Analysis:
Created clear and simple visualizations using Matplotlib:
•	Monthly income distribution
•	Loan amount distribution
•	Credit score boxplot
•	Loan approval count
•	Approval rate by employment type

Results & Insights:
Some key findings from the cleaned dataset:
•	68% of applicants earn between ₹20k–₹60k
•	55% of loan applications are rejected
•	Salaried applicants show ~20% higher approval rate than self-employed applicants
•	70% of credit scores lie between 550 and 750
•	The fully cleaned dataset had zero missing values and standardized categories

Skills Demonstrated:
•	Data Cleaning (beginner–intermediate Pandas)
•	Handling missing values & invalid formats
•	Feature engineering
•	Exploratory data analysis
•	Visualization with Matplotlib
•	Presentation building using Gamma

How to Run the Project:
1. Install required libraries
pip install pandas NumPy matplotlib
2. Open Jupyter Notebook
jupyter notebook
3. Run the notebook
•	Load the dataset
•	Execute each cell step-by-step
•	Review visualizations & insights
4. View Presentation
•	Open the Gamma-generated PPT in the “presentation” folder
