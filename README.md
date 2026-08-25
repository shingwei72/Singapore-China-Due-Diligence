# US Technology Acquisition — Due Diligence Risk Analysis

## Case Study Overview

This fictional case study models a cross-border enhanced due diligence investigation into **NovaTech Solutions Inc.**, a US-based enterprise technology company being considered for acquisition by a private equity investor.

The objective is to identify **non-financial risks that could affect the transaction**, including political exposure, geopolitical dependencies, supply-chain concentration, cross-border transactions, regulatory issues and management-related risks.

The project demonstrates how SQL can be used to structure, interrogate and analyse due diligence information to support an acquisition decision.

---

## Client Scenario

A private equity investor is conducting preliminary due diligence on NovaTech Solutions Inc. before deciding whether to proceed with an acquisition.

The target operates across several jurisdictions and has exposure to suppliers, counterparties and technology infrastructure in Asia, Europe and North America.

The investigation focuses on whether these relationships create material:

- Geopolitical risks
- Sanctions and export-control risks
- Supply-chain vulnerabilities
- Political exposure
- Regulatory and legal risks
- Cross-border transaction risks

---

## Key Investigative Questions

The analysis was designed around five core questions:

1. Which members of management have political or government connections?
2. Which transactions require enhanced review?
3. Which countries create significant geopolitical or sanctions exposure?
4. Where does the company have material supply-chain concentration?
5. Which legal and regulatory issues could affect the acquisition?

---

## Database Structure

The project uses a relational SQL Server database:

`USTechDueDiligenceWB`

The database contains eight tables:

| Table | Purpose |
|---|---|
| `target_company` | Core information about the acquisition target |
| `management` | Senior management and political connections |
| `ownership` | Shareholders and beneficial ownership |
| `transactions` | Cross-border commercial transactions |
| `suppliers` | Supplier concentration and geopolitical exposure |
| `legal_issues` | Legal and regulatory concerns |
| `countries` | Country-level geopolitical and sanctions risk |
| `country_exposure` | Company's exposure to higher-risk jurisdictions |

---

## Analytical Workflow

The project is organised into eight SQL stages.

### 01 — Database Creation

Creates the dedicated `USTechDueDiligenceWB` database.

### 02 — Schema Creation

Creates the relational database structure and establishes relationships between the tables.

### 03 — Data Insertion

Loads a fictional dataset representing the target company, management, ownership, transactions, suppliers, legal issues and country exposure.

### 04 — Risk Analysis

Identifies initial red flags involving:

- Political connections
- High-risk transactions
- Geopolitical exposure
- Supplier concentration
- Legal and regulatory issues

### 05 — Risk Scoring

Applies a weighted scoring framework to quantify the relative significance of identified risks.

### 06 — Acquisition Risk Matrix

Aggregates the risk indicators into an overall acquisition risk score and preliminary risk classification.

### 07 — Client Risk Summary

Consolidates the most relevant findings into a client-oriented summary.

### 08 — Final Due Diligence Report

Produces a final analytical view of the target's risk profile and a preliminary acquisition recommendation.

---

## Key Findings

The analysis identified several areas requiring enhanced due diligence.

### High-Risk Transactions

Two transactions were flagged for further investigation.

The combined value of these transactions was:

**$15.3 million**

The transactions involved counterparties in **China and Hong Kong**, creating potential geopolitical, sanctions and export-control considerations.

### Geopolitical Exposure

The analysis identified elevated exposure to:

- China
- Taiwan
- Hong Kong

These exposures are particularly relevant to a technology company because geopolitical tensions and regulatory restrictions can affect semiconductor supply chains, cloud infrastructure and cross-border technology transfers.

### Supply-Chain Risk

Several suppliers were identified as having material dependency levels combined with elevated geopolitical risk.

This creates potential **concentration and resilience risks** if geopolitical tensions, export controls or trade restrictions disrupt supply.

### Management Exposure

Three members of senior management were identified as having government or political connections requiring further review.

The presence of a political connection does not itself establish misconduct. However, it creates a requirement for further investigation into the nature, recency and relevance of those relationships.

### Legal and Regulatory Risk

The database identified an ongoing regulatory investigation concerning potential export-control compliance.

This was treated as a high-severity issue within the risk-scoring framework.

---

## Overall Risk Assessment

The weighted risk model produced an overall score of:

**26**

This placed the target in the:

**CRITICAL**

risk category under the project's scoring framework.

The preliminary recommendation was:

> **Do not proceed without enhanced due diligence.**

This does not represent a definitive investment recommendation. Instead, it indicates that the identified risks warrant further investigation before an acquisition decision is made.

---

## Recommended Next Steps

A real-world investigation would require additional research into:

1. Beneficial ownership and corporate structures
2. Sanctions and restricted-party screening
3. Export-control exposure
4. Management biographies and political relationships
5. Counterparty ownership and jurisdictional links
6. Supplier alternatives and supply-chain resilience
7. Regulatory and litigation records
8. Cross-border data-transfer arrangements
9. Technology and intellectual-property exposure
10. Reputational and adverse-media risks

---

## Risk Framework

The project uses a simplified weighted risk model for demonstration purposes.

| Risk Indicator | Weight |
|---|---:|
| Political / management connection | 2 |
| High-risk transaction | 2 |
| High-risk supplier | 2 |
| High-risk country exposure | 3 |
| High-severity legal issue | 3 |

The scoring system is intentionally transparent and reproducible. It is a **portfolio demonstration rather than a proprietary Wallbrook methodology**.

---

## Technical Skills Demonstrated

### SQL

- SQL Server
- Database creation
- Relational data modelling
- Primary and foreign keys
- `SELECT`
- `WHERE`
- `JOIN`
- `GROUP BY`
- `ORDER BY`
- `COUNT`
- `SUM`
- `CASE`
- Common Table Expressions
- Subqueries
- Risk scoring logic

### Analytical Skills

- Enhanced due diligence
- Geopolitical risk assessment
- Sanctions and export-control risk identification
- Supply-chain risk analysis
- Political exposure screening
- Legal/regulatory risk assessment
- Risk prioritisation
- Client-oriented reporting

---

## Limitations

This is a **fictional portfolio case study**. The companies, individuals, transactions and risk indicators are mock data created for analytical and technical demonstration.

The risk score is a simplified model designed to demonstrate how structured risk indicators can be translated into an analytical framework. It should not be interpreted as an actual investment, legal or compliance assessment.

---

## Portfolio Purpose

This project demonstrates the application of **SQL and structured analytical methods to investigative due diligence**.

The emphasis is not solely on technical SQL proficiency, but on using structured data to identify relationships, prioritise risks and communicate findings in a way that could support a client's decision-making process.
