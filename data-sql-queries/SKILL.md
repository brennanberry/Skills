# Data: SQL Queries

Write SQL queries for extracting and analyzing data from ERP databases in industrial real estate contexts. Use for custom reports, reconciliation validation, and dashboard data extraction. Role: Analyst. Frequency: Weekly.

## Supported Systems
- Yardi custom reporting database
- MRI Software reporting database
- NetSuite GL extracts
- SAP GL extracts

## Common Table Schemas

**Yardi**
- `ENTITY` — property/entity master
- `GLTRANS` — general ledger transactions
- `LEAS` — lease master

**MRI**
- `pr_master` — property master
- `gl_trans` — GL transactions
- `ar_lease` — lease and AR data

## Query Patterns

**GL Trial Balance**
```sql
SELECT account_code, account_name, SUM(amount) as balance
FROM gl_trans
WHERE entity_id = '[property]'
  AND period BETWEEN '[start]' AND '[end]'
GROUP BY account_code, account_name
ORDER BY account_code;
```

**Rent Roll**
```sql
SELECT tenant_name, unit, lease_start, lease_end,
       monthly_rent, sqft
FROM ar_lease
WHERE property_id = '[property]'
  AND status = 'ACTIVE'
ORDER BY lease_end;
```

## Best Practices
- Always include a WHERE clause to limit scope
- Use table aliases for readability
- Test with a narrow date range before full execution
- Add comments explaining non-obvious logic
