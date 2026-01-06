# SUPERMARKET SALES DATASET ANALYSIS
A dataset on a Supermarket Sales

![pexels-rdne-7948055](https://github.com/user-attachments/assets/9aaad189-96a0-4831-b6a3-a2408db7ae44)

This image was gotten from [here](https://www.pexels.com/photo/colored-pencils-and-a-magnifying-glass-over-documents-with-graphs-7948055/)

# INTRODUCTION
For this project, I obtained a dataset that contains sales records from a supermarket, capturing various aspects of customer transactions. It includes details such Branch, Location (city), Customer Type, Gender, Product Line, Quantity Purchased, Time of Purchase, Payment Method, and Customer Ratings. The dataset consists of 1000 rows, providing valuable insights into customer purchasing behaviour, sales trends, and product performance.
[Link to the dataset](https://www.kaggle.com/datasets/alexhuitron/supermarket-sales)

# AIM OF ANALYSIS
The goal of this analysis is to:
+ Determine noticable sales trends over time
+ Know which are the best and worst selling products
+ Identify the company's key customers
+ Improving customer experience

# DATA EXPLORATION

### How The Data Was Collected 
The dataset was collected from Kaggle Datasets. This dataset contains a summary of a supermarket sales. It was downloaded into a desktop folder which was later loaded into pandas dataframe for analysis.

### Features Identified for Analysis 
The features identified for the analysis are total number of sales per city, total number of sales by payment method, average ratings per product line, and sales trend across different times of the day. The reason for choosing these features is simply because we want to know how the supermarket makes sales in their branches by comparing the total number of sales and the city with other parameter like product line e.t.c.

### Images of Pandas-Profiling Report

![Supermarket-1](https://github.com/user-attachments/assets/b5550e0d-0c39-4e0b-ba0c-b078da2b4d68)
> Fig 1: Loading the Dataset into Pandas DataFrame

![Supermarket-3](https://github.com/user-attachments/assets/2dfc8bce-d787-441e-9330-e65b78ac45e3)
> Fig 2: Count Plot Showing Total Number of Sales per City

![Supermarket-4](https://github.com/user-attachments/assets/842066f8-c3d5-4b51-801e-5e3d1d7e0343)
> Fig 3: Count Plot Showing Total Number of Sales by Payment Method

![Supermarket-5](https://github.com/user-attachments/assets/6dc5e733-b8df-414a-801a-bb98cf012019)
> Fig 4: Bar Plot Showing Average Rating per Product Line

![Supermarket-6](https://github.com/user-attachments/assets/05a26cf3-7317-409e-9b7c-9ab80e96ac36)
> Fig 5: Count Plot Showing Sales Trends Across Different Times of the Day

### Visualizations Generated Using Power BI
I also generated Visualizations Using Power BI to compare the analysis of the panda-profiling reports.

![Supermarket-7](https://github.com/user-attachments/assets/10dd9cb2-6ba6-4f5b-b3bf-290347062d63)
> Fig 6: Visualization Using Power BI

# METHODS

## Pre-Processing Techniques Used
The following are some of the pre-processing techniques we carried out: 
### Loading the Dataset: 
After downloading the dataset, the first pre-processing technique we did was to load the dataset. This was done by the initial importing of python libraries such Pandas, Matplotlib, Seaborn, etc. The dataset was downloaded and named as a csv file and then loaded into Pandas data frame for cleaning and exploratory analysis. 
### Understanding the Dataset: 
This was done by knowing the features each column stands for to avoid mistakes in data analysis and modelling. We created a data frame with the names of the columns, data types, the first and last few rows’ values, unique column values and statistical summary from the data dictionary 
### Dataset Cleaning: 
The dataset cleaning was done by writing python code that checked for any null value.

# KEY INSIGHTS AND RECOMMENDATIONS

The analysis of this dataset reveals valuable trends which is stated below:
+ Sales Distribution: This dataset indicates variation in sales across different cities where Yangon have higher sales than others.

  <ins>Recommendations:</ins> Focus marketing efforts on lower-performing branches and analyse factors contributing to better performance in high-sales branches.

+ Popular Product Lines: Health & Beauty product lines have higher sales and customer ratings compared to others.

  <ins>Recommendations:</ins> Stock more of the best-selling product lines and analyse customer preferences for targeted promotions.

+ Payment Method Preferences: Certain payment methods (e.g. E-wallets & Credit cards) may be more popular than cash, depending on the city and customer type.

  <ins>Recommendations:</ins> Promote digital payment options with incentives (e.g. discounts on e-wallet transactions) to encourage cashless payments.

### THANKS FOR READING




