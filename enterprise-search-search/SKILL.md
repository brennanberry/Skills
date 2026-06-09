# Enterprise Search: Cross-Platform Search

Search across Notion, Google Drive, Gmail, and Slack to locate industrial real estate documents — leases, deal memos, budgets, LP correspondence, permits, and vendor contracts.

## Step 1: Define Your Need
Before searching, specify:
- Document type (lease, budget, memo, email, etc.)
- Property or entity name
- Timeframe
- Key terms or parties involved
- Expected format (spreadsheet, PDF, email, etc.)

## Step 2: Platform-Specific Search Syntax

**Notion**
- Use built-in search: property name, deal name, meeting notes keyword

**Google Drive**
- `type:spreadsheet "[property name]" budget 2024`
- `type:pdf "[address]" lease`

**Gmail**
- `from:[broker email] "[address]" has:attachment`
- `subject:"[property]" after:2024/01/01`

**Slack**
- `in:#channel-name "[keyword]"`
- `from:@person "[property]"`

## Step 3: Cross-Reference
- Check date and author to confirm correct version
- Note document location for future reference

## Common Document Locations by Type
| Document | Typical Location |
|----------|----------------|
| Financial models | Google Drive |
| Meeting notes / SOPs | Notion |
| Broker/vendor correspondence | Gmail |
| Internal team discussion | Slack |
| Executed leases | Google Drive or document management system |
