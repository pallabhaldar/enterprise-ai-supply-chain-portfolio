# Deployment Summary: Inventory Target Prediction

## Publication record

**Inventory Management Optimization: Predictive Material Purchase Target Identification and Forecasting Using Machine Learning**, Journal of Computational Analysis and Applications, Volume 34, Number 11, 2025, pages 658-674. DOI: [10.48047/jocaaa.2025.34.11.45](https://doi.org/10.48047/jocaaa.2025.34.11.45).

## Project period

The paper reports a training dataset spanning 2020-2023. The development, validation and any operational deployment dates must be confirmed separately.

## Organizational context

Enterprise inventory and procurement forecasting using historical inventory, shipment and procurement records. The paper does not publicly identify an adopting organization.

## My role

Pallab Haldar is identified as the author and designer of the published methodology. Any employer role, production responsibility or decision authority requires independent verification.

## Operational problem

Fixed reorder points and manual forecasting can produce excess inventory or shortages when consumption, shipments and supply conditions change. The objective was to predict monthly material purchase quantities from governed enterprise data.

## Original contribution

The paper presents an interpretable in-database forecasting pattern using:

- Composite keys for material, warehouse, year and month
- Remaining inventory and shipped quantity as predictors
- Monthly material order quantity as the target
- Linear regression in SAP HANA Predictive Analytics Library
- Database views and temporal holdout validation
- Interpretable coefficient and forecast outputs

## Deployment classification

**Published empirical methodology with a reported SAP HANA PAL implementation context. Production deployment is not independently established by the paper.**

## Deployment details requiring verification

- Organization and program: **To be verified**
- Development and validation dates: **To be verified**
- Prototype, pilot or production classification: **To be verified**
- SAP HANA system and PAL version: **To be verified**
- Model execution and scoring schedule: **To be verified**
- Procurement-workflow integration: **To be verified**
- Release or change identifier: **To be verified**
- Operational monitoring and retraining: **To be verified**

## Supporting records

- Publisher and DOI record
- Sanitized SAP HANA design and model output
- Release or change-management record
- Validation report
- Workflow or user evidence
- Independent employer, client or technical-verifier letter
