# House-Price-Prediction
We have the data for house sale price along with various pieces of information about the house, its location, and the sale type and condition. In this project, we will try to clean the data, model the data and plot some graphs and find out the important feature variables and values using Python.

### Task 1 : Reading the Data
Here we get all the information related to House information and price.

### Task 2 : Data Analysis
We can analysis the data by plotting a graph.

### Task 3 : Data Cleaning
Now we need to clean the data where by finding the missing data, null data and will drop the 0 values.

3.1 : Checking outlayers and plotting graph: by the graph we identified that outlayers are there.
Arranged the data so that all o values we got.

### Task 4 : Datatype of features
We had numerical values and filtered to get the names only and shown categorically too.

### Task 5 : Lock Transformation
We plotted a graph to see the sales price and categorical values

### Task 6 : Change categorical string to representative numbers
Categorized MSzoning

6.1 : converting MSZoning to numerics - 
Converted the MSzoning in numeric values and added tranformed price

6.2 Dropping ID, Sales price and transformed price - 
We dropped the ID, sales price and transformed price

### Task 7 : Cross Validation
Now we will cross validate the data using Ridge and Lasso regression

7.1 : Importing Ridge, Lasso and GridsearchCV

7.2 Lasso Cross validation

Converted dictionary to dataframe,
we find out the mean test score and mean train score to test overfitting

7.3 Plotting to test overfitting

We got train score and test score, no overfitting

7.4 Ridge Cross validation

coverting dictionary to dataframe, 
Converting to float

7.5 Plotting to test overfitting
We got train score and test score, no overfitting

# Conclusion:
In this project We have the data for house sale price along with various pieces of information about the house, its location, and the sale type and condition. In this project, we cleaned the data, modelled the data and plot some grapgs and find out the important feature variables and values using Python. We got tranformed price and we did cross validation of the data with Lasso and Ridge approach and tested overfitting.




