# Architecture Record: Integrated Small Food Supply Chain Optimization

- Record status: **Published research architecture; organizational approval not established**
- Publication year: 2026
- Original architecture decision date: **To be verified**
- Repository publication date: **Use the actual Git commit date**
- Architecture author: Pallab Haldar
- Review or approval authority: **To be verified**
- Approval status: **Not established by the paper**

## Context

Small food retailers face volatile demand, perishability, stock imbalance, delivery-routing inefficiency, supplier dependence and cost instability. A useful architecture must coordinate forecasting, replenishment, routing and budget decisions rather than optimize each process in isolation.

## Proposed architecture

1. Collect and preprocess historical sales, inventory, supplier and route information.
2. Use ARIMA for interpretable time-series forecasting and LSTM for nonlinear sequence patterns.
3. calculate replenishment quantities and reorder points using EOQ and real-time sales information.
4. Use Dijkstra and VRP methods to plan delivery routes.
5. Apply linear programming and the Simplex method to minimize constrained supply-chain cost.
6. Integrate outputs into an end-to-end decision-support workflow.

## Alternatives considered

The paper contrasts the proposed approach with manual forecasting and heuristic routing at a conceptual level. Any formal alternatives analysis or organizational rejection decision must be supported by the original architecture-review record.

## Technical significance

The contribution is the integration of forecasting, replenishment, routing and cost optimization for resource-constrained small-food operations. Its claimed scalability, security, governance and production resilience require implementation evidence.

## Implementation and adoption

- Implemented architecture version: **To be verified**
- Review or approval date: **To be verified**
- Deployment status: **To be verified**
- Reuse by other stores or organizations: **To be verified**

## Verification

Pair the published architecture with a contemporaneous design record, dated code or model artifact, approval email, implementation record or independent letter. A newly authored repository diagram explains the method but does not prove historical approval.
