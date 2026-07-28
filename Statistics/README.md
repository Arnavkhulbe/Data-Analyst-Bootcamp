# 📊 Statistics

## 📚 Module 1: Introduction to Statistics

---

# What is Statistics?

### Definition
**Statistics** is the science of **collecting, organizing, analyzing, interpreting, and presenting data** to support decision-making.

---

# What is Data?

### Definition
**Data** refers to facts, observations, measurements, or pieces of information collected for analysis.

### Examples

- Student Heights
- Student Weights
- Student IQ
- House Prices
- Sales Data
- Temperature

---

# Applications of Statistics

Statistics is widely used in Data Science and Machine Learning.

### Major Applications

- Data Exploration and Summarization
- Model Building and Validation
- Statistical Analysis
- Hypothesis Testing
- Optimization and Decision Making
- Business Reporting
- Data Visualization

---

# Types of Statistics

Statistics is divided into two major branches.

## 1. Descriptive Statistics

### Definition

Descriptive Statistics is used to **summarize, organize and describe data**.

It helps us understand the characteristics of a dataset.

### Topics Included

- Measures of Central Tendency
  - Mean
  - Median
  - Mode

- Measures of Dispersion
  - Range
  - Variance
  - Standard Deviation

- Data Distribution
  - Histogram
  - Box Plot
  - Pie Chart
  - PDF
  - PMF

- Summary Statistics
  - Five Number Summary
    - Minimum
    - Q1
    - Median (Q2)
    - Q3
    - Maximum

### Example Questions

- What is the average height of students?
- What is the highest salary?
- What is the median age?

---

## 2. Inferential Statistics

### Definition

Inferential Statistics uses **sample data** to make conclusions or predictions about the **entire population**.

### Topics Included

- Hypothesis Testing
- P-value
- Confidence Interval
- Statistical Tests
  - Z-Test
  - T-Test
  - ANOVA (F-Test)
  - Chi-Square Test

### Example Questions

- Will customers buy the product?
- Is the average height of sampled students similar to the whole college?
- Can we predict house prices?

---

# Descriptive vs Inferential Statistics

| Descriptive Statistics | Inferential Statistics |
|-------------------------|-----------------------|
| Describes existing data | Makes predictions about population |
| Uses complete data | Uses sample data |
| No prediction | Prediction and decision making |
| Mean, Median, Mode | Hypothesis Testing, Confidence Interval |

---

# Population and Sample

## Population

### Definition

A **Population** is the **entire collection of individuals or objects** that we want to study.

### Characteristics

- Complete set of observations
- Represented using **Parameters**
- Includes every member

### Common Parameters

- Population Mean (μ)
- Population Variance (σ²)

### Examples

- All students in a school
- All consumers in a city
- All patients suffering from a disease

---

## Sample

### Definition

A **Sample** is a **subset of the population** selected for analysis.

### Characteristics

- Small part of population
- Represented using **Statistics**
- Used to estimate population characteristics
- Should be randomly selected

### Common Statistics

- Sample Mean
- Sample Variance

### Examples

- 50 students from a school
- 500 consumers from a city
- 200 patients in a medical study

---

# Population vs Sample

| Population | Sample |
|------------|---------|
| Entire group | Subset of population |
| Uses Parameters | Uses Statistics |
| More expensive | Less expensive |
| More time consuming | Faster |

---

# Sampling

## Definition

Sampling is the process of selecting a subset of individuals from a population.

---

# Types of Sampling Techniques

Sampling techniques are divided into two categories.

```
Sampling
│
├── Probability Sampling
│
└── Non-Probability Sampling
```

---

# Probability Sampling

Every member has a **known and equal probability** of being selected.

## 1. Simple Random Sampling

### Definition

Every individual has an equal chance of selection.

### Example

Randomly selecting students from a class.

---

## 2. Systematic Sampling

### Definition

Select every **nᵗʰ** individual after choosing a random starting point.

### Example

Every 10th customer entering a mall.

---

## 3. Stratified Sampling

### Definition

Divide the population into homogeneous groups (**Strata**) and randomly sample from every group.

### Example

Selecting employees from every department.

---

## 4. Cluster Sampling

### Definition

Divide the population into clusters and randomly select some clusters.

Study everyone inside the selected clusters.

### Example

Randomly selecting schools and surveying every teacher inside them.

---

## 5. Multistage Sampling

### Definition

Uses multiple sampling methods together.

### Example

Select cities → Select schools → Select students.

---

# Non-Probability Sampling

Selection is **not random**.

---

## 1. Convenience Sampling

### Definition

