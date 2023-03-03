# Mini-project IV

### [Assignment](assignment.md)

## Project/Goals
The business problem related to loan approval automation process using machine learning is that traditional loan approval processes often rely on manual reviews of applicant data, which can be time-consuming and error-prone. Machine learning can help to automate the loan approval process by analyzing large amounts of data and identifying patterns and relationships that can be used to make loan decisions more accurately and efficiently. However, developing and implementing a machine learning-based loan approval system can be complex and requires careful data integration, model development, and testing. There is also a risk of bias in machine learning algorithms, which must be carefully monitored and mitigated to ensure fair and ethical lending practices. Despite these challenges, machine learning has the potential to significantly improve the loan approval process by reducing processing times, increasing accuracy, and improving customer experience.

## Hypothesis
Hypothesis generation involves identifying all possible factors that could impact the outcome, such as the likelihood of loan approval. Proposed research hypotheses are:
* Education: Applicants with a higher level of education, such as a graduate degree, may have a greater chance of being approved for a loan.
* Income: Applicants with a higher income may be more likely to be approved for a loan.
* Loan amount: Applicants requesting a smaller loan amount may have a higher probability of being approved.
* Loan term: Loans with shorter terms may be more likely to be approved.
* Credit history: Applicants who have a history of repaying their debts on time may have a higher likelihood of being approved for a loan.
* Monthly installment amount: Applicants with a lower monthly installment amount may have a higher probability of being approved for a loan.

## EDA 
The train set contains 614 rows and 13 columns of features. The features in the test set are similar to those in the train set, except for the Loan_Status variable, which we aim to predict using the model built on the train data. We will use Python to explore and analyze the data, utilizing various visualization techniques to summarize the main characteristics of the features and target variable.

The dataset includes variables in different formats:
* Object: Variables in object format are categorical variables. Examples of categorical variables in our dataset include Loan_ID, Gender, Married, Dependents, Education, Self_Employed, Property_Area, and Loan_Status.
* Int64: Int64 format represents integer variables. An example of an integer variable in our dataset is ApplicantIncome.
* Float64: Float64 format represents variables with decimal values, which are also numerical variables. Examples of numerical variables in our dataset include CoapplicantIncome, LoanAmount, Loan_Amount_Term, and Credit_History.


## Process
(fill in what you did during EDA, cleaning, feature engineering, modeling, deployment, testing)
### (your step 1)
### (your step 2)

## Results/Demo
(fill in your model's performance, details about the API you created, and (optional) a link to an live demo)

## Challanges 
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time? are there any potential issues/biases with your model/use case?)