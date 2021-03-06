# AttritionAnalysis
Analyze the attrition rate of a leading BPO company.

Employee attrition is a major problem in the Business Process Outsourcing(BPO) industry. Attrition is defined as the 
reduction in the workforce(headcount) due to any reason like retirement, resignation or death.  In this project, we will 
analyze the data for a leading BPO company and utilize statistical tools and models.

Dataset:Attrition analysis.csv. 
No. of variables: 5
Variables descriptioin: Employee ID(type: continuous), Retain_Indicator(Binary,  0=Employee retained,1=Employee left, Sex_Indicator(Binary, 0=Male,1=Female),Relocation_indicator(Binary, 0=relocation is reason to resign, 1 =relocation 				 is not the reason to resign),Marital Status(Binary,0=Married, 1=Unmarried)
Dependent Variable:	Retain_Indicator (Binary)  , 0 indicates employee retained and 1 indicates employee left.
Business solution: 		 To build a Binomial Logistic Regression model 



Post implementation of the Logistic Regression model, the result obtained is in the file saved as LogisticRegression.pdf.

Here are the conclusions that we can derive:

The p-value below 0.05 was for the variable ‘Employee_ID’
Hence, ‘Employee_ID’ is the significant variable in the dataset.
The slope of the significant variable ‘Employee_ID’ is 0.0443
Hence, we can conclude that 1 unit of increase in Employee_ID increases the log odds of employee 
retention by 0.04.
The Cstatistic value for the model is 70.9%.  
