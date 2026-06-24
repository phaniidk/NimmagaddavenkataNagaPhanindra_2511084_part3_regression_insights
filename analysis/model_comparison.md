# Model Comparison

## Objective

The objective of this analysis was to identify the factors influencing monthly sales and determine the most effective regression model for prediction and business decision-making.

---

## Simple Regression Model 1

### Dependent Variable
Monthly Sales

### Independent Variable
Marketing Spend

### Results

| Metric | Value |
|----------|----------|
| R Square | 0.1679 |
| P-value | 2.39E-14 |

### Interpretation

Marketing Spend has a statistically significant positive relationship with Monthly Sales. The model explains approximately 16.79% of the variation in sales.

### Business Insight

Increasing marketing expenditure is associated with higher sales performance, making marketing an important business driver.

---

## Simple Regression Model 2

### Dependent Variable
Monthly Sales

### Independent Variable
Footfall

### Results

| Metric | Value |
|----------|----------|
| R Square | 0.0545 |
| P-value | 2.52E-05 |

### Interpretation

Footfall has a positive and statistically significant relationship with Monthly Sales. However, it explains only 5.45% of the variation in sales.

### Business Insight

Store traffic contributes to sales performance but is not a strong standalone predictor.

---

## Multiple Regression Model

### Variables Used

- Marketing Spend
- Footfall
- Inventory Availability Percentage
- Customer Rating
- Region Dummy Variable

### Results

| Metric | Value |
|----------|----------|
| R Square | 0.8083 |
| Adjusted R Square | 0.8053 |
| Significance F | 5.6E-110 |

### Interpretation

The model explains approximately 80.83% of the variation in Monthly Sales. Combining multiple business variables provides significantly stronger predictive power than individual models.

### Business Insight

Marketing effectiveness, customer traffic, inventory management, customer satisfaction, and location-related factors collectively influence sales performance.

---

## Final Model Selection

### Selected Model
Multiple Regression Model

### Reason for Selection

The Multiple Regression Model achieved the highest R Square value (0.8083), indicating superior explanatory power compared to the simple regression models.

### Conclusion

The Multiple Regression Model is the most appropriate model for forecasting and business decision-making because it incorporates multiple operational and customer-related factors simultaneously.
