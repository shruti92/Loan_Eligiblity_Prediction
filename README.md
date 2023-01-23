# Loan_Eligiblity_Prediction

Loan_ID	--> Unique id for every loan request
Gender	--> Applicant's Gender
Married	--> Applicant's Marital status
Dependents --> How many people are dependednt on the Applicant in his/her family.
Education --> Applicant's Education
Self_Employed --> Whether the applicant is employed | Owner of business
ApplicantIncome	--> Applicant's Income on record
CoapplicantIncome --> CoApplicant's Income on record
LoanAmount --> Amount of Loan required
Loan_Amount_Term	--> Duration in which applicant wants to pay back the loan amount.
Credit_History --> Whether the candidate has good or bad credit history in past
Property_Area --> Type of locality of property which the candidate has given as mortage. The type tells us about property valuation. 


Problem Statement: 

A Company wants to automate the loan eligibility process based on customer details provided while filling online application form. The details filled by the customer are Gender, Marital Status, Education, Number of Dependents, Income of self and co applicant, Required Loan Amount, Required Loan Term, Credit History and others. The requirements are as follows:

1.)Check eligibility of the Customer given the inputs described above.(Classification)
2.)Identify customer segments from given data and categorize customer into one of the segments.(Clustering)
3.)If customer is not eligible for the input required amount and duration:
a.)what can be amount for the given duration.(Regression)
b.)if duration is less than equal to 20 years, is customer eligible for required amount for some longer duration? What is that duration?(Regression)
