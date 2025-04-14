# DJIA Exploratory Data Analysis (1914–1968)

# Introduction

In this project, I performed an Exploratory Data Analysis (EDA) on historical data from the Dow Jones Industrial Average (DJIA), 
one of the oldest and most widely followed stock indices, covering monthly values from December 1914 to December 1968. 
The goal was to better understand stock market performance, detect patterns, identify trends, and explore major historical anomalies like the Great Depression crash.

# About the Dataset

The dataset I used contained 649 monthly records of the DJIA, structured with two columns:

- **Date**: The first day of each month (YYYY-MM-DD).
- **Price**: The DJIA closing index value on that date.

# Tools 

- Python
- Jupyter Notebook
- Pandas (data manipulation)
- NumPy (numerical calculations)
- Matplotlib & Seaborn (data visualization)

#  Steps

# 1. Data Preparation and Exploration
I started by loading and exploring the data using Pandas to ensure there were no missing values and to understand its structure clearly.

# 2. Calculating Summary Statistics
Using built-in functions from Pandas, I calculated essential statistics to summarize the data clearly:
- **Mean:** Approximately 290.8
- **Median:** Approximately 172.3
- **Standard Deviation:** Approximately 256.1
- **Minimum:** 46.85 (occurred during the Great Depression)
- **Maximum:** 985.93 (peak in the 1960s)

These statistics provided initial insights into market volatility, growth, and major historical fluctuations.

# 3. Visualizing Data Distribution
I created visualizations to better understand the dataset's distribution:

- **Box Plot:** Highlighted the median, quartiles, and potential outliers, clearly showing significant data skewness and distribution.
- **Violin Plot:** Provided a deeper visualization of the data density, showing where most DJIA values clustered and highlighting the skew towards higher values over time.

# 4. Time Series Analysis
A detailed line chart helped illustrate the DJIA performance clearly over the decades. This step visually highlighted historical periods such as the rapid growth in the 1920s, the massive crash in 1929, the prolonged recovery through the Great Depression, and the post-WWII economic boom.

# 5. Trend Analysis (Line of Best Fit)
I applied NumPy’s polyfit and poly1d functions to create a "line of best fit," revealing an average monthly increase of roughly 1.13 points. This quantified the general upward trend across the analyzed period.

# Key Findings
- The DJIA significantly increased overall (from about 55 points to nearly 1000 points between 1914–1968).
- The dataset reflected high volatility, especially during events like the 1929 crash and subsequent Great Depression.
- The calculated statistical measures and visualizations demonstrated clear upward market trends and highlighted critical historical anomalies effectively.

Thank you for reviewing my project. Feel free to explore the provided notebook for detailed code.
