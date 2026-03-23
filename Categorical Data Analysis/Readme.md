# Experiment 11 — Categorical Data Analysis Using Python

---

**Name:** Bedang Das
**PRN:** 25070123031
**Branch:** ENTC
**Batch:** ENTC-A2

---

## Aim

To explore and analyze categorical data using Python and the Pandas library by performing operations including frequency counting, cross-tabulation, grouping, filtering, and percentage distribution.

---

## Tools Used

- Google Colab / Jupyter Notebook
- Python (Pandas library)

---

## Introduction

Categorical data consists of values that represent distinct groups or labels rather than measurable quantities. Common examples include gender, department, product type, payment method, and mode of delivery.

Analyzing categorical variables is essential to uncovering patterns, trends, and distributions within a dataset. The Pandas library in Python offers a robust set of tools to handle such data effectively — from computing category frequencies to building contingency tables and grouping data by specific attributes.

These methods find widespread application across domains such as business intelligence, consumer behavior studies, academic research, and survey data analysis.

---

## Theory

### 1. Categorical Data

Categorical data captures qualitative attributes that belong to predefined groups. Unlike numerical data, it describes characteristics rather than measurable quantities.

**Common examples:**

- Product category
- Payment method
- Delivery type
- Customer type
- Department
- Gender

Studying categorical variables allows us to detect meaningful patterns and relationships among different groups in a dataset.

---

### 2. Frequency Count

Frequency counting tells us how often each category appears in the dataset — useful for understanding the distribution of values.

**Pandas method:**
```python
df['column_name'].value_counts()
```

---

### 3. Unique Values

Unique values represent all the distinct categories present within a column.

**Pandas methods:**
```python
df['Category'].unique()    # Lists all unique values
df['Category'].nunique()   # Returns the count of unique values
```

---

### 4. Cross-Tabulation

Cross-tabulation (also called a contingency table) is used to examine the relationship between two categorical variables by displaying their joint frequency distribution.

**Pandas method:**
```python
pd.crosstab(df['Column1'], df['Column2'])
```

**Use cases:**
- Category vs. Payment Mode
- Gender vs. Department

---

### 5. Percentage Distribution

Converting raw counts into percentages helps understand the relative proportion of each category.

```python
df['Category'].value_counts(normalize=True) * 100
```

---

### 6. Filtering Data

Filtering extracts only the rows that meet a specific condition.

```python
df[df['Category'] == 'Furniture']
```

This returns all rows where the Category column equals `'Furniture'`.

---

### 7. Grouping Data

Grouping organizes the dataset by one or more categorical columns, enabling more granular analysis within each group.

```python
df.groupby('Category')['Payment_Mode'].value_counts()
```

---

### 8. Sorting Data

Sorting arranges the rows in a desired order based on a chosen column.

```python
df.sort_values(by='Category')
```

---

## Applications

- Analyzing customer purchase behavior
- Market basket analysis
- Evaluating academic performance data
- Interpreting survey responses
- Supporting data-driven business decisions
- Studying demographic distributions

---

## Advantages

- Simplifies the analysis of non-numerical variables
- Highlights relationships and patterns between categories
- Enables efficient data grouping and summarization
- Supports both frequency and proportional analysis
- Easily integrates with visualization libraries for reporting

---

## Conclusion

Categorical data was successfully analyzed using Python and the Pandas library. Operations such as frequency counting, unique value identification, cross-tabulation, filtering, grouping, and percentage distribution were carried out to uncover patterns and relationships present in the dataset. These techniques provide a solid foundation for drawing meaningful insights from qualitative data in real-world analytical tasks.
