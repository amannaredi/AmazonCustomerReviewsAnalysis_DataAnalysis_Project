## Introduction
This repository contains Python code for analyzing a dataset of Amazon reviews using Pandas, NumPy, Seaborn, Matplotlib, and TextBlob for sentiment analysis. The dataset is stored in a SQLite database and is read into a Pandas DataFrame for analysis. The code performs various tasks such as data cleaning, exploratory data analysis, and sentiment analysis.

## Contents
- `AmazonCustomerReviewsAnalysis.ipynb`: Jupyter Notebook containing the Python code.
- `database.sqlite`: SQLite database file containing the Amazon reviews dataset.

## Dependencies
Ensure you have the following Python packages installed:
- pandas
- numpy
- seaborn
- matplotlib
- sqlite3
- textblob

## Tasks Performed
1. **Reading data from SQLite database**: The code reads the Amazon reviews dataset from a SQLite database into a Pandas DataFrame.
2. **Data Preparation**: Basic data cleaning and wrangling tasks are performed, including removing invalid rows, removing duplicate rows, and converting the 'Time' feature to datetime format.
3. **Analyzing top users**: Identifying top users based on the number of reviews, texts, average score, and number of products purchased.
4. **Identifying products with good reviews**: Finding products with a significant number of reviews and visualizing their distribution of scores.
5. **Analyzing frequent vs. non-frequent viewers**: Comparing the behavior of frequent and non-frequent reviewers based on their rating distributions.
6. **Analyzing verbosity**: Investigating whether frequent users tend to provide longer reviews compared to non-frequent users.
7. **Sentiment Analysis**: Performing sentiment analysis on review summaries to identify common positive and negative keywords used by reviewers.

## Conclusion
The code provides insights into the Amazon reviews dataset, including user behavior, product popularity, sentiment analysis of reviews, and more. It can be extended for further analysis or integrated into larger projects for understanding customer sentiments and preferences on e-commerce platforms.
