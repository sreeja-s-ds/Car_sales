# Car_sales

🚗 **Car Sales Data Analysis**

This project focuses on exploratory data analysis (EDA) and data visualization of a car sales dataset using Python. The goal is to uncover insights related to vehicle specifications, pricing, sales performance, and trends across different manufacturers.

📁 **Dataset Overview**

The dataset includes 157 car models and 16 features, such as:

Manufacturer & Model

Sales in Thousands

Resale Value (after one year)

Vehicle Type

Price, Engine Size, Horsepower

Dimensions & Weight

Fuel Efficiency

Launch Date

Performance Factor

🛠️ **Tools & Libraries Used**

Pandas – for data manipulation

Matplotlib & Seaborn – for static visualizations

Plotly – for interactive graphs

SciPy – for statistical analysis

🔍 **Exploratory Data Analysis**

The notebook walks through the following:

Initial Data Inspection

Handling missing values

Data types and conversions

Feature understanding

Data Cleaning

Renamed a column

Converted date fields

Imputed missing numerical values using median

Descriptive Statistics

Mean, median, mode, std deviation, variance

Correlation matrix & heatmaps

Z-score outlier detection

📊 **Data Visualization**

The project includes various plots such as:

📉 Histogram of vehicle prices

📦 Boxplot of horsepower

🔥 Heatmap of feature correlations

📈 Scatter plot (Price vs Horsepower)

🧮 Count plots and bar charts grouped by Manufacturer, Vehicle Type, etc.

📅 Launch year trends

📈 **Statistical Insights**

Heavier cars with larger engines are generally less fuel-efficient.

Strong correlation between resale value and horsepower/performance.

Price is significantly associated with horsepower and performance metrics.

Passenger cars dominate the dataset (~74%).

📁 **File Structure**

📦Car-Sales-Analysis/

 ┣ 📊 car_sales_info.ipynb
 
 ┣ 📄 README.md
 
 ┗ 📁 Car_sales.csv
