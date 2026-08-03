# 📊 Probability Distributions

## 📚 Contents

1. PMF and CDF
2. Bernoulli Distribution
3. Binomial Distribution
4. Poisson Distribution
5. Normal (Gaussian) Distribution
6. Standard Normal Distribution
7. Uniform Distribution
8. Log-Normal Distribution
9. Power Law Distribution
10. Pareto Distribution
11. Central Limit Theorem (CLT)
12. Estimation

---

# 1. Probability Distribution

## Definition

A probability distribution describes how the probabilities of a random variable are distributed over all possible values.

There are two types:

- Discrete Probability Distribution
- Continuous Probability Distribution

---

# 2. PMF (Probability Mass Function)

## Definition

PMF gives the probability of each possible value of a **discrete random variable**.

Example

Rolling a fair dice

P(X=1)=1/6

P(X=2)=1/6

...

P(X=6)=1/6

### Properties

- Used only for discrete variables.
- Probability of every value lies between 0 and 1.
- Sum of all probabilities equals 1.

---

# 3. CDF (Cumulative Distribution Function)

## Definition

CDF gives the probability that a random variable is **less than or equal to** a particular value.

Mathematically

F(x)=P(X≤x)

### Properties

- Used for both discrete and continuous distributions.
- Always increases from 0 to 1.

---

# 4. Bernoulli Distribution

## Definition

A Bernoulli Distribution models an experiment having only **two possible outcomes**.

Examples

- Yes / No
- Success / Failure
- Pass / Fail

Parameter

- p = Probability of Success

Mean

μ = p

Variance

σ² = p(1-p)

Applications

- Email Spam Detection
- Loan Approval
- Binary Classification

---

# 5. Binomial Distribution

## Definition

Binomial Distribution models the number of successes in **n independent Bernoulli trials**.

Conditions

- Fixed number of trials
- Only two outcomes
- Constant probability
- Independent trials

Examples

- Number of heads in 10 coin tosses
- Number of students passing an exam

Parameters

- n = Number of trials
- p = Probability of success

Mean

μ=np

Variance

σ²=np(1-p)

---

# 6. Poisson Distribution

## Definition

Models the number of times an event occurs in a fixed interval of time or space.

Examples

- Calls arriving at a call center
- Customers entering a shop
- Website visits per minute
- Typing mistakes per page

Parameter

λ = Average number of events

Mean

μ=λ

Variance

σ²=λ

---

# 7. Normal (Gaussian) Distribution

## Definition

A continuous probability distribution having a symmetric bell-shaped curve.

Characteristics

- Bell-shaped curve
- Symmetric
- Mean = Median = Mode
- Area under curve = 1

Examples

- Heights
- IQ Scores
- Measurement Errors

---

## Empirical Rule

- 68% data lies within ±1σ
- 95% data lies within ±2σ
- 99.7% data lies within ±3σ

---

# 8. Standard Normal Distribution

## Definition

A Normal Distribution with

Mean = 0

Standard Deviation = 1

Used to calculate Z-Scores.

Formula

Z=(X-μ)/σ

Applications

- Hypothesis Testing
- Confidence Intervals
- P-value Calculation

---

# 9. Uniform Distribution

## Definition

Every value has equal probability.

## Types

### Discrete Uniform Distribution

Finite equally likely values.

Example

Rolling a fair dice.

### Continuous Uniform Distribution

Every value within an interval has equal probability density.

Example

Arrival time of a bus between 10:00 and 10:10.

Characteristics

- Rectangle-shaped PDF
- Constant probability density

---

# 10. Log-Normal Distribution

## Definition

A variable is Log-Normally distributed if its logarithm follows a Normal Distribution.

Characteristics

- Right-skewed
- Values are always positive
- Long right tail

Applications

- Income
- House Prices
- Stock Prices
- Population Growth

---

# 11. Power Law Distribution

## Definition

A distribution where a few observations are extremely large while most are very small.

Characteristics

- Heavy tail
- No typical average
- Extreme values occur more frequently

Applications

- Social Media Followers
- Earthquakes
- Internet Traffic
- Word Frequency

---

# 12. Pareto Distribution

## Definition

A special case of Power Law Distribution based on the 80-20 rule.

Principle

Approximately

- 80% results come from 20% causes.

Examples

- 80% company profit from 20% customers
- 80% bugs from 20% code
- 80% sales from 20% products

Applications

- Business Analytics
- Quality Control
- Machine Learning Feature Importance

---

# Difference Between Power Law and Pareto

| Power Law | Pareto |
|------------|---------|
| General mathematical distribution | Specific Power Law distribution |
| Heavy tail | Heavy tail |
| Used in physics, networks | Used in economics and business |

---

# 13. Central Limit Theorem (CLT)

## Definition

The sampling distribution of the sample mean approaches a Normal Distribution as the sample size becomes large, regardless of the original population distribution.

Conditions

- Random samples
- Independent observations
- Large sample size (typically n ≥ 30)

Importance

- Basis of Hypothesis Testing
- Confidence Intervals
- Z-Test
- T-Test

---

# 14. Estimation

## Definition

Estimation is the process of using sample data to estimate unknown population parameters.

## Types

### Point Estimation

Provides a single estimate.

Example

Sample Mean = 170 cm

### Interval Estimation

Provides a range of likely values.

Example

170 ± 2 cm

or

168 cm – 172 cm

---

# Key Takeaways

- PMF → Discrete probability
- CDF → Cumulative probability
- Bernoulli → One Yes/No experiment
- Binomial → Multiple Bernoulli trials
- Poisson → Count events in time or space
- Normal → Bell-shaped distribution
- Standard Normal → Mean = 0, SD = 1
- Uniform → Equal probability
- Log-Normal → Positive, right-skewed data
- Power Law → Few very large values
- Pareto → 80-20 principle
- CLT → Sample means become Normal
- Estimation → Estimate population using sample