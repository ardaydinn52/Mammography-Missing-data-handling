# Mammography-Missing-data-handling
Missing data filling


	At first, missing values converted pd.NA to handle identify these in pandas dataframe. After, that missing values are decided to be filled in using a KNN. The process can be explained in the following way: since KNN will be used the data min-max scaled to reduce the possibility of an error due to the differences in dimensions. Then, data is split into two parts, one training and one test set. These sets are used put into a KNN value filler with different k between range 1 to 21. KNN filled sets are used to develop different Naïve Bayes classifiers. Best k for this process is selected and dataset is filled according to this k. 
