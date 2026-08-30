# Retrospective Architecture Decision Record: Inventory Target Prediction

## Document classification

This retrospective record was prepared in August 2026. It is not the original Architecture Board record and must be corroborated by the versioned diagram and architecture-review record.

## Decision

The Architecture Board reportedly approved an in-database predictive workflow using linear regression in SAP HANA Predictive Analytics Library before the May 2024 limited-production deployment. The exact approval date is unavailable and is not estimated.

## Approved design

- Historical inventory and shipment data held in the enterprise data platform
- Data preparation and analytical views inside SAP HANA
- Linear-regression training and scoring using SAP HANA PAL
- Monthly material-purchase quantity as the prediction target
- Current inventory and recent shipment quantities as core predictors
- Operational consumption of predictions by procurement and planning users

## Rationale

The design supported reduced data movement, in-database processing, enterprise governance and interpretable predictions suitable for operational review. It replaced reliance on manual forecasting and fixed reorder-point logic with a repeatable predictive workflow.

## Applicant's contribution

Pallab Haldar reports responsibility for the data architecture, model design and configuration, SAP HANA PAL implementation and limited-production deployment leadership.

## Approval evidence identified

- Architecture-review record
- Versioned architecture diagram

## Standardization

The architecture reportedly later became an approved or published pattern supported by a published architecture standard and reusable solution template. The exact publication date, title, identifier and approval authority remain to be confirmed.

## Remaining evidence gaps

- Original Architecture Board date and meeting or decision identifier
- Architecture title and version
- Board participants or approving authority record
- Alternatives considered and recorded rationale
- Standard title, version, publication date and repository location
- Authenticated verifier confirmation

## Evidence-integrity statement

No approval date, document identifier or version has been invented. The record states only that approval preceded the May 2024 deployment.
