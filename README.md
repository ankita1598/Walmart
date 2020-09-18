# Walmart
Predicting Walmart's weekly sales based upon Unemployment rate, CPI, Markdown1, Markdown2, Markdown3, Markdown4, Fuel rate, Temperature, IsHoliday, Size, date, Store, and department

### Problem Statement

Walmart has collected data of internal and external factors of 45 store to determine their weekly sales. The data consists of Unemployment rate, CPI, markdowns, fuel rate, temperature, etc. The project starts with data preprocessing, cleaning, and data visualization. We will then make models based on Linear regression, Extra tree regression, Random forest regression, K-Nearest Neighbor, Nearest Neighbor classifier, Decision Tree and XGBoosting to predict the weekly sales of the 45 departments. Finally, we will compare the accuracy of all the models to find the best performing model.

### Team Members
| Members  | Username |
| ------------- | ------------- |
|  Lokesh Arora | @lokesh2334 |
| Ankita Shinde  | @ankita1598 |

### Data Dictionary

The dataset consists of 13 columns and 421570 rows.

| Sr. No | Field Name | Data Type | Data format | Description | Accepts Null values? |
| ------ | ------ | ------ | ------ | ------ | ------ |
| 1 | Store | Integer | 1-45 | Describes the store number | N |
| 2 | Department | Integer | 1-98 | Describes the department number | N |
| 3 | Date | Date/Time | mm/dd/yy | Date | Y |
| 4 | Weekly_sales | Double | NN.NN | Sales for the given department for the given store | N |
| 5 | IsHoliday | Boolean | TRUE/FALSE | Describes whether the week is a special holiday week  | N |
| 6 | Temperature | Double | NN.NN | Describes the average temperature in the region | N |
| 7 | Fuel Price | Double | NN.NN | Cost of fuel in the region | N |
| 8 | Markdown(1-5) | Double | NN.NN | Anonymized data related to promotional markdowns that Walmart is running | Y |
| 9 | CPI | Double | NN.NN | Consumer Price Index | N |
| 10 | Unemployment | Double | NN.NN | The Unemployment rate | N |


### SPAP plan for the Project

**Goal:** Predict Weekly sales of Walmart

**Dependent Variable:** Weekly Sales

**Specific Questions:** Q1: Do the markdowns during a specific holiday improve the weekly sales of a particular department?, Q2: Does external factors for the week affect the sales of a store for that week?

**Independent Variable:** Unemployment rate, CPI, Markdown1, Markdown2, Markdown3, Markdown4, Fuel rate, Temperature, IsHoliday, Size, date, Store, and department.

**Specific Analysis and Graphs:** Weekly sales by store, Weekly sales by Department, Overall monthly sales, Top performing departments, and least performing department.

### References
[https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview)
