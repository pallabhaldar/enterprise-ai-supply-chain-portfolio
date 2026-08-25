# Performance Results: Inventory Target Prediction

## Evaluation objective

Predict monthly material purchase quantities using remaining inventory and recent shipped quantity across material-warehouse-time combinations.

## Dataset

- Training-data period reported in the paper: 2020-2023
- Sources: inventory transactions, shipment records and procurement orders from SAP ERP systems
- Target: monthly material order quantity
- Predictors: remaining inventory quantity and shipped quantity
- Number of observations: **Not stated in the paper; verification required**
- Exact temporal holdout dates and validation sample: **To be verified**

## Method

- Linear regression
- SAP HANA Predictive Analytics Library implementation context
- Composite material, warehouse, year and month keys
- Temporal holdout validation

## Published results

| Metric | Published result | Meaning |
|---|---:|---|
| Mean Absolute Error | 4.3 units | Average absolute difference between predicted and actual order quantity |
| Mean Absolute Percentage Error | 15.7% | Average absolute percentage forecast error |
| R-squared | 0.78 | Approximately 78% of observed target variance explained by the model |

The paper also reports correlations of approximately 0.72 between shipped quantity and order quantity, 0.58 between remaining quantity and order quantity, and 0.45 between the two predictors.

## Baseline limitation

The paper conceptually compares the method with fixed reorder points and traditional forecasting, but it states that direct comparison with alternative forecasting methods falls outside its immediate scope. Therefore, no unsupported improvement percentage should be calculated against a baseline.

## Validation limitations requiring evidence

- Exact training and holdout sample sizes
- Temporal cutoff and validation duration
- Reproducible metric calculations
- Treatment of zero actual orders in MAPE
- Missing-data and outlier rules
- Confidence intervals or repeated-validation variability
- Model coefficients and approved output record

## Business consequence

The paper discusses potential reductions in excess inventory, stockouts, working capital and expedited shipping. It also cites results reported in broader literature. These should not be presented as outcomes caused by this specific model unless organization-specific operational records confirm them.

## Supporting records

- Publisher and DOI record
- Sanitized validation output
- Metric calculation table
- Model and database-view configuration
- Deployment or release record
- Independent technical or operational verification
