Dataset Source: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset


Summary of Data Cleaning and Exploratory Data Analysis (EDA)

1. Loading the Dataset
    - We loaded the dataset using pandas and displayed the first few rows to understand its structure.

2. Data Cleaning
    - Inspection: We checked the data types and missing values in each column.
    - Convert Numerical Columns: We converted columns like discounted_price, actual_price, discount_percentage, rating, and rating_count to numeric types.
    - Handle Missing Values: We filled the missing values in rating_count with the median value.
    - Remove Duplicates: We removed any duplicate rows to ensure data quality.
    - Verify Data Types: We confirmed that all columns had the correct data types after conversions.

3. Exploratory Data Analysis (EDA)
    - Distribution of Ratings: We plotted a histogram to visualize the distribution of product ratings.
    - Distribution of Prices: We plotted histograms for discounted_price and actual_price to understand their distributions.
    - Box Plot of Discounted Price by Category: We created a box plot to compare discounted prices across
