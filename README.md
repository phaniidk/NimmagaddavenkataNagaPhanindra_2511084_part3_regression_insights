# NimmagaddavenkataNagaPhanindra_2511084_part3_regression_insights

# Part 3 – Regression Insights and Business Recommendations

## Student Information

**Name:** YOUR NAME

**Student ID:** YOUR STUDENT ID

**Assignment:** Part 3 – Regression Insights and Business Recommendations

---

# Business Problem Summary

A retail company wants to understand the factors that influence monthly sales and use data-driven insights to improve business performance. Regression analysis was performed to identify the most important variables associated with monthly sales and to develop predictive models for decision-making.

---

# Dataset Description

The dataset contains retail store performance information including sales, marketing, customer behavior, and operational metrics.

### Dependent Variable (Target)

* monthly_sales

### Independent Variables

* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating
* monthly_profit

### Categorical Variables

* region
* store_type

### Variables Excluded From Regression

* store_id
* month

---

# Data Preparation

## Missing Value Treatment

The following columns contained missing values:

| Variable               | Missing Values |
| ---------------------- | -------------- |
| competitor_distance_km | 6              |
| customer_rating        | 8              |

Missing values were replaced using mean imputation.

---

## Dummy Variable Creation

Categorical variables were converted into dummy variables before regression analysis.

### Region

Reference Category:

* West

Dummy Variables Created:

* Region_North
* Region_East
* Region_South

The reference category is represented when all dummy variables are equal to zero.

---

# Regression Approach

## Simple Regression Models

Two simple regression models were developed:

### Model 1

Dependent Variable:

* monthly_sales

Independent Variable:

* marketing_spend

### Model 2

Dependent Variable:

* monthly_sales

Independent Variable:

* footfall

---

## Multiple Regression Model

Dependent Variable:

* monthly_sales

Independent Variables:

* marketing_spend
* footfall
* inventory_availability_pct
* customer_rating
* region dummy variable

Residual analysis was also performed to evaluate model performance.

---

# Model Comparison Summary

| Model               | Variables Used                                                                   | R Square |
| ------------------- | -------------------------------------------------------------------------------- | -------- |
| Simple Regression 1 | Marketing Spend                                                                  | 0.1679   |
| Simple Regression 2 | Footfall                                                                         | 0.0545   |
| Multiple Regression | Marketing Spend, Footfall, Inventory Availability, Customer Rating, Region Dummy | 0.8083   |

---

# Best Model

## Selected Model

Multiple Regression Model

### Reason

The Multiple Regression Model achieved the highest explanatory power with an R Square value of 0.8083.

This indicates that approximately 80.83% of the variation in monthly sales is explained by the model.

---

# Key Findings

The analysis identified the following factors as the strongest drivers of monthly sales:

1. Marketing Spend
2. Inventory Availability Percentage
3. Footfall
4. Customer Rating
5. Regional Factors

Marketing Spend was the strongest individual predictor among the simple regression models.

---

# Business Recommendations

Based on the analysis, the following actions are recommended:

### Marketing

* Increase investment in effective marketing campaigns.
* Track campaign performance and return on investment.

### Inventory Management

* Maintain high inventory availability.
* Improve demand forecasting and stock replenishment.

### Customer Experience

* Improve customer service quality.
* Monitor and respond to customer feedback.

### Store Traffic

* Increase footfall through promotions and engagement programs.

### Regional Strategy

* Monitor performance differences across regions.
* Develop location-specific business strategies.

---

# Residual Analysis Summary

Residual analysis identified observations with unusually high positive and negative prediction errors.

The model performs well overall but some store-specific factors remain unexplained.

Potential additional variables for future analysis include:

* Seasonal demand
* Local promotions
* Economic conditions
* Competitor activities

---

# Assumptions and Limitations

* Regression identifies association, not causation.
* External factors were not included in the dataset.
* Some variation in monthly sales remains unexplained.
* Results are dependent on the quality of available data.

---

# Files Included

## Data

* business_regression_data.xlsx

## Analysis

* regression_workbook.xlsx
* model_comparison.md
* residual_analysis.md

## Outputs

* regression_summary.xlsx
* model_equations.md
* final_recommendation.md

## Screenshots

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png

---

# Conclusion

Three regression models were evaluated to understand the drivers of monthly sales.

The Multiple Regression Model was selected as the final model because it achieved the highest explanatory power (R Square = 0.8083) and provides the most comprehensive understanding of sales performance.

The analysis indicates that marketing effectiveness, inventory availability, customer satisfaction, and store traffic are the primary areas leadership should focus on to improve monthly sales.
