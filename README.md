# Project: Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

### Project Background

> This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'Defaulters'. 

### Project Statement

> Analyse the data and derive insights from the data to explain to the business based on what factors loans are charged off

### Data Set

> The dataset *loan.csv* is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Loan Status: The number of Fully Paid customers is almost six times higher than the number of charged off customers.
- Loan Grade: Higher-grade customers tend to borrow larger amounts, while B grade has the highest number of borrowers.
- Experience Level (Derived Metrics): Junior-level employees are more likely to take out loans.
- Home Ownership: People living in rented homes tend to borrow more money.
- Issue Year: Over the years, the number of borrowers has increased up to the latest date.
- Annual Income: People with medium salaries (25-50K) are more likely to borrow loans.
- Loan Amount: Most people tend to borrow smaller loan amounts.
- Interest Rate: As the interest rate increases, the rate of defaulters also increases.
- Loan to Income Ratio: We can conclude that people with a ratio of 40% or higher are considered risky applicants.
- Grade: Grade G is the riskiest category of applicants, with a median loan amount of almost 15-20K, which is the highest among all grades.
- Purpose: The ratio of defaulters is highest for small business loans. The 75th percentile is also highest for small business loans, indicating potential risk to the company.

## Technologies Used
- matplotlib==3.8.0
- numpy==1.26.1
- pandas==2.1.1
- seaborn==0.13.0

## Acknowledgements

This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [@ritwikdesai] [@sudipkandel123]

## License

This project is open source and available without restrictions.
