# Data Intern Challenge - Candidate: Renan Neri

This is Conta Stone's data challenge for intern applicants. The objective is to extract and analyze data from a database.

## Instructions

The solution can be developed using Python, SQL scripts, a BI tool or a combination of those.
It must be sent as a compressed `.zip` folder including all the necessary files or hosted in a public code repository, such as **GitHub** or **GitLab**.

The database contains credit card transactional data in 4 tables:

- `customers`
- `cards`
- `transactions`
- `frauds`

1. Extract and analyze the data in the database in order to answer the following questions. Provide a description and/or comments for each solution.

* What is the average `age` of the customers in the database?

The average `age` of the customers is 35 yeras.

* How is the `card_family` ranked based on the `credit_limit` given to each card?

The `card_family` ranked based on the `credit_limit` is: Premium, Platinum and Gold.

* For the transactions flagged as fraud, what are the `id`s of the transactions with the highest value?

The `ids` of 10 fraud transactions with the highest value is: CTID20567160, CTID15034243, CTID95884307, CTID54759604, CTID55429304, CTID29469747, CTID76723439, CTID85085771, CTID25962688 e CTID60575167.

2. Analysis:

###### Analyze whether or not the fraudulent transactions are somehow associated to the other features of the dataset. Explain your results.

Throught my analysis and observation of the data, I think that the frauds has no trivial pattern or correlation, maybe with some Machine Learning model is possible to predict a fraud, but just with a simple statistical analysis was not possible to decide wheter or not a transaction was a fraud.

**It is not necessary to answer all questions.**

To see the notebook where the analysis were made [click here](conta_stone_challenge.ipynb).
