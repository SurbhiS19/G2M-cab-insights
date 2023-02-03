# G2M Cab DataSets
In the G2M insight for Cab Investment firm project, we will show which company (Yellow Cab or Pink Cab) is the better opportunity to invest in it.

Here are some points before checking the results out:

We use 4 datasets,: Cab_Data.csv City.csv Customer_ID.csv Transaction_ID.csv US Bank holidays.csv

Profit is defined by me: Profit = Price Charged - Cost of Trip

"df_total" is a dataframe is created by merging mentioned 5 dataframes : The days which is not a holiday, has "-" value in "Holiday" column After Merging if any record has at least 1 NaN value, the whole record is dropped. it means we do not have enough information of that trip

Hypothesis and Conclusions are provided in the notebook

