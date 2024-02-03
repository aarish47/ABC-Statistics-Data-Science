# **Standard Deviation in ABC Statistics**

## **Written by:** Aarish Asif Khan

## **Date:** 23 January 2024

> # **Standard Deviation**

In statistics, the standard deviation is a measure of the amount of variation or dispersion present in a set of data. It indicates how spread out the values in a dataset are relative to the mean (average). 

A low standard deviation suggests that the data points tend to be close to the mean, while a high standard deviation indicates that the data points are spread out over a wider range.

## **Formula**

The standard deviation (\(S\) or \(\sigma\)) is calculated using the following formula:

\[ S = \sqrt{\frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}} \]

Where:
- \(S\) is the sample standard deviation.
- \(n\) is the number of data points in the sample.
- \(x_i\) is each individual data point.
- \(\bar{x}\) is the mean of the dataset.

## **Interpretation**

- **Small Standard Deviation**: Indicates that the data points are closely packed around the mean, suggesting low variability.
- **Large Standard Deviation**: Suggests that the data points are more spread out from the mean, indicating higher variability.

## **Relationship with Variance**

The standard deviation is the square root of the variance (\(S = \sqrt{S^2}\)). It is often preferred for interpretation because it is in the same units as the original data.

## **Example**

Consider the dataset: 4, 7, 9, 11, 13.

1. Calculate the mean: \(\bar{x} = \frac{4 + 7 + 9 + 11 + 13}{5} = 8.8\).
2. Calculate the squared differences from the mean: \((4-8.8)^2, (7-8.8)^2, (9-8.8)^2, (11-8.8)^2, (13-8.8)^2\).
3. Sum the squared differences: \(70.8\).
4. Calculate the variance: \(S^2 = \frac{70.8}{5-1} = 17.7\).
5. Calculate the standard deviation: \(S = \sqrt{17.7} \approx 4.21\).

In this example, the standard deviation is approximately 4.21, providing a measure of the spread of data points from the mean.
