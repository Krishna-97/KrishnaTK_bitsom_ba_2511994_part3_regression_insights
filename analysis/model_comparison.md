# Model Comparison

## Objective

The purpose of this analysis is to determine which business factors are most strongly associated with monthly sales across retail stores. Three regression models were developed and compared to evaluate their explanatory power and business usefulness.

---

# Model 1: Marketing Spend

### Dependent Variable

Monthly Sales

### Independent Variable

Marketing Spend

## Regression Statistics

| Metric                |    Value |
| --------------------- | -------: |
| R²                    |    0.167 |
| Adjusted R²           |    0.165 |
| Marketing Coefficient |   2.1296 |
| P-value               | 2.48E-14 |

## Interpretation

Marketing spend has a statistically significant positive relationship with monthly sales.

The coefficient indicates that each additional unit of marketing spend is associated with approximately **2.13 additional units of monthly sales**, assuming no other factors are considered.

Although statistically significant, the model explains only **16.7%** of the variation in monthly sales.

This indicates that marketing alone is not sufficient to explain store performance.

### Business Usefulness

Useful for understanding the isolated effect of marketing expenditure, but not suitable for forecasting monthly sales because many other business drivers are ignored.

---

# Model 2: Footfall

### Dependent Variable

Monthly Sales

### Independent Variable

Footfall

## Regression Statistics

| Metric               |    Value |
| -------------------- | -------: |
| R²                   |    0.736 |
| Adjusted R²          |    0.735 |
| Footfall Coefficient |  35.6780 |
| P-value              | 4.75E-94 |

## Interpretation

Footfall has a very strong positive relationship with monthly sales.

The coefficient suggests that every additional customer entering the store is associated with approximately **35.68 additional units of monthly sales**.

The model explains **73.6%** of total sales variation, making it substantially stronger than the marketing-only model.

### Business Usefulness

Footfall is an excellent predictor of monthly sales and provides valuable insights into customer traffic and store performance.

---

# Model 3: Multiple Regression

### Dependent Variable

Monthly Sales

### Independent Variables

* Marketing Spend
* Footfall
* Average Discount Percentage
* Mall Store Dummy Variable

## Regression Statistics

| Metric         |     Value |
| -------------- | --------: |
| R²             |     0.788 |
| Adjusted R²    |     0.786 |
| Significance F | 7.01E-105 |

## Coefficient Summary

| Variable           | Coefficient | P-value | Interpretation                                                                                  |
| ------------------ | ----------: | ------: | ----------------------------------------------------------------------------------------------- |
| Mall Dummy         |   13,815.99 |   0.029 | Mall stores generate higher sales than the reference category.                                  |
| Marketing Spend    |       1.123 |  <0.001 | Positive relationship with sales.                                                               |
| Footfall           |      33.430 |  <0.001 | Strongest positive predictor of sales.                                                          |
| Average Discount % |  -87,633.17 |   0.027 | Higher discounts are associated with lower monthly sales after controlling for other variables. |

---

# Overall Model Comparison

| Model               | Variables                                    |    R² | Business Value |
| ------------------- | -------------------------------------------- | ----: | -------------- |
| Simple Regression 1 | Marketing Spend                              | 0.167 | Low            |
| Simple Regression 2 | Footfall                                     | 0.736 | High           |
| Multiple Regression | Marketing + Footfall + Discount + Mall Dummy | 0.788 | Excellent      |

---

# Strengths and Limitations

## Strengths

* All models are statistically significant.
* Multiple regression explains nearly 79% of sales variation.
* Footfall consistently remains the strongest predictor.
* Marketing contributes positively after accounting for other variables.
* Store location type (Mall) provides additional explanatory power.

## Limitations

* Regression identifies associations rather than cause-and-effect relationships.
* Seasonal demand is not included.
* Competitor pricing is unavailable.
* Promotional campaigns outside discounts are not considered.
* Economic conditions and customer demographics are excluded.

---

# Final Model Selection

The multiple regression model was selected because it has the highest explanatory power (R² = 0.788), incorporates multiple operational drivers, and provides the most useful insights for business planning and decision-making.
