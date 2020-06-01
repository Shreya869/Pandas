# Pandas

In short, Pandas is a Software Library in Computer Programming. It is written for the Python Programming Language. They are used in Python to deal with data analysis and manipulation. To put it in simpler words, Pandas help us to organize data and manipulate the data by putting it in a tabular form. It is built on the Numpy package and its key data structure is called the DataFrame. DataFrames allow you to store and manipulate tabular data in rows of observations and columns of variables.

#1. Dataframe

A Data frame is a two-dimensional data structure, i.e., data is aligned in a tabular fashion in rows and columns.

Features of DataFrame
Potentially columns are of different types
Size – Mutable
Labeled axes (rows and columns)
Can Perform Arithmetic operations on rows and columns
Structure

A pandas DataFrame can be created using the following constructor −
pandas.DataFrame( data, index, columns, dtype, copy)
The parameters of the constructor are as follows −
data:-data takes various forms like ndarray, series, map, lists, dict, constants and also another DataFrame.
index:-For the row labels, the Index to be used for the resulting frame is Optional Default np.arange(n) if no index is passed.
columns:-For column labels, the optional default syntax is - np.arange(n). This is only true if no index is passed.
dtype:-Data type of each column.
copy:-This command (or whatever it is) is used for copying of data, if the default is False.
Create DataFrame
A pandas DataFrame can be created using various inputs like −
Lists,dict,Series,Numpy ndarrays,Another DataFrame

#2.Indexing and Selection

Indexing in pandas means simply selecting particular rows and columns of data from a DataFrame. Indexing could mean selecting all the rows and some of the columns, some of the rows and all of the columns, or some of each of the rows and columns. Indexing can also be known as Subset Selection.

#3.Descriptive Statistics 

Descriptive statistics is a study of data analysis to describe, show or summarize data in a meaningful way. It involves the calculation of various measures such as the measure of center, the measure of variability, percentiles and also the construction of tables & graphs.
https://towardsdatascience.com/a-quick-guide-on-descriptive-statistics-using-pandas-and-seaborn-2aadc7395f32

#4.Handling Missing Data

fillna() function of Pandas conveniently handles missing values. Using fillna(), missing values can be replaced by a special value or an aggreate value such as mean, median. Furthermore, missing values can be replaced with the value before or after it which is pretty useful for time-series datasets.
https://towardsdatascience.com/handling-missing-values-with-pandas-b876bf6f008f

#5.Reading and writing Files

A comma-separated values (CSV) file is a plaintext file with a .csv extension that holds tabular data. This is one of the most popular file formats for storing large amounts of data. Each row of the CSV file represents a single table row. The values in the same row are by default separated with commas, but you could change the separator to a semicolon, tab, space, or some other character.
https://realpython.com/pandas-read-write-files/
