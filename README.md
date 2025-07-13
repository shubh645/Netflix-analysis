# Netflix-analysis

## Overview
This repository focuses on analyzing Netflix user data to understand various aspects of customer behavior, subscription patterns, and engagement. It involves loading the dataset, performing initial data inspection, and setting the groundwork for deeper analytical insights.

## Data Source
The analysis in Jupyter notebook of this repo is based on the `Netflixdata.csv` file. This dataset contains detailed information about Netflix customers, including:
* `customer_no` and `customer_id`: Unique identifiers for customers.
* `age` and `gender`: Demographic information about the users.
* `subscription_type`: The type of subscription a user has.
* `watch_hours` and `avg_watch_time_per_day`: Metrics related to user viewing habits.
* `last_login_days`: The number of days since the last login.
* `region` and `device`: Information about user location and access device.
* `monthly_fee`: The monthly subscription cost.
* `churned`: Indicates whether a customer has churned.
* `payment_method`: The payment method used by the customer.
* `number_of_profiles`: The number of profiles associated with an account.
* `favorite_genre`: The user's preferred content genre.

## Libraries Used
The following Python libraries are integral to the operations performed in the jupyter notebook:
* `pandas`: Employed for efficient data manipulation and analysis, particularly for handling CSV data and DataFrame operations.
* `numpy`: Utilized for numerical computing tasks.
* `matplotlib.pyplot`: Used for creating static, animated, and interactive visualizations in Python.

## Analysis Highlights
The notebook of this repository initiates the analysis with fundamental steps:
* **Data Loading**: The `Netflixdata.csv` file is loaded into a pandas DataFrame.
* **Initial Data Inspection**: The `info()` method is used to display a summary of the DataFrame, including data types, non-null values, and memory usage. This helps in understanding the completeness and structure of the dataset.

This repo serves as a foundation for further in-depth analysis, such as exploring customer demographics, identifying factors contributing to watch hours, analyzing churn rates, and understanding genre preferences.

## Usage
To execute the code in Notebook of repo, ensure that you have Jupyter Notebook installed along with the required Python libraries (`pandas`, `numpy`, `matplotlib`). Make sure the `Netflixdata.csv` file is accessible from the notebook's directory, or update the file path in the code as necessary.
