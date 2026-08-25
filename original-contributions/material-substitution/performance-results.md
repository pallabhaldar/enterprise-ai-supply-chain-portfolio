# Performance Results: Predictive Material Substitution

## Evaluation objective

Evaluate whether the proposed method could identify suitable material-substitution candidates under relevant technical and business constraints.

## Dataset

- Data sources: material attributes, historical consumption, procurement records and substitution constraints, as reported
- Number of material records: **To be verified**
- Evaluation period: **To be verified**
- Training sample: **To be verified**
- Validation or test sample: **To be verified**
- Exclusion and data-quality rules: **To be verified**

## Methods

- Enterprise data preparation and feature engineering
- Random forest
- Decision trees
- Material-similarity and constraint evaluation
- Business-rule validation

## Reported result

An approximately **85% match result** has been reported. This figure is not yet independently established as accuracy and must not be described as “85% accuracy” until the supporting record defines the calculation.

## Required metric definition

Document precisely:

- What constituted a correct match
- Unit of analysis and denominator
- Whether multiple substitutes could be correct
- Top-1, top-k or threshold-based evaluation
- Holdout, cross-validation or temporal-validation method
- Calculation formula
- Confidence interval or variability, if available

## Baseline

- Manual or rule-based baseline: **To be verified**
- Baseline value and calculation: **To be verified**
- Proposed-method value: approximately 85% reported; metric definition pending
- Absolute and relative improvement: **Do not calculate until both measures are verified**

## Business consequence

The intended operational benefit was faster, more consistent identification of potential substitute candidates to support supply-continuity decisions. Any claim regarding cost savings, shortage reduction, production continuity or decision-time improvement requires an authorized operational record or verifier.

## Supporting records

- Sanitized model-evaluation report
- Reproducible validation output or approved summary
- Metric calculation and test-set definition
- Baseline comparison
- Architecture and deployment record
- Employer or client confirmation
