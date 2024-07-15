# Retail Sales Trend Analysis

This project focuses on analyzing retail sales data to identify trends and patterns. The analysis involves data cleaning, transformation, and visualization to derive insights from the dataset.

# Key Findings

**Data Cleaning and Preprocessing:**
* Handling Missing Values: The dataset initially contained missing values, which were removed to ensure data integrity.
* Removing Duplicates: Duplicate entries were identified and removed to avoid skewed results.
* Data Type Conversion: Columns such as 'Order Date', 'Quantity Ordered', and 'Price Each' were converted to appropriate data types for further analysis.

**Sales Analysis:**
* Monthly Sales: The sales data was aggregated by month to observe monthly sales trends. The analysis revealed fluctuations in sales across different months.
* Sales by City: The sales data was analyzed based on the cities where purchases were made. This helped identify which cities had higher sales contributions.

**Data Visualization:**

* Bar Plots: Used to visualize monthly sales, showing clear trends and comparisons between different months.
* Pie Charts: Used to represent the distribution of sales across different cities, providing a visual understanding of city-wise sales contributions.

# Technologies Used
> * Pandas: For data manipulation and analysis, including handling missing values, removing duplicates, and performing aggregations.
> * NumPy: For numerical operations and data type conversions.
> * Matplotlib and Seaborn: For creating visualizations, including bar plots and pie charts to represent sales data.
> * Data File Formats: Feather: Used to store and read the dataset efficiently, leveraging its fast read and write capabilities.

# Conclusions
The analysis provided valuable insights into retail sales trends, highlighting key periods of high sales and identifying top-performing cities. By leveraging Python's data analysis and visualization libraries, the analysis effectively transformed raw sales data into actionable insights. These findings can guide business decisions, such as inventory management and targeted marketing strategies, to enhance sales performance.
