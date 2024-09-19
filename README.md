Air Passengers Time Series Analysis

Overview
This repository contains a Jupyter Notebook for analyzing the Air Passengers dataset. The analysis includes time series decomposition, rolling statistics, and autocorrelation to identify patterns, trends, and seasonality in monthly air passenger numbers.

Dataset

The dataset used for this analysis is AirPassengers.csv. It contains monthly data of the number of passengers from 1949 to 1960.

Dataset Columns:
   
   Month: The time period in 'YYYY-MM' format.
   
   #Passengers: The number of passengers for each month.

Source:

The dataset is a well-known dataset available in the datasets package in R.

Analysis Performed

The notebook covers the following steps:
   1.	Data Loading and Preprocessing:
         Load the dataset and convert the Month column to a datetime format.
         Set the Month as the index of the DataFrame for easier time series manipulation.
   2.	Exploratory Data Analysis (EDA):
        Plot the original data to observe overall trends and patterns.
        Calculate rolling mean and standard deviation to understand the trend and volatility over a 7-month window.
   3.	Autocorrelation:
        Compute the autocorrelation with different lags to understand the persistence of trends.
   4.	Time Series Decomposition:
        Decompose the time series into trend, seasonal, and residual components using an additive model.
   5.	Visualization:
        Visualize the original time series, rolling statistics, autocorrelation, and decomposed components.
Usage
To run this analysis, follow these steps:
   1.	Clone the Repository:

       git clone https://github.com/<username>/<repository>.git
       cd <repository>


 
   2.	Install Required Libraries: Make sure you have the following Python libraries installed:

     	 •	pandas

     	 •	matplotlib

     	 •	statsmodels

You can install them using:

  	     !pip install pandas matplotlib statsmodels

 4.	 Run the Jupyter Notebook

     Open the Jupyter Notebook (Time_Series_Air_Passengers.ipynb) in your preferred environment.
     Run all cells to reproduce the analysis.
  
  5.	Explore the Results
       	Visualize and interpret the results presented in the notebook.

Files in the Repository
      •	Time_Series_Air_Passengers.ipynb: The main Jupyter Notebook containing the analysis.
      •	AirPassengers.csv: The dataset used for the analysis.
      •	README.md: This file, describing the project and how to use it.
Results
The analysis shows:
      •	A clear upward trend in the number of passengers over time.
      •	Seasonal patterns with regular peaks and troughs each year.
      •	Increasing variability in passenger numbers as indicated by rolling statistics and residuals.

Contributing
   If you would like to contribute to this project, feel free to create a pull request or submit issues for any bugs or feature requests.
License
   This project is licensed under the MIT License.

