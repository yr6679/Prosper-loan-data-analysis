# Propser Loan :bank: Data Exploration & Analysis :bar_chart:

## Dataset
The dataset used for this project is the **Prosper Loan Dataset**. The dataset contains data about the details of the various loans lent to the borrowers from Prosper. Each row in the dataset represents a loan, uniquely identified by the *Listing Key*.<br>
Various attributes about the Borrower such as Employment Status, Credit Score, etc. Every row also describes other parameters such as Monthly Payments, On Time Payments, Interest Rate, etc.

## Summary of Findings
The exploration of the dataset led to the discovery of the various attributes about the Borrower's in the Prosper Loan dataset:
* Califoria is the state with the Highest Number of Borrowers.
* Highest number of the loans taken by the Borrowers have been categorised as **Debt Consolidation**.
* The number of Borrowers who **Own & Dont Own** a Home are almost evenly distributed in the dataset.
* Majority of the portion of Borrowers are **Employed**.
* Majority of the Borrowers have an income between **3000 - 6000**.
* Majority of the Borrowers have a Credit Score between **650 - 750**.
* Most of the Borrowers have Prosper Scores between **4 - 8**, with the Most Commonly occurring Prosper Score being **4**.
* Most of the loans are given for a period of **36 Months/3 Years**.<br>


The exploration of the dataset, led to the identification of some interesting dependencies between the Borrower's Attributues and Loan Attributes. 
* Borrowers with **Higher Monthly Income** are assigned a **Higher Prosper Score**.
* Borrowers with **Prosper Score** higher than or equal to 8, are more likely to own a home, when compared to those with score less than or equal to 7. 
* **Employed** Borrowers take loans of **Higher Amounts** when compared to Borrower's who are Retired or Unemployed.
* **Unemployed** Borrowers are charged a **Higher Interest Rate** in comparison to **Employed and Retired** Borrowers.
* **Employed** Borrowers are assigned a **Higher Prosper Score**.
* The **Interest Rate** is Negatively Correlated with **Prosper Score**. Higher Prosper Score leads to Lower Interest Rates.
* The **Loan Amounts** given has constantly increased over the years.
* Higher **Loan Amount** also leads to a Higher **Loan Term**.
* The **Prosper Score** is Positively Correlated with **On-Time Monthly Payments**. The borrowers with Higher Prosper Scores are more likely to make On-Time Monthly Payments.
* A Higher **Credit Score** leads to a Higher **Prosper Score**.
* The **Estimated Loss** reduces with an increase in the Borrowers **Prosper Score**.
* Borrowers who have **Fewer Current Delinquencies** and **Higher On-Time Payments**, are more likely to have **Higher Number of Loans**.
* The **Estimated Loss** increase with the increase in **Interest Rate and Yield**.
