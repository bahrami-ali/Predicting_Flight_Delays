# Predicting Flight Delays

## Goal
The goal is to predict arrival delays of commercial flights. Often, there isn't much airlines can do to avoid the delays, therefore, they play an important role in both profits and loss of the airlines. It is critical for airlines to estimate flight delays as accurate as possible because the results can be applied to both, improvements in customer satisfaction and income of airline agencies.

**Contributors:** Ali Bahrami and Khaildyn Chan

## Data

We will be working with data from air travel industry. We will have four separate tables:

1. **flights**: The departure and arrival information about flights in US in years 2018 and 2019.
2. **fuel_comsumption**: The fuel comsumption of different airlines from years 2015-2019 aggregated per month.
3. **passengers**: The passenger totals on different routes from years 2015-2019 aggregated per month.
5. **flights_test**: The departure and arrival information about flights in US in January 2020. This table will be used for evaluation. For submission, we are required to predict delays on flights from first 7 days of 2020 (1st of January - 7th of January). We can find sample submission in file _sample_submission.csv_

The data was graciously provided by Lighthouse Labs for our Midterm Project.

## Tools used

1. **Data Extraction:** PostrgreSQL and Pandas
2. **Data preprocessing:** Numpy, Pandas, Sci-kit Learn
3. **Data visualization:** Matplotlib, Seaborn, Plotly, and Tableau
4. **Supervised Machine Learning**: Sci-kit Learn's Linear Reg, Random Forest, and XGBoost


## File Directory

1. **workbench**: Contains all the notebooks and datasets for the project
    - **data:** contains the raw, cleaned, and scaled data
    - **notebooks:** 
        1. data extraction
        2. data preprocessing
        3. exploratory data analysis: 10 separate notebooks
        4. feature selection
        5. modeling
2. **presentation:** contains the presentation slide
3. **output:** contains the prediction on unseen test data



