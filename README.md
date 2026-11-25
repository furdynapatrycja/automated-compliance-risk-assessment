
# Automated Compliance Risk Assessment & Register

## Project Overview

This project demonstrates a Python-based Governance, Risk and Compliance (GRC) approach for a fictional European fintech company, FinoraPay.

The solution supports structured business process identification, regulatory mapping, risk assessment, control effectiveness evaluation and remediation tracking.

## Business Scenario

FinoraPay is a fictional financial technology company headquartered in Warsaw, Poland.

- Industry: Financial Technology
- Employees: 250
- Customers: 100,000
- Business model: Digital payment services
- Technology environment: Cloud-based infrastructure

## Project Objectives

- Build a business process inventory.
- Establish a regulatory and standards universe.
- Create a structured risk register.
- Map risks to controls.
- Calculate inherent and residual risk scores.
- Classify risks by severity.
- Track remediation activities.
- Generate management-level reporting.

## Methodology

### Inherent Risk

Inherent Risk Score = Likelihood × Impact × Velocity

Each factor is assessed on a scale from 1 to 5.

### Residual Risk

Residual Risk Score = Inherent Risk Score × (1 - Control Effectiveness)

Control effectiveness is represented as a decimal between 0 and 1.

### Risk Classification

| Score | Risk Level |
|---|---|
| 80–125 | Critical |
| 50–79.99 | High |
| 25–49.99 | Medium |
| Below 25 | Low |

These thresholds are illustrative project assumptions and are not regulatory or ISO-prescribed thresholds.

## Regulatory and Framework References

- GDPR
- DORA
- NIS2
- EU AML Framework
- ISO 27001
- NIST Cybersecurity Framework 2.0

Regulatory applicability is subject to assessment based on the organization's legal status and activities. ISO 27001 and NIST CSF are used as voluntary reference frameworks.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub
- CSV

## Project Structure

- `data/` - Project datasets
- `notebooks/` - Python analysis notebook
- `reports/` - Management reporting
- `visuals/` - Risk visualizations
- `src/` - Reusable Python functions

## Limitations

This is an educational portfolio project using fictional company information and illustrative risk scores.

Control effectiveness values are assumptions, not results of independent control testing.

The project does not constitute a legal opinion, regulatory compliance assessment, audit or certification.

## Author

GRC Portfolio Project
