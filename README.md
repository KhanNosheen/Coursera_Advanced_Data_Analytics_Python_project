# Coursera_Advanced_Data_Analytics_Python_project
My personal collection of Artificial Intelligence and Machine Learning projects, experiments, and notebooks.
# 🚕 NYC Yellow Taxi Trip Data Cleaning and Preprocessing (Python)

## Overview

This project focuses on the crucial initial phases of a data science lifecycle: **data loading, cleaning, transformation, and exploratory data analysis (EDA)**. Using the real-world NYC Yellow Taxi Trip Records dataset, the objective was to transform raw, messy trip data into a clean, structured format ready for downstream modeling, while extracting initial, actionable business insights.

This project was completed as part of the [Specify the Coursera Specialization Name, e.g., Advanced Data Analytics Specialization].

## 🛠️ Data Preprocessing & Transformation Highlights

* **Handling Outliers:** Identified and removed or capped outliers related to trip distance, fare amounts, and passenger counts (e.g., zero-fare trips, distances > 50 miles) to ensure data integrity.
* **Feature Engineering:** Created new features, such as **trip duration** (from pickup/dropoff timestamps) and **time-based features** (hour of day, day of week) to better analyze trends.
* **Data Cleaning:** Addressed over **No** missing or inconsistent values (e.g., invalid geographical coordinates) 

* **Data Validation:** Performed validation checks to ensure logical consistency (e.g., verifying that dropoff time is always after pickup time).

## 📊 Key Insights from Exploratory Data Analysis (EDA)

The preprocessing effort enabled the following key insights:

* **Payment Types::**  Check the distribution of payment types used in the dataset by counting the occurrences of each payment type. This helps to understand the preferred payment methods among passengers. The most common payment type is '1', followed by '2', '3', and '4' which is 'credit card' payment.
* **Vendor Analysis::** Count the number of trips serviced by each vendor to understand their market share in the dataset. This analysis helps to identify which vendors are more active in providing taxi services. We found that VendorID '2' has serviced more trips compared to VendorID '1', indicating a larger market presence for VendorID '2'.
* **Filter the data for Credit Card Payment::**  Filter the data for credit card payments only and analyze the distribution of passenger counts for these trips. 

## ⚙️ Technical Stack

* **Language:** Python
* **Core Libraries:** `pandas` and `numpy` for efficient data cleaning and manipulation.
* **Environment:** Jupyter Notebook

## 📁 Repository Structure
