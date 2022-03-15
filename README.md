# Data-Cleaning-With-Python

# Introduction:

Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. When combining multiple data sources, there are many opportunities for data to be duplicated or mislabeled. If data is incorrect, outcomes and algorithms are unreliable, even though they may look correct. There is no one absolute way to prescribe the exact steps in the data cleaning process because the processes will vary from dataset to dataset. But it is crucial to establish a template for your data cleaning process so you know you are doing it the right way every time. (Source: https://www.tableau.com/learn/articles/what-is-data-cleaning).


# I conducted data cleaning on a data set that I took from the Kaggle Website. The data set is Telco Customer Churn. 
This data contains information on Telco company customers in the form of services taken by each customer and their churn status in the last month. 


# Goal:

Before the data is analyzed and modeling is carried out, it is necessary to check first to find out if there are parts of the data that need to be cleaned or fixed so that the data can be used in the next step. 
So the purpose of this project is to get clean data and know the characteristics of clean and ready to use data.

# Data Understanding:

In this data set there are 21 columns with the following information:

* Customer ID : Contains customer ID number, consist of 7043 unique value
* Gender : Whether the customer is a male of a female
* Senior Citizen : Whether the customer is a senior citizen or not.
* Partner : Whether the customer has a partner or not
* Dependents : Whether the customer has dependents or not
* Tenure : Number of months the customer has stayed with the company
* Phone Service : Whether the customer has a phone service or not
* Multiple Lines : Whether the customer has multiple lines or not
* Internet Service : Customer’s internet service provider (DSL, Fiber optic, No)
* Online Security : Whether the customer has online security or not (Yes, No, No Internet   Service)
* Online Backup : Whether the customer has online backup or not (Yes, No, No Internet Service)
* Device Protection : Whether the customer has device protection or not (Yes, No, No Internet Service)
* Tech Support : Whether the customer has tech support or not (Yes, No, No internet service)
* StreamingTV : Whether the customer has streaming TV or not (Yes, No, No internet service)
* StreamingMovies : Whether the customer has streaming movies or not (Yes, No, No internet service)
* Contract : The contract term of the customer (Month-to-month, One year, Two year)
* PaperlessBilling : Whether the customer has paperless billing or not (Yes, No)
* PaymentMethod : The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
* MonthlyCharges : The amount charged to the customer monthly
* TotalCharges : The total amount charged to the customer
* Churn : Whether the customer churned or not (Yes or No)

# Data preparation:

- Code used:
  * Python Version : 3.7.12
  * Packages : Pandas, Numpy.
  
- Datasets: https://drive.google.com/file/d/12lsTf3c1trd_CEAJPSlWdQNfW8lrykkb/view?usp=sharing

# Inspection steps:

* Display the first, last and random 5 rows.
* Display the data frame information : number of rows, column name & type, number of missing rows per column, memory usage.
* Display each unique value in each column and the number of each unique value.
* Display duplicate data.

# Inspection results:    
* It was found that the data type in the Total Charges column did not match, it should have been an integer, but the data type obtained was object.

  <img src= "https://user-images.githubusercontent.com/97079280/158359643-cd728839-9377-4c4e-a2d5-a4b6e898a6cc.jpeg" width="500">
  
* There is a missing value in 11 rows in the Total Charges column.

  <img src= "https://user-images.githubusercontent.com/97079280/158359810-ef9d85cf-1606-4f9e-a4d6-6f34f8258e6b.jpeg" width="500">
  
* No duplicated rows found.

# Steps in the data cleaning process:

* Change the data type of the Total Charges column with the appropriate data type.
* Perform imputation of the missing value in the Total Charges column.
 



  
  




 






