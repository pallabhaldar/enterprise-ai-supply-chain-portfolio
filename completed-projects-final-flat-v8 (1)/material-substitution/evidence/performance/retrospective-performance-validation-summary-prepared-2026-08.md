# Retrospective Performance and Validation Summary: Predictive Material Substitution

## Document classification

This retrospective summary was prepared in August 2026 from applicant-provided information. It is not the original 2020 validation report. The reported values should be corroborated using the sanitized aggregate metric report, model screenshot, evaluation table and technical-lead confirmation.

## Evaluation objective

Evaluate whether the machine-learning framework could assign potential material-substitution candidates to operationally meaningful suitability categories with sufficient consistency to support expert review and production decision-making.

## Public-safe classification target

The multiclass target is described functionally as:

1. Usable without restriction
2. Usable with expert review
3. Unsuitable

These are sanitized functional descriptions. Internal category codes or proprietary business-rule definitions are not disclosed.

## Dataset

The evaluation included material records and known or evaluated substitution pairs. Exact counts are confidential and are therefore excluded from this public summary.

- Number of materials: Confidential
- Number of substitution pairs: Confidential
- Data provenance: Enterprise material and substitution information from a global manufacturing enterprise
- Original evaluation period: 2020, with technical review reported during September-October 2020

An unredacted confidential validation report should preserve the exact sample counts, inclusion rules, exclusions, class balance and data-quality treatment for legal review.

## Methods

- SAP HANA analytical processing
- Random forest
- Decision trees
- 80/20 train/test split
- 10-fold cross-validation
- Production-output comparison with expert decisions

## Reported primary result

Average multiclass classification accuracy from 10-fold cross-validation: **approximately 85%**.

This value represents cross-validation accuracy, not business-cost reduction, production uptime or a generic “match rate.”

## Additional reported metrics

- Precision: Approximately 80%-84%
- Recall: Approximately 80%-84%
- F1-score: Approximately 80%-84%

Exact class-level and aggregate values were not supplied for this public summary. They should be taken directly from the original evaluation output before use in a formal evidentiary filing.

## Baseline comparison

The model was compared with a rule-based baseline reportedly producing accuracy within the 70%-79% range. The exact baseline value is not included in this public record.

An earlier model baseline reportedly existed, but no verified value was provided; therefore, no comparison with that model is claimed.

Because the rule-based baseline is available only as a range, this summary does not calculate an exact percentage-point or relative improvement.

## Expert validation

Business or domain experts reportedly:

- Compared model recommendations with expert decisions
- Validated the recommended substitution category

The technical lead reportedly confirmed the results during a review meeting held between September and October 2020. The exact meeting date, participants, sample size and agreement rate remain to be verified.

## Reported business effects

Following production deployment, the applicant reports:

- Material-shortage reduction within an 11%-20% range
- Between 11 and 50 avoided shortage events
- Improved production continuity

The exact values, measurement period, baseline, affected sites and causal-attribution method were not supplied. These outcomes must remain ranges until the supporting operational report or verifier supplies exact, reproducible figures.

## Publishable supporting evidence identified

- Sanitized aggregate metric report
- Redacted model-results screenshot
- Sanitized evaluation table
- Technical-lead review confirmation

Each exhibit should identify its original date and method while removing material identifiers, internal system names, credentials, customer-confidential information and proprietary rule definitions.

## Remaining evidence gaps

- Exact material and substitution-pair counts
- Class distribution and test-set size
- Exact precision, recall and F1-score
- Confusion matrix or per-class results
- Exact rule-based baseline value
- Expert-comparison sample size and agreement rate
- Exact technical-review date and participants
- Exact shortage-reduction percentage and measurement period
- Exact avoided-event count and calculation
- Signed technical-lead or business-expert confirmation

## Evidence-integrity statement

All performance and business-impact statements are labeled according to the information currently available. No undisclosed exact value should be inferred from a published range.
