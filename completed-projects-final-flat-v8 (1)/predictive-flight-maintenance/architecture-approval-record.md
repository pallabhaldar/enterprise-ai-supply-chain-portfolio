# Architecture Record: Predictive Flight Maintenance

- Status: **Published research architecture; operational approval not established**
- Original research decision date: **To be verified**
- Repository publication date: **Use the actual Git commit date**
- Architecture author: Pallab Haldar, subject to publication record
- Operational review authority: **Not established**

## Context

The research addresses early identification of maintenance risk from high-volume engine sensor information while supporting governed ingestion, in-database analytics and understandable visualization.

## Proposed architecture

1. Ingest sensor history through an enterprise integration layer such as SAP SDI.
2. Store and prepare governed analytical data in SAP HANA.
3. Apply regression, decision-tree, logistic-regression and One-Class SVM methods using PAL.
4. Compare predictive and anomaly signals.
5. Present maintenance-risk information through SAP Analytics Cloud.

## Alternatives and significance

Document the paper's actual model comparisons and rationale. The significance lies in combining enterprise-data integration, in-database analytics and decision visualization; production safety, certification and airline adoption are outside the verified record.

## Verification

Use the paper, conference presentation, versioned research artifact, reproducible results and independent research verification. Do not label this architecture “Approved” by an airline without a contemporaneous approval record.
