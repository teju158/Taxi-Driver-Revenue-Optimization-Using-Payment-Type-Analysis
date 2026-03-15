# Taxi-Driver-Revenue-Optimization-Using-Payment-Type-Analysis
This project analyzes taxi trip data to study how passenger payment methods affect driver revenue. Using data cleaning, exploratory data analysis, and visualization, it identifies patterns in fare amounts across different payment types and provides insights that may help drivers improve their earnings.

## Project Overview

This project analyzes taxi trip data to understand how passenger payment methods influence driver revenue. The goal is to examine whether payment types such as **card or cash** affect fare amounts, trip distance, and passenger behavior. Using data preprocessing, exploratory data analysis, and visualization, the project identifies patterns that may help drivers maximize their earnings.

---

## Objectives

* Analyze taxi trip data to identify revenue patterns.
* Compare fare amounts for different payment methods.
* Study how passenger count and trip distance influence revenue.
* Generate insights that may help drivers improve earnings.

## Dataset

The dataset contains taxi trip records with the following features:

* `tpep_pickup_datetime` – Trip start time
* `tpep_dropoff_datetime` – Trip end time
* `passenger_count` – Number of passengers
* `trip_distance` – Distance traveled during the trip
* `fare_amount` – Total fare charged
* `payment_type` – Passenger payment method

The dataset is included in this repository or can be downloaded from the original data source.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Jupyter Notebook / VS Code

## Project Workflow

### 1. Data Loading

The dataset is loaded using Pandas and initial exploration is performed to understand its structure.

### 2. Feature Engineering

Trip duration is calculated by subtracting pickup time from drop-off time and converting it into minutes.

### 3. Data Cleaning

* Handling missing values
* Removing duplicate rows
* Converting data types
* Filtering unrealistic values

### 4. Data Filtering

The analysis focuses on:

* Payment types **Card and Cash**
* Passenger counts between **1 and 5**
* Positive fare amount, trip distance, and duration

### 5. Outlier Removal

Outliers are detected and removed using the **Interquartile Range (IQR)** method.

### 6. Exploratory Data Analysis

Various visualizations are used to analyze the dataset:

* Box plots for fare comparison
* Histograms for fare and trip distance distribution
* Pie charts for payment preference
* Stacked bar charts for passenger distribution

### 7. Statistical Analysis

A **Q-Q plot** is generated to analyze the distribution of fare amounts.

## Key Insights

* Payment method influences fare distribution patterns.
* Trip distance is strongly related to fare amount.
* Passenger count varies between payment methods.
* Card payments tend to dominate over cash payments in many trips.

## How to Run the Project

1. Clone the repository

git clone https://github.com/yourusername/Taxi-Revenue-Analysis.git

2. Navigate to the project folder

cd Taxi-Revenue-Analysis

3. Install dependencies

pip install pandas numpy matplotlib seaborn statsmodels

4. Open the notebook

jupyter notebook

5. Run the notebook file

Taxi Driver Revenue Optimization.ipynb

---

## Project Structure

Taxi-Revenue-Analysis
│
├── Taxi Driver Revenue Optimization.ipynb
├── README.md
├── dataset/


## Future Improvements

* Build a machine learning model to predict taxi fare revenue.
* Develop an interactive dashboard for revenue insights.
* Perform location-based trip analysis.
