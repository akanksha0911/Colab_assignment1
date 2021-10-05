# Colab_assignment1
Dataset-cleaning-preprocessing in Colab


Dataset: Here aim is to predict cancellation and how many factors are playing a role.

I have picked the data from kaggle: copy kaggle API to import data from kaggle
!kaggle datasets download -d jessemostipak/hotel-booking-demand

I have used below common methods along with feature engineering, corelation and standard sclar methods to preprocess the data.
Some important and common methods needed to get a better understanding of DataFrames and diagnose potential data problems are the following:

    .head() prints the header of a DataFrame
    .dtypes prints datatypes of all columns in a DataFrame
    .info() provides a bird's eye view of column data types and missing values in a DataFrame
    .describe() returns a distribution of numeric columns in your DataFrame
    .isna().sum() allows us to break down the number of missing values per column in our DataFrame
    .unique() finds the number of unique values in a DataFrame column


    sns.displot() plots the distribution of one column in your DataFrame.

Evaluated different models and compared them.
