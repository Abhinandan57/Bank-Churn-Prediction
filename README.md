<h2 style="color:red">About the Repository</h2>

Bank Churn Prediction is a **Binary Classification** problem. The required data for this problem is collected from Kaggle (https://www.kaggle.com/competitions/playground-series-s4e1/data). As a part of the solution of this problem statement, I have created multiple machine learning models. As the dataset is imbalanced, I have taken the help of SMOTE technique for oversampling. Each model is created after performing Exploratory Data Analysis (EDA), Data Preprocessing & Hyperparameter Tuning. And at the end the model performance is evaluated individually.

I have created this repository basically to explore different machine learning algorithms & implement my knowledge, and skill on binary classification problem statement, in separate files. 🧐 Modular programming structure is not followed here. In my future repositories for specific projects, I will follow modular programming structure. 👍

The details of the dataset, task & model evaluation criteria are provided below:

<h2 style="color:red">Description</h2>

The bank customer churn dataset is a commonly used dataset for predicting customer churn in the banking industry. It contains information on bank customers who either left the bank or continue to be a customer. The dataset includes the following attributes:

1. `id`: A unique identifier for a record
2. `CustomerId`: A unique identifier for each customer
3. `Surname`: The customer's surname or last name
4. `CreditScore`: A numerical value representing the customer's credit score
5. `Geography`: The country where the customer resides (France, Spain or Germany)
6. `Gender`: The customer's gender (Male or Female)
7. `Age`: The customer's age
8. `Tenure`: The number of years the customer has been with the bank
9. `Balance`: The customer's account balance
10. `NumOfProducts`: The number of bank products the customer uses (e.g., savings account, credit card)
11. `HasCrCard`: Whether the customer has a credit card (1=yes, 0=no)
12. `IsActiveMember`: Whether the customer is an active member (1=yes, 0=no)
13. `EstimatedSalary`: The estimated salary of the customer
14. `Exited`: Whether the customer has churned (1=yes, 0=no)

<h2 style="color:red">Task</h2>

Predict whether a customer continues with their account or closes it (e.g., churns).

<h2 style="color:red">Evaluation Metric</h2>

Submissions are evaluated on `area under the ROC curve` between the predicted probability and the observed target.

