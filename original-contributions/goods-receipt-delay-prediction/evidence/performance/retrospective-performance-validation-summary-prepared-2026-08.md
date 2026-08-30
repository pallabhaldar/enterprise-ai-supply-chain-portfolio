# Retrospective Performance and Validation Summary: Goods Receipt Delay Prediction

## Document classification

This retrospective summary was prepared in August 2026 from applicant-provided information. It is not the original 2024 model-validation report. Reported values should be corroborated with the original model output, sanitized evaluation tables, production-comparison records and an authorized verifier's confirmation before formal submission.

## Evaluation objective

Evaluate whether the deployed prediction workflow could forecast goods-receipt timing and identify delay risk early enough to support procurement, production planning, supply-chain operations and supplier-management decisions.

## Dataset

- Fewer than 50,000 goods-receipt events
- Less than one year of historical data
- Source: Enterprise operational data from a global manufacturing enterprise
- Development began: February 2024
- Limited-production deployment: April-June 2024

Exact event counts, date boundaries, exclusions, feature definitions and data-quality treatments were not supplied for this public summary and should be preserved in the confidential validation record.

## Models and execution platform

- Random-forest regression
- Neural-network scoring
- Combined model outputs under Architecture Version 1.1
- SAP HANA Predictive Analytics Library for in-database processing

The evaluated outputs included a delay-risk classification, predicted receipt date and intervention-priority category. The production workflow also produced a delay-duration estimate.

## Validation design

- 80/20 training-test split
- 10-fold cross-validation
- Held-out test-set evaluation
- Comparison with limited-production outcomes

The original report should confirm whether cross-validation was performed only on the training portion, how model selection was separated from final testing and how duplicate or related transactions were prevented from crossing evaluation partitions.

## Primary result and measurement definition

Reported receipt-date forecast accuracy: **81%**.

A forecast was counted as correct when the predicted receipt date fell within **plus or minus three days** of the actual receipt date. The 81% value should therefore be described as tolerance-based receipt-date forecast accuracy, not generic classification accuracy or R-squared.

Reported mean absolute error: **1.5 days**.

## Additional reported metrics

- Precision: **84%**
- Recall: **82%**
- F1-score: **86%**

The F1-score is recorded exactly as reported by the applicant. Because a simple harmonic mean of aggregate precision of 84% and recall of 82% is approximately 83%, the original evaluation report should identify whether the 86% F1-score arose from macro, micro, weighted or class-specific averaging, or from a different evaluation subset. No recalculation or correction has been made in this retrospective record.

## Baseline comparison

The following values were reported:

| Method | Reported result |
| --- | ---: |
| Rules-based delay alerts | 88% |
| Traditional reporting | 56% |
| Earlier random-forest model | 67% |
| Final combined workflow | 81% tolerance-based receipt-date forecast accuracy |

These figures should not be interpreted as a single ranked accuracy comparison until the original records confirm that every baseline used the same target, plus-or-minus-three-day tolerance, dataset, test period and denominator. In particular, the reported 88% rules-based result exceeds the final workflow's 81% receipt-date forecast accuracy and may measure a different output, threshold or case subset. The current evidence does not establish metric comparability.

## Operational context

The limited-production solution supported approximately 11-50 users across 4-10 sites. The participating functions were procurement, production planning, supply-chain operations and supplier management. Available deployment evidence reportedly demonstrates an active limited-production environment, active scoring and operational use by the teams.

## Supporting evidence identified

- Release or change record
- Production screenshot
- Operations or model report
- Original validation output for the 80/20 test and 10-fold cross-validation
- Baseline definitions and evaluation results
- Production-comparison record
- Direct-manager verification

All exhibits should be sanitized to remove confidential transaction data, material identifiers, supplier details, system credentials and internal environment names.

## Remaining evidence gaps

- Exact event count and historical date range
- Training, validation and held-out test sample sizes
- Feature and target definitions
- Cross-validation procedure and leakage controls
- Denominator for the 81% tolerance-based forecast accuracy
- Averaging method or evaluated class for precision, recall and F1-score
- Explanation and source record for the reported 86% F1-score
- Confirmation that baseline results use the same metric and evaluation population
- Confidence intervals or fold-to-fold variability
- Exact production-comparison period and sample size
- Signed or authenticated verifier confirmation

## Evidence-integrity statement

This document distinguishes reported facts from items that still require corroboration. It does not infer metric comparability, causal business impact or a level of deployment beyond the limited-production scope described above.
