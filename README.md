# Smartphones_Project

#### Table of Contents

---------------------


-  [Project Overview](#Project_Overview)
  

-  [Data Source](#Data_Source)
  

-  [Tools](#Tools)


-  [Data Cleaning/Preparation](#Data_Cleaning/Preparation)
  

-  [Exploration Data Analysis](#Exploration_Data_Analysis)


- [Results/Findings](#Results/Findings)


- [Recommendations](#Recommendations)
  


  





### Project Overview

The Smartphone dataset comprises 210 rows and 26 columns, detailing various attributes of different smartphone models from multiple brands. The dataset includes information such as price, rating, 5G and NFC support, processor details, battery capacity, and camera specifications etc. This report presents an analysis of the dataset using visualizations to communicate insights from the dataset, and offering insights into the trends and distributions of key features.






### Data Source
The primary dataset utilized for this project was downloaded from the provided link [smartphones-dataset ](https://www.kaggle.com/datasets/informrohit1/smartphones-dataset)


### Tools
Python was utilized for importing and inspecting the dataset, checking for duplicate records, and identifying null values to standardize the dataset for data quality assurance.


### Data Cleaning/Preparation
In the initial data preparation, I performed the following tasks below:

1. Data loading and inspection.
2. Handling for missing values.
3. Checking for duplicate values.
4. Handling Inconsistent data and typos.
5. Checked and handled outliers using the interquartile range (IQR) method, and visualized the price column using a boxplot to identify outliers in the dataframe.
6. Handled null values by replacing them with the mean of the respective columns.
7. Replaced unknown values in the "processor brand" column where there were null strings.




### Exploration Data Analysis
EDA involved exploring   smartphones dataset to answer key questions such as:

1.	What are the smartphone prices across the top ten brands?
2.	Are there any correlations between the price of a smartphone and its battery capacity, RAM capacity, internal memory, as well as the correlation between price and rating?
3.	What are the price distributions across the dataset?
4.	What percentage of smartphones have fast charging available?
5.	How does the processor brand impact performance and rating?
6.	What were the performance differences among different operating systems?
7.	How does processor speed and the number of cores vary across different processor brands?
8.	What were the top five average prices of smartphone models with 5G?
9.	What were the top five average prices of smartphone models without 5G?
10.	Are there any relationships between smartphone cameras?
11.	Are there any relationships between smartphone screen resolution width and height?



### Results/Findings


*1.Brand Pricing:*
(a) Xiaomi smartphones tend to be the most expensive, averaging $26,318.31.
(b) Poco smartphones tend to be the cheapest, averaging $7,576.47.

*2.Correlations with Battery Capacity:*
(a) Negative correlation of -0.09 between fast charging and battery capacity.
(b) Negative correlation of -0.05 between price and battery capacity.
(c) Negative correlation of -0.01 between battery capacity and rating.

*3.Moderate Correlations:*
(a) Fast charging and RAM capacity: 0.47.
(b) Fast charging and internal memory: 0.41.
(c) Fast charging and price: 0.52.
(d) Fast charging and rating: 0.39.

*4.High Correlations:*
(a) RAM capacity and internal memory: 0.81.
(b) RAM capacity and price: 0.67.
(c) RAM capacity and rating: 0.67.

*5.Price Distribution:*
(a) Smartphone prices range from $3,499 to $65,000.

*6.Percentage of Brands with Fast Charging:*
(a) Xiaomi: 13.28%.
(b) Samsung: 11.34%.
(c) Vivo: 9.73%.
(d) Realme: 9.16%.
(e) Oppo: 7.56%.

*7.Processor Brand Ratings:*
(a) Highest average rating: Snapdragon 81.085%.
(b) Lowest average rating: 61%.

*8.Operating System Analysis:*
(a) Android: Total price of $1,851,179 and average rating of 78%.
(b) iOS: Total price of $81,566 and average rating of 73.53%.

*9.Processor Speeds and Cores:*
(a) Bionic: 3.02 GHz, 6 cores.
(b) Spreadtrum: 1.35 GHz, 4 cores.

*10.Top Five Smartphone Models by Average Price:*
(a) Apple iPhone 12 (256GB): $67,999.
(b) Apple iPhone 14: $65,999.
(c) OnePlus 10 Pro 5G (12GB RAM + 256GB): $65,499.
(d) iQOO 11 (16GB RAM + 256GB): $64,999.
(e) Apple iPhone 13 Mini: $64,900.

*11.Camera Relationships:*
Positive correlation between primary rear and primary front cameras.

*12.Resolution Relationships:*
Positive correlation between resolution width and height.







