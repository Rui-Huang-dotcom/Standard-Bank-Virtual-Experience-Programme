# Standard Bank Virtual Experience

## 📝 Overview
Standard Bank is embracing the digital transformation wave and intends to use new and exciting technologies to give their customers a complete set of services from the convenience of their mobile devices. As Africa’s biggest lender by assets, the bank aims to improve the current process in which potential borrowers apply for a home loan. The current process involves loan officers having to manually process home loan applications. This process takes 2 to 3 days to process upon which the applicant will receive communication on whether or not they have been granted the loan for the requested amount. To improve the process Standard Bank wants to make use of machine learning to assess the credit worthiness of an applicant by implementing a model that will predict if the potential borrower will default on his/her loan or not, and do this such that the applicant receives a response immediately after completing their application.


##  👨‍💻 Analysis 
### 1. EDA
1. An overview of the data. (HINT: Provide the number of records, fields and their data types. Do for both).

Train datset has 614 records and 13 colums, test datset has 366 records and 12 colums. Data types include float, int and object.

2. What data quality issues exist in both train and test? (HINT: Comment any missing values and duplicates)

Both train and test dataset have missing values while no duplicates.

3. How do the the loan statuses compare? i.e. what is the distrubition of each?

'Y' accounts for 67.7% and 'N' accounts for 31.3%.

4. How do women and men compare when it comes to defaulting on loans in the historical dataset?

The number of default loan or not for women is 75 and 37, for men is 339 and 150.

5. How many of the loan applicants have dependents based on the historical dataset?

269

6. How do the incomes of those who are employed compare to those who are self employed based on the historical dataset? 

![](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/image/1.png) 

7. Are applicants with a credit history more likely to default than those who do not have one?

![](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/image/2.png) 

8. Is there a correlation between the applicant's income and the loan amount they applied for? 

![](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/image/__results___47_1.png)

There's a positive correlation between the applicant's income and the loan amount.
### 2. Data Visualation

Here are a visual:

![Tableau Dashboard](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/Dashboard%201.png)

*Interactive dashboard please see in Tableau Dashboard [Loan Dashboard](https://public.tableau.com/app/profile/rui.huang7025/viz/LoanDashboard_17018580855110/Dashboard1).*

### 3. Data Modelling

![](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/image/3.png) 

### 4. Hypothesis Testing

![](https://github.com/Rui-Huang-dotcom/Standard-Bank-Virtual-Experience-Programme/blob/main/image/4.png) 


