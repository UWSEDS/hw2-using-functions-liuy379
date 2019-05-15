# HW2 - Using Functions

##### Final grade: 7/7

-0: In general, it is generally not the best idea to use integer values for boolean condition checks.     


Grade: 2/7     

-3: Didn't show that the dataframe has at least 3 columns     
-1: df.columns.equals(trans.columns) will return False even if you have the same columns but in a different order     
-1: df.dtypes.equals(trans.dtypes) will return False even if you have the same column types but in a different order  

-----

Create a python module (a file with extension ‘.py’) with the following functions:

1. (4 points) Find an on-line data source (e.g., from data.gov). Write python codes that read the on-line file and create a data frame that has at least 3 columns.

1. (3 points) Create the function test_create_dataframe that takes a pandas DataFrame as input and returns True if the following conditions hold:

   1. The DataFrame contains only the columns that you specified in #1.
   1. The columns contain the correct data type
   1. There are at least 10 rows in the DataFrame.
