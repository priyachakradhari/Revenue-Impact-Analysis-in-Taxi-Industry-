# Hypothesis-Testing-Python-Project

This project involves analyzing a dataset of yellow taxi trips in New York City. The dataset contains key information such as trip distance, fare amount, passenger count, payment type, and trip duration. The primary goal is to perform exploratory data analysis (EDA) to understand the underlying patterns in the data and conduct hypothesis testing, particularly t-tests, to derive meaningful insights.

## Dataset Description: 

The dataset comprises the following columns:

trip_distance: The distance covered during the trip in miles.

fare_amount: The total fare charged for the trip in dollars.

passenger_count: The number of passengers in the taxi during the trip.

payment_type: The method of payment used (e.g., cash, credit card).

duration: The duration of the trip in minutes.

## Exploratory Data Analysis (EDA):

EDA involves summarizing the main characteristics of the data and visualizing them to uncover patterns, anomalies, and relationships between variables. Key steps in EDA include:

Data Cleaning: Handling missing values, correcting data types, and filtering out outliers.

Descriptive Statistics: Calculating measures such as mean, median, standard deviation, and range for each numerical column.

Data Visualization: Creating histograms, bar charts, scatter plots, and box plots to visualize the distribution and relationships of the data.

## Hypothesis Testing:

Hypothesis testing is a statistical method used to make inferences about a population based on sample data. In this project, we'll focus on the following hypotheses:


## Hypothesis 1: The average fare amount for cash payments is different from that for credit card payments.

Null Hypothesis (H0) : There is no difference in the average fare amount between cash and credit card payments.

Alternative Hypothesis (H1): There is a significant difference in the average fare amount between cash and credit card payments.

## Hypothesis 2: The trip duration is independent of the passenger count.

Null Hypothesis (H0): Trip duration is independent of passenger count.

Alternative Hypothesis (H1): Trip duration depends on passenger count.

## T-Testing

A t-test is used to determine if there is a significant difference between the means of two groups. In this project, we will perform the following t-tests:

Two-sample t-test: To compare the average fare amount between cash and credit card payments.

Correlation t-test: To determine if there is a correlation between trip duration and passenger count.

## Tools and Libraries

This analysis will be conducted using Python, leveraging the following libraries and tools:

Pandas: For data manipulation and analysis.

Matplotlib and Seaborn: For data visualization.

Scipy and Statsmodels: For statistical testing and hypothesis testing.

Google Colab: As the development environment for running the Python code.

## Conclusion
By performing EDA and hypothesis testing on the yellow trip dataset, we aim to derive actionable insights into the patterns and factors influencing taxi trip fares, distances, durations, and payment methods in New York City. This project will enhance our understanding of urban transportation dynamics and support data-driven decision-making in the transportation sector.
