# Performance Results: Goods Receipt Delay Prediction

## Evaluation objective

Predict delayed goods-receipt events early enough to support procurement or supply-planning action.

## Dataset

- Approximately 250,000 historical ERP goods-receipt events
- Approximately three years of history
- Data provenance, inclusion criteria and fields: **To be verified**
- Training period and sample count: **To be verified**

## Validation

- Reported holdout period: six months
- Temporal cutoff date: **To be verified**
- Validation sample size: **To be verified**
- Leakage controls and missing-data treatment: **To be verified**

## Methods

- Random-forest regression
- Relevant baseline methods: **To be documented**
- Reported execution context: SAP HANA Predictive Analytics Library

## Reported result

Approximately **81%** has been reported. The metric is not yet defined and must not be presented as “81% accuracy” until the original evaluation record establishes whether it represents accuracy, R-squared, forecast accuracy, precision, recall, threshold agreement or another measure.

## Measurement definition

- Target variable: **To be verified**
- Prediction horizon: **To be verified**
- Metric name and formula: **To be verified**
- Classification or regression threshold, if applicable: **To be verified**
- Denominator and excluded cases: **To be verified**
- Confidence interval or variability: **To be verified**

## Baseline comparison

- Baseline method: **To be verified**
- Baseline result: **To be verified**
- Proposed-method result: approximately 81% reported; definition pending
- Incremental improvement: **Do not calculate until metric comparability is verified**

## Business consequence

Describe only verified operational outcomes, such as additional warning time, reduced manual review, changed procurement intervention or improved material availability. Do not state that the model caused a business improvement without an appropriate comparison and authorized confirmation.

## Supporting records

- Sanitized performance report
- Model-validation output
- Feature and target definitions
- Baseline comparison
- Deployment record
- Employer or client confirmation
