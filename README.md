# Credit Card Fraud Analysis

## Overview

This repository analyzes credit card fraud using a simulated dataset (`ccf_simulation.csv`). The analysis involves data preprocessing, exploratory data analysis, and hypothesis testing to determine if there is a dependency between transaction type and fraud status.

## Data Loading

The dataset is loaded from `ccf_simulation.csv`.

## Data Preprocessing

Data is preprocessed by converting relevant columns to factors and removing missing values.

## Data Reduction

A subset of data is created, containing only specific transaction types (`CASH_OUT` and `TRANSFER`), and saved to `ccf_red.csv`.

## Sample Selection

A sample dataset is created with 1000 fraud cases and 4000 non-fraud cases.

## Summary Statistics

Summary statistics, including mean and standard deviation, are generated using the `gtsummary` package.

## Data Visualization

A bar plot is created to visualize the distribution of transaction types by fraud status.

## Hypothesis Testing

A chi-squared test is performed to test the independence of transaction type and fraud status.

**Conclusion:** There is strong evidence that the transaction type and fraud status are dependent.
