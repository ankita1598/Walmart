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

### Key Performance Indicators (KPI’s)


The KPI’s for our project are as follows -

 - **Weekly Sales to Markdown ratio**
 - **Sales of a deaprtment by store**

**What is your desired outcome?**

To increase weekly sales by intoducing new offers and promotions.

**Why does this outcome matter?**

The ratio of Weekly Sales to Markdown will tell us how the offers and promotions are working in order to increase the weekly sales of the store.

**How are you going to measure progress?**

Lower the ratio, greater the progress. When the ratio is low it means sales is good.

**How can you influence the outcome?**

We can influence the outcome by increasing the Markdown values.

**Who is responsible for the outcome?**

The Marketing team and PR team is responsible for the outcome.

**How will you know you have achieved the outcome?**

When the weekly sales are increasing over time and ratio is constant.

**How often will you review progress towards the outcome?**

In order to review progress we need to check the result every week or every 2 weeks.

### Hypothesis

**Department:** The sales of a specific department within a store will increase when markdowns are introduced, especially during special holidays.

**Weekly_Sales:** The weekly sales are affected negatively when the unemployment rate as well as CPI is high.

**Is_holiday:** If it is a holiday week then most of the stores will have better weekly sales and a lower CPI.

**Temperature:** If the average temperature decreases then the sales of stores are affected negatively.

**Consumer Price Index:** The CPI will decrease during holidays and when markdowns are introduced leading to improved weekly sales.

**Markdowns:** Markdowns will improve the sales in all the stores.

### References
[https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/overview)
