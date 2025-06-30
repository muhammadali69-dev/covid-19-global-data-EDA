# covid-19-global-data-EDA
analysed the global covid 19 data
Project Title: Exploratory Data Analysis (EDA) on COVID-19 Global Cases

Objective:
The main goal of this project was to perform basic exploratory data analysis on a COVID-19 dataset. I wanted to understand how the virus spread across different countries, how many people were affected, recovered, and unfortunately lost their lives. Through this, I also practiced data cleaning, analysis, and visualization using Python libraries like Pandas, Matplotlib, and Seaborn.

Steps I Followed:

Dataset Selection:
I found a publicly available COVID-19 dataset from Kaggle that contained the columns I needed: Date, Country, Confirmed, Deaths, and Recovered cases.

Imported Required Libraries:
I started by importing the necessary Python libraries such as Pandas, Matplotlib, and Seaborn.

Loading the Dataset:
Using Pandas, I loaded the CSV file into a DataFrame and checked the top 5 rows to get an idea of the data structure.

Data Cleaning:
I checked for missing values and duplicate records. Luckily, there were no duplicates, but a few null values were present, which I handled accordingly. I also verified that all the columns had the correct data types.

Basic Data Analysis:

I explored the dataset using functions like .info() and .describe() to see basic statistics.

Found out the total number of unique countries in the data.

Identified the top 10 countries most affected by COVID-19 in terms of confirmed cases and deaths.

Data Visualization:
To make the analysis more insightful, I created:

A line chart to show how confirmed cases increased over time globally.

A bar chart displaying the top 10 countries with the highest death counts.

A pie chart illustrating the proportion between total recovered cases and deaths worldwide.

Observations:
Through the analysis, I noticed:

Certain countries consistently had higher cases and death counts.

There was a steady increase in cases globally during specific months.

The recovery rate was significantly higher than the death rate globally, which was a positive takeaway.

Conclusion:
This project helped me get more comfortable working with real-world data. I learned how to clean data, perform group-based analysis, and create visualizations to support my findings. It was a good hands-on experience to see how data can tell meaningful stories when properly analyzed.

Tools Used:

Python

Google Colab

Pandas

Matplotlib

Seaborn
