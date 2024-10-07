
# Loan Data Analysis

This project involves analyzing a loan dataset to derive meaningful insights and visualizations. The analysis explores various factors affecting loan approval, interest rates, credit scores, and more. By combining data processing techniques with statistical analysis, the goal is to uncover patterns that can help in making informed decisions regarding loan management and risk assessment.

**The dataset contains information about various loans, including details such as:**

ApplicationDate: object

Age: int64

AnnualIncome: int64

CreditScore: int64

EmploymentStatus: object

EducationLevel: object

Experience: int64

LoanAmount: int64

LoanDuration: int64

MaritalStatus: object

NumberOfDependents: int64

HomeOwnershipStatus: object

MonthlyDebtPayments: int64

CreditCardUtilizationRate: float64

NumberOfOpenCreditLines: int64

NumberOfCreditInquiries: int64

DebtToIncomeRatio: float64

BankruptcyHistory: int64

LoanPurpose: object

PreviousLoanDefaults: int64

PaymentHistory: int64

LengthOfCreditHistory: int64

SavingsAccountBalance: int64

CheckingAccountBalance: int64

TotalAssets: int64

TotalLiabilities: int64

MonthlyIncome: float64

UtilityBillsPaymentHistory: float64

JobTenure: int64

NetWorth: int64

BaseInterestRate: float64

InterestRate: float64

MonthlyLoanPayment: float64

TotalDebtToIncomeRatio: float64

LoanApproved: int64

RiskScore: float64



**Key Analyses and Visualizations**
1. Data Cleaning and handling null vaalues
2. pivot table: that shows the average LoanAmount for different EmploymentStatus and EducationLevel groups and combination of MaritalStatus and RiskScore
3. Apply Function: * use the apply() function to categorize individuals as "High Income" or "Low Income" based on whether their AnnualIncome is above or below the median income.
*How can you apply a function to calculate the difference between InterestRate and BaseInterestRate for each row and add it as a new column called RateDifference? ​​
4. What is the total loan amount for each loan purpose?, Visualize the total loan amount for different loan purposes using a bar chart.
5. Create a scatter plot showing the relationship between Age and LoanAmount. Color the points based on the LoanApproved status
6. plot a pie chart for EmploymentStatus showing the percentages of loan approval (1) and loan rejection (0)
7. Create a line plot showing the trend of average InterestRate over increasing LoanDuration. Add error bars to indicate the standard deviation at each point.
8. What is the distribution of borrower ages in the loan dataset, and how does it look when visualized using a histogram with a KDE (Kernel Density Estimate) overlay?

**Technologies Used**

Python: For data processing, analysis, and visualization.

Pandas: Data manipulation and preparation.

Matplotlib & Seaborn: For creating visualizations such as scatter plots, violin plots, boxplots, and heatmaps.

Google Collab: For interactive data exploration and visualization.
