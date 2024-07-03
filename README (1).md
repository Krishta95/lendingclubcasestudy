# Lending Club Case Study
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 




## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
		This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
		Borrowers can easily access lower interest rate loans through a fast online interface. 

- What is the background of your project?
		Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
		Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 
		In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
I
- What is the business probem that your project is trying to solve?
		The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  
		The company can utilise this knowledge for its portfolio and risk assessment. 

- What is the dataset that is being used?
		The loan.csv dataset and the Data_Dictionary.xlsx files are used as the datasets

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Ordered Categorical Variables

	Grade : 
		Univariate result : Grade B gets charged off the most     
		Bivariate result : Loan Grade B is defaulted the most followed by C

	Subgrade : 
		Univariate result : Subgrade B2 is charged off the most followed by C4, C5 and C1    
		Bivariate result : Grade B5 is charged off the most followed by C1, B3 and B4

	Term :
		Univariate result : 36 month loans get defaulted the most   
		Bivariate result : The ratio of 60 month loans getting defaulted are higher

	Employment Length : 
		Univariate result : Employees with 10 years and more experience tend to default the most        
		Bivariate result : Employees having experience of 10 years tend to take the most loans and default more than the others

	Year : 
		Univariate result : 2011 may have economic factors due to which the charged off loans are more      
		Bivariate result : The number of loan applicants increased in 2011 indicating increased economic activity
		
	Quarter : 
		Univariate result : Q4 takes the highest number of loans mostly due to december holiday season
        Bivariate result : Q4 takes the highest number of loans mostly due to december holiday season


Unordered Categorical Variables

	State : 
		Univariate result : Arizona contributes the most defaulters    
		Bivariate result : California shows the highest percent of defaulters floowed by Florida and New York

	Home Ownnership : 
		Univariate result : Rental owners default the most
		Bivariate result : Rental and mortgage owners tend to default more on loans due to other payments like other mortgages and rent.

	Purpose : 
		Univariate result : Credit card loans has the highest number of defaulters with 17500 defaulters
		Bivariate result : Debt consolidation loans are the most defaulted, as the user takes loans to pay off previous loans causing cash flow issues.
							Recomendation is to stringently assess loans for debt consolidation


Quantitative Variables 

	Loan Amount : 
		Univariate result : Mid size loans of 5 - 10k are the most defaulted
		Bivariate result : Mid size loans of 5 - 10k are the most in demand but the ratio of defaulters is more in the 15k and above list.
							Recomendation is to stringently assess loans for higher amounts
							
	Annual Income : 
		Univariate result : People with the lower income bucket of 0 - 50k are more likely to default   
		Bivariate result : People with the lower income bucket of 0 - 40k are more likely to default due to low cashflow and repayment capacity.

	Installments : 
		Most of the installments are around $270. Installments of around 160 to 400 are more likely to default.

	DTI :
		Univariate result : Highest and the lowest DTIs are more likely to default, but no strong correlation observed.
		Bivariate result : Very low DTI is most common, but no strong correlation with charged off debts observed.

	Interest Rate : 
		Univariate result : Higher defaults are seen in 11 - 15% interest rates
		Bivariate result : The highest interest rate is uncommon but has the highest ration of defaults. The interest rate is optimal between 6 - 10%

	Funded amount : 
		Univariate result : Lower funded amounts tend to be defaulted more
		Bivariate result : Higher funded amounts have a slighly higher ration of defaulting


Correlation analysis : 

	DTI has the lowest correlation. also observed in bivariate analysis point 2.3.4 a and 2.3.4 b
	Employment length and term have weak correlations too
	Loan amt, funded amt and installment values have the highest correlation
	Annual income has a negative correlation with dti
	The lowest (Negative) correlation is observed between loan amount and derogatory public records

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.3.9
- pandas - version 1.5.3
- numpy - version 1.24.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the EDA module tutorials of the Upgrad AI and ML program
- References if any...
- This project was based on EDA module tutorials of the Upgrad AI and ML program.


## Contact
Created by @siddharthr193 and @Krishta95 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->