# Retrospective Performance and Validation Summary: Small Food Supply Chain Optimization

## Document classification

This summary was prepared in August 2026 from applicant-confirmed production figures. It requires corroboration with original validation, production-comparison and financial or operational records.

## Evaluation scope

- Historical period: February 2022 through January 2025
- Dataset count: Confidential
- 10-fold cross-validation
- Production comparison
- Integrated forecasting, replenishment, routing and cost optimization

## Reported production results

| Measure | Reported result |
| --- | ---: |
| Weekly demand-forecast accuracy | 90% |
| Storage-cost reduction | 15% |
| Delivery-time reduction | 20% |
| Procurement-expense reduction | 12% |

The original source records should define the comparison periods, denominators, cost categories, excluded cases and attribution methodology.

## Comparable forecast baselines

The applicant confirmed that the same dataset and evaluation definition were used.

| Forecasting method | Accuracy | Difference from final model |
| --- | ---: | ---: |
| Integrated final model | 90.0% | - |
| Moving-average baseline | 89.3% | +0.7 percentage points |
| Seasonal ARIMA baseline | 92.7% | -2.7 percentage points |

Seasonal ARIMA outperformed the integrated final model by 2.7 percentage points on aggregate forecast accuracy. Therefore, no claim of best forecasting accuracy is made.

## Operational selection rationale

The integrated solution was selected because it also optimized replenishment, routing and cost, performed better for nonlinear or volatile demand segments and produced reported reductions in storage cost, delivery time and procurement expense. These benefits should be evidenced independently from forecast accuracy.

## Evidence identified

- Model-validation report
- Production-comparison record
- Cost and delivery-time reports
- Model-retraining reports
- Direct-manager confirmation based on project records

## Remaining evidence gaps

- Exact fold sizes and variability
- Forecast-accuracy formula
- Segment-level evidence for nonlinear or volatile demand
- Cost and delivery measurement periods
- Attribution and confounding controls
- Signed verifier confirmation

## Evidence-integrity statement

This summary reports the superior seasonal ARIMA result transparently and does not mischaracterize the integrated model as the most accurate forecaster.
