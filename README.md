# Investigate Business Hotel using Data Visualization

It is very important for a company to always analyze its business performance. On this occasion, we will explore the business in the hospitality sector more. Our focus is to find out how our customers behave in making hotel reservations, and their relationship to the cancellation rate of hotel reservations. The results of the insights we find will be presented in the form of visualization data to make it easier to understand and more persuasive.

## Data Preprocessing
- Found 4 columns with missing values. The children and agent columns are filled with 0, remove the row containing null values in the city column, and delete the company column because it has a lot of null values, which are 112593 values.
- Found undefined values in the meal, market_segment, and distribution_channel columns. Replace undefined value with mode of each columns.
- Create 2 new columns, namely total_guest and stay_duration. Then drop rows that contains 0 values in total_guest and stay_duration columns.

## Monthly Hotel Booking Analysis Based on Hotel Type

![image](https://user-images.githubusercontent.com/101455281/189301691-a6e15d83-3ea4-4c41-a4cd-6e8aafd86a1d.png)

The number of hotel bookings increases in June - July and November - December every year. Both for the type of city hotel and resort hotel. If you pay attention again, these months coincide with school holidays and year-end holidays. In these months, the hotel must be prepared to face the large number of visitors during the holiday season.

## Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates

![image](https://user-images.githubusercontent.com/101455281/189310459-75ae3102-2bab-44f6-bc01-0e5a191a4599.png)

The graph above shows the trend or correlation between the duration of stay and the rate of cancellation of hotel reservations. Both types of hotels have a positive trend, where the longer the duration of the stay, the higher the probability of the booking being cancelled. As for city hotels, the positive trend is steeper (significant) compared to resort hotels.

## Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate

![image](https://user-images.githubusercontent.com/101455281/189322120-fca661df-d148-4b54-8af7-9b56fd6a13fb.png)

The image above shows the correlation between waiting time (the distance between hotel bookings and arrival times) and hotel booking cancellation rates. The lowest booking cancellation rate is for bookings with a waiting time of less than 30 days and applies to both types of hotels. Resort Hotels are quite stagnant with a 40% cancellation rate, while Urban Hotels have a fairly high ratio (60%) when the waiting time is around 1 year.
