# DS_project
# Market Basket Analysis of French Customer Transactions

This project performs Market Basket Analysis on a dataset of customer transactions to identify associations between items frequently purchased together in France. The analysis utilizes the Apriori algorithm and association rule mining techniques to uncover insights into customer purchasing patterns.

## Methodology

1. **Data Preparation:**
   - Load the dataset (`Assignment-1_Data.csv`).
   - Preprocess the data, including cleaning, handling missing values, and converting data types.
   - Filter transactions specific to France.

2. **Market Basket Creation:**
   - Transform the data into a market basket format, representing items purchased in each transaction.
   - Create a binary representation of the basket, indicating the presence or absence of items.

3. **Association Rule Mining:**
   - Apply the Apriori algorithm to identify frequent itemsets based on minimum support.
   - Generate association rules using lift and confidence metrics to establish relationships between items.

4. **Visualization and Interpretation:**
   - Visualize the top association rules using bar plots and scatter plots.
   - Analyze the rules to gain insights into customer behavior and potential product recommendations.


## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, mlxtend, warnings, random, logging

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Place the `Assignment-1_Data.csv` file in the specified path.
4. Run the Python script to execute the analysis.

## Results

The analysis reveals interesting associations between items purchased by customers in France. The visualizations highlight the strongest relationships and provide valuable insights for business decisions, such as product placement, promotions, and recommendations.
