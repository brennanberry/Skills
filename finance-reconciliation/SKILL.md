# Finance: Account Reconciliation

Bank and account reconciliation for industrial real estate entities. Use for monthly close and audit preparation. Role: Controller. Frequency: Monthly.

## Four-Step Workflow

1. **Data Gathering**
   - GL cash balance
   - Bank statement
   - Prior reconciliation
   - Known outstanding items (checks, deposits in transit)

2. **Standard Reconciliation Format**
   ```
   Bank Statement Balance:          $X,XXX
   + Deposits in Transit:           $X,XXX
   - Outstanding Checks:           ($X,XXX)
   = Adjusted Bank Balance:         $X,XXX

   GL Cash Balance:                 $X,XXX
   +/- Reconciling Items:          $X,XXX
   = Adjusted GL Balance:           $X,XXX

   Difference (must be $0):         $0
   ```

3. **Variance Investigation — Common Causes**
   - Unrecorded bank fees
   - Timing differences
   - Duplicate postings
   - Miscoded transactions

4. **Sub-Ledger Tie-Outs**
   - AP sub-ledger = AP GL control account
   - AR sub-ledger = AR GL control account
   - Fixed asset schedule = FA GL control account
   - Intercompany balances net to zero

## Output Deliverables
- Reconciliation schedule (tabular)
- Variance explanation memo for unresolved items
- Open items log with owner and status
