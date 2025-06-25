# Diwali Sales Analysis

This project analyzes Diwali sales data to identify key trends and insights that can help businesses improve their sales strategies. The analysis covers various aspects such as gender, age group, state, marital status, occupation, and product categories.

## Dataset

The dataset used in this analysis is `Diwali Sales Data.csv`. It contains information about customer details, product information, order details, and sales amount.

## Analysis Steps

The analysis was performed using Python and several libraries including `numpy`, `pandas`, `matplotlib.pyplot`, and `seaborn`. The key steps involved were:

1.  **Data Loading and Inspection:** Loading the dataset and inspecting its structure, columns, and data types.
2.  **Data Cleaning:** Handling missing values and dropping irrelevant columns (`Status` and `unnamed1`).
3.  **Data Transformation:** Changing the data type of the `Amount` column to integer.
4.  **Exploratory Data Analysis (EDA):**
    *   Analyzing sales based on Gender, Age Group, State, Marital Status, Occupation, and Product Category.
    *   Visualizing the data using bar charts to understand the distribution and trends.
    *   Identifying the top selling products.

## Key Findings

Based on the analysis, the following key findings were observed:

*   **Gender:** Most buyers are females, and their purchasing power is greater than men.
*   **Age Group:** The majority of buyers are in the 26-35 age group, particularly females.
*   **State:** The top states in terms of orders and sales amount are Uttar Pradesh, Maharashtra, and Karnataka.
*   **Marital Status:** Married women have a high purchasing power and are the dominant buyer group.
*   **Occupation:** Buyers working in IT, Healthcare, and Aviation sectors are the most frequent customers.
*   **Product Category:** The most sold products are from the Food, Clothing, and Electronics categories.
*   **Top Products:** The analysis identified the top 10 most sold products based on the number of orders.

## Conclusion

The analysis concludes that married women in the age group of 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are more likely to buy products from the Food, Clothing, and Electronics categories during Diwali. This information can be valuable for targeting marketing campaigns and optimizing product offerings.

## Project Links
*   **GitHub:** https://github.com/Narayan0-0/Diwali-Sales-Analysis

## How to Run the Notebook

1.  Clone the repository from GitHub.
2.  Ensure you have the necessary libraries installed (`numpy`, `pandas`, `matplotlib`, `seaborn`).
3.  Place the `Diwali Sales Data.csv` file in the correct directory as referenced in the notebook.
4.  Run the cells in the Jupyter Notebook or Google Colab environment.

## Acknowledgements

*   The dataset was obtained from Kaggle.
