# **Interquartile Range (IQR)**

## **Written by:** Aarish Asif Khan
## **Date:** 23 January 2024

> # **Interquartile Range (IQR)**

The Interquartile Range (IQR) is a measure of statistical dispersion that describes the spread of a dataset by focusing on the middle 50% of the values. It is a robust statistic, meaning that it is less sensitive to outliers compared to measures like the range.

## **Formula**

The IQR is calculated as the difference between the third quartile (Q3) and the first quartile (Q1) of a dataset.

\[ IQR = Q3 - Q1 \]

Where:
- \( Q1 \) is the first quartile (25th percentile).
- \( Q3 \) is the third quartile (75th percentile).

## **Calculation Steps**

1. **Sort the Data**: Arrange the dataset in ascending order.
2. **Find Q1 and Q3**:
   - \( Q1 \) is the median of the lower half of the dataset.
   - \( Q3 \) is the median of the upper half of the dataset.
3. **Calculate IQR**:
   - \( IQR = Q3 - Q1 \)

## **Interpretation**

The IQR provides a more robust measure of variability because it is not influenced by extreme values. It gives an indication of the range of values where the middle 50% of the data is concentrated. Outliers can significantly affect the range but have a lesser impact on the IQR.

## **Example**

Consider the dataset: 3, 7, 8, 9, 12, 15, 18, 21, 22.

1. Sort the data: 3, 7, 8, 9, 12, 15, 18, 21, 22.
2. Find \( Q1 \) and \( Q3 \):
   - \( Q1 \) (median of the lower half) = 8
   - \( Q3 \) (median of the upper half) = 18
3. Calculate \( IQR \):
   - \( IQR = Q3 - Q1 = 18 - 8 = 10 \)

In this example, the IQR is 10, indicating that the middle 50% of the data is spread over a range of 10 units.

