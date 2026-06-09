# God Mode: Extended Autonomous Operation

Enable Claude to handle complex, multi-step industrial real estate workflows with minimal interruptions — planning, executing, and delivering complete results.

## Activation
```
/god-mode [task description]
```
Provide relevant supporting data (GL export, bank statement, rent roll, etc.) with the request.

## Operational Phases

**Phase 1 — Planning**
Display estimated steps, assumptions being made, and data sources being used. Pause for confirmation before proceeding.

**Phase 2 — Execution**
Work through all steps sequentially. Show progress markers: `[Step 3/12 complete]`. No confirmation requests between steps.

**Phase 3 — Delivery**
Structured summary including:
- Work completed
- Key decisions made during execution
- Items requiring human review or approval

## Built-in Safeguards (Always Require Explicit Approval)
- External communications (emails, LP notices)
- Irreversible transactions
- Decisions with > $50K financial impact
- Overriding or deleting existing records

## Best Use Cases
- Full monthly financial close sequence
- Multi-asset portfolio analysis (10+ properties)
- Workflows with clear starting data and well-defined outputs
- Sequential, non-judgmental steps repeated across multiple assets

## Not Suitable For
- Tasks requiring external system access not provided
- Decisions requiring human judgment on strategy or relationship matters
- Situations where assumptions cannot be validated from provided data
