# Data-Cleaning

## Overview
Data cleaning is one of the most important aspects of data analysis. It is so important that the success of any data analysis project depends on how clean your data is. Unclean data will affect the accuracy of Exploratory data analysis
Unclean data will also affect the clarity and the actualization of data visualization. And thus this makes data cleaning an important part of data analysis.
As a rule, before any project is carried out or before any use of data, it is best to carry out data cleaning, this in the long run saves stress and makes work faster.

## Objectives
The goal or objectives of this data is to:
- To learn how to import data from Microsoft Excel into Python
- Clean a call log data making it more useful for call agents that would put a call across to customers
- To utilize all the various Data cleaning techniques and codes in Python to clean up data
- To utilize advanced Python functions like lambda in the cleaning of data


## Special line of codes in this project'

- The data was imported using
  ``` Python
  df = pd.read_excel(r"C:\Users\akinl\Documents\Pandas\Customer Call List.xlsx")
  ```
- Duplicates were removed using
  ``` Python
  df = df.drop_duplicates()
  ```
- The use of lambda functions in Python
  ``` Python
  df["Phone_Number"].apply(lambda x: x[0:3] + '-' + x[3:6] + '-' + x[6:10])
  ```
  You can [view the full code here](https://github.com/TommyDatageek01/Data-Cleaning/blob/main/Data%20Cleaning%20New%20.ipynb)
