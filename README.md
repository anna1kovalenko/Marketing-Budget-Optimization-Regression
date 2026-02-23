# Marketing Budget Optimization: Multiple Linear Regression Analysis

## Project Overview
This project focuses on analyzing the impact of various marketing channels (TV, Radio, Social Media) and Influencer tiers on total Sales. The goal is to provide data-driven recommendations on budget allocation to maximize revenue.

## Key Accomplishments:
*   Built a **Multiple Linear Regression model** using Python (`statsmodels`).
*   Achieved an **Adjusted R-squared of 0.904**, explaining over 90% of sales variance.
*   Conducted **ANOVA** and **Tukey's HSD post-hoc tests** to validate the significance of categorical TV budget levels.
*   Verified all regression assumptions: **Linearity, Independence, Normality, and Homoscedasticity.**

## Business Insights:
1.  **TV Advertising** is the primary driver of sales. Shifting from a Low to a High budget results in an average increase of ~210 units.
2.  **Radio Advertising** shows a strong positive correlation, contributing ~2.97 units of sales for every $1M invested.
3.  **Influencer Marketing** showed no statistically significant impact on sales in this specific dataset.

## Tools & Libraries Used:
*   **Python** (Pandas, NumPy)
*   **Visualization:** Matplotlib, Seaborn
*   **Statistical Modeling:** Statsmodels (OLS, ANOVA)
*   **Post-hoc Testing:** Scipy, Statsmodels (Tukey HSD)

## How to Use:
1. Clone this repository.
2. Ensure you have the `marketing_sales_data.csv` in the root folder.
3. Open `Marketing_Budget_Analysis.ipynb` in Jupyter Notebook or Google Colab to see the full analysis.
