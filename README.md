**Data Wrangling in Python**
•	Data Wrangling is a crucial topic for Data Science and Data Analysis. Pandas Framework of Python is used for Data Wrangling. Pandas is an open-source library in Python specifically developed for Data Analysis and Data Science. It is used for processes like data sorting or filtration, Data grouping, etc.
•	Data wrangling in Python deals with the below functionalities:
1.	Data exploration: In this process, the data is studied, analyzed, and understood by visualizing representations of data.
2.	Dealing with missing values: Most of the datasets having a vast amount of data contain missing values of NaN, they are needed to be taken care of by replacing them with mean, mode, the most frequent value of the column, or simply by dropping the row having a NaN value.
•	Reshaping data: In this process, data is manipulated according to the requirements, where new data can be added or pre-existing data can be modified.
1.	Filtering data: Some times datasets are comprised of unwanted rows or columns which are required to be removed or filtered
2.	Other: After dealing with the raw dataset with the above functionalities we get an efficient dataset as per our requirements and then it can be used for a required purpose like data analyzing, machine learning, data visualization, model training etc
**Pandas and Numpy**
3.	Pandas: Python is one of the most popular languages for Machine Learning, Data Analysis, and Deep learning tasks. It is powerful because of its libraries that provide the user full command over the data.
4.	Numpy: Numpy is the fundamental library of Python, used to perform scientific computing. It provides high-performance multidimensional arrays and tools to deal with them
**Data Visualisation**
5.	Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. It's an essential part of data analysis and communication because it allows complex data sets to be understood more easily and quickly

**Code used for Data wrangling and Data Acquistion**
•	   1.To upload Data set in Notebook

Data=Pd.read_csv(“filename.csv”)

•	2.importing important library.

Import pandas as pd
Import numpy as np

•	3.To check top 5 row of data set

Data1.head()

•	4.To check shape of dataset.

Data1.shape()

•	5. To check Unique value in column

 data1.unique
 
•	6.To merge to data set

Data_merge=pd.merge(data1,data2,on =“instant”,how =“inner”)

•	7.To check null value in data set

 data1.isnull().sum()
 
•	8.To check columns name in Data set

Data1.columns

•	9.To drop any unwanted columns in data set 

Data1.drop([“column_name”],axis=1,inplcae=True)

for project info

data.info()

**We can check the outliars in any data by ploting the data in box plot
Syntax**

•	sns.boxplot(data123["atemp"])
•	plt.title("Outliars in atemp")
•	plt.show()

T





