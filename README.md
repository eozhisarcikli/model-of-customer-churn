# Which customers may churn?

Customer churn means whether an existing customer, user, player, subscriber or any kind of return client stops doing business or ends the relationship with a company. 
Aim is to create a classifier which can predict(based on previous info) churn probability of a customer.

A data from kaggle will be used for this model.
This is a historical dataset. So there is a field stating whether that customer has churnded or not, for an unknown telecommunications company.

Here is the link of the dataset; https://www.kaggle.com/blastchar/telco-customer-churn

Field descriptions are below;

customerID - Customer ID <br/>
gender - Whether the customer is a male or a female <br/>
SeniorCitizen - Whether the customer is a senior citizen or not (1, 0) <br/>
Partner - Whether the customer has a partner or not (Yes, No) <br/>
Dependents - Whether the customer has dependents or not (Yes, No) <br/>
tenure - Number of months the customer has stayed with the company <br/>
PhoneService - Whether the customer has a phone service or not (Yes, No) <br/>
MultipleLines - Whether the customer has multiple lines or not (Yes, No, No phone service) <br/>
InternetService - Customer’s internet service provider (DSL, Fiber optic, No) <br/>
OnlineSecurity - Whether the customer has online security or not (Yes, No, No internet service) <br/>
OnlineBackup - Whether the customer has online backup or not (Yes, No, No internet service) <br/>
DeviceProtection - Whether the customer has device protection or not (Yes, No, No internet service) <br/>
TechSupport - Whether the customer has tech support or not (Yes, No, No internet service) <br/>
StreamingTV - Whether the customer has streaming TV or not (Yes, No, No internet service) <br/>
StreamingMovies - Whether the customer has streaming movies or not (Yes, No, No internet service) <br/>
Contract - The contract term of the customer (Month-to-month, One year, Two year) <br/>
PaperlessBilling - Whether the customer has paperless billing or not (Yes, No) <br/>
PaymentMethod - The customer’s payment method (Electronic check, Mailed check Bank transfer (automatic), Credit card (automatic)) <br/>
MonthlyCharges - The amount charged to the customer monthly <br/>
TotalCharges - The total amount charged to the customer <br/>
Churn - Whether the customer churned or not (Yes or No) <br/>