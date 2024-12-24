# Lending Club Case Study

Lending Club, a consumer finance marketplace specializing in offering a variety of loans to urban customers, faces a critical challenge in managing its loan approval process. When evaluating loan applications, the company must make sound decisions to minimize financial losses, primarily stemming from loans extended to applicants who are considered "risky."

These financial losses, referred to as credit losses, occur when borrowers fail to repay their loans or default. In simpler terms, borrowers labeled as "charged-off" are the ones responsible for the most significant losses to the company.

The primary objective of this exercise is to assist Lending Club in mitigating credit losses. This challenge arises from two potential scenarios:

1. Identifying applicants likely to repay their loans is crucial, as they can generate profits for the company through interest payments. Rejecting such applicants would result in a loss of potential business.
2. On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

The objective of this case study is to identify loan applicants who are at risk of defaulting, in order to reduce credit losses for Lending Club. This will be achieved through exploratory data analysis (EDA) of the provided dataset.

Lending Club aims to understand the driving factors behind loan default, which can be used for portfolio and risk assessment. By identifying these factors, the company can make more informed lending decisions and mitigate potential losses.

This exercise focuses on two key scenarios:

* Identifying creditworthy applicants: Accurately identifying applicants who are likely to repay their loans is crucial. These applicants generate profits for the company. Rejecting them would lead to a loss of potential business.
* Identifying high-risk applicants: Approving loans for applicants who are unlikely to repay can result in significant financial losses for the company. It is essential to identify and reject these high-risk applicants.

By addressing these scenarios, Lending Club can optimize its lending practices and minimize credit losses.

## Conclusions

1. **Grades B,C and D**: *Grades B, C, and D* attract a significant portion of loan applicants, presenting a higher risk of default.
Thorough risk assessment is crucial for these grades, particularly for *subgrades B3-B5, C1-C3, as well as D2*.

2. **Annual Income 20K to 60K and DTI**: Applicants with annual incomes between *20,000 and 60,000* are more likely to apply for loans in grades B, C, and D, placing them within a higher-risk portfolio.These applicants often exhibit higher debt-to-income (DTI) ratios, typically ranging from *10 to 25+* or more. Careful monitoring of these factors is essential.

3. **Reject loans with high amount for grades F and G**: Grades F and G do not have many loan applicants but the loan applications are of high amounts. *Very high amounts for these grades need to be rejected as they are more likely to be defaulted*

4. **Reduction in interest rates**: Loan applications with higher interest rates are more likely to be defaulted. *Lending club should consider reduction in the interest rates for reducing number of defaults.*

5. **Purpose and derogatory record**: Loan applicant taking loan for *debt consolidation* should be properly verified. Also, applicant with *zero and one derogatory public record* tend to default as well. Risk should be assessed for them as well.

## Technologies Used

- [Python](https://www.python.org/) - version 3.12.4
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- IIITB and Upgrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Collaborators

Created by [@AdityaKarnik](https://github.com/kandiadi)


