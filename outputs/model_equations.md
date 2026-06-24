# Model Equations

## Objective

Regression models were developed to understand the relationship between business factors and Monthly Sales.

---

## Simple Regression Model 1

### Variable Used
Marketing Spend

### Equation

Monthly Sales = 560613.6 + 70389.11 × (Marketing Spend)

### Interpretation

The coefficient for Marketing Spend is positive, indicating that an increase in marketing expenditure is associated with higher monthly sales.

For every one-unit increase in Marketing Spend, Monthly Sales are expected to increase by approximately 70,389 units on average.

---

## Simple Regression Model 2

### Variable Used
Footfall

### Equation

Monthly Sales = 4914.605 + 0.029247 × (Footfall)

### Interpretation

The positive coefficient indicates that stores with higher customer traffic tend to achieve higher sales.

For every additional unit increase in Footfall, Monthly Sales are expected to increase by approximately 0.029 units on average.

---

## Multiple Regression Model

### Variables Used

- Marketing Spend
- Footfall
- Inventory Availability Percentage
- Customer Rating
- Region Dummy Variable

### General Equation

Monthly Sales = β0 + β1(Marketing Spend) + β2(Footfall) + β3(Inventory Availability) + β4(Customer Rating) + β5(Region Dummy)

### Model Performance

| Metric | Value |
|----------|----------|
| R Square | 0.8083 |
| Adjusted R Square | 0.8053 |

### Interpretation

The Multiple Regression Model combines multiple business variables and explains approximately 80.83% of the variation in Monthly Sales.

Compared with the simple regression models, this model provides substantially better predictive performance and captures the combined influence of operational and customer-related factors.

---

## Dummy Variable Information

### Variable Converted

Region

### Reference Category

West

### Created Dummy Variables

- Region_North
- Region_East
- Region_South

The reference category (West) is represented when all dummy variables equal zero.

---

## Final Model Selected

### Selected Model

Multiple Regression Model

### Reason

The Multiple Regression Model achieved the highest explanatory power (R Square = 0.8083) and provides the most comprehensive understanding of sales performance.

---

## Conclusion

The Multiple Regression Model is recommended for forecasting and business decision-making because it incorporates multiple drivers of sales simultaneously and significantly outperforms the simple regression models.
