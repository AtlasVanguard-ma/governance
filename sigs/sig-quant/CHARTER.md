# SIG Charter: Quantitative Research (SIG-QUANT)

## 1. Purpose

SIG-QUANT defines and maintains the quantitative foundations of AtlasVanguard.

It is responsible for ensuring that all quantitative reasoning used across the system is:

- consistent
- reproducible
- well-defined
- methodologically sound

This SIG establishes the canonical quantitative language of the platform.

---

## 2. Mission

The mission of SIG-QUANT is to define and maintain the core quantitative standards used to interpret Moroccan financial markets.

This includes ensuring that all derived metrics and models are:

- mathematically consistent
- empirically meaningful
- comparable across assets and time
- aligned with institutional research standards

---

## 3. Scope

### In Scope

SIG-QUANT governs:

- definitions of financial returns
- volatility frameworks and assumptions
- correlation and dependency measures
- beta and exposure models (in coordination with model governance)
- statistical transformations of market data
- normalization conventions used in quantitative analysis

---

### Out of Scope

SIG-QUANT does NOT govern:

- raw data ingestion or storage (SIG-DATA-INFRASTRUCTURE)
- visualization or reporting (SIG-OBSERVABILITY-COMMUNICATION)
- market structure interpretation (SIG-MARKET-STRUCTURE)
- system-wide risk interpretation (SIG-SYSTEMIC-RISK)

---

## 4. Authority

SIG-QUANT has authority to:

- define canonical quantitative methods
- approve or reject new statistical definitions
- propose new quantitative models through RFCs
- enforce consistency of quantitative assumptions across SIGs

SIG-QUANT does NOT have authority to:

- override Steering Committee decisions
- enforce changes in data architecture
- modify external benchmark definitions independently

---

## 5. Interfaces

SIG-QUANT collaborates with:

- SIG-DATA-INFRASTRUCTURE -> data consistency requirements
- SIG-MARKET-STRUCTURE -> interpretation of market behavior
- SIG-SYSTEMIC-RISK -> stress and instability metrics
- SIG-OBSERVABILITY-COMMUNICATION -> interpretation of outputs
- MODEL-GOVERNANCE -> formal model definitions and validation

---

## 6. Responsibilities

SIG-QUANT is responsible for:

- defining canonical quantitative definitions
- maintaining consistency of statistical methods
- reviewing all quantitative RFCs
- ensuring comparability of metrics across assets
- preventing contradictory mathematical definitions across SIGs

---

## 7. Decision Rights

SIG-QUANT may:

- approve quantitative definitions within its scope
- reject inconsistent or ambiguous statistical proposals
- propose RFCs for new quantitative models

SIG-QUANT may NOT:

- finalize cross-domain governance decisions
- modify benchmark definitions without coordination
- override model governance decisions

---

## 8. Governance Model

All significant changes must follow the RFC process.

This includes:

- new quantitative metrics
- changes in statistical definitions
- modifications of existing formulas
- introduction of new assumptions

---

## 9. Design Principle

SIG-QUANT follows a strict principle:

> “A metric is only valid if it is explicitly defined, reproducible, and consistent across time.”

---

## 10. Success Criteria

SIG-QUANT is successful if:

- quantitative definitions are unambiguous
- no conflicting formulas exist in the system
- all metrics are reproducible
- cross-SIG quantitative consistency is maintained
