# Telco customer analysis


This dataset provide a list of customers  from a Californian telco provider. 
Data provided are: customers infos, billing, contracts types, services, statuts, ...

My analysis is focused on customers churn and the financial impact. 
I also did some exploration on other fields such as socio-demographic and geographic

## 🛠 Tools used 
Excel, Python, PowerBI

## 🔍 Dataset exploration 

- 7043 rows
- 38 fields / Types count: object = 24; float = 9; int = 6

## 🎡 Data profiling 
- Missing values check ok
- No duplicates
- No incoherent data
- No outliers

## 🔍 Functional analysis

### Churn
Churn represent 17% of revenue loss for a total loss of 3 684 459$.

**Insights**
-   Newjoiner (Tenure < 5 months) tend to churn the most.
-   More churn on the higher Monthly charge
-   Total charge and Revenue: Higher churn count for lower amount, Newjoiners spend less because they don't stay much
-    Fiber Optic is the most churned technology
-   Offer E appears to be the most popular offer around churned customers. Perhaps the company may want to review and look for potential pain points about this offer.
-   More than half of churned customers haven't subscribed to additional internet services and streaming services.
-   88.55% have a Month-to-Month contract wich is bad for customer retention.
-   Our competitors are the N°1 threat

**Recommendations**

- Identify what's wrong with offer E

- Competitor threat: A market study is needed

- More marketing on additional services as they are a retain factor

- too much month-to-month contracts is not a fidelity habit. Pushing more on year contract


### Financial

### Socio-demographic

### Geographic
