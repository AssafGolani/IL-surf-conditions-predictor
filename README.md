# IL-surf-conditions-predictor

# Research Question: Is it possible to predict waves height according to history of them.

# Data Acquisition:
I have crawled MSW website to get all the data that I needed.
I had to create account and pay for pro package in order to get the history of the waves.
I have decided to get the data from several beaches that I like and are close to each other.

# Data cleaning:
I had to clean the data such as units from the height/period columns.
I created few dataframes for EDA and ML and used IQR to remove outliers.

# EDA:
I have presented few plots and compared them by years, I have also checked data per month using the avarage df that I created in the previous stage.

# ML:
I have used Random Forest model on 4 different approaches of cross validation.
