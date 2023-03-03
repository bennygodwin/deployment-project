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
### Step 1 Data Exploration
* Basic data exploration to make some inferences about the data
* Figure out some irregularities
* Address missing values
* Performed some basic statistics for numerical variables
* Measured the distribution of various variables using histogram & box plots
### Step 2 Data Cleaning
* This step typically involves imputing missing values and treating outliers. 
* Imputing Missing Values
* Used a log transformation to get rid of the extreme values
### Step 3 Building a Predictive Model
* Logistic Regression showed an Accuracy of 78.378%
* Later, paramater grid search was used to improve the results
* The Best parameters:  {'max_depth': 3, 'min_samples_leaf': 4, 'min_samples_split': 2, 'n_estimators': 100} Best score was observed to be at 0.8204651162790698
### Step 4 Using Pipeline
* Pipeline was created to take one row of the dataset and predict the probability of being granted a loan.
### Step 5 Deploying ML 
* Machine learning model was deployed using Flask

## Results/Demo
Initially, the Logistic Regression model achieved an accuracy of 78.378%. However, to further improve the results, a parameter grid search was performed. The grid search identified the best parameters for the model to be 'max_depth': 3, 'min_samples_leaf': 4, 'min_samples_split': 2, 'n_estimators': 100. With these parameters, the best score observed was 0.8204651162790698.

## Challanges 
Several challenges were encountered while developing a machine learning model for automating loan approval processes. Such as:
* Bias in the data
* Missing or incomplete data
* Overfitting

## Future Goals
Maintaining the model is crucial as it needs to be continuously monitored and updated to ensure that it provides accurate predictions. This process can be demanding in terms of time and resources, as it requires consistent investment in data collection, model updates, and performance monitoring.