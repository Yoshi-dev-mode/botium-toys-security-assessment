# Botium Toys Cybersecurity Risk Assessment

A cybersecurity portfolio case study focused on reviewing security controls, documenting potential risks, identifying compliance-related gaps, and proposing prioritized remediation actions.

> **Project type:** Educational case study  
> **Focus:** Risk assessment, security controls, compliance gap review, remediation planning  
> **Case-study organization:** Botium Toys  
> **Assessment basis:** Provided scope, goals and risk assessment report; control categories reference; controls and compliance checklist

## Overview

This project reviews the security posture described in the Botium Toys case-study materials. It summarizes the documented control environment, identifies areas that may expose the organization to risk, and proposes actions to improve security and operational resilience.

The source report assigns an overall risk score of **8/10** and describes the risk level as fairly high. This score is reproduced from the case-study material; it is not an independently calculated score.

## Objectives

- Review the security controls described in the case-study documents.
- Identify missing, weak, or inconsistently maintained controls.
- Consider risks involving access management, sensitive data, recovery, network monitoring, and asset visibility.
- Summarize compliance-related questions involving PCI DSS, GDPR, and SOC criteria.
- Propose prioritized remediation actions and evidence that could be used to validate improvements.

## Assessment Scope

The source materials describe a review covering:

- Asset inventory and management
- Employee devices and internal systems
- Network security and firewall controls
- User access and separation of duties
- Password policy and password management
- Sensitive data protection and encryption
- Antivirus and intrusion detection
- Backups and disaster recovery
- Legacy-system monitoring and maintenance
- Physical security, including locks, CCTV, and fire systems
- Compliance-related practices and documentation

## Key Findings

Based on the supplied case-study report:

- **Access management:** Least privilege and separation of duties were not implemented, and the report states that all employees could access internally stored data.
- **Payment-data protection:** Locally stored credit card information was not encrypted.
- **Recovery readiness:** Disaster recovery plans and backups of critical data were not in place.
- **Threat detection:** An intrusion detection system was not in place.
- **Password security:** A password policy existed, but its requirements were described as weak or outdated. A centralized password management system was also absent.
- **Asset visibility:** The report describes inadequate asset management and uncertainty about which assets were at risk.
- **Legacy systems:** Monitoring and maintenance were reported, but there was no regular schedule and intervention methods were unclear.
- **Existing controls:** The report describes firewall rules, monitored antivirus, physical locks, CCTV, and functioning fire systems.

These findings reflect what the source documents report; they have not been independently validated through technical testing.

## Recommended Priorities

| Priority | Proposed action | Intended outcome |
|---|---|---|
| Critical | Review access permissions and implement least privilege | Limit access to approved business needs |
| Critical | Identify payment-data storage locations and apply appropriate protection, including encryption where required | Reduce the risk of sensitive payment data exposure |
| Critical | Establish and test backups for critical data | Improve recovery from data loss |
| Critical | Create and test a disaster recovery plan | Improve resilience during major incidents |
| High | Strengthen and review password requirements | Improve account security |
| High | Evaluate centralized password management | Improve consistency of password administration |
| High | Evaluate intrusion detection and monitoring capabilities | Improve visibility into suspicious activity |
| High | Implement separation of duties | Reduce excessive privileges and conflicting responsibilities |
| High | Create an asset inventory and data-classification process | Improve visibility into assets and sensitive data |
| Medium | Schedule and document legacy-system maintenance | Make maintenance more consistent and auditable |

Priorities above are proposed for this portfolio analysis. They are not all assigned by the original report, and they should be refined using an explicit likelihood-and-impact method.

## Repository Guide

- [Identified Risks](findings/identified-risks.md) — risk register with impacts and proposed priorities.
- [Security Controls Review](findings/security-controls-review.md) — summary of reported control status.
- [Compliance Gap Review](findings/compliance-gaps.md) — questions and gaps to validate against applicable requirements.
- [Remediation Plan](recommendations/remediation-plan.md) — suggested actions, owners, and validation evidence.
- [Source Documents](docs/README.md) — guidance for handling the supporting case-study materials.

## Methodology

1. Review the scope and risk assessment report.
2. Compare reported controls with the control categories reference and checklist.
3. Record the documented state of each control.
4. Describe potential impacts without assuming an incident has occurred.
5. Propose remediation actions and evidence that could validate completion.

## Limitations

This is a document-based educational assessment, not a live technical audit, penetration test, legal opinion, or formal compliance certification. The findings depend on the completeness and accuracy of the supplied case-study documents. Compliance-related observations should be validated against applicable requirements and supporting evidence before being treated as definitive conclusions.

## Disclaimer

This project is intended to demonstrate cybersecurity analysis and documentation skills. Botium Toys is used as a case-study organization. Third-party course materials should only be redistributed when their licensing and sharing permissions allow it; see [Source Documents](docs/README.md).

## Skills Demonstrated

- Cybersecurity risk identification
- Security controls review
- Access management analysis
- Data protection review
- Compliance gap analysis
- Risk prioritization
- Remediation planning
- Security documentation
