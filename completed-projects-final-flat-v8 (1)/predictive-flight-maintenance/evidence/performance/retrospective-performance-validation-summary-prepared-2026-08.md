# Retrospective Performance and Validation Summary: Predictive Flight Maintenance

## Document classification

This summary separates supplementary simulation results reported in the paper "AI-Powered Predictive Flight Maintenance" from the claimed real production deployment. No verified real-production performance metrics were supplied.

## Supplementary simulated evaluation

The paper describes:

- 10 simulated engines
- 12 months of simulated flight data
- More than 1 million simulated sensor points
- Simulated Airbus A330 fleet representation
- SAP HANA PAL linear regression, decision tree, logistic regression and one-class SVM

The paper reports the following simulated operational outcomes:

| Simulated measure | Reported result |
| --- | ---: |
| Mean Time Between Failures | 15% increase |
| Maintenance cost | 18% reduction |
| Aircraft-on-Ground events | 90% reduction |

These figures are simulation results only. They are not presented as measured airline-production outcomes.

## Real limited-production evaluation

No verified real-production performance metrics or separate operational performance report were provided. Therefore, this package does not claim a measured improvement in MTBF, maintenance cost, AOG events, model accuracy, precision, recall, F1-score, ROC AUC or RUL error for the real deployment.

## Permitted evidentiary use

The simulated study may support technical feasibility, algorithm selection and architecture rationale. It cannot independently prove deployment, airline adoption, safety improvement, cost savings or operational impact.

## Required future evidence

- Production model-monitoring report
- Defined targets, thresholds and denominators
- RUL error metrics and classification metrics
- Production comparison period and baseline
- Aircraft or engine sample scope
- Authorized operations or maintenance-owner confirmation
- Clear separation of real and simulated data

## Evidence-integrity statement

No simulated result is attributed to actual airline production. No real-production improvement is claimed without a supporting operational record.
