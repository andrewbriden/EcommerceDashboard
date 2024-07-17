# E-Commerce Data Dashboard Project

## Introduction
This project provides an insightful analysis and visualization of e-commerce data. The data is processed using Python and visualized using Tableau to uncover trends in customer behavior, sales, and product performance.

## Data Source
The data used in this project is sourced from [Kaggle's E-Commerce Data]((https://www.kaggle.com/datasets/ilkeryildiz/online-retail-listing/data)).

## Technologies Used
- **Python**: For data cleaning, transformation, and analysis.
- **Tableau**: For data visualization and dashboard creation.

## Project Workflow
1. **Data Loading**: Load the dataset from Google Drive.
2. **Data Cleaning**:
   - Replace commas with dots in the 'Price' column and convert it to float.
   - Parse 'InvoiceDate' to datetime format.
   - Remove missing values and duplicates.
   - Feature engineering to calculate 'TotalPrice'.
3. **Visualization**: Create visualizations using seaborn and matplotlib.
   - Orders placed by hour.
   - Top 10 products by quantity sold.
   - Top 10 products by total revenue.
   - Top 10 customers by total revenue.
   - Revenue by country.
   - Average order value over time.
   - Heatmap of orders by hour and day of the week.
4. **Text Analysis and Clustering**: Preprocess product descriptions, vectorize text data, and perform clustering to categorize products.
5. **Dashboard Creation**: Use Tableau to create an interactive dashboard with the processed data, including various visualizations to provide insights into the e-commerce data.

See the public dashboard [here](https://public.tableau.com/app/profile/andrew.briden/viz/Book2_17207425776070/Dashboard1?publish=yes).
