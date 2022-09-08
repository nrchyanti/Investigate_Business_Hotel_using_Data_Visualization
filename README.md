# Investigate Business Hotel using Data Visualization

It is very important for a company to always analyze its business performance. On this occasion, we will explore the business in the hospitality sector more. Our focus is to find out how our customers behave in making hotel reservations, and their relationship to the cancellation rate of hotel reservations. The results of the insights we find will be presented in the form of visualization data to make it easier to understand and more persuasive.

## Data Preprocessing
- Found 4 columns with missing values. The children and agent columns are filled with 0, remove the row containing null values in the city column, and delete the company column because it has a lot of null values, which are 112593 values.
- Found undefined values in the meal, market_segment, and distribution_channel columns. Replace undefined value with mode of each columns.
- Create 2 new columns, namely total_guest and stay_duration. Then drop rows that contains 0 values in total_guest and stay_duration columns.

![image](https://user-images.githubusercontent.com/101455281/189172049-89e76707-3d58-4c6f-b17d-96ef5e4307d6.png)

## 
