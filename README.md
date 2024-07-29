# GlobalTerrorismDB
## data cleaning
I meet problem in reading data normally with pandas so I used
chardet library to know encoding of data
Data encoding is: Windows-1252

handling problems in data

1- a lot of missing values
Drop columns with too large number of missing values \
2- There are 0 in month and day columns
Replace 0 with mode value
3- Unnecessary columns
Delete unnecessary columns
4- Data types
Change datatypes
5- Fromat
Change text columns in consistent fromat (make all text
lower)
6- Rename columns
7-check If data contains duplicates
## Data analysis and visualization
Libraries:
numpy
Pandas
seaborn
matplotlib
