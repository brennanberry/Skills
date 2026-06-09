# ERP: Reconciliation Workflow

Systematic account reconciliation procedures for industrial real estate ERP systems. No reconciliation is complete with an unexplained variance.

## Reconciliation Types

**1. Bank Reconciliation**
- Align GL cash balance with bank statement
- Account for outstanding checks, deposits in transit, bank charges
- Investigate variances > $100

**2. Rent Roll to GL Tie-Out**
- Validate billed rent matches executed leases
- Compare property management exports against AR/revenue GL detail
- Correct discrepancies > $500

**3. AP Sub-Ledger to GL**
- Confirm total open payables = AP GL balance
- Investigate items > $1,000

**4. Intercompany Reconciliation**
- Ensure intercompany receivables and payables net to zero across entities
- Flag timing differences beyond 30 days

**5. Month-End Close Checklist (7-day, 10-step)**
| Day | Owner | Task |
|-----|-------|------|
| 1 | Controller | Cash posting complete |
| 1–2 | AP | Invoice entry cutoff |
| 2–3 | Controller | Accruals posted |
| 3 | Controller | Depreciation run |
| 4–5 | Controller | Sub-ledger tie-outs |
| 6 | Controller | Bank recs complete |
| 7 | Controller/FM | Final review and sign-off |

## Quality Standards
- All open items must have a designated owner and due date
- Audit-ready format: account name, entity, GL balance, bank/sub-ledger balance, reconciling items, required actions
