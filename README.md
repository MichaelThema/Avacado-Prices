
# QCTO - Workplace Module

### Project Title: Exploring Hass Avocado Market Trends: A Data-Driven Analysis of Sales and Pricing (2015-2023)
#### Done By: Michael Thema

© ExploreAI 2024

---

## Table of Contents

- [Background Context](#background-context)
1. [Importing Packages](#importing-packages)
2. [Data Collection and Description](#data-collection-and-description)
3. [Loading Data](#loading-data)
4. [Data Cleaning and Filtering](#data-cleaning-and-filtering)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Modeling](#modeling)
7. [Evaluation and Validation](#evaluation-and-validation)
8. [Final Model](#final-model)
9. [Conclusion and Future Work](#conclusion-and-future-work)
10. [References](#references)

---

## Background Context

The purpose of this project is to analyze the sales and pricing trends of Hass avocados in the United States from 2015 to 2023. The project aims to provide insights into how various factors, such as seasonality, regional differences, and economic conditions, influence avocado prices and sales volumes.

By understanding these dynamics, the project seeks to help stakeholders—such as producers, retailers, and consumers—make more informed decisions regarding avocado pricing strategies, inventory management, and market expansion.

### Goals

- **Trend Analysis**: Examine historical trends in avocado prices and sales volumes over the given period, identifying patterns linked to seasonal or regional factors.
- **Regional Comparison**: Compare avocado market dynamics across different regions to understand how local conditions affect pricing and sales.
- **Predictive Modeling**: Develop models to forecast future avocado prices and sales volumes, aiding in planning and decision-making.
- **Impact Assessment**: Assess the impact of external factors, such as economic changes or shifts in consumer preferences, on avocado prices and sales.

---

## 1. Importing Packages

The following Python libraries are used in the project for data manipulation, visualization, and modeling:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning and modeling.
- **Statsmodels**: For statistical modeling.
- **Datetime**: For handling date and time data.

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score
import statsmodels.api as sm
from datetime import datetime

