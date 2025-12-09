# Suicide Rates Overview (1985–2016) — Data Analysis & Insights

This project explores global suicide trends between 1985 and 2016, using the Kaggle dataset:
“Suicide Rates Overview 1985 to 2016” by Russell Yates.
The goal is to understand patterns in suicide rates across countries, genders, age groups, and generations, and perform complete end-to-end data analysis including cleaning, visualization, feature engineering, and insights.

**Dataset Overview**
Rows: 34,857
Columns: 22
Prediction Target: Price (house sale price)
Many columns contain missing values, making this dataset ideal for practicing data preprocessing.

**Dataset Description**
The dataset includes the following columns:
| Feature             | Description                                |
| ------------------- | ------------------------------------------ |
| `country`           | Country name                               |
| `year`              | Year of observation                        |
| `sex`               | Gender (male/female)                       |
| `age`               | Age-group brackets                         |
| `suicides_no`       | Number of recorded suicides                |
| `population`        | Population of that segment                 |
| `suicides/100k pop` | Normalized suicide rate                    |
| `country-year`      | Combined identifier                        |
| `HDI for year`      | Human Development Index                    |
| `gdp_for_year`      | GDP for the year (string → needs cleaning) |
| `gdp_per_capita`    | GDP per capita                             |
| `generation`        | Generation category                        |


**Project Objectives**
Perform Exploratory Data Analysis (EDA)
Clean and preprocess messy fields
Understand suicide trends by gender, age, country, and generation
Study correlations with GDP, population, and HDI
Build visualizations that explain long-term global patterns
Identify high-risk categories and global shifts