# Identified Risks

This register translates the findings described in the Botium Toys case-study report into potential risks and proposed priorities. Priorities are preliminary portfolio judgments, not scores supplied for every finding by the source report.

| ID | Documented finding | Potential impact | Proposed priority |
|---|---|---|---|
| R-01 | Least privilege was not implemented. | Employees may be able to access information or systems beyond their job requirements. | Critical |
| R-02 | Separation of duties was not implemented. | Conflicting responsibilities may increase the risk of errors or inappropriate activity going unnoticed. | High |
| R-03 | Locally stored credit card information was not encrypted. | Sensitive payment information could be exposed if an unauthorized party accesses the relevant storage. | Critical |
| R-04 | Backups of critical data were not in place. | Critical information may be difficult or impossible to recover after loss or corruption. | Critical |
| R-05 | A disaster recovery plan was not in place. | Recovery from a major incident or service disruption may be delayed or inconsistent. | Critical |
| R-06 | An intrusion detection system was not in place. | Suspicious activity may be harder to identify promptly. | High |
| R-07 | Password requirements were described as weak or outdated. | Weak authentication practices may increase the chance of account compromise. | High |
| R-08 | A centralized password management system was absent. | Password administration may be inconsistent and harder to oversee. | High |
| R-09 | Asset management was inadequate. | The organization may not know which assets hold sensitive data or require protection. | High |
| R-10 | Legacy-system monitoring and maintenance had no regular schedule, and intervention methods were unclear. | Maintenance gaps may allow issues to persist or complicate incident response. | Medium |

## Risk Prioritization Notes

- The source report assigns an overall risk score of **8/10** and describes the overall risk as fairly high.
- The source report does not provide a full likelihood-and-impact score for every item in this register.
- The priority labels in this file are proposed for this portfolio analysis and should be validated using a documented scoring method.
- Potential impacts are scenarios, not claims that an incident has occurred.

## Suggested Next Steps

1. Confirm each finding with evidence from the relevant system, policy, or interview.
2. Identify the affected assets and business processes.
3. Assess likelihood and impact using an agreed risk matrix.
4. Assign a control owner and target date.
5. Track remediation and retain evidence of validation.
