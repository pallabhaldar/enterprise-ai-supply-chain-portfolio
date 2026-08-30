# Retrospective Architecture Decision Record: Small Food Supply Chain Optimization

## Document classification

This retrospective record was prepared in August 2026. It requires corroboration using the original Technical Review Committee record and versioned architecture diagram.

## Approval

The architecture was formally approved by the Technical Review Committee before full-production deployment in December 2025.

## Integrated design

1. Historical sales, inventory, procurement, supplier and delivery data were prepared for analytical use.
2. ARIMA and LSTM models generated demand forecasts.
3. EOQ logic translated demand into replenishment recommendations.
4. Dijkstra and Vehicle Routing Problem methods optimized delivery paths and multi-stop routing.
5. Linear programming using the Simplex method optimized spending subject to supplier, storage and budget constraints.
6. Operational outputs supported planning and execution across four facilities.

## Decision rationale

Although seasonal ARIMA achieved higher aggregate forecast accuracy than the integrated final model, the selected architecture addressed a wider decision problem. It combined nonlinear-demand handling with replenishment, routing and cost optimization and produced verified reductions in storage cost, delivery time and procurement expense.

## Applicant's contribution

Pallab Haldar reports responsibility for data architecture, forecasting-model design, replenishment and routing optimization, cost modeling, production integration and deployment leadership.

## Evidence identified

- Architecture-review record
- Versioned architecture diagram
- Later architecture diagrams
- Published architecture standard
- Reusable solution template

## Remaining evidence gaps

- Architecture title, version and approval date
- Technical Review Committee decision identifier
- Production integration, security and monitoring details
- Published-standard title, version and date
- Signed verifier confirmation

## Evidence-integrity statement

The architecture rationale does not claim that the integrated model was the most accurate forecasting method. It records broader operational optimization as the selection basis.
