# Final Business Recommendation

## Executive Summary

This regression analysis was conducted to identify the business factors most strongly associated with monthly sales across retail stores. Three regression models were evaluated, including two simple linear regression models and one multiple linear regression model. Based on the statistical results, the multiple regression model was selected as the final model because it explains the largest proportion of variation in monthly sales (R² = 0.788) while incorporating several important operational and business variables.

The findings provide valuable insights that can support leadership in making informed decisions regarding marketing investment, customer acquisition, pricing strategy, and store operations.

---

# 1. Which Factors Appear Most Strongly Associated with Monthly Sales?

The regression analysis identified the following factors as having the strongest association with monthly sales:

## Customer Footfall

Customer footfall is the strongest individual predictor of monthly sales.

Regression evidence:

* R² = **0.736**
* Coefficient = **35.6780**
* P-value = **4.75E-94**

This indicates that stores attracting more customers consistently achieve higher monthly sales. The relationship is both statistically significant and practically meaningful.

---

## Marketing Spend

Marketing expenditure also has a statistically significant positive relationship with monthly sales.

Regression evidence:

* R² = **0.167**
* Coefficient = **2.1296**
* P-value = **2.48E-14**

Although marketing contributes positively to sales, it explains a much smaller proportion of sales variation when analyzed independently.

---

## Store Type (Mall Dummy)

The multiple regression model indicates that mall stores generally perform better than the reference category after controlling for the remaining variables.

Regression evidence:

* Positive coefficient (13,815.99)
* Statistically significant (P < 0.05)

This suggests that store location contributes to sales performance beyond marketing and customer traffic.

---

## Average Discount Percentage

The multiple regression model produced a negative coefficient for average discount percentage.

Regression evidence:

* Coefficient = -87,633.17
* P-value < 0.05

This indicates that larger discounts are associated with lower monthly sales after controlling for other variables.

Rather than increasing revenue, excessive discounting may reduce profitability or may occur more frequently in lower-performing stores.

---

# 2. Which Variables Should Leadership Focus On?

Based on the regression results, leadership should prioritize the following areas.

## Increase Customer Footfall

Since footfall is the strongest predictor of monthly sales, management should invest in initiatives that attract more customers to stores.

Recommended initiatives include:

* Digital marketing campaigns
* Customer loyalty programs
* Local promotional events
* Improved store experience
* Community engagement activities

Increasing customer traffic is expected to have the greatest positive impact on monthly sales.

---

## Continue Strategic Marketing Investment

Marketing spend remains an important contributor to sales growth.

However, management should focus on improving marketing effectiveness rather than simply increasing expenditure.

Campaign performance should be monitored using return on investment (ROI), customer acquisition cost, and conversion rates.

---

## Optimize Store Operations

The significance of the Mall Dummy variable suggests that location influences store performance.

Leadership should investigate why mall stores outperform other store types.

Possible areas include:

* Customer accessibility
* Product assortment
* Store layout
* Operating hours
* Staffing levels

Successful operational practices from high-performing stores should be replicated across other locations where feasible.

---

## Review Discount Strategy

The negative coefficient for average discount percentage suggests that excessive discounting may not be an effective long-term sales strategy.

Rather than increasing discount levels, leadership should focus on:

* Targeted promotions
* Personalized offers
* Value-added bundles
* Customer loyalty incentives

These approaches may improve revenue without reducing margins unnecessarily.

---

# 3. Which Variables Should Not Be Over-Interpreted?

Although several predictors are statistically significant, some findings should be interpreted carefully.

## Marketing Spend

Marketing spend is positively associated with sales; however, its standalone explanatory power is relatively low (R² = 0.167).

This indicates that marketing alone cannot explain store performance.

Other operational variables also contribute substantially.

---

## Average Discount Percentage

The negative relationship between discounts and sales does not necessarily imply that discounts always reduce revenue.

Possible explanations include:

* Poor-performing stores offering larger discounts.
* Discounts being used during low-demand periods.
* Reverse causality, where weaker sales lead managers to increase discounting.

Therefore, management should avoid concluding that all discounts are harmful without further investigation.

---

## Store Type

The Mall Dummy variable captures differences between mall and non-mall stores, but it does not explain why those differences exist.

Additional factors such as demographics, competition, store size, and local demand may contribute to the observed performance differences.

---

# 4. Recommended Business Actions

Based on the regression findings, the following actions are recommended.

### Customer Growth

Increase customer visits through targeted marketing campaigns, improved customer engagement, and enhanced in-store experiences.

### Marketing Optimization

Continue investing in marketing while measuring campaign effectiveness and reallocating budgets toward high-performing channels.

### Pricing Strategy

Reduce dependence on excessive discounting and emphasize targeted promotional campaigns that preserve profitability.

### Operational Improvements

Study high-performing mall stores to identify operational best practices that can be implemented across other store formats.

### Data-Driven Decision Making

Use the multiple regression model as a decision-support tool for forecasting sales and evaluating future business strategies.

---

# 5. Risks and Limitations

Although the regression model performs well, leadership should recognize several important limitations.

* Approximately **21.2%** of the variation in monthly sales remains unexplained (1 − R² = 0.212).
* Important variables such as seasonality, competitor pricing, customer demographics, economic conditions, and promotional events were not included in the model.
* Unexpected market events cannot be predicted accurately using historical regression models.
* Relationships identified in historical data may change over time.

Therefore, regression results should complement—not replace—business expertise and operational judgment.

---

# 6. Why Regression Shows Association but Not Causation

Regression analysis identifies statistical relationships between variables.

However, a statistically significant relationship does not automatically prove that one variable causes another.

For example:

* Higher footfall is associated with higher sales, but regression alone cannot prove that increasing footfall will always increase sales.
* Larger discounts are associated with lower sales, but this may occur because struggling stores choose to offer larger discounts rather than discounts causing lower sales.

Many external factors may influence both variables simultaneously.

Examples include:

* Economic conditions
* Competitor activity
* Local events
* Consumer preferences
* Seasonal demand

To establish true cause-and-effect relationships, businesses should combine regression analysis with controlled experiments, A/B testing, or longitudinal studies.

---

# Final Conclusion

Among all evaluated models, the **Multiple Linear Regression Model** provides the strongest explanation of monthly sales performance, with an R² value of **0.788**.

The analysis demonstrates that:

* Customer footfall is the strongest driver of monthly sales.
* Marketing spend positively influences sales but should be optimized for effectiveness.
* Store type contributes to differences in performance.
* Excessive discounting should be reviewed carefully rather than expanded indiscriminately.

The regression model provides valuable evidence for supporting strategic decisions in marketing, store operations, and pricing. However, leadership should interpret these findings as evidence of association rather than proof of causation and combine statistical insights with business knowledge when making decisions.
