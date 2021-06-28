# All-about-Pandas


**Object creation**
Series
DataFrame
**Viewing data**
Head
Tail
Index
Columns
DataFrame to Numpy
Describe
Transpose
Sort By Axis
Sort by Values
**Selection**
Getting 
Selecting  a Single Column
Selection by Label
Selecting via [], which sices the rows
Getting a cross section using a label
Selecting on a multi-axis by label
Label slicing with both endpoints included
Reduction in the dimensions of the returned object
Getting a scalar value
Seletion by Position
Getting fast access to a scalar (equivalent to the prior method
Select via the position of the passed integers
By integer slices, acting similar to numpy/Python
By lists of integer position locations, similar to the NumPy/Python style
slicing rows explicitly
slicing columns explicitly
Boolean Indexing
getting a value explicitly
getting fast access to a scalar (equivalent to the prior method)
Setting
Using a single column’s values to select data.
Selecting values from a DataFrame where a boolean condition is met.
Using the isin() method for filtering:
Setting a new column automatically aligns the data by the indexes.
Setting values by label:
Missing data
Setting values by position:
Setting by assigning with a NumPy array:
The result of the prior setting operations.
**Operations**
Stats
Apply
A where operation with setting.
Histogramming
String Methods
Reindexing allows you to change/add/delete the index on a specified axis. This returns a copy of the data.
To drop any rows that have missing data.
**Merge**
Concat
Join
**Grouping**
Stack
Pivots
Splitting
Applying
Combining
Grouping and then applying the sum() function to the resulting groups.
Grouping by multiple columns forms a hierarchical index, and again we can apply the sum() function.
Concatenating pandas objects together with concat():
**Reshaping**
Filling missing data.
To get the boolean mask where values are nan.
Performing a descriptive statistic:
Same operation on the other axis:
**Time series**
Time zone representation:
Converting to another time zone:
Converting between time span representations:
Converting between period and timestamp enables some convenient arithmetic functions to be used
Operating with objects that have different dimensionality and need alignment. In addition, pandas automatically broadcasts along the specified dimension.
Applying functions to the data:
**Categoricals**
Convert the raw grades to a categorical data type.
Rename the categories to more meaningful names (assigning to Series.cat.categories() is in place!).
Reorder the categories and simultaneously add the missing categories (methods under Series.cat() return a new Series by default).
Sorting is per order in the categories, not lexical order
Grouping by a categorical column also shows empty categories.
**Plotting**
Getting data in/out
CSV / HDFS / EXCEL
The stack() method “compresses” a level in the DataFrame’s columns.
**Gotchas**

