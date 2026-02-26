
# Exploratory Data Analysis (EDA) on Auto Sales

This project performs an in-depth Exploratory Data Analysis (EDA) on the Auto Sales dataset. The analysis is conducted in Python using pandas, matplotlib, seaborn, and scikit-learn.

## Dataset

- **File:** Auto_Sales.csv
- The dataset contains sales records including order, customer, product, and sales details.

## Steps Performed

1. **Importing Libraries**
	- pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

2. **Data Loading & Initial Exploration**
	- Loaded the dataset and displayed the first 10 rows
	- Checked the shape and data types of all columns
	- Checked for duplicate records and removed them if any

3. **Outlier Detection**
	- Identified numerical columns (excluding IDs)
	- Used the IQR method to detect outliers
	- Visualized outliers using boxplots

4. **Unique Value Analysis**
	- Counted unique customers and unique countries

5. **Date Feature Engineering**
	- Converted `ORDERDATE` to datetime
	- Extracted `YEAR` and `MONTH` columns

6. **Sales Trend Analysis**
	- Visualized monthly sales trends over time

7. **Country-wise Sales**
	- Calculated total sales by country
	- Identified top 3 countries by sales

8. **Deal Size Analysis**
	- Calculated average order value for each `DEALSIZE`
	- Identified which deal size contributes the most revenue

9. **Price vs MSRP**
	- Identified and counted items where selling price is higher than MSRP

10. **Product Line Analysis**
	 - Created a bar chart showing total sales by product line

11. **Correlation Analysis**
	 - Examined relationships between `QUANTITYORDERED`, `PRICEEACH`, and `SALES` using a correlation matrix and heatmap

12. **Customer Insights**
	 - Found customers whose last order was more than the average days
	 - Identified customers who placed more than one order

13. **Missing Values**
	 - Checked for missing records in each column

14. **Dataframe Splitting**
	 - Created separate dataframes for numerical and categorical variables

15. **Feature Engineering**
	 - Renamed columns for clarity (e.g., `ORDERNUMBER` to `order_number`)

16. **Feature Scaling**
	 - Applied StandardScaler to numerical features

17. **Skewness Analysis & Transformation**
	 - Checked skewness of numerical variables
	 - Tagged variables as low, moderate, or highly skewed
	 - Applied log, square-root, and Box–Cox transformations to highly skewed variables

## How to Run

1. Open the notebook `EDA on Auto_Sales.ipynb` in Jupyter or VS Code.
2. Ensure all required Python libraries are installed:
	- pandas, numpy, matplotlib, seaborn, scikit-learn, scipy
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## Visualizations

- Boxplots for outlier detection
- Line plot for monthly sales trend
- Bar chart for sales by product line
- Heatmap for correlation analysis
- Histograms and KDE plots for skewness

## Key Insights

- Outliers and missing values were identified and handled
- Top contributing countries and deal sizes were found
- Product line and sales trends were visualized
- Feature scaling and skewness correction were performed for further modeling

---

**Author:**
Sagar Singh
Aspiring Data Scientist