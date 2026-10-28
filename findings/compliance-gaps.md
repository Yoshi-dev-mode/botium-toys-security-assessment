# Compliance Gap Review

This document organizes compliance-related observations from the supplied Botium Toys case-study materials. It is a preliminary gap review—not a legal determination, audit opinion, or certification.

## PCI DSS — Payment Card Data

The case-study checklist asks whether payment-card data is restricted to authorized users, held in a secure environment, encrypted, and supported by secure password management practices.

### Observations from the source materials

- The risk assessment says all employees had access to internally stored data.
- The report states that locally stored credit card information was not encrypted.
- A centralized password management system was absent.
- A password policy existed but was described as weak or outdated.

### Recommended follow-up

- Identify where payment-card data is stored, processed, or transmitted.
- Review access permissions and restrict access to authorized business needs.
- Assess applicable encryption and payment-data protection requirements.
- Review password and authentication controls.
- Validate applicable PCI DSS requirements against current evidence and the organization's actual payment environment.

## GDPR — Personal Data and Privacy

The source materials describe EU customers, a plan to notify them within 72 hours if a breach occurs, and privacy policies, procedures, and processes that were reported as developed and enforced. The materials also identify weaknesses in asset management and broad access to internally stored data.

### Observations from the source materials

- The report describes a plan to notify EU customers within 72 hours of a breach.
- The report states that privacy policies, procedures, and processes had been developed and enforced.
- The report describes inadequate asset management and broad employee access to internally stored data.

### Recommended follow-up

- Inventory and classify personal data and document where it is stored and processed.
- Review access controls and safeguards for personal data.
- Validate the breach-response process, including roles, escalation, evidence gathering, and applicable notification obligations.
- Review the privacy policies and confirm that actual practices match the documented procedures.
- Assess the applicable GDPR requirements with qualified privacy or legal support where necessary.

**Important:** The existence of a 72-hour notification plan does not, by itself, establish that every applicable GDPR obligation is satisfied.

## SOC-Related Criteria — Security and Operational Controls

The supplied checklist raises questions about user-access policies, confidentiality of PII/SPII, data integrity, and availability.

### Observations from the source materials

- The risk assessment states that least privilege and separation of duties were not implemented.
- The report says all employees had access to internally stored data, which may include customer PII/SPII and payment-card information.
- The report states that availability and data-integrity controls were in place.

### Recommended follow-up

- Review the documented access policies and test whether permissions follow approved roles.
- Identify sensitive data and verify confidentiality safeguards.
- Collect evidence for data-integrity and availability controls.
- Confirm which SOC framework or report type is relevant, define the system boundary, and map evidence to the applicable trust services criteria.

**Important:** A checklist observation is not enough to conclude that an organization does or does not meet a SOC reporting standard. The applicable criteria and supporting evidence must be determined.

## Evidence to Collect

- Current asset inventory and data classification
- Access-control policy, user-role matrix, and access-review records
- Encryption configuration and data-storage inventory
- Password policy and password-management evidence
- Backup logs and restoration-test results
- Disaster recovery plan and exercise records
- Incident-response and breach-notification procedures
- Firewall, antivirus, and security-monitoring records
- Privacy policies and evidence of implementation
- Control-owner interviews and approved exceptions
