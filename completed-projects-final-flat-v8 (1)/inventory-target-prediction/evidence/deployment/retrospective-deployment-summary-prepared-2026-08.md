# Retrospective Deployment Summary: Inventory Target Prediction

## Document classification

This summary was prepared in August 2026 from applicant-provided information and the attached 2025 article, "Inventory Management Optimization: Predictive Material Purchase Target Identification and Forecasting Using Machine Learning." It is not an original deployment record. Deployment claims require corroboration using the identified contemporaneous records.

## Deployment overview

- Organization: Global manufacturing enterprise
- Development start: August 2023
- Limited-production deployment start: May 2024
- Deployment scope: 8 production sites
- Users or people relying on the solution: Approximately 34
- Current status: Reported as continuing through August 2026
- Technology: Linear regression using SAP HANA Predictive Analytics Library

## Operational problem

Manual forecasting and rigid reorder-point methods contributed to excess inventory, tied-up working capital, stockouts and production interruptions. The solution predicted monthly material-purchase quantities using current inventory levels and recent shipment volumes to support more proactive procurement planning.

## Applicant's responsibilities

Pallab Haldar reports responsibility for:

1. Enterprise data-architecture design
2. Linear-regression model design and configuration
3. SAP HANA PAL implementation
4. Limited-production deployment leadership

These responsibilities should be corroborated by the architecture records, release documentation and independent verifier.

## Dataset and workflow

The implementation reportedly used approximately 12.3 million historical inventory records covering 2019 through 2023. The workflow transformed inventory and shipment information into monthly purchase-target predictions inside SAP HANA.

## Identified deployment evidence

- Release record
- Production screenshot
- Operations report

## Remaining evidence gaps

- Exact release identifier and May 2024 deployment date
- Exact system environment and version
- Precise definition of the 12.3-million-record count
- Site and user-count source records
- Named operational owners and participating teams
- Authenticated verifier confirmation

## Evidence-integrity statement

This retrospective record describes a limited-production deployment only. It does not convert the publication into proof of deployment or infer full-production status.
