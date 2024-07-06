# Smartphones_Project

#### Table of Contents

---------------------


-  [Project Overview](#Project_Overview)
  

-  [Data Source](#Data_Source)
  

-  [Tools](#Tools)


-  [Data Cleaning/Preparation](#Data_Cleaning/Preparation)
  

-  [Exploration Data Analysis](#Exploration_Data_Analysis)
  

-  [Data Analysis](#Data_Analysis)
  





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







