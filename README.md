# 📱 iPhone Data Analysis Project

## 📖Project Overview
This project involves the analysis of iPhone products data from Flipkart to gain insights into various product features, prices, ratings, and discounts. The dataset includes information about different iPhone models, including product names, sale prices, MRP (Maximum Retail Price), discount percentages, number of ratings and reviews, RAM specifications, and star ratings.

## 🎯 Objectives
- Understand Product Pricing: Identify the price range of iPhones, including the highest and lowest-priced models.
- Discover Customer Preferences: Analyze ratings and reviews to understand customer satisfaction.
- Explore Discount Trends: Study the discounts applied to different iPhone models.
- Gain Insights for Decision-Making: Provide actionable insights for customers and businesses, such as identifying models under a specific price point or with high ratings.

## 🔑 Features & Key Functionalities:
- Data Cleaning: The dataset contains 62 entries for various iPhone products.Missing data analysis, checking the dataset for inconsistencies or anomalies.
- Exploratory Data Analysis (EDA): Descriptive statistics, filtering, and visualizing data to gain insights.
- Data Visualizations: Histograms, scatter plots, and bar plots to understand price distributions, star ratings, and RAM effects on ratings.

## 🔍 Key Insights
- Price Range: iPhone models in the dataset range from ₹39,900 (iPhone SE) to ₹1,49,900 (iPhone 12 Pro, 512 GB).
- Best Discount: The iPhone SE (64 GB) offers a 24% discount, making it one of the most affordable models in the dataset.
- High-End Models: Premium models like the iPhone 12 Pro Max and iPhone 11 Pro Max dominate the upper price range, starting at ₹1,00,000.
- Customer Ratings: Most iPhones have ratings above 4.5, indicating high customer satisfaction across the board.

## 📂 Dataset
The dataset (apple_products.csv) contains the following columns:

- Product Name: Name of the iPhone product.
- Product URL: URL for purchasing the product.
- Brand: Brand of the product (Apple).
- Sale Price: Current sale price of the product.
- MRP: Maximum Retail Price of the product.
- Discount Percentage: Percentage of discount offered.
- Number of Ratings: Number of ratings the product has received.
- Number of Reviews: Number of reviews the product has received.
- UPC: Unique product code.
- Star Rating: Average star rating of the product.
- RAM: RAM specification of the product.

## 💻 Code Overview
The code uses the pandas library to load the dataset and clean the data, matplotlib and seaborn for visualizations, and the numpy library for some numeric calculations.

## 📝 Steps:
- Data Import: The dataset is read into a pandas DataFrame from a CSV file.
- Data Cleaning: We explore the dataset by checking for missing values and counting entries for each column.
- Exploratory Data Analysis (EDA):
We identify the maximum and minimum values in the "MRP" column.
- Filter and analyze products with MRP under ₹50,000 and above ₹100,000.

## 📊 Visualizations:
- Discount Analysis: A scatter plot comparing the discount percentage against the number of ratings, highlighting the relationship between discounts and customer feedback.
- Price Trends Across Models: A bar chart showing the average sale price of different iPhone models to track pricing patterns.
- Relationship Between Sale Price and Star Rating: A scatter plot to explore if higher-priced models tend to have better ratings.
- Heatmap: Correlations Between Variables: A heatmap displaying correlations between numerical variables like sale price, discount percentage, and ratings.
- Distribution of Discount Percentages: A histogram showing the variation in discount percentages across iPhone models.

## 🛠️ Tools & Techniques
- Python: Programming language used for data analysis and visualization.
- Pandas: Library for data manipulation and analysis (loading, cleaning, and analyzing the dataset).
- Matplotlib: Library for generating visualizations like histograms, scatter plots, and bar plots.
- Seaborn: Data visualization library built on top of Matplotlib, used for advanced plots like bar plots and scatter plots with improved aesthetics.
- Jupyter Notebooks: Integrated development environment (IDE) used for executing the code in an interactive manner.
  
## 🚀 Project Significance
This project serves as an excellent introduction to data analysis concepts using Python. It demonstrates how datasets can be used to derive insights, make informed decisions, and explore customer preferences. The analysis performed here lays the groundwork for more advanced analytics, such as predictive modeling or visualization.
