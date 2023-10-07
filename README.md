# Sales Data Analysis

This project involves analyzing sales data for a real-world scenario. The data is cleaned, processed, and analyzed to derive meaningful insights. The analysis includes tasks like merging data, cleaning up inconsistencies, and answering several questions about the sales data.

## Project Overview

The project can be broken down into the following tasks:

### Task 1: Merge Sales Data
- 12 months of sales data from different CSV files are merged into a single `all_data.csv` file for analysis.

### Data Cleaning
- Rows containing NaN values are removed.
- Rows with 'Or' in the 'Order Date' column are removed.
- Columns are converted to the correct data types.

### Augmenting Data
- **Task 2:** Added a 'Month' column extracted from the 'Order Date'.
- **Task 3:** Added a 'Sales' column calculated from the product of 'Quantity Ordered' and 'Price Each'.
- **Task 4:** Added a 'City' column extracted from the 'Purchase Address'.

### Analysis and Visualization
- **Q1:** Determined the best month for sales and the corresponding earnings.
- **Q2:** Identified the city with the highest number of sales.
- **Q3:** Analyzed the best times to display advertisements to maximize the likelihood of customer purchases.
- **Q4:** Discovered products often sold together.
- **Q5:** Identified the best-selling product and explored possible reasons for its high sales.

## Project Structure

- `main.py`: Python script containing the code for data analysis.
- `all_data.csv`: Merged dataset used for analysis.
- `README.md`: Project overview and documentation.
- `images/`: Directory containing images used in the README or generated during analysis.

## Prerequisites

- Python 3.x
- Libraries: pandas, matplotlib

## How to Run

1. Clone the repository:
