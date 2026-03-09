Final Project Report ( Used Car Data from Kaggle)

Report Information:

- Introduction
- Data Description
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Key Findings
- Future Work
- Report Summary

1- Introduction:

The goal of this project is to analyze used car data using Python data analysis libraries. This project consists of several basic stages, including: reading data, cleaning data, handling missing and outlier values, creating new features, and finally performing exploratory analysis to understand the relationships within the data .

The data used in the project contains information about cars such as price, year of manufacture, mileage, fuel type, company, and model. My goal for this project is to understand the factors that affect used car prices and extract useful insights from the data .

2- Data description:

The data consists of several columns containing different information about used cars. In my opinion, the most important columns are:

- Price
- Year of manufacture
- Mileage
- Car company
- ModelCar
- gear type

I used the Pandas library in Python to read the data and displayed the first few rows to understand the data format and verify it.

3- Data cleaning:

During the cleaning process, I went through several stages to improve the data for the model.

- I deleted rows that contained missing values in important columns such as price and mileage.
- I removed illogical values such as cars with a price of zero or cars that had traveled an illogical and unrealistic distance.
- I made sure that the data types were correct. For example, price and mileage are numbers that can be handled mathematically.
- Finally, I searched for duplicate rows in the data and deleted them so that they would not affect the model.

4- Feature engineering:

At this stage, I created new features to help me understand the data.

I created a new column for the age of the car. I calculated the age of the car by subtracting the year of manufacture from the current year, 2026. This column helps to understand the effect of the price of the car on its age.

5- Exploratory data analysis:

After preparing the data, I performed an exploratory analysis using graphs and statistics to understand the distribution of the data and the relationship between them.

I used several graphs, including:

- A histogram to see the distribution of car prices, and I found that most car prices are within the average range and few are very high.
- A scatter plot to determine the relationship between price and mileage, and I discovered that the results showed that cars with high mileage were priced lower than cars with low mileage.

I determined the relationship between the age of the car and its price and discovered that newer cars were often priced higher.

\- Key findings:

After the analysis, I learned that:

- The age of the car affects the price.
- The number of kilometers traveled often affects the price reduction.
- Some companies maintain the value of their cars longer than others.
- Most cars fall within the average price range.

These results give a general idea of the used car market.

7- Future work:

I hope to develop this project in the future in several ways:

- I can use a larger set of more detailed information, such as car color and best-selling colors, etc.
- I can create a model to predict the price of a car based on information about its characteristics.
- I can add other characteristics, such as whether it is an agency car, has a modified engine, has been spray-painted, and so on.

8- Summary:

In this project, I analyzed used car data using basic steps and then exploratory analysis through illustrations, which showed me that factors such as the age of the car and the year of manufacture affect the price of the car.

Data Link : -

<https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data>