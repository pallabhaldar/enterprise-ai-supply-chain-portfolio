# Retrospective Deployment Summary: Predictive Flight Maintenance

## Document classification

This retrospective summary was prepared in August 2026 from applicant-provided information. It describes a real limited-production deployment in a production environment at a global airline. It is not an original release record and must be corroborated with the pending architecture document, release record, production screenshot and an authorized airline-side verifier.

## Deployment overview

- Organization: Global airline
- Deployment level: Limited production in a real production environment
- Development date: Unavailable
- Production deployment date: Unavailable and pending confirmation from the release record
- Operational reach: 4 sites or maintenance bases
- Users relying on the solution: Approximately 22 maintenance or engineering users
- Aircraft or engine count: Unavailable
- Current status: Reported as continuing through August 2026

## Operational purpose

The solution supported condition-based aircraft maintenance by ingesting telemetry, calculating component-health and failure-risk indicators, estimating remaining useful life and presenting actionable information to maintenance personnel. It was intended to improve intervention planning compared with exclusively reactive or calendar-based maintenance practices.

## Production data context

The applicant reports that the production solution used a combination of real and simulated telemetry. The relative volume, aircraft coverage, date range and validation role of each source remain to be established from technical and release records.

## Production architecture

- SAP Smart Data Integration for telemetry ingestion
- SAP HANA and Predictive Analytics Library for in-database model training and scoring
- Linear regression for remaining-useful-life estimation
- Decision tree and logistic regression for supervised risk classification
- One-class SVM for anomaly detection
- SAP Analytics Cloud for maintenance dashboards

## Applicant's responsibilities

Pallab Haldar reports responsibility for data architecture, model design, SAP HANA PAL implementation, SDI integration, dashboard architecture and limited-production deployment leadership.

## Primary deployment evidence identified

- Release record
- Sanitized production screenshot
- Versioned architecture diagram, to be attached
- Qualified airline-side verifier, to be identified

## Remaining evidence gaps

- Development and deployment dates
- Release identifier and environment record
- Aircraft or engine scope
- Real-versus-simulated telemetry proportions and date ranges
- Definition and source of the 22-user and four-site counts
- Attached architecture document and approval metadata
- Qualified independent verifier

## Evidence-integrity statement

The accompanying paper is not used as proof of production deployment because its evaluation is explicitly simulated. The real deployment claim depends on separate organizational records.
