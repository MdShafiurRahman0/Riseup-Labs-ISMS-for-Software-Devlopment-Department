# Risk Register

**Organization:** Riseup Labs  
**Document ID:** RUL-ISMS-005  
**Framework:** ISO/IEC 27001:2022  
**Version:** 1.0  
**Status:** Draft  
**Data Classification:** Portfolio Simulation – Fictional Internal Data

## 1. Purpose

The purpose of this Risk Register is to identify, assess, document, and track information security risks associated with the simulated Software Engineering & Application Development environment.

This register helps the organization understand potential threats, vulnerabilities, likelihood, impact, and risk levels affecting its information assets.

It also supports risk-based decision-making and helps prioritize appropriate risk treatment actions.

## 2. Risk Assessment Methodology

A proposed 5×5 Risk Assessment Matrix is used for this educational simulation.

### 2.1 Likelihood Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | Very unlikely to occur |
| 2 | Unlikely | Not expected to occur frequently |
| 3 | Possible | May occur under certain circumstances |
| 4 | Likely | Has a reasonable possibility of occurring |
| 5 | Almost Certain | Expected to occur frequently or repeatedly |

### 2.2 Impact Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Insignificant | Negligible business impact |
| 2 | Minor | Limited operational impact |
| 3 | Moderate | Noticeable business or operational impact |
| 4 | Major | Significant financial, operational, or reputational impact |
| 5 | Severe | Critical business disruption, major data exposure, or serious contractual impact |

### 2.3 Risk Calculation

**Risk Score = Likelihood × Impact**

| Risk Score | Risk Level |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

These thresholds are proposed for this portfolio simulation and are not prescribed by ISO/IEC 27001.

## 3. Identified Information Security Risks

### Risk RA-001: Unauthorized Access to Client Source Code

| Field | Details |
|---|---|
| Risk ID | RA-001 |
| Related Asset ID | AST-001 |
| Asset Name | Client Source Code |
| Threat | Unauthorized Access / Credential Compromise |
| Vulnerability | MFA is not enabled on a simulated developer GitHub account |
| Risk Scenario | An attacker may compromise a developer's GitHub account and gain unauthorized access to confidential client source code. |
| Potential Consequences | Source code leakage, intellectual property theft, unauthorized code modification, contractual and reputational damage |
| Likelihood | 4 – Likely |
| Impact | 5 – Severe |
| Inherent Risk Score | 20 |
| Inherent Risk Level | Critical |
| Existing Controls | Not assessed – Evidence Pending |
| Recommended Treatment | Enforce mandatory MFA, review repository permissions, implement appropriate SSO, and monitor suspicious account activity. |
| Assessment Status | Hypothetical – Pending Evidence Validation |

## 4. Risk Assessment Summary

| Risk ID | Asset | Risk Description | Likelihood | Impact | Score | Level |
|---|---|---|---:|---:|---:|---|
| RA-001 | AST-001 | Unauthorized access to client source code | 4 | 5 | 20 | Critical |

## 5. Risk Treatment
