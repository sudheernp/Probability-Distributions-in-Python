# Probability Distributions in Python

This repository contains Python notebooks for two projects focused on analyzing probability distributions and related statistical techniques using Python.

## Project 1: Modeling with the Normal Distribution

### Introduction
Throughout this notebook, we will use the normal distribution to model our data. We will also compute z-scores to find any outliers in our data. Before getting started, make sure to watch the associated instructional video and complete the in-video question. All of the code we will be implementing and related instructions are contained in this notebook.

### Overview
In this notebook, we will continue with the previous scenario in which you’re a data professional working for the Department of Education of a large nation. Recall that we are analyzing data on the literacy rate for each district, and we have already computed descriptive statistics to summarize your data. For the next part of our analysis, we want to find out if the data on district literacy rate fits a specific type of probability distribution.

### Import Packages and Libraries
Before getting started, we will need to import all the required libraries and extensions. Throughout the course, we will be using pandas and numpy for operations, and matplotlib for plotting. We will also be using two Python packages that may be new to you: SciPy stats and Statsmodels.

- **SciPy**: An open-source software you can use for solving mathematical, scientific, engineering, and technical problems.
- **SciPy Stats**: A module designed specifically for statistics.
- **Statsmodels**: A Python package that lets you explore data, work with statistical models, and perform statistical tests. It includes an extensive list of stats functions for different types of data.

### Key Findings
Using z-scores, we can identify two outlying districts that have unusually low literacy rates: DISTRICT461 and DISTRICT429. The literacy rates in these two districts are more than 3 standard deviations below the overall mean literacy rate.

This analysis provides important information for the government, suggesting that additional funding and resources should be allocated to these two districts to significantly improve literacy.

## Project 2: Analyzing Air Quality Data

### Introduction
The ability to determine which type of probability distribution best fits data, calculate z-score, and detect outliers are essential skills in data work. These capabilities enable data professionals to understand how their data is distributed and identify data points that need further examination.

In this activity, you are a member of an analytics team for the United States Environmental Protection Agency (EPA). The data includes information about more than 200 sites, identified by state, county, city, and local site names. One of your main goals is to determine which regions need support to make air quality improvements. Given that carbon monoxide is a major air pollutant, you will investigate data from the Air Quality Index (AQI) with respect to carbon monoxide.

### Key Observations
- The aqi_log for West Phoenix is slightly above 3 standard deviations of the mean, indicating worse air quality at that site compared to the others in the data.

### Importance of Outlier Detection
Detecting outliers is important because they can reveal two important things, depending on the context: First, they can identify measurements that were taken incorrectly. Second, they can highlight parts of the data that can be focused on to make improvements.

For example, if the aqi_log for West Phoenix is considered an outlier, then that site can be studied further to determine what practices or changes might improve the air quality.

### Key Takeaways
- Plotting the data using a histogram and observing the shape can help determine whether the data is normally distributed.
- The empirical rule can be used to verify whether a distribution is normal.
- The mean and standard deviation are important measures when applying the empirical rule to a distribution.
- Z-score allows you to identify potential outliers in the data.

### Summary for Stakeholders
- The distribution of the aqi_log data is approximately normal.
- Using statistical methods, it was determined that the site at West Phoenix has worse air quality than the other sites.
- Consider allocating more resources toward further examining this site in order to improve its air quality.

---

### Notebooks

1. [Project 1 - Modeling with the Normal Distribution](project1.ipynb)
2. [Project 2 - Analyzing Air Quality Data](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for analyzing probability distributions in Python.

