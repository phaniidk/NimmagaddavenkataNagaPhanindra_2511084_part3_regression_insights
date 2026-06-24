# Residual Analysis

## Objective

Residual analysis was performed to evaluate model performance and identify observations where actual sales differed significantly from predicted sales.

Residual = Actual Sales - Predicted Sales

---

## Largest Positive Residuals

| Observation | Residual |
|------------|------------|
| 111 | 116222.10 |
| 253 | 103750.70 |
| 256 | 91922.09 |
| 103 | 91544.24 |
| 275 | 90949.48 |

### Interpretation

These observations achieved sales significantly higher than predicted by the regression model.

Possible reasons include:

- Successful local marketing campaigns
- Higher customer demand
- Seasonal effects
- Strong store management
- Unobserved factors not included in the model

---

## Largest Negative Residuals

| Observation | Residual |
|------------|------------|
| 66 | -150185.00 |
| 44 | -128119.00 |
| 32 | -122200.00 |
| 89 | -118376.00 |
| 3 | -110004.00 |

### Interpretation

These observations achieved sales significantly lower than predicted by the model.

Possible reasons include:

- Inventory shortages
- Operational inefficiencies
- Increased local competition
- Lower customer satisfaction
- Temporary business disruptions

---

## Overall Model Performance

The Multiple Regression Model achieved:

- R Square = 0.8083
- Adjusted R Square = 0.8053

This indicates that approximately 80.83% of the variation in Monthly Sales is explained by the model.

---

## Conclusion

The residual analysis suggests that the model performs well overall. However, a small number of observations exhibit unusually large prediction errors, indicating that some store-specific factors are not captured by the available variables.

Future improvements may include incorporating additional variables such as local promotions, seasonal trends, economic conditions, and competitor activities.
