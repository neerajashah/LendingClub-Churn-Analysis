# Lending Club: Loan Default & Customer Churn Analysis

End-to-end Big Data Analytics pipeline analyzing 2.26 million real loan records to identify borrowers likely to default and understand the financial 
factors driving churn.

## Tech Stack
- **PySpark**: distributed data ingestion, cleaning, type casting
- **Spark SQL**: 5 business questions on 2.26M records
- **MongoDB Atlas + PyMongo**: CRUD operations, aggregation pipelines, indexing
- **Scikit-learn**: Logistic Regression & Random Forest (451K records)
- **Matplotlib, Seaborn**: EDA visualizations
- **Plotly**: Interactive 4-panel dashboard

## Business Questions Answered
1. What is the overall churn/default rate?
2. Which loan grades have the highest churn?
3. Which loan purposes are riskiest?
4. Does income level affect churn?
5. How much revenue is lost to churned customers?

## Key Findings
- **13.09% overall churn rate** - 294K borrowers defaulted across 2.26M loans
- **Grade G loans churn 10x more than Grade A** (40.73% vs 3.67%)
- **Small business loans are riskiest** at 20.41% churn rate
- **$2.16 billion in revenue at risk** from churned borrowers
- **Low income borrowers (<40K) churn at 15.51%** vs 8.9% for high earners
- Both models achieved ~87% accuracy (weighted F1: 0.81)

## Dataset
Lending Club Accepted Loans 2007–2018 - 2.26M rows

