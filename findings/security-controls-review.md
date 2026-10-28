# Security Controls Review

This review summarizes the control status described in the Botium Toys case-study report and checklist. **Reported status is not the same as independently verified effectiveness.**

| Control | Status based on source materials | Notes |
|---|---|---|
| Least privilege | Not implemented | Access should be reviewed against job responsibilities. |
| Disaster recovery plan | Not in place | Create and test a documented recovery plan. |
| Password policy | Exists, but weak or outdated | Review requirements and communicate them to users. |
| Separation of duties | Not implemented | Define roles and separate conflicting responsibilities where appropriate. |
| Firewall | Reported as present | The report says firewall rules are configured to block traffic; configuration was not independently tested. |
| Intrusion detection system (IDS) | Not in place | Evaluate monitoring and detection needs. |
| Backups of critical data | Not in place | Define backup scope, frequency, retention, and restoration testing. |
| Antivirus | Reported as present and regularly monitored | Confirm coverage and monitoring evidence during a real assessment. |
| Legacy-system monitoring and maintenance | Reported as present, but inconsistent | Establish a regular schedule and document intervention procedures. |
| Encryption of locally stored credit card information | Not in place | Identify affected data stores and determine appropriate protection requirements. |
| Centralized password management | Not in place | Evaluate a suitable managed approach. |
| Physical locks | Reported as present | Validate coverage and operation during an on-site review. |
| CCTV | Reported as up to date | Validate coverage, retention, access restrictions, and operation if in scope. |
| Fire detection/prevention systems | Reported as functioning | Validate inspection and maintenance records if in scope. |

## Interpretation

The source materials describe a mixture of existing controls and significant gaps. The most urgent proposed actions concern access control, sensitive payment-data protection, and the ability to recover critical data and services.

Controls marked as present should not automatically be treated as effective. A real assessment would collect evidence such as configurations, policies, access reviews, logs, backup restoration results, maintenance records, and interviews.

## Validation Checklist

- [ ] Confirm the current asset inventory and identify sensitive-data locations.
- [ ] Review user accounts, roles, and permissions.
- [ ] Inspect relevant firewall and endpoint-protection configurations.
- [ ] Confirm whether an IDS or equivalent monitoring capability exists.
- [ ] Review encryption and payment-data storage practices.
- [ ] Inspect backup schedules and perform an authorized restoration test.
- [ ] Review disaster recovery documentation and test results.
- [ ] Review password policy and password administration practices.
- [ ] Confirm legacy-system maintenance schedules and procedures.
- [ ] Review physical-security inspection and maintenance evidence.
