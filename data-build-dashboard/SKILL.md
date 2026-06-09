# Data: Build Dashboard

Create KPI dashboards for industrial real estate portfolio performance tracking. Covers occupancy, NOI, IRR, rent collections, leasing activity, and CapEx metrics.

## Design Principles
- **Audience first**: internal asset managers get operational detail; LP reports focus on returns and capital deployment
- Lead with the most important metric
- Show trend alongside current figure (not just a snapshot)
- Use traffic light indicators (🟢 On track / 🟡 Watch / 🔴 Off track)
- Single-page constraint for external audiences

## Dashboard Types

| Type | Audience | Frequency | Key Metrics |
|------|----------|-----------|-------------|
| Portfolio Management | Internal | Monthly | Occupancy, NOI, collections, CapEx |
| LP Quarterly Report | External | Quarterly | IRR, distributions, equity multiple |
| Rent Collection | Internal | Weekly | Collected %, delinquency, aging |
| Leasing Activity | Internal | Monthly | Tours, proposals, executed leases, pipeline SF |
| Asset Scorecard | Internal/IC | Monthly | All metrics per property |

## Build Workflow
1. Identify key metrics from available data
2. Calculate period comparisons (MoM, YoY, vs. budget)
3. Flag budget variances above materiality threshold
4. Assign status indicators
5. Write 3-point portfolio health summary at top

## Output
Clean table format with clear headers, status indicators, and brief executive summary.
