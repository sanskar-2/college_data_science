Activity 01: Introduction to Python Programming
Basics of Python
Python is a popular programming language for data science and machine learning due to its simplicity and readability. Understanding Python is crucial for effective coding

Variables and Assignmets:

Variables are used to store data values. Example: x = 10
Some datatypes supported by python are integers(int), floating-point numbers(float), strings(str), booleans(bool), lists(list), dictionaries(dict), etc.
Comments are used to add explanantions or notes within the code. They are preceded by the # symbol.
print Statement is used to display the output on the console. The print() function is used for display.
Class Activity
Dictionaries are versatile data structures in Python that are commonly used in data science and machine learning projects. They allow you to store and retrieve data using key-value pairs.

In the activity, data structures of python are used. With these data structures, the following functions supported are also used.

Activity 02: Python Libraries
Python has libraries with large collections of mathematical functions and analytical tools. In this activity, the following libraries were used:

Pandas
This library is used for structured data operations, like import CSV files, create dataframes, and data preparation

Numpy
This is a mathematical library also known as numeric python. It has a powerful N-dimension array object, linear algebra, Fourier transform, etc.

Matplotlib
This library is used for data visualization. From this library we are able to make scatter plot, line plot, bar graph, histogram, etc.

Activity 03: World Countries dataset
Data Preparation
This is the process of preparing raw data so that it is suitable for further processing and analysis. The following dataset is of .csv(comma separted values) type. To access this dataset, the pandas library is used. The function read_csv() is able to create a dataframe from this dataset. Now, the dataframe is ready for further processing

Data Preprocessing
Functions in python can be used to clean, transform and preprocess the raw data. For example, you can create functions to handle missing values, normalize data, or apply feature scaling. For cleaning of the data , either the rows can be dropped using the dropna() function or the null values can be filled with mean or median of the dataframe using the fillna() function.

Data Visualization
The graphical representation of data and information is known as data visualization. Where visual elements likes charts, graphs, plots can be used. In the activity bar graph, pie chart, scatter plot, line graph and histogram are created.

Activity 04: Pokemon Dataset
Data Reading
The dataset contains all the varieties of pokemon from air to fire. The attack, health and defence are also listed with the corresponding pokemon. From the dataset the question was to find out the legendary pokemon. The legendary pokemon had to be filtered using the statement legend = data[data['LEGENDARY']==True]

Data Cleaning
Another issue with the dataset was, many of the pokemons had their names beginning with mega.To remove this from the name , using the regex function is the only way. On applying this statement: data.index = data.index.str.replace(".*(?=Mega)"," ") , the following names with mega are removed.

Data Visualization
To find out the outliers in the dataset, using the boxplot is the best way. The box plot provides a quick summary of the variablility of values in the dataset. They show the median, upper and lower quartiles, max and min values, and any outliers. Using the heatmap, finds out whether or not there are any features co-relating with each other.


