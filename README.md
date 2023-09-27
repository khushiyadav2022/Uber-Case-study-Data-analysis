

# Uber-Case-study-Data-analysis
An in-depth analysis of Uber's business model, growth strategies, and impact on the transportation industry.
![](https://0701.static.prezi.com/preview/v2/meun2ytoymcmeinmx4ygrlirvt6jc3sachvcdoaizecfr3dnitcq_3_0.png)

# About Dataset:
There are six attributes associated with each request made by a customer:

**Request id:** A unique identifier of the request

**Time of request:** The date and time at which the customer made the trip request

**Drop-off time:** The drop-off date and time, in case the trip was completed

**Pick-up point:** The point from which the request was made

**Driver id:** The unique identification number of the driver

**Status of the request:** The final status of the trip, that can be either completed, cancelled by the driver or no cars available

[Notebook](https://github.com/khushiyadav2022/Uber-Case-study-Data-analysis/blob/08089cf98cfa56683871b7a42e86c9e17de8f089/uber-data-analysis.ipynb)<br>

# Task Performed
1. Which date had the most completed trip durig the two week period?<br>
2. What was the highest no. of completed trips within a 24 hour period?<br>
3. What was the highest no. of completed trips within a 24 hour period of a driver?<br>
4. Which hour of the day had the most requests during the two week period?<br>
5. What is the day with the highest number of requests in the dataset?<br>
6. What percentages of all zeroes during the two week period occurred?<br>
7. What percentage of the total requests were either cancelled or put on hold due to unavailability of cabs?<br>
8. During which time of the day did the majority of the requests occur? Was it during early morning, morning, afternoon, evening, or late night?<br>

# Methodology<br>
**Data Understanding:** Dataset have 6745 rows and 6 columns. In two column, Driver_id and Drop timestamp null values.

**Data Preprocessing:** Here we change the datatype where needed. Dealing with missing value.

**Data Visualization:** Completed all tasks by different visualization.

# Conclusion
- The date with the most completed trips is November 7th, 2016, with 601 completed trips, and the mean of completed trip duration on that date is 1372.5707154742097.
- The highest number of completed trips within a 24-hour period is 47, and it occurred on November 7th, 2016, at 9:00 AM.
- The top drivers who completed the highest number of trips during a 24-hour period are driver id 67, driver id 296, and driver id 178, with each completing 4 trips.
- The highest peak hours for requests occurred in the evening from 6-8 PM. The hour with the most requests during the two week period was 6 PM, with 510 requests, followed by 8 PM with 492 requests, and 7 PM with 473 requests.
- The peak number of requests on a particular day are as follows: Wednesday with 2644 requests, Friday with 1381 requests, Monday with 1367 requests, and Thursday with 1353 requests.
- There were 42% of completed trips, 39% of unfulfilled requests due to unavailability of cars, and 19% of cancelled requests by either the rider or the driver.
- The unavailability of drivers is a significant issue, as it accounts for 58% of the time.
- The highest rush hours are in the evening and morning with 2342 requests, and the least rush time is late night with only 498 requests.

# Message For Business Stakeholder:
Based on the insights provided by the data analysis, here are some recommendations on how to increase business:

- Increase the number of available drivers during peak hours, particularly in the evenings and mornings, to meet the high demand for rides.

- Improve driver retention by providing incentives and benefits that encourage them to remain active on the platform during high-demand periods.

- Increase the efficiency of the ride allocation process to reduce the number of cancelled and unfulfilled requests.

- Expand the service coverage to other areas and increase the number of cars available to provide rides during peak hours.

- Provide incentives to riders for scheduling rides in off-peak hours, thus spreading out the demand and reducing the pressure on drivers during peak hours.

- Utilize machine learning algorithms to optimize the allocation of drivers based on demand and supply patterns, thus increasing efficiency and reducing wait times for riders.

- By implementing these strategies, the ride-sharing company can increase its market share, improve customer satisfaction, and boost revenue.
