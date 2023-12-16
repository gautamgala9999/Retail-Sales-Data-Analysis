
# Retail Sales Data Analysis 

## Overview

This project involves applying association rule mining techniques, specifically the Apriori algorithm, to analyze a dataset containing information about orders and item transactions. The main goal is to discover interesting associations and patterns within the data, providing insights that can be useful for business decision-making.

## Dependencies

- Python
- pandas
- numpy
- mlxtend

## Getting Started

1. Install the required dependencies using the following command:

   ```bash
   pip install pandas numpy mlxtend
   ```

2. Download the project files and run ipynb,
    - the dataset `data.csv` 
    - the Python Notebook `MBA.ipynb`

## Parameters

- **Support (s)**: The minimum support threshold for the Apriori algorithm.
- **Confidence (c)**: The minimum confidence threshold for association rules.

## Script Explanation

- The script reads the dataset into a Pandas DataFrame.
- It preprocesses the data by grouping it based on order ID and item name, applying the Apriori algorithm to find frequent itemsets and association rules.
- The results are printed for different support and confidence thresholds, allowing for the exploration of various patterns within the data.


## Results

- The script prints frequent itemsets and association rules for different support and confidence values.
- The output provides insights into significant item associations and their confidence levels.

## Note

- The script contains parameters, support and confidence initially set to `s=0.01` and `c=0.01`, that can be adjusted to explore different patterns.  

## Author

Gautam Gala