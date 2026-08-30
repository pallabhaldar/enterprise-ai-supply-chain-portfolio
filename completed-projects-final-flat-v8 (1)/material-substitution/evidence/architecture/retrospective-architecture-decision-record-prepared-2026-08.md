# Retrospective Architecture Decision Record: Enterprise Material Substitution Architecture

## Document classification

This retrospective record was prepared in August 2026 from applicant-provided information. It is not the original 2019 architecture-review record or the original Version 2.0 diagram. The historical statements should be corroborated using the sanitized review-meeting record, versioned architecture diagram and independent confirmation.

## Architecture identification

- Title: Enterprise Material Substitution Architecture
- Final reported version: Version 2.0
- Project: Predictive Material Substitution
- Organization: Global manufacturing enterprise
- Initial formal architecture review: 2019
- Version 2.0 revision and informal approval period: April-June 2020
- Production deployment: August 2020
- Repository publication date: August 2026

## Decision ownership and review authority

- Architecture contributor: Pallab Haldar
- Reported responsibilities: Data architecture, solution architecture, machine-learning design and production-deployment leadership
- Initial review authority: Enterprise Architecture Team
- Revised integration-design approver: Enterprise Architecture Lead
- Version 2.0 approval classification: Informally approved

The initial architecture review and the later informal approval of Version 2.0 are intentionally distinguished. This record does not characterize Version 2.0 as formally approved unless the original evidence establishes that status.

## Context

The project addressed the need to identify potential material substitutes using governed enterprise data when material shortages and procurement constraints affected supply continuity and production planning. The architecture needed to combine enterprise-data integration, in-database analytical processing and machine-learning scoring while preserving business control over final substitution decisions.

## Initial architecture decision

The reviewed design used:

- SAP HANA analytical architecture
- Enterprise-source data integration
- In-database processing
- Random-forest and decision-tree methods
- Model output supporting material-substitution evaluation

## Version 2.0 revisions

Before implementation, the integration design was revised in two identified areas:

1. Source-data integration
2. SAP HANA data flow

The detailed before-and-after integration pattern remains to be extracted from the versioned architecture diagram. Internal system names, schemas, interfaces and security-sensitive details must be removed from the public version.

## Selection rationale

The architecture was reportedly selected to support:

- In-database analytical processing
- Integration with governed enterprise data

Any additional claim concerning scalability, latency, security, cost or cross-program reuse should be added only when the original record or an authorized verifier confirms it.

## Implementation outcome

Version 2.0 was reportedly implemented for the full-production deployment in August 2020 across four to ten production sites. This implementation statement remains applicant-reported until corroborated by the production record and direct-manager or architecture-lead confirmation.

## Available supporting evidence

The applicant reports having:

- Architecture review-meeting record
- Versioned architecture diagram

The sanitized evidence should establish the document title, version, original date, review participants or authority, decision status, principal architecture decision and relationship between the reviewed version and Version 2.0.

## Remaining evidence gaps

- Exact date of the 2019 formal review
- Initial architecture version number
- Exact date of Version 2.0 informal approval
- Detailed before-and-after integration changes
- Meeting or decision identifier
- Sanitized meeting record and Version 2.0 diagram
- Written confirmation from the Enterprise Architecture Lead or another participant

## Confidentiality statement

Public evidence must remove customer-confidential names, internal hostnames, schemas, credentials, proprietary interfaces, security controls and transaction-level data.
