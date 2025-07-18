# DSA-Capstone-Project_Amazon-Product-Review-Analysis-
To use pivot tables and calculated columns to analyze and get insights from the data.

## PROJECT TOPIC: Analysis of Amazon Product Review

### Project Overview: 
The dataset contains information scraped from Amazon product pages, including: 
•       Product details: name, category, price, discount, and ratings 
•       Customer engagement: user reviews, titles, and content 
•       Each row represents a unique product, with aggregated reviewer data 
stored as comma-separated values

### Table of Content
1. Project Topic
2. Project Overview
3. Data Source
4. Tools used
5. Data Cleaning and Preparation
6. Exploratory Data Analysis (EDA)
7. Building of Dashboard
 
### Data Source
Data used for this project is a Secondary data as it was scraped from Amazon product pages. 

### Tools Used
- Microsoft Excel
  - For Data Collection
  - For Data cleaning
    1. By Manipulation 
    2. By Data Munching.  
  - For Data Analysis
  - For Creation of Dashboard

### Data Cleaning and Preparation
In the initial phase of the Data cleaning, and preparations, we performed the following actions;
1. Data loading and Inspection: Checking for missing values and Invalid entries using COUNTBLANK FUNCTION and filters: 2 (Two) Missing values and 1 (one) invalid entry detected.
2. Handling missing variables:  Rating_count Column: Empty cells under "rating_count" column were replaced by the average rating_count.
- Rating Column: Invalid entries under "rating" column were replaced by the average rating.
- Rating_count Column: Empty cells under "rating_count" column were replaced by the average rating_count.
3. Data cleaning and Removing Duplicates: Since each row of the dataset represents a Unique Product, It is important that we remove duplicates as part of the Data Cleanig process.                                       
- Dataset contains 1465 Rows and 14 Columns before Duplicates are removed, Now, Dataset has 1400 Rows and 14Columns

### Exploratory Data Analysis (EDA)
EDA involved the exploring of the data to answer some questions about the data such
These were done with the use of Excel Functions and Pivot tables.

### Building of Dashboard
After performing all analysis with Excel Functions and Pivot tables, we build a Dashboard as shown below. The Dashboard shows different chats of the Exploratory Data Analysis performed on the Data.

![View]<img width="940" height="527" alt="Amazon Product Analysis Dashboard" src="https://github.com/user-attachments/assets/337a3b50-6e36-4ca9-99cb-15e7d1ba9a2b" />



