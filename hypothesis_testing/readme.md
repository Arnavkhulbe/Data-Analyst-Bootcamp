# 📊 Inferential Statistics & Hypothesis Testing

## 📚 Contents

1. Hypothesis Testing
2. P-value
3. Z-Test
4. Student's t-Distribution
5. T-Test
6. Z-Test vs T-Test
7. Type I & Type II Errors
8. Bayes' Theorem

---

# 1. Hypothesis Testing

## Definition

Hypothesis Testing is a statistical method used to determine whether there is enough evidence from a sample to support or reject a claim about a population.

## Why do we need it?

- We cannot collect data from the entire population.
- We collect a sample and make decisions about the population.

---

## Hypotheses

### Null Hypothesis (H₀)

Default assumption.

Usually assumes **no difference**, **no effect**, or **no change**.

Example

H₀ : μ = 50

---

### Alternative Hypothesis (H₁)

Opposite of the null hypothesis.

Claims that a difference or effect exists.

Examples

H₁ : μ ≠ 50

H₁ : μ > 50

H₁ : μ < 50

---

## Steps of Hypothesis Testing

1. Define H₀ and H₁
2. Choose Significance Level (α)
3. Select the appropriate statistical test
4. Calculate the Test Statistic
5. Find P-value or Critical Value
6. Reject or Fail to Reject H₀

---

# 2. P-value

## Definition

P-value is the probability of obtaining the observed result (or a more extreme result) assuming the Null Hypothesis is true.

## Decision Rule

If

P-value < α

→ Reject H₀

If

P-value ≥ α

→ Fail to Reject H₀

---

## Interpretation

Small P-value

- Strong evidence against H₀
- Reject H₀

Large P-value

- Weak evidence against H₀
- Fail to Reject H₀

---

# 3. Z-Test

## Definition

A Z-Test is used to compare a sample mean with a population mean when:

- Population standard deviation (σ) is known.
- Sample size is large (n ≥ 30).

---

## Formula

Z = (x̄ − μ) / (σ / √n)

---

## Applications

- Manufacturing
- Medical Research
- Quality Control
- Machine Learning Experiments

---

# 4. Student's t-Distribution

## Definition

Student's t-distribution is similar to the Normal Distribution but has heavier tails.

## Why?

Because the population standard deviation is unknown.

---

## Characteristics

- Symmetric
- Bell-shaped
- Heavier tails
- Approaches Normal Distribution as sample size increases

---

# 5. T-Test

## Definition

T-Test compares means when the population standard deviation is unknown.

---

## Types

### One Sample T-Test

Compare sample mean with population mean.

---

### Independent T-Test

Compare means of two independent groups.

Example

Class A vs Class B

---

### Paired T-Test

Compare measurements before and after treatment.

Example

Weight before and after exercise.

---

## Formula

t = (x̄ − μ) / (s / √n)

where

s = Sample Standard Deviation

---

# 6. Z-Test vs T-Test

| Feature | Z-Test | T-Test |
|----------|---------|---------|
| Population SD | Known | Unknown |
| Sample Size | Large | Small |
| Distribution | Normal | Student's t |
| Statistic | Z | t |

---

# 7. Type I and Type II Errors

## Type I Error (False Positive)

Reject a true Null Hypothesis.

Probability

α

Example

Concluding a medicine works when it actually doesn't.

---

## Type II Error (False Negative)

Fail to reject a false Null Hypothesis.

Probability

β

Example

Concluding a medicine doesn't work when it actually does.

---

## Summary

| Error | Meaning |
|---------|----------|
| Type I | Reject True H₀ |
| Type II | Accept False H₀ |

---

# 8. Bayes' Theorem

## Definition

Bayes' Theorem updates the probability of an event using new evidence.

Formula

P(A|B)

=

[P(B|A) × P(A)] / P(B)

---

## Applications

- Spam Detection
- Disease Diagnosis
- Fraud Detection
- Recommendation Systems
- Machine Learning

---

# Confidence Level

Confidence Level

=

1 − α

Common Values

| Confidence Level | α |
|------------------|------|
| 90% | 0.10 |
| 95% | 0.05 |
| 99% | 0.01 |

---

# Confidence Interval

Confidence Interval estimates the range within which the true population parameter is likely to lie.

General Formula

Sample Mean ± Margin of Error

---

# Choosing the Correct Test

| Situation | Test |
|------------|------|
| Compare one sample mean (σ known) | Z-Test |
| Compare one sample mean (σ unknown) | One Sample T-Test |
| Compare two independent means | Independent T-Test |
| Compare before vs after | Paired T-Test |
| Compare 3 or more means | ANOVA |
| Compare categorical variables | Chi-Square Test |

---

# Key Takeaways

- Hypothesis Testing helps make decisions using sample data.
- H₀ is the default assumption.
- P-value measures evidence against H₀.
- Z-Test uses known population standard deviation.
- T-Test uses sample standard deviation.
- Student's t-distribution is used for small samples.
- Type I Error → False Positive.
- Type II Error → False Negative.
- Bayes' Theorem updates probabilities using new evidence.
- Confidence Interval estimates the likely range of the true population parameter.

---

# Quick Revision

- H₀ → Default assumption
- H₁ → Alternative claim
- P-value < α → Reject H₀
- P-value ≥ α → Fail to Reject H₀
- Z-Test → σ known
- T-Test → σ unknown
- ANOVA → Compare 3 or more means
- Chi-Square → Compare categorical variables
- Bayes → Update probability with evidence