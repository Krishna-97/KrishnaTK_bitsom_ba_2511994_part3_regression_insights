# Model Equations

## Simple Regression Model 1

### Equation

Monthly Sales = 560777.35 + 2.1296 × Marketing Spend

### Interpretation

The intercept (560777.35) represents the estimated monthly sales when marketing spend equals zero.

The marketing coefficient (2.1296) indicates that increasing marketing spend is associated with higher monthly sales.

Although statistically significant, this model explains only 16.7% of sales variation.

---

# Simple Regression Model 2

### Equation

Monthly Sales = 446410.58 + 35.6780 × Footfall

### Interpretation

The intercept represents baseline monthly sales.

The footfall coefficient indicates that every additional customer entering the store is associated with approximately 35.68 additional units of monthly sales.

This model explains approximately 73.6% of total sales variation.

---

# Multiple Regression Equation

Monthly Sales

=

405547.77

* 13815.99(Mall Dummy)

* 1.1232(Marketing Spend)

* 33.4296(Footfall)

− 87633.17(Average Discount Percentage)

---

# Interpretation of Coefficients

## Intercept

Estimated monthly sales when all predictor variables equal zero.

## Mall Dummy

Stores located in malls are expected to generate approximately 13,816 additional units of monthly sales compared with the reference store type.

## Marketing Spend

Higher marketing investment contributes positively to sales after controlling for other variables.

## Footfall

Footfall is the strongest predictor in the model.

An increase in customer visits leads to a substantial increase in expected monthly sales.

## Average Discount Percentage

The negative coefficient suggests that larger discounts are associated with lower monthly sales after accounting for the remaining variables.

This may indicate that excessive discounting reduces overall revenue or occurs in lower-performing stores.

---

# Dummy Variable Approach

Categorical Variable Used:

Store Type

Dummy Variable Created:

Mall Store = 1

Reference Category:

Non-Mall Store = 0

Only one dummy variable was included to avoid perfect multicollinearity (Dummy Variable Trap).

---

# Final Model Selection

The multiple regression model was selected because it provides the highest explanatory power (R² = 0.788), includes multiple significant predictors, and produces the most reliable estimates for supporting retail business decisions.
