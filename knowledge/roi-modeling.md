# ROI Modeling

Reference formulas, calculation patterns, and estimation heuristics for proposal ROI sections.

---

## Core Formulas

| Metric | Formula |
|--------|---------|
| Net Savings (monthly) | Current monthly cost - Post-implementation monthly cost |
| Payback Period | Total investment / Monthly net benefit |
| 3-Year ROI | ((36-month net benefit - Total investment) / Total investment) * 100 |
| Annual Cost Savings | Monthly savings * 12 |
| Efficiency Gain (%) | (Time saved per cycle / Current time per cycle) * 100 |
| Revenue Impact | New revenue enabled + Revenue protected (risk mitigation) |

---

## Cost Categories

### Investment Costs (One-Time)

| Category | Includes |
|----------|----------|
| Development | Engineering hours * blended rate |
| Infrastructure setup | Cloud provisioning, CI/CD, environments |
| Migration | Data migration, cutover, parallel running |
| Training | Team onboarding, documentation |
| Project management | Coordination, status reporting, stakeholder management |

### Ongoing Costs (Annual)

| Category | Includes |
|----------|----------|
| Infrastructure | Compute, storage, networking, SaaS licenses |
| Maintenance | Bug fixes, security patches, dependency updates |
| Support | L1/L2/L3 support hours |
| Monitoring | Observability tooling, incident response |

### Savings Categories

| Category | Measurement |
|----------|-------------|
| Labor reduction | Hours saved * fully-loaded hourly rate |
| Infrastructure optimization | Current spend - Projected spend |
| Error reduction | Error rate reduction * cost-per-error |
| Time-to-market | Release cycle reduction * opportunity cost |
| Downtime prevention | Uptime improvement * revenue-per-hour |

---

## Estimation Heuristics

### Software Development Rates (Blended)

| Role Tier | Range (USD/hr) |
|-----------|----------------|
| Junior engineer | $75-125 |
| Mid-level engineer | $125-200 |
| Senior engineer | $175-275 |
| Architect / Lead | $225-350 |
| Blended team rate | $150-225 |

### Common Efficiency Benchmarks

| Process | Manual Baseline | Automated Target | Typical Gain |
|---------|----------------|-------------------|--------------|
| Deployment | 2-4 hours | 10-30 minutes | 75-90% |
| Code review cycle | 24-48 hours | 2-4 hours | 80-90% |
| Environment provisioning | 1-2 days | 5-15 minutes | 95%+ |
| Incident detection | 15-30 minutes | 1-3 minutes | 85-95% |
| Report generation | 4-8 hours | Real-time | 95%+ |

---

## Presentation Rules

1. Use ranges, not point estimates: "$180K-$240K" not "$210K"
2. State every assumption explicitly: "Assumes 10 engineers at blended rate of $185/hr"
3. Show the math: input values, formula, result — not just the result
4. Separate hard savings (measurable cost reduction) from soft savings (productivity, morale)
5. Include sensitivity analysis for the largest variable: "If team size is 8 instead of 10, payback extends from 9 to 11 months"
6. Round to appropriate precision: thousands for costs, whole months for payback, whole percentages for ROI
7. Never claim ROI without showing the calculation that produces it

---

## ROI Table Template

| Metric | Value |
|--------|-------|
| Total Investment (Professional tier) | $X |
| Annual Cost Savings | $A |
| Annual Efficiency Gains (monetized) | $B |
| Annual Revenue Impact | $C |
| Total Annual Benefit | $A + $B + $C |
| Monthly Net Benefit | Total Annual / 12 |
| Payback Period | Investment / Monthly Net |
| 3-Year Net Benefit | (Annual Benefit * 3) - Investment |
| 3-Year ROI | ((3-Year Net - Investment) / Investment) * 100% |
