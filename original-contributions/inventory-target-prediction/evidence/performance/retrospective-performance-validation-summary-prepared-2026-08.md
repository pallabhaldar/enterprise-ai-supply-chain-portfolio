# Retrospective Performance and Validation Summary: Inventory Target Prediction

## Document classification

This summary was prepared in August 2026 using applicant-confirmed figures also reported in the attached 2025 article. It is not the original 2024 model-validation report. The figures require corroboration using original evaluation output and verifier confirmation.

## Evaluation objective

Evaluate whether linear regression could predict monthly material-purchase quantities from inventory and shipment information with sufficient accuracy for procurement-planning support.

## Dataset

- Approximately 12.3 million historical inventory records
- Historical period: 2019-2023
- Organization: Global manufacturing enterprise
- Target: Monthly material-purchase quantity
- Core predictors: Current or remaining inventory and recent shipment quantity

The exact material count, warehouse count, monthly observation count, inclusion criteria and data-quality treatments were not supplied.

## Method and validation

- Linear regression using SAP HANA PAL
- 80/20 random train/test split
- 5-fold cross-validation

The original report should establish whether cross-validation was limited to the training portion and whether material, warehouse or time-related leakage was prevented across partitions.

## Confirmed reported results

| Metric | Reported value |
| --- | ---: |
| Mean Absolute Error | 4.3 units |
| Mean Absolute Percentage Error | 15.7% |
| R-squared | 0.78 |

An R-squared value of 0.78 indicates that the fitted model accounted for approximately 78% of observed variance in the evaluated order quantities. It does not mean 78% classification accuracy.

## Baseline

The model was compared operationally with a fixed reorder-point method. The baseline metric was identified as MAE, but its numerical value is unavailable. Accordingly, this summary does not calculate or claim a numerical improvement over the baseline.

## Source alignment

The attached publication reports the same MAE, MAPE and R-squared figures, but publication alone does not prove that these were obtained in the claimed limited-production environment. Original model output, dated validation records and independent confirmation are needed to connect the published evaluation to the deployment.

## Supporting evidence identified

- Operations or model report
- Sanitized model-validation output
- Publication describing the method and results
- Production screenshot
- Direct-manager confirmation from project records

## Remaining evidence gaps

- Exact sample counts after preprocessing
- Exact train and test observation counts
- Cross-validation fold results and variability
- Randomization method and leakage controls
- Exact fixed reorder-point baseline MAE
- Confidence intervals and subgroup performance
- Production-monitoring period and drift results
- Authenticated verifier confirmation

## Evidence-integrity statement

No baseline value or improvement percentage has been estimated. The performance figures are recorded as reported and must be tied to the original evaluation records.
