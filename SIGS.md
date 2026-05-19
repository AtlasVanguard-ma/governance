# SIGs — AtlasVanguard

This document defines the Special Interest Groups (SIGs) within AtlasVanguard.

SIGs are the primary governance and coordination units of the initiative. Each SIG represents a long-lived domain of responsibility within the AtlasVanguard system and operates under the governance framework defined in `GOVERNANCE.md`.

---

## Overview

SIGs exist to:

- Structure collaboration across distinct domains of the system
- Distribute ownership of research, methodology, and implementation
- Ensure consistency and traceability of decisions via RFCs
- Enable scalable participation across technical and non-technical contributors
- Maintain clear boundaries between domains of responsibility

---

## Current SIGs

| SIG | Focus Area | Repository Location |
|-----|------------|---------------------|
| [SIG-QUANT](./sigs/sig-quant/) | Quantitative models, returns, volatility, beta, exposure analysis | `sigs/sig-quant/` |
| [SIG-MARKET-STRUCTURE](./sigs/sig-market-structure/) | Spot vs futures interaction, MASI/sector structure, price discovery | `sigs/sig-market-structure/` |
| [SIG-RISK](./sigs/sig-risk/) | Systemic risk, stress propagation, correlation breakdown, regime behavior | `sigs/sig-risk/` |
| [SIG-DATA-INFRASTRUCTURE](./sigs/sig-data-infrastructure/) | Data ingestion, normalization, dataset integrity, internal data APIs | `sigs/sig-data-infrastructure/` |
| [SIG-OBSERVABILITY-COMMUNICATION](./sigs/sig-observability-communication/) | Dashboards, visualization, reporting layer, communication of market signals | `sigs/sig-observability-communication/` |

---

## SIG Coordination Model

SIGs operate independently within their defined scope but are expected to coordinate when responsibilities overlap.

Cross-SIG coordination typically occurs through:

- RFC-based proposals
- Explicit interface definitions between domains
- Steering Committee escalation when necessary

No SIG has authority outside its defined scope.

---

## SIG Governance Rules

Each SIG must adhere to the following principles:

- Maintain a clearly defined scope and responsibility boundary
- Designate at least one maintainer or lead
- Document decisions, assumptions, and rationale where relevant
- Use the RFC process for any meaningful structural or methodological change
- Ensure reproducibility and traceability of domain decisions
- Respect governance constraints defined at the system level

SIGs cannot:

- Override governance rules defined in `GOVERNANCE.md`
- Modify system-wide conventions unilaterally
- Resolve cross-domain conflicts without coordination or escalation

---

## SIG Lifecycle

SIGs may evolve over time through governance review:

- **Creation** — when a new domain of responsibility is identified
- **Modification** — when scope or responsibilities evolve
- **Split** — when a domain becomes too large or heterogeneous
- **Merge** — when significant overlap is identified
- **Retirement** — when the domain is no longer active or required

All lifecycle changes must follow the RFC process and Steering Committee review when applicable.

---

## Design Intent

The SIG system is designed to:

- Enable structured, scalable collaboration across domains
- Ensure clear ownership of analytical and engineering responsibilities
- Prevent ambiguity in methodological and system definitions
- Support reproducibility of financial and quantitative research
- Provide a governance foundation compatible with institutional environments

---
