# Architecture Record: Inventory Target Prediction

- Record status: **Published technical architecture; organizational approval not established**
- Dataset period: 2020-2023
- Original architecture decision date: **To be verified**
- Repository publication date: **Use the actual Git commit date**
- Architecture author: Pallab Haldar
- Review or approval authority: **To be verified**
- Approval status: **Not established by the publication**

## Context

The architecture needed to use enterprise inventory and shipment history for monthly material-order forecasting while limiting data movement and retaining interpretable decision logic for procurement stakeholders.

## Proposed decision

Create governed database views over SAP ERP-derived inventory, shipment and procurement data; construct material-warehouse-time composite keys; use remaining inventory and shipped quantity as predictors; execute linear regression using SAP HANA PAL; validate on temporally held-out observations; and expose predicted monthly order quantities for procurement decision support.

## Alternatives considered

The paper discusses fixed reorder points, manual or spreadsheet forecasting, classical time-series methods and more complex machine-learning algorithms. It intentionally favors linear regression for interpretability and computational efficiency. A formal organizational alternatives decision must be confirmed by the original review record.

## Technical significance

The pattern brings interpretable forecasting closer to governed enterprise data, reduces the need for extracting data to a separate modeling platform, and provides a reusable material-location-time structure. Claims about production scalability, latency, security or reuse require implementation evidence.

## Implementation and adoption

- Implemented PAL procedure and configuration: **To be verified**
- Approved environment: **To be verified**
- Procurement integration: **To be verified**
- Operational users: **To be verified**
- Reuse by other programs: **To be verified**

## Verification

Add a sanitized architecture document, dated database-view or PAL configuration record, approval email, change record or independent letter showing the original decision date, review authority, applicant's role and implementation outcome.
