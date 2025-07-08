# WebScrapping-EDA -on-E commerce Amazon
This project involves web scraping headphone listings from Ecommerce and conducting detailed exploratory data analysis (EDA) to uncover consumer trends and product insights. 

Objective
The objective of this project is to automate the extraction of headphones from AMAZON using web scraping and transform it into a structured dataset.

This dataset is then used to perform exploratory data analysis (eda) on key features such as ratings, models, color, type, discounts, and pricing of multiple brands.

The goal is to uncover meaningful patterns, trends, and insights that can inform consumer behavior, brand preferences, and market opportunities in the industry.

Tech Stack & Libraries
Language: Python

Web Scraping: requests, BeautifulSoup

Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn

IDE: Jupyter Notebook

Features Extracted
Brand, Model, Colour, Type, Rating, Counts of ratings, Discounted price, Original price, Brought frequency

Exploratory Data Analysis
Data cleaning

Step1: import all the required libraries to perform EDA on data collected.

Step2: clean the data : in this section you have to clean the data like:

removing the special characters, incorrect headers
Incorrect format of the data (invalid values, columns)
converting the data types
Data manipulation:

Identifying and treatment of the missing values
Identifying and treating the outliers (based on the problem statement or data)
summarize data using statistics (e.g, Average, sum, count)
Conclusions
Wireless items are far more common and expensive than wired ones
Products with higher original prices tend to have higher discounted prices. Ptron and amazon offer the biggest discounts, while realme keeps its discounts low.
Boat dominates in popularity, while boult is most frequently purchased. Green and grey is the top color choice, and active black and black are least favored.
Ratings are mostly between 3.0 and 4.5, with wired and wireless products rated very similarly. Realme and truke are with higher average ratings
Higher-rated products attract more reviews, confirming that well-rated items tend to gain more attention
