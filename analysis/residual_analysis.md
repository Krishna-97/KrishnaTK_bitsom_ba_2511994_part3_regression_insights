# Residual Analysis

## Objective

Residual analysis evaluates how accurately the selected regression model predicts monthly sales across retail stores.

Residuals are calculated using:

Residual = Actual Monthly Sales − Predicted Monthly Sales

Positive residuals indicate that the store achieved higher sales than predicted.

Negative residuals indicate that the model overestimated sales.

---

# Model Used

The selected model is the Multiple Regression Model including:

* Marketing Spend
* Footfall
* Average Discount Percentage
* Mall Store Dummy

This model explains approximately **78.8%** of the variation in monthly sales.

---

# Interpretation of Positive Residuals

Stores with the largest positive residuals performed substantially better than expected.

Possible business reasons include:

* Successful local marketing campaigns
* Strong store management
* Better customer service
* Temporary local demand increases
* Community events or seasonal festivals
* Higher customer loyalty

These stores represent examples of operational excellence that may provide best practices for other locations.

---

# Interpretation of Negative Residuals

Stores with the largest negative residuals generated lower sales than predicted.

Possible explanations include:

* Inventory shortages
* Poor customer service
* Staff shortages
* Increased local competition
* Temporary store disruptions
* Lower product availability

Management should investigate these stores to identify operational challenges and corrective actions.

---

# Model Performance

Residuals are distributed around zero without obvious systematic bias, indicating that the regression model provides a reasonable overall fit.

However, several observations have relatively large residuals, suggesting that additional explanatory variables could improve predictive accuracy.

Potential variables include:

* Store size
* Competitor presence
* Promotional events
* Holiday seasons
* Local income levels
* Product assortment
* Customer demographics

---

# Business Insights

The regression model performs well for most stores but cannot perfectly explain every difference in monthly sales.

Stores with unusually large positive or negative residuals deserve additional management attention because they may reveal hidden opportunities or operational risks that are not captured by the current model.

Residual analysis therefore complements regression by identifying stores requiring further business investigation rather than relying solely on statistical predictions.
