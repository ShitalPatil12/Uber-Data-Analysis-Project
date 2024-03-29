# Uber-Data-Analysis-Project

## Overview
The objective of this project is to analyze Uber trip data to understand patterns, trends, and user behaviors, ultimately deriving actionable insights to improve service efficiency, customer satisfaction, and operational effectiveness.

## Project Structure
- `UberData.csv`: Dataset containing Uber trip records.
- `UberTripAnalysis.ipynb`: Collab Notebook containing the Python code for data analysis.
- `Uber_data_Analysis.csv` : The final analyzed dataset is saved.


## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn

## Data Understanding
We start by importing the necessary libraries and loading the dataset using pandas. We then perform an initial inspection of the dataset using `uber_df.head()` to understand its structure. The dataset consists of the following columns:
1. `START_DATE`: Date and time when the trip started.
2. `END_DATE`: Date and time when the trip ended.
3. `CATEGORY`: Category of the trip (Business/Personal).
4. `START`: Starting point or location of the trip.
5. `STOP`: Ending point or destination of the trip.
6. `MILES`: Distance traveled during the trip.
7. `PURPOSE`: Purpose or reason for the trip.

## Data Cleaning
We check for and remove duplicate entries. Then, we create new features representing the month and day of the ride, as well as the duration of the ride.

## Data Exploration
We analyze summary statistics of numerical columns and visualize data distributions using histograms and box plots.

## Data Visualization
We visualize various aspects of the dataset, including:
- Distribution of trip categories (`CATEGORY`).
- Distribution of trip purposes (`PURPOSE`).
- Top 10 start and stop locations.
- Distribution of time of day (`TIME_OF_DAY`).
- Distribution of months (`MONTH_OF_THE_RIDE`) and days (`DAY_OF_THE_RIDE`) of the rides.
- Mean time of the day (`TIME_DAY`) for each month.

## Conclusion
The insights derived from this analysis can be valuable for Uber to optimize its services, improve customer experience, and make data-driven decisions.

## Note :
- Data Exploration can be perform another ways using Univariate and multivariate both ways too.
- Uber-Data-Analysis-Project run ongoogle collab.

Feel free to reach out for any queries or suggestions!

**Author:** Shital Patil  
**Contact:** shitalpatil122197@gmail.com
