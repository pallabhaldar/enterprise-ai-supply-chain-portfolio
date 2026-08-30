# Retrospective Architecture Decision Record: Predictive Flight Maintenance

## Document classification

This retrospective record was prepared in August 2026. The original versioned architecture diagram is identified but has not yet been attached or reviewed.

## Reported approval

The Predictive Flight Maintenance architecture was reportedly approved by a Technical Review Committee. The approval date, review identifier, architecture title and version are unavailable.

## Architecture decision

The design integrated telemetry ingestion, in-database analytical processing, model scoring, feedback and visualization:

1. SAP Smart Data Integration ingested aircraft telemetry.
2. SAP HANA stored and prepared time-series data.
3. SAP HANA PAL executed linear regression, decision tree, logistic regression and one-class SVM models.
4. Model outputs supported remaining-useful-life estimation, failure-risk classification and anomaly detection.
5. SAP Analytics Cloud exposed health and maintenance indicators to authorized users.

## Rationale

The architecture supported reduced data movement, controlled analytical processing, integration with enterprise data governance and operational presentation of maintenance-risk information.

## Applicant's contribution

Pallab Haldar reports responsibility for the end-to-end data architecture, analytical model design, SAP HANA PAL implementation, SDI integration, dashboard architecture and deployment leadership.

## Evidence identified

- Versioned architecture diagram, pending attachment
- Technical Review Committee approval record, if available
- Release record
- Configuration records from later reuse
- Later architecture diagrams

## Remaining evidence gaps

- Architecture title, version and date
- Technical Review Committee date and approval record
- Production interfaces, security controls and monitoring design
- Exact real and simulated data flows
- Formal model-governance and aviation-safety boundaries
- Qualified independent verifier

## Evidence-integrity statement

This record does not infer regulatory approval, airworthiness certification or autonomous maintenance authority. The system is documented as maintenance decision support.
