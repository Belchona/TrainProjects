# 7. AB test
Data Analysis projects

7. Together with the marketing department, I have prepared a list of hypotheses for revenue increasing. I've prioritize hypotheses, I've run an A / B test, and have analyzed the results. 
I had to decide what to do:
- Stop the test, record the victory of one of the groups.
- Stop the test, fix the absence of differences between groups.
- Continue the test.

We have 2 datasets: visitors and orders.
During A / B test analysis I did these steps:
- Created a graph of cumulative revenue by group.
- Plotted the cumulative average receipt by group.
- Plotted the relative change in the cumulative average check of group B to group A.
- Plotted the cumulative conversion rate by group.
- Plotted the relative change in the cumulative conversion of group B to group A.
- Created a dotted graph of the number of orders by user.
- Calculated the 95th and 99th percentiles of the number of orders per user. Selected a border to identify abnormal users.
- Constructed a scatter plot of the values of orders.
- Calculated the 95th and 99th percentiles of the order value. Select the boundary for the determination of anomalous orders.
- Calculated the statistical significance of differences in conversion between groups based on raw data.
- Calculated the statistical significance of differences in the average order receipt between groups based on " raw " data.
- Calculated the statistical significance of differences in conversion between groups based on" cleared " data.
- Calculated the statistical significance of differences in the average order receipt between groups based on" cleared " data.
- Made a decision based on the test results and explain it.
- Made conclusions and assumptions.


What conclusions can we draw from the test? Available facts:

- There are statistically significant differences in the conversion rate between groups for both "raw" and data after filtering anomalies;
- For raw data and for purified data, there is a difference in the conversion of groups A and B (p-value = 0.023 less than 0.05)
- there Is no statistically significant difference in the average check between the groups, either for "raw" or for data after filtering anomalies (P-value for purified data = 0.839, significantly more than 0.05)
- The conversion difference graph between groups reports that the results of group B exceed the results of A and is fixed at a level greater than +0.1 image. png
- The graph of the difference in the average receipt shows that the results of group B are generally higher than the results of group A: image. png

Based on the discovered facts, the test should be stopped and recognized as successful.
- The conversion rate increases significantly by +0.1% in group B.
- The experiment does not affect the average receipt.
- Our experiment increased the conversion rate, but did not affect the average receipt in any way.
