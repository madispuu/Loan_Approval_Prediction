# Loan Approval Prediction
Madis Puu, Rando Roosik
# Task1 - done 
```
Task 2 - Business understanding
```

## Identifying your business goals
### Background
Panganduses on laenude väljastamine eraisikutele oluline protsess, mis mõjutab nii pankasi kui ka laenu taotlejaid. Finantsasutuste eesmärk on minimeerida maksejõuetuse riske,
maksimeerida kasumit ning tagada klientide rahulolu. Siiski on laenuvõtjate sobivuse hindamine tihti töömahukas manuaalne protsess või tugineb aegunud meetoditele.
Me soovime parandada otsustusprotsessi tõhusust ja täpsust, kasutades ennustusalgoritme laenutaotluste hindamise automatiseerimiseks. Suur osa manuaalsest tööst on võimalik ära jätta,
kui enne leida automaatselt need inimesed, kes väga suure tõenäosusega ei ole kvalifitseeritud laenu saama. See muudaks laenude andmist odavamaks pankade jaoks ning kiirendaks laenu saamis protsessi klientide jaoks.
### Business goals 
-Ennustada väga suure täpsusega isikud, kes ei ole kvalifitseeritud laenu saama, et nende avaldust ei peaks käsitsi vaatama.
-Parandada kliendikogemust, pakkudes kiiremaid otsuseid laenutaotlustele.
-Minimeerida finantsriske, tuvastades tõhusamalt kõrge riskiga taotlejad.
### Business success criteria
- Otsus, et klient ei saa laenu, kuigi ta peaks(vale-negatiivne) peab olema väga väike %, sest iga klient, kes oleks pidanud saama laenu, aga ei saanud, tähendab et pank kaotas võimaliku tulu allika.
- Samas peab olema negatiivseid vastuseid võimalikult palju, et maksimaalses koguses manuaalset tööd

## Assessing your situation
### Inventory of resources
### Requirements, assumptions, and constraints
### Risks and contingencies
### Terminology
### Costs and benefits

## Defining your data-mining goals
### Data-mining goals
### Data-mining success criteria



```
Task3 - Data understanding
(ns infoks)(keegi oli postitanud kaggelisse)

Descriptions for the column names based on the data provided:

id: Unique identifier for each record.
person_age: Age of the individual, categorized into ranges.
person_income: Income of the individual, categorized into income ranges.
person_home_ownership: Homeownership status, which includes categories like 'RENT', 'MORTGAGE', etc.
person_emp_length: Employment length of the individual, categorized into ranges based on years.
loan_intent: The purpose of the loan, with categories such as 'EDUCATION', 'MEDICAL', etc.
loan_grade: The credit grade of the loan, such as 'A', 'B', etc.
loan_amnt: Loan amount, categorized into ranges.
loan_int_rate: Loan interest rate, categorized into percentage ranges.
loan_percent_income: Percentage of the individual’s income that the loan represents, categorized into - ranges.
cb_person_default_on_file: Whether the person has a history of loan default, with values 'true' or 'false'.
cb_person_cred_hist_length: Length of the individual’s credit history, categorized into ranges.
loan_status: with values representing whether the loan status approval( binary values)
The dataset is a about loan applications, including personal, financial, and loan details. It's likely used for predicting whether a person will default on a loan, making it a binary classification problem. The goal is to figure out which applicants are at higher risk of not paying back their loans based on their age, income, employment, loan purpose, credit history, and other related information.

```
```
Task4
```
