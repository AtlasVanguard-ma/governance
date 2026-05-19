# SIG-Data-Infrastructure Charter

## 1. Purpose

SIG-Data-Infrastructure is responsible for designing, building, and maintaining the data foundations that support all AtlasVanguard analytical systems.

It ensures that financial data is reliable, structured, reproducible, and usable across quantitative, risk, and observability workflows.

---

## 2. Scope

SIG-Data-Infrastructure covers:

- Market data ingestion pipelines
- Data normalization and standardization
- Time-series data modeling
- Data quality validation and consistency checks
- Storage structures for financial datasets
- Internal APIs for structured data access
- Data versioning and lineage tracking
- Integration of external financial data sources

---

## 3. Out of Scope

SIG-Data-Infrastructure does NOT cover:

- Definition of financial metrics or models
- Interpretation of market behavior
- Visualization or dashboard design
- Trading or investment logic
- Decision-making frameworks for risk or strategy

---

## 4. Objectives

The SIG aims to:

- Build a unified and reliable financial data foundation
- Ensure consistency across all datasets used in AtlasVanguard
- Reduce data fragmentation across sources and systems
- Enable reproducible quantitative research and analysis
- Support scalable ingestion of Moroccan market data (equities, indices, derivatives where available)

---

## 5. Key Outputs

SIG-Data-Infrastructure produces:

- Data ingestion pipelines and connectors
- Standardized time-series schemas
- Data validation rules and integrity checks
- Cleaned and normalized datasets
- Data access layers (APIs / internal services)
- Documentation of data sources and transformations

---

## 6. Operating Principles

SIG-Data-Infrastructure operates under:

- **Reliability first**: data correctness is more important than completeness
- **Reproducibility**: datasets must be reconstructable from raw sources
- **Standardization**: all data must conform to shared schemas
- **Traceability**: every dataset must have a clear lineage
- **Separation of concerns**: data infrastructure does not define analytics logic

---

## 7. Interfaces with Other SIGs

SIG-Data-Infrastructure collaborates with:

- **SIG-QUANT** → provides structured datasets for returns, volatility, beta models
- **SIG-RISK** → supplies consistent inputs for stress and correlation analysis
- **SIG-MARKET-STRUCTURE** → provides datasets for market behavior analysis
- **SIG-OBSERVABILITY-COMMUNICATION** → supplies structured data for visualization layers

---

## 8. Governance

All changes to data systems must:

- Be documented in GitHub
- Be proposed via RFC when affecting schemas or pipelines
- Maintain backward compatibility where possible
- Be reviewed for downstream impact across SIGs

---

## 9. Membership Expectations

Members of SIG-Data-Infrastructure are expected to:

- Understand basic data engineering principles
- Ensure correctness and consistency of datasets
- Collaborate with quant and risk teams on data requirements
- Prioritize stability and reproducibility over ad-hoc optimization

---

## 10. Deliverables Standard

All outputs must:

- Be reproducible from defined raw inputs
- Follow standardized schemas
- Be versioned when modified
- Be documented for cross-SIG usage

---

## 11. Guiding Principle

SIG-Data-Infrastructure exists to answer:

> “How do we ensure that all financial analysis in AtlasVanguard is built on reliable, structured, and reproducible data?”

---
