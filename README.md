# EDA_

# EDA

# Cars Dataset – Exploratory Data Analysis (EDA) 🚗📊

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a cars dataset to understand relationships between different car features such as **engine power, mileage, transmission type, and price**.

The analysis focuses on:

* Data cleaning
* Visualization
* Finding correlations between features

---

## Dataset Features

Main columns used in the analysis:

* Make
* Model
* Year
* HP (Horsepower)
* Engine Cylinders
* Transmission
* Driven Mode
* MPG_H (Highway MPG)
* city mpg
* Price

---

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Steps Performed

1. Loaded dataset using Pandas
2. Checked dataset structure using `info()` and `describe()`
3. Removed duplicates and unnecessary columns
4. Renamed columns for easier analysis

---

## Visualizations Used

The following plots were used for analysis:

* **Count Plot** → Distribution of categorical variables
* **Bar Plot** → Mean price across categories
* **Scatter Plot** → Relationship between HP and Price
* **Joint Plot** → Combined distribution and relationship
* **Pair Plot** → Relationships between multiple variables
* **Heatmap** → Correlation between numerical features

---

## Correlation Heatmap

A correlation matrix was created to understand relationships between numerical variables.

Example:

```python
corr = df.corr(numeric_only=True)

plt.figure(figsize=(12,8))
sns.heatmap(corr, cmap='BrBG', annot=True)
```

---

## Key Insights

* Higher **horsepower tends to increase car price**.
* Cars with **more engine cylinders usually cost more**.
* **Fuel efficiency decreases as horsepower increases**.

Author Kishan Aspiring Data Scientist | Python & Machine Learning Enthusiast
