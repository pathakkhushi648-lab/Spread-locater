##  Spread Locator

## Project Overview

This project focuses on analyzing transaction behavior in the Spread Locator system using statistical distributions, probability theory, data transformation techniques, and visualization methods. The project was developed using Python and Google Colab to understand transaction patterns, identify skewness, model probabilities, and generate meaningful business insights from transaction data.

The analysis applies multiple statistical concepts including Bernoulli Distribution, Binomial Distribution, Poisson Distribution, Log-Normal Distribution, Power Law Distribution, Box-Cox Transformation, Z-score Analysis, PDF, CDF, and Q-Q Plot analysis.

---

# Project Objectives

The main objectives of this project are:

* Analyze customer transaction behavior
* Identify transaction distribution patterns
* Detect skewness and outliers in transaction data
* Apply probability distributions to real-world transaction analysis
* Visualize statistical distributions using graphs
* Improve understanding of transaction probability behavior
* Support business intelligence and decision-making

---

# Dataset Information

The dataset used in this project contains realistic transaction records for the Spread Locator platform.

## Dataset Columns

| Column Name        | Description                       |
| ------------------ | --------------------------------- |
| transaction_id     | Unique transaction identifier     |
| customer_id        | Unique customer identifier        |
| transaction_amount | Amount spent during transaction   |
| transaction_count  | Number of transactions            |
| transaction_status | Success or failure of transaction |
| region             | Customer region                   |
| transaction_date   | Date of transaction               |

---

# Technologies Used

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Statsmodels

---

# Statistical Concepts Used

## 1. Bernoulli Distribution

Bernoulli Distribution was used to analyze transaction success and failure outcomes.

### Formula

P(X=x)=p^x(1-p)^(1-x)

### Purpose

* Analyze binary outcomes
* Calculate success probability
* Study transaction reliability

---

## 2. Binomial Distribution

Binomial Distribution was used to calculate probabilities of multiple successful transactions within fixed transaction attempts.

### Formula

P(X=x)=nCx p^x (1-p)^(n-x)

### Purpose

* Analyze repeated transaction success
* Model multiple trial probabilities

---

## 3. Poisson Distribution

Poisson Distribution modeled transaction frequency occurring within a fixed interval.

### Formula

P(X=x)=e^-λλ^x/x!

### Purpose

* Analyze transaction occurrence rate
* Estimate average transaction counts

---

## 4. Log-Normal Distribution

Transaction amounts were positively skewed; therefore, Log-Normal Distribution was applied.

### Formula

Y = ln(X)

### Purpose

* Reduce skewness
* Analyze highly varying transaction amounts

---

## 5. Power Law Distribution

Power Law Distribution was used to identify long-tail transaction behavior.

### Formula

P(x)=Cx^-α

### Purpose

* Detect high-value transactions
* Analyze heavy-tail distributions

---

## 6. Q-Q Plot

Q-Q Plot compared transaction data with normal distribution.

### Purpose

* Check data normality
* Identify skewness and outliers

---

## 7. Box-Cox Transformation

Box-Cox Transformation reduced skewness and improved data normality.

### Formula

Y(λ)=(X^λ -1)/λ

### Purpose

* Stabilize variance
* Improve statistical analysis

---

## 8. Z-score Analysis

Z-score analysis identified unusual transaction values.

### Formula

Z=(X-μ)/σ

### Purpose

* Detect outliers
* Measure deviation from mean

---

## 9. PDF and CDF Analysis

PDF and CDF plots were used to understand probability density and cumulative probability behavior.

### Formulas

PDF = f(x)

CDF = P(X ≤ x)

---

# Graphs and Visualizations

The following graphs were created in this project:

* Histogram Distribution
* Bernoulli Distribution Graph
* Binomial Distribution Plot
* Poisson Distribution Curve
* Log-Normal Histogram
* Power Law Distribution Graph
* Q-Q Plot
* Box-Cox Transformation Graph
* PDF Plot
* CDF Plot
* Z-score Graph
* Correlation Heatmap

---

# Key Findings

* Transaction amounts are positively skewed.
* Most customers perform smaller transactions.
* Few customers generate very large transaction amounts.
* Log-Normal and Power Law distributions best represent transaction behavior.
* Poisson Distribution effectively modeled transaction frequency.
* Box-Cox Transformation improved distribution normality.
* Z-score analysis successfully identified unusual transactions.
* PDF and CDF plots improved understanding of probability behavior.

---

# Final Conclusion

The Statistical Distribution and Probability Analysis for the Spread Locator project successfully analyzed transaction behavior using probability distributions, statistical techniques, and visualization methods.

The project demonstrated how statistical modeling helps:

* Understand transaction patterns
* Detect abnormal transactions
* Analyze customer behavior
* Support business intelligence
* Improve decision-making processes

Overall, the project provided practical implementation of probability theory and statistical distributions using Python and Google Colab.

---

# How to Run the Project

1. Open Google Colab
2. Upload the dataset file
3. Run all Python cells step-by-step
4. Generate graphs and statistical analysis
5. Interpret results and conclusions

---

# Author
Swarna Ajay pathak
