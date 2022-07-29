# README.md
The README.md GitHub repository contains a brief explanation of the Python code that has been upload.

This is a sample Python file with several lines of code showing how to build a connection to a SQL database. Then we wrote simple and complex queries and read them into a DataFrame, along with many lines of Python code.

We have used the vgsales-2016 Database which contains data on Different Video games list and their Metadata. We will be performing some queries using this data set to get relevant information.

First, we must install all of the Python packages that will be needed for this code. To install all of the required packages, we utilize the Package Manager pip. The following step will be to import the Python libraries that will be used to execute the code. It includes code bundles that may be reused in several apps. It simplifies and facilitates Python programming for the programmer.

We must now create a connection between SQL. SQLConnect connects to both a driver and a data source. We must provide our Host name, User ID, password, and database name. Then we'll read a simple query into the DataFrame. We will read all of the data from the Dataset into a Dataframe and then use the "df.head" function to get an output of the top 10 data from the dataset.

To know the number of records that are available in the dataset we will add the df.shape and to know the size of the elements present we will use the df.size function which in this case is 468. The function df.columns return the names of all the columns in the excel sheet. The "df.types" function will be used to determine the kind of data in the columns of the provided data frame. For example, if the columns include numeric values, the dtype function will return int64 as the data type. If the data is alphabetical, the result will be an object.

The subsequent step is to perform complex queries and read the results into a DataFrame. We chose a few Columns from all the columns in this complex query. And we divided the total of NA_Sales by the total of Global_Sales. And we need the output of the video games that were released after 2005.

Finally, we utilized the WHERE clause, which is used in MySQL databases to filter data based on the criterion specified. Using the WHERE clause, one can retrieve, remove, or change a specific collection of data in the MySQL database.
