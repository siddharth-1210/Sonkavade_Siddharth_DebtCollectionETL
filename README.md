# Debt Collection ETL and Basic Analysis

This repository contains a Jupyter notebook for performing ETL (Extract, Transform, Load) operations and basic analysis on debt collection data using Predixion AI.

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Files](#files)
5. [Results](#results)
6. [Contributing](#contributing)

## Introduction

The objective of this project is to demonstrate the use of ETL processes for debt collection data and to perform basic analysis to extract useful insights. This analysis helps in understanding the loan distribution, identifying top borrowers, and evaluating repayment histories.

## Installation

To run the notebook and perform the analysis, you need to have the following software installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy

You can install the required Python packages using the following command:

```sh
!pip install pandas numpy jupyter
```
Usage
1. Clone the repository:
```
git clone https://github.com/your-username/Debt_Collection_ETL_and_Basic_Analysis.git
cd Debt_Collection_ETL_and_Basic_Analysis
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```

3. Open the Jupyter notebook:
```
jupyter notebook Debt_Collection_ETL_and_Basic_Analysis_Predixion_AI.ipynb
```
4. Run all cells in the notebook to execute the ETL process and perform the analysis.
```
```
## Files
Debt_Collection_ETL_and_Basic_Analysis_Predixion_AI.ipynb: Jupyter notebook containing the ETL process and basic analysis.
borrowers_analysis_report.txt: Text file with the results of the analysis.

## Results
Average Loan Amount for Borrowers More Than 5 Days Past Due
54683.16


Top 10 Borrowers with the Highest Outstanding Balance:
Name	Outstanding Balance
Jayant Bhandari	-108.01
Riaan Bhargava	-122.31
Prisha Char	-149.79
Ivan Keer	-152.70
Ira Varty	-156.64
Riaan Lalla	-158.91
Urvi Virk	-161.40
Yasmin Divan	-163.69
Kiara Kurian	-166.93
Bhavin Bala	-168.79

Top 10 Borrowers with the Highest Outstanding Balance:
Name	Outstanding Balance
Jayant Bhandari	-108.01
Riaan Bhargava	-122.31
Prisha Char	-149.79
Ivan Keer	-152.70
Ira Varty	-156.64
Riaan Lalla	-158.91
Urvi Virk	-161.40
Yasmin Divan	-163.69
Kiara Kurian	-166.93
Bhavin Bala	-168.79

Loan Analysis by Type:
Loan Purpose	Number of Borrowers	Average Loan Amount
Debt Consolidation	1020	55704.98
Education Fees	1053	56063.98
Home Renovation	956	54320.20
Medical Emergency	981	54787.69
Wedding Expenses	990	55490.03

## Contributing: 
If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome improvements and new features.


