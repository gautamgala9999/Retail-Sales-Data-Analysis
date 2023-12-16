
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

The repository includes explanations of three key results scenarios:

1. **Result 1:** MBA analysis with support = 0.01 and confidence = 0.3. Provides limited, high-confidence itemset combinations.
2. **Result 2:** MBA analysis with minimal support and confidence values, yielding numerous itemsets and rules.
3. **Result 3:** Nested loop exploration of varying support and confidence thresholds.

The script prints frequent itemsets and association rules for different support and confidence values.The output provides insights into significant item associations and their confidence levels.

## Excel Visual Representations

The Excel file contains visualizations of the analysis results using pivot tables, column charts, and bar charts. These visualizations help understand the frequent itemsets and association rules discovered through the MBA process.

## Note

- The script contains parameters, support and confidence initially set to `s=0.01` and `c=0.01`, that can be adjusted to explore different patterns.  

## Author
*Gautam Gala*

For inquiries, please [email me](mailto:gautamgala5544@gmail.com).