Select individuals who are easiest to reach.

### Example

Surveying people in a shopping mall.

---

## 2. Judgment (Purposive) Sampling

### Definition

Researcher selects participants using personal judgment.

### Example

Interviewing domain experts.

---

## 3. Snowball Sampling

### Definition

Existing participants recruit future participants.

### Used For

Hidden or rare populations.

### Example

Rare disease surveys.

---

## 4. Quota Sampling

### Definition

Population is divided into groups and a fixed number of participants are selected from each group.

### Example

Selecting people based on

- Age
- Gender
- Occupation

---

# Types of Data

```
Data
│
├── Quantitative (Numerical)
│
│   ├── Discrete
│   └── Continuous
│
└── Qualitative (Categorical)
    ├── Nominal
    └── Ordinal
```

---

## Quantitative Data

### Definition

Numerical data that can be measured.

### Types

### Discrete Data

Countable values.

Examples

- Number of students
- Number of bank accounts
- Number of children

---

### Continuous Data

Measured values.

Examples

- Height
- Weight
- Temperature
- Speed

---

## Qualitative Data

### Definition

Categorical or descriptive data.

### Types

---

### Nominal Data

Categories without order.

Examples

- Gender
- Blood Group
- City
- Color

---

### Ordinal Data

Categories with ranking.

Examples

- Customer Feedback
- Education Level
- Satisfaction Level

---

# Scales of Measurement

There are four scales of measurement.

```
1. Nominal
2. Ordinal
3. Interval
4. Ratio
```

---

# 1. Nominal Scale

### Definition

Classifies data into categories with **no natural order**.

### Characteristics

- Categorical
- No ranking
- No mathematical operations

### Examples

- Gender
- Blood Group
- Nationality
- Colors

---

# 2. Ordinal Scale

### Definition

Classifies data into ordered categories.

### Characteristics

- Categories
- Ranking exists
- Difference between ranks is unknown

### Examples

- Customer Satisfaction
- Education Level
- Socioeconomic Status

---

# 3. Interval Scale

### Definition

Numerical scale with **equal intervals** but **no true zero**.

### Characteristics

- Ordered
- Equal spacing
- No true zero
- Ratios are not meaningful

### Examples

- Temperature (°C, °F)
- Calendar Years
- IQ Scores

Example

20°C − 10°C = 10°C

Difference is meaningful.

But

20°C is **not twice** 10°C.

---

# 4. Ratio Scale

### Definition

Numerical scale having **equal intervals and a true zero**.

### Characteristics

- Ordered
- Equal intervals
- True zero
- Ratios are meaningful

### Examples

- Height
- Weight
- Distance
- Income
- Age

Example

20 kg is twice 10 kg.

---

# Comparison of Measurement Scales

| Scale | Order | Equal Difference | True Zero | Example |
|--------|:-----:|:----------------:|:---------:|---------|
| Nominal | ❌ | ❌ | ❌ | Gender |
| Ordinal | ✅ | ❌ | ❌ | Customer Rating |
| Interval | ✅ | ✅ | ❌ | Temperature |
| Ratio | ✅ | ✅ | ✅ | Weight |

---

# Quick Revision

### Descriptive Statistics

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Histogram
- Box Plot

### Inferential Statistics

- Sample → Population
- Hypothesis Testing
- P-value
- Confidence Interval
- Z-Test
- T-Test
- ANOVA
- Chi-Square

### Probability Sampling

- Simple Random
- Systematic
- Stratified
- Cluster
- Multistage

### Non-Probability Sampling

- Convenience
- Judgment
- Snowball
- Quota

### Types of Data

- Quantitative
  - Discrete
  - Continuous

- Qualitative
  - Nominal
  - Ordinal

### Measurement Scales

- Nominal → Name
- Ordinal → Order
- Interval → Equal Gap
- Ratio → Equal Gap + True Zero

---

# Key Definitions (Exam-Oriented)

- **Statistics:** Science of collecting, organizing, analyzing, interpreting and presenting data.
- **Data:** Facts or observations collected for analysis.
- **Population:** Entire group under study.
- **Sample:** Subset of the population.
- **Parameter:** Numerical summary of a population.
- **Statistic:** Numerical summary of a sample.
- **Sampling:** Process of selecting a sample from a population.
- **Descriptive Statistics:** Summarizes and describes data.
- **Inferential Statistics:** Draws conclusions about a population using sample data.
- **Discrete Data:** Countable numerical values.
- **Continuous Data:** Measurable numerical values.
- **Nominal Data:** Categories without order.
- **Ordinal Data:** Categories with order.