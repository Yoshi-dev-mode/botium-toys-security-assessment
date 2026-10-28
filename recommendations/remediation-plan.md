# Remediation Plan

This plan proposes actions based on the findings described in the Botium Toys case-study materials. Owners and priorities are suggestions for the exercise, not actual assignments made by Botium Toys.

| ID | Proposed action | Priority | Suggested owner | Example evidence of completion |
|---|---|---|---|---|
| A-01 | Inventory user accounts and implement least-privilege access. | Critical | IT / Security | Approved role-access matrix and completed access review |
| A-02 | Identify payment-data storage locations and implement appropriate safeguards, including encryption where required. | Critical | IT / Security | Data-location inventory, documented configuration, and validation results |
| A-03 | Define backup scope, frequency, retention, and protection for critical data. | Critical | IT Operations | Backup policy and successful backup logs |
| A-04 | Create a disaster recovery plan and test recovery procedures. | Critical | IT Operations / Business Continuity | Approved plan and documented exercise results |
| A-05 | Review and strengthen password requirements. | High | IT / Security | Approved policy and documented communication |
| A-06 | Evaluate centralized password management. | High | IT / Security | Decision record and, if adopted, deployment and configuration evidence |
| A-07 | Evaluate IDS or other suitable security monitoring capabilities. | High | Network / Security | Monitoring design, alert tests, and documented coverage |
| A-08 | Define separation of duties and review conflicting permissions. | High | IT / Management | Approved role definitions and access-review records |
| A-09 | Create an asset inventory and classify sensitive data. | High | IT / Data Owners | Maintained asset register and data classification records |
| A-10 | Establish a scheduled legacy-system maintenance process. | Medium | IT Operations | Maintenance calendar, completed work records, and intervention procedures |
| A-11 | Validate existing firewall, antivirus, physical-security, and fire-system controls. | Medium | Relevant control owners | Configuration reviews, inspection records, and test results |

## Suggested Implementation Sequence

### Phase 1 — Reduce urgent exposure

1. Identify sensitive payment data and limit access to approved personnel.
2. Establish reliable backups for critical data.
3. Develop a disaster recovery plan and schedule a recovery test.
4. Review high-risk user permissions.

### Phase 2 — Improve preventive and detective controls

1. Strengthen password requirements and password administration.
2. Evaluate security monitoring and intrusion detection needs.
3. Implement separation of duties.
4. Validate existing firewall and antivirus controls.

### Phase 3 — Improve governance and evidence

1. Build and maintain an asset inventory.
2. Classify sensitive data and document where it resides.
3. Schedule legacy-system maintenance.
4. Review privacy and compliance documentation.
5. Track control ownership, exceptions, and validation results.

## Tracking Template

For a real implementation, track each action with these fields:

| Field | Description |
|---|---|
| Finding ID | Links the action to a documented risk |
| Action | Specific work to be completed |
| Owner | Person or team accountable |
| Priority | Agreed risk-based priority |
| Target date | Approved due date |
| Status | Not Started, In Progress, Implemented, or Validated |
| Evidence | Link to the relevant records or test results |
| Validation | Who reviewed the evidence and the outcome |

Do not mark a control as implemented or validated until supporting evidence has been reviewed. Priorities should be confirmed using a documented likelihood-and-impact method and the organization's business context.
