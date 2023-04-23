# Customer_segmentation

### Methodology
Using a dataset that contains sales orders in a period of time, we will use Python to obtain the frequency, recency and monetary values in the withnessed period. Later with those values we will give `R, F, and M scores` to each customer, that will allow us to cluster them in different segments. Also skew distribution will be applied for imblanced distributions.

- Recency will be the `minimum of 'days_since_last_purchase'` for each customer.
- Frequency will be the `total number of order`s in the period for each customer.
- Monetary, will be the `total value of the purchases` in the period for each customer.

Also using Kmeans to find patterns and test whether or not the algorithm would fit frm analysis. the elbow method was included to choose the number of clusters K
