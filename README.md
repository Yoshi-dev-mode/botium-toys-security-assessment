<!--
  Botium Toys Cybersecurity Risk Assessment
  Portfolio case study — document-based review, not a formal audit.
-->

<div align="center">

# 🛡️ Botium Toys Security Assessment

### Cybersecurity Risk Assessment · Controls Review · Remediation Planning

*A practical, documentation-based security case study*

<br>

![Project Type](https://img.shields.io/badge/Project-Educational%20Case%20Study-2457C5?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Cybersecurity-167D6D?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-6D5BD0?style=for-the-badge)

<br>

**[Explore the Findings](findings/identified-risks.md) · [Review the Controls](findings/security-controls-review.md) · [View the Remediation Plan](recommendations/remediation-plan.md)**

</div>

---

## 📌 Project Overview

This project analyzes the security posture described in the **Botium Toys case study**. It organizes reported security weaknesses, reviews existing controls, highlights compliance-related questions, and recommends practical actions to reduce risk.

The goal is to demonstrate how a cybersecurity analyst can turn assessment materials into clear findings and an actionable remediation plan.

> [!IMPORTANT]
> The source report gives an overall risk score of **8/10** and describes the risk level as fairly high. This score is quoted from the case-study material; it was not independently calculated or validated by this project.

## 🧭 At a Glance

| | |
|---|---|
| **Project type** | Educational cybersecurity case study |
| **Organization** | Botium Toys (case-study organization) |
| **Primary focus** | Risk identification and security controls review |
| **Related frameworks** | PCI DSS, GDPR, and SOC-related criteria |
| **Deliverables** | Risk register, controls review, compliance gap review, remediation plan |
| **Assessment method** | Review of supplied documents and checklist |

## 🎯 Objectives

- Review the security controls described in the case-study materials.
- Identify missing, weak, or inconsistently maintained controls.
- Assess potential risks involving access, sensitive data, recovery, monitoring, and asset visibility.
- Organize compliance-related questions involving PCI DSS, GDPR, and SOC criteria.
- Recommend prioritized remediation actions and evidence that could validate improvements.

## 🔍 Assessment Scope

The source materials describe a review of the following areas:

| Domain | Areas considered |
|---|---|
| **Asset management** | Asset inventory, employee devices, internal systems, and data storage |
| **Access management** | Least privilege, account access, and separation of duties |
| **Data protection** | Sensitive data handling and encryption |
| **Network & endpoint security** | Firewall, antivirus, and intrusion detection |
| **Recovery & resilience** | Backups and disaster recovery planning |
| **Identity security** | Password policy and centralized password management |
| **Legacy systems** | Monitoring, maintenance, and intervention procedures |
| **Physical security** | Locks, CCTV, and fire detection/prevention systems |
| **Compliance** | Practices and documentation related to the frameworks referenced in the case study |

## 🚩 Key Findings

The following findings are based on the supplied report and checklist. They are **reported conditions**, not independently verified technical results.

| Finding | What the source materials report | Proposed priority |
|---|---|:---:|
| **Access control** | Least privilege was not implemented; the report says all employees could access internally stored data. | 🔴 Critical |
| **Payment-data protection** | Locally stored credit card information was not encrypted. | 🔴 Critical |
| **Data recovery** | Backups of critical data and a disaster recovery plan were absent. | 🔴 Critical |
| **Threat detection** | An intrusion detection system was not in place. | 🟠 High |
| **Password security** | A password policy existed but was described as weak or outdated; centralized password management was absent. | 🟠 High |
| **Separation of duties** | Separation of duties was not implemented. | 🟠 High |
| **Asset visibility** | Asset management was inadequate, leaving uncertainty about which assets were at risk. | 🟠 High |
| **Legacy-system maintenance** | Monitoring and maintenance existed, but a regular schedule and clear intervention methods were lacking. | 🟡 Medium |

**Priority labels above are proposed for this portfolio analysis.** They are not original scores for every finding and should be refined using a documented likelihood-and-impact method.

## 🧰 Recommended Remediation Roadmap

### 🔴 Critical — Address first

- Review user permissions and implement **least privilege**.
- Identify payment-data locations and apply appropriate safeguards, including encryption where required.
- Establish and test backups for critical data.
- Create and test a disaster recovery plan.

### 🟠 High — Strengthen security controls

- Review and strengthen password requirements.
- Evaluate centralized password management.
- Evaluate intrusion detection and security-monitoring capabilities.
- Implement separation of duties.
- Build an asset inventory and classify sensitive data.

### 🟡 Medium — Improve consistency and evidence

- Schedule and document legacy-system maintenance.
- Validate existing firewall, antivirus, physical-security, and fire-system controls.
- Retain evidence showing that controls operate as intended.

See the [full remediation plan](recommendations/remediation-plan.md) for suggested owners and examples of validation evidence.

## 🗂️ Repository Guide

Use these documents to explore the assessment in more detail:

| Document | Description |
|---|---|
| 📋 [**Identified Risks**](findings/identified-risks.md) | Risk register with documented findings, potential impacts, and proposed priorities |
| 🔐 [**Security Controls Review**](findings/security-controls-review.md) | Summary of the controls reported as present, missing, or needing improvement |
| 📑 [**Compliance Gap Review**](findings/compliance-gaps.md) | Preliminary PCI DSS, GDPR, and SOC-related observations and follow-up questions |
| 🛠️ [**Remediation Plan**](recommendations/remediation-plan.md) | Suggested actions, priorities, owners, and evidence of completion |
| 📚 [**Source Document Notes**](docs/README.md) | Guidance on source materials, redistribution, and assessment limitations |
| 🖼️ [**Project Visuals**](images/README.md) | Ideas for diagrams and visual summaries |

## ⚙️ Methodology

1. **Review** — examine the supplied scope, risk assessment, control reference, and checklist.
2. **Identify** — record the controls and weaknesses described in those materials.
3. **Analyze** — describe plausible impacts without claiming an incident occurred.
4. **Prioritize** — propose an order for remediation based on the potential severity of each issue.
5. **Recommend** — define actions and examples of evidence that could demonstrate progress.
6. **Validate** — identify the additional testing and evidence needed before treating a control as effective.

## 🧠 Skills Demonstrated

- Cybersecurity risk identification and documentation
- Security controls review
- Access management and least-privilege analysis
- Sensitive-data protection review
- Compliance gap analysis
- Risk prioritization
- Remediation planning
- Evidence-based security reporting

## ⚠️ Scope & Limitations

This is a **document-based educational assessment**. It is not a live technical audit, penetration test, legal opinion, or formal compliance certification.

The findings depend on the completeness and accuracy of the supplied case-study materials. A control described as present has not necessarily been tested for effectiveness. Compliance-related observations are preliminary questions for further validation—not definitive conclusions that an organization complies or fails to comply with a law or standard.

## 📚 Source Materials & Responsible Sharing

The analysis is based on the Botium Toys case-study materials covering:

- Scope, goals, and risk assessment
- Security control categories
- Controls and compliance checklist

Before uploading original course PDFs, confirm that their licensing or course terms permit redistribution. If permission is unclear, keep your own analysis in the repository and link to an authorized source where possible. See [source document guidance](docs/README.md).

---

<div align="center">

**Built as a cybersecurity learning and portfolio project.**

*Identify the risk. Understand the control. Recommend the improvement.*

</div>
