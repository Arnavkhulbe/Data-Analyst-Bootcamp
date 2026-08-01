📊 Module 1: Descriptive Statistics
📖 What is Descriptive Statistics?

Definition:

Descriptive Statistics is the branch of statistics that collects, organizes, summarizes, and presents data to describe its main characteristics.

Its purpose is to understand the data, not to make predictions.

📌 1. Measures of Central Tendency

Measures of Central Tendency represent the center or average of a dataset.

Mean

Definition

Mean is the arithmetic average of all observations.

Mean=
N
∑X
	​

Characteristics
Uses all observations
Easy to calculate
Sensitive to outliers
Median

Definition

Median is the middle value of an ordered dataset.

Characteristics
Not affected by outliers
Suitable for skewed data
Mode

Definition

Mode is the value that occurs most frequently in a dataset.

Characteristics
Can have one, two or multiple modes
Useful for categorical data
Difference
Mean	Median	Mode
Average value	Middle value	Most frequent value
Sensitive to outliers	Robust to outliers	Depends on frequency
📌 2. Measures of Dispersion

Measures of Dispersion describe how spread out the data is.

Range

Definition

Difference between the maximum and minimum value.

Range=Maximum−Minimum
Variance

Definition

Variance measures the average squared distance of observations from the mean.

## Population Variance

$$
\sigma^2=\frac{\sum_{i=1}^{N}(x_i-\mu)^2}{N}
$$​

−μ)
2
	​


$$
s^2=\frac{\sum_{i=1}^{n}(x_i-\bar{x})^2}{n-1}
$$
	​

Why do we square the differences?
Removes negative signs
Gives more importance to larger deviations
Makes mathematical calculations easier
Standard Deviation

Definition

Standard Deviation is the square root of variance.

σ=
σ
2
	​

Why do we use it?

Variance is in squared units.

Standard deviation converts it back to the original unit.

Why divide by n−1?

Using the sample mean reduces the spread slightly.

Dividing by n−1 (Bessel's Correction) corrects this underestimation and provides an unbiased estimate of the population variance.

📌 3. Random Variable

A Random Variable assigns a numerical value to each outcome of a random experiment.

Types
Discrete Random Variable

Takes countable values.

Examples

Number of students
Dice outcome
Number of emails
Continuous Random Variable

Takes infinitely many values within an interval.

Examples

Height
Weight
Temperature
Waiting time
📌 4. Percentiles and Quartiles

These describe the position of a value in a dataset.

Percentile

Definition

A percentile indicates the percentage of observations below a particular value.

Example

90th percentile

Means

90% of observations lie below that value.

Quartiles

Quartiles divide data into four equal parts.

Quartile	Meaning
Q1	25%
Q2	50% (Median)
Q3	75%
📌 5. Five Number Summary

The Five Number Summary describes the overall distribution of a dataset.

It consists of

Minimum
Q1
Median (Q2)
Q3
Maximum
Interquartile Range (IQR)

Measures the spread of the middle 50% of data.

IQR=Q3−Q1

Used for detecting outliers.

📌 6. Histogram
Definition

A Histogram is a graphical representation of the frequency distribution of continuous numerical data.

Characteristics
Adjacent bars
Used for continuous data
Shows shape of distribution
Helps identify skewness and outliers
📌 7. Skewness

Skewness measures the asymmetry of a distribution.

Symmetric Distribution
Left and right sides are equal.
Mean = Median = Mode
Positive (Right) Skew

Long tail on the right.

Relationship

Mean>Median>Mode

Examples

Salary
House Prices
Negative (Left) Skew

Long tail on the left.

Relationship

Mean<Median<Mode

Examples

Easy Exam Scores
Retirement Age
📌 Box Plot

A Box Plot is a graphical representation of the Five Number Summary.

Components

Minimum
Q1
Median
Q3
Maximum

Used for

Detecting outliers
Measuring skewness
Comparing distributions
📌 8. Covariance
Definition

Covariance measures the direction of the relationship between two variables.

Interpretation

Positive

Both variables increase together.

Negative

One increases while the other decreases.

Zero

No linear relationship.

Limitation

Covariance does not indicate the strength of the relationship.

📌 Correlation
Definition

Correlation measures both the direction and strength of the relationship between two variables.

Range

−1≤r≤1
Interpretation
Correlation	Meaning
+1	Perfect Positive
0	No Linear Relationship
-1	Perfect Negative
📌 Pearson Correlation

Measures linear relationship between two continuous variables.

Assumptions
Linear relationship
Normally distributed data
Sensitive to outliers

Used when numerical data is linear.

📌 Spearman Correlation

Measures monotonic relationship using ranks.

Instead of original values,

Spearman converts data into ranks and then computes correlation.

Advantages
Works with non-linear monotonic data
Robust to outliers
Works with ordinal data
Pearson vs Spearman
Pearson	Spearman
Uses actual values	Uses ranks
Linear relationship	Monotonic relationship
Sensitive to outliers	Less sensitive
Requires normality	No normality assumption
📌 Feature Selection

Feature Selection is the process of selecting the most relevant features for building a machine learning model.

Why is it important?
Reduces overfitting
Improves accuracy
Reduces training time
Removes irrelevant features
Correlation-based Feature Selection

If two features are highly correlated,

one of them can often be removed to reduce redundancy.