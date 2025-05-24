# Internpulse
Analysis of Direct Marketing Campaign
Analysis of the Dataset
The dataset has 14 columns and 4521 rows of data which contain the information of customers and campaign outcomes.
Data Preparation and cleaning
*Data types;
Numerical: Age, Balance, Day, Duration, Campaign 
Categorical: Marital, Job, Education, Default, Housing, Loan, Contact, Month, Poutcome
*Missing Values: The dataset contains a lot of “unknown” variables that I treated as either insufficient or missing data
*Negative Balances: Some customers have negative balances which I treated as overdraft 
However, I use conditional formatting for check for errors such as empty cells and duplicate data.

Exploratory Data Analysis 
Key Statistics 
Age: Ranges from 19 to 87 years
Balance: Varies From -€970 to €71,188
Duration: Contact duration ranges from 7 to 3025 seconds
Campaign: Number of Contacts ranges from 1 to 50

Distribution of Key Variables 
1.  Job Roles
  i. Most common: Management (21.4%$,               Blue Collar (20.9%), Technician (17.0%)
  ii. Least common: Student(1.9%), Housemaid (2.5%), unemployed (2.8%), entrepreneur(3.7%).
2. Marital Status 
* 61.9% of the subscribers are married
* 11.7% are Divorced 
* While 26.4% are single 
3. Level of Education 
    Secondary Education; those with secondary education appears to be the most common, followed by Tertiary education and the least is primary education 
4. Campaign Outcomes (poutcome)
* Unknown variables (missing or insufficient data) appears the most 
* Failure is the most common known outcome 
* Success cases are very few.

Insights From The Dataset
1. Customer Profile
* Typical Customer is married, has second education, works in management/blue-collar/technician roles
* Average age around 35-40years
2. Financial Features of the customer 
* Most customers have no default history (Pivot table P/Default)
* About half have housing loans( pivot table P/Housing)
* Only few of them have personal loan (pivot table P/loan)
3. Campaign Patterns 
* Most customers were contacted via cellular phone(pivot table P/contact)
* Campaign activity peaks in May (Most common contact months (pivot table P/Moc)).
Recommendations
1. The bank should focus on married customers with secondary and tertiary level of education 
2. They should also prioritize management and technician professions which may have higher conversion rates
3. Thorough analysis should be done as to why May shows highest contact activity 
4. Address missing “unknown” values in marital, education,job and poutcome field.
5. Analyze customer segments that respond positively to campaigns.
