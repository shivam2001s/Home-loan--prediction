# Home-loan--prediction

Project Explanation
Data Collection
The dataset is collected from Kaggle.
The dataset which we get from kaggle consists of two CSV(Comma Separated Values) files.
One is Train Data (loan_sanction_train.csv)
Another is Test Data (loan_sanction_test.csv)
Loading the collected data

The CSV data is loaded with the help of read_csv method in pandas library.
# TODO : To Load previous applicants loan application data
test= pd.read_csv('/content/loan_sanction_test.csv')
train= pd.read_csv('/content/loan_sanction_train.csv')
The Training data consists of 614 applicant samples and 12 features.
The 12 features are Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicanIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History and Property Area.

Dependents

The Dependents feature is a discrete kind of quantitative data.
From my thought, dependents feature refer to the number of children of applicant.
For 15 applicants, Dependents is not mentioned in the data.

![image](https://github.com/shivam2001s/Home-loan--prediction/assets/136186606/c7324bb8-f260-407f-8974-808bbc46a1df)

![image](https://github.com/shivam2001s/Home-loan--prediction/assets/136186606/4389b46a-b754-4138-b4ff-12abf19d8cbb)

There are 4 unique values present in this feature. They are 0, 1, 2, and 3+
