# Operations: Runbook

Create operational runbooks and playbooks for recurring property management processes, maintenance incidents, and tenant procedures.

## Primary Scenarios Covered
- Emergency response (leaks, HVAC failure, fire, flood)
- Tenant move-in and move-out
- Preventive maintenance scheduling
- After-hours incident management
- Vendor escalation
- Seasonal property preparation

## Runbook Template Structure

```
Runbook Title:  [Scenario Name]
Property:       [All / Specific]
Trigger:        [What initiates this runbook]
Owner:          [Primary Role]
Last Updated:   [Date]

IMMEDIATE ACTIONS (First 15 Minutes)
1. [Action] — [Role]
2. [Action] — [Role]

NOTIFICATION SCRIPT
"[Exact language to use when contacting stakeholders]"

ESCALATION PATH
Level 1: Property Manager → [contact]
Level 2: Emergency Vendor → [contact / trade]
Level 3: Asset Manager → [contact]
Level 4: Insurance → [policy / contact]

DECISION TREE
If [condition A]: go to Step X
If [condition B]: go to Step Y

RESOLUTION CRITERIA
- [What "done" looks like]

DOCUMENTATION REQUIRED
- Incident log entry
- Photos
- Vendor work order
- Insurance claim (if applicable)

POST-INCIDENT REVIEW
Schedule within 5 business days. Document root cause and preventive action.
```
