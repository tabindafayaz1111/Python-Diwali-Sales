# Diwali Sales Analysis Project

## Project Overview
This project analyzes Diwali sales data to identify purchasing patterns of specific customer segments. The focus is on unmarried women aged 26–35 from the states of Uttar Pradesh (UP), Maharashtra, and Karnataka, working in IT, Healthcare, and aviation sectors. The analysis determines their likelihood of buying products from **food**, **clothing**, and **electronics** categories.

## Datasets
- **Product_ID**: Unique identifiers for products (e.g., P00265242, P00110842).
- **Orders**: Number of orders placed for each product.
- **Customer segments**: Demographic and professional details (age, marital status, state, occupation).

## Analysis Performed
1. **Sales visualization**: A bar chart plots orders per product ID to highlight top-selling items.
2. **Customer segmentation**: Insights into purchase behavior of the targeted demographic group.
3. **Category preference**: Identification of preferred product categories (food, clothing, electronics).

## Code Structure (Jupyter Notebook)
- **Libraries**: `pandas` (imported as `pd`) for data manipulation.
- **Visualization**: Matplotlib/seaborn used to generate the bar chart.
- **Key code snippet**: Annotation of product ID `P00110842` in the plot.

## How to Run the Project
1. Clone the repository.
2. Install dependencies: `pip install pandas matplotlib`.
3. Open `diwali sales analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells to reproduce the analysis and visualizations.

## Results & Insights
- Product `P00265242` has the highest order count (~120).
- Target customers (married women, 26–35, from UP/Maharashtra/Karnataka in IT/Healthcare/aviation) prefer food, clothing, and electronics.
- Sales strategy should focus on these categories for the identified segment.

## Future Enhancements
- Add predictive modeling for sales forecasting.
- Expand segmentation to other age groups or states.
- Integrate additional product categories for deeper analysis.

## Contributors
- Tabinda Fayaz Lone - Project lead & analyst.

