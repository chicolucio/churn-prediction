# About the dataset

In this study, an IBM dataset will be analyzed. The Telco customer churn data contains
information about a telecom company named Telco that provides home phone and internet
services to 7043 customers. It indicates which customers have left, stayed, or signed up
for their service. Multiple important demographics and services are included for each
customer, totaling 20 features. The aim is to predict behavior to retain customers.

## Data dictionary

Each row represents a customer, and each column contains the customer's attributes, as
described below. The dataset includes information about:

- Customers who left within the last month:
    - `Churn`: *Yes* = the customer left the company within the last month. *No* = the
    customer remained with the company.
- Customers' demographic info:
    - `gender`: customer's gender: *Male*, *Female*
    - `SeniorCitizen`: customer is 65 or older: *1*, *0* (meaning *Yes* and *No*,
    respectively)
    - `Partner`: customer is married: *Yes*, *No*
    - `Dependents`: customer lives with any dependents: *Yes*, *No*. Dependents could be
    children, parents, grandparents, etc.
- Services that each customer has signed up for:
    - `PhoneService`: customer subscribes to home phone service with the company: *Yes*,
    *No*
    - `MultipleLines`: customer subscribes to multiple telephone lines with the company:
    *Yes*, *No*, *No internet service*
    - `InternetService`: customer subscribes to Internet service with the company: *No*,
    *DSL*, *Fiber Optic*
    - `OnlineSecurity`: customer subscribes to an additional online security service
    provided by the company: *Yes*, *No*, *No internet service*
    - `OnlineBackup`: customer subscribes to an additional online backup service
    provided by the company: *Yes*, *No*, *No internet service*
    - `DeviceProtection`: customer subscribes to an additional device protection plan
    for their Internet equipment provided by the company: *Yes*, *No*, *No internet
    service*
    - `TechSupport`: customer subscribes to an additional technical support plan from
    the company with reduced wait times: *Yes*, *No*, *No internet service*
    - `StreamingTV`: customer uses their Internet service to stream television
    programming from a third-party provider: *Yes*, *No*, *No internet service*
    - `StreamingMovies`: customer uses their Internet service to stream movies from a
    third-party provider: *Yes*, *No*, *No internet service*
- Customer account information:
    - `tenure`: total number of months that the customer has been with the company.
    - `Contract`: customer's current contract type: *Month-to-Month*, *One Year*, *Two
    Year*.
    - `PaperlessBilling`: customer has chosen paperless billing: *Yes*, *No*
    - `PaymentMethod`: how the customer pays their bill: *Electronic check*, *Credit
    Card*, *Mailed Check*, *Bank transfer*
    - `MonthlyCharge`: customer's current total monthly charge for all their services
    from the company
    - `TotalCharges`: customer's total charges, calculated to the end of the quarter
- Finally, each customer has a `CustomerID`, a unique ID that identifies the customer.
