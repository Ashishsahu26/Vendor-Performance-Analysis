Vendor Performance Analysis 📈
This project is a comprehensive data analysis of vendor sales and purchase data to evaluate vendor performance and provide key business insights. The analysis identifies top-performing vendors, uncovers trends in profitability and inventory management, and offers actionable recommendations to optimize procurement strategy.

Project Objective
The main goal of this project is to:

Connect to a database and extract raw transactional data.

Clean and preprocess the data for analysis.

Engineer key business metrics to assess vendor performance.

Visualize data to identify patterns, trends, and anomalies.

Deliver data-driven insights to improve gross profit and inventory turnover.

Key Features & Analysis Highlights
Data Sourcing & Cleaning
Database Connection: The analysis begins by establishing a connection to a MySQL database to securely retrieve raw data, demonstrating practical experience with database management and retrieval.

Data Preprocessing: The notebook includes robust steps for handling missing values, correcting data types, and ensuring data consistency, which are crucial for reliable analysis.

Business Metrics & Insights
Profitability Analysis: GrossProfit was calculated to shift focus from mere sales volume to actual profitability, revealing that some high-volume vendors were not the most profitable.

Performance Ratios: Two critical business metrics were engineered:

SalesToPurchaseRatoi: This ratio helps in understanding the return on investment from each vendor's products.

StockTurnover: This metric provides insights into inventory efficiency, identifying fast-moving and slow-moving products.

Data Visualization
Exploratory Data Analysis (EDA): The project uses matplotlib and seaborn to create compelling visualizations, including:

Histograms: To understand the distribution of key variables like TotalSalesDollars and GrossProfit.

Bar Plots & Scatter Plots: To compare vendor performance and uncover relationships between different metrics.

Summary Tables: To rank vendors based on their performance for quick reference.

Project Structure
vendor_purchase_analysis.ipynb: This Jupyter Notebook contains all the code for data retrieval, cleaning, analysis, and visualization.

README.md: The file you're currently reading, which provides an overview of the project.

Technologies & Libraries
Python: The core programming language used for the analysis.

Pandas: Essential for data manipulation and analysis.

Numpy: Used for numerical operations.

Matplotlib & Seaborn: For creating professional-grade data visualizations.

SQLAlchemy: To establish a robust connection to the MySQL database.

MySQL Connector: For interaction with the MySQL database.

