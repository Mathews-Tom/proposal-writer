# Proposal Structure

Section order, content requirements, and formatting rules for technical proposals.

---

## Section Order

| # | Section | Required | Purpose |
|---|---------|----------|---------|
| 1 | Cover Page | Yes | Title, client, date, version, validity period |
| 2 | Executive Summary | Yes | 3-4 sentences: problem, solution, ROI, investment range |
| 3 | The Challenge | Yes | Problem-Agitate framing with quantified cost of inaction |
| 4 | Proposed Solution | Yes | Solution in business language, architecture diagram |
| 5 | Scope of Work | Yes | Inclusions, exclusions, optional add-ons |
| 6 | Deliverables | Yes | Table: name, description, acceptance criteria, target date |
| 7 | Timeline & Milestones | Yes | Phased timeline with gate criteria |
| 8 | Investment | Yes | Three pricing tiers with itemized breakdown |
| 9 | Return on Investment | Yes | ROI table with payback period and 3-year projection |
| 10 | Team & Approach | Yes | Methodology, team composition, communication cadence |
| 11 | Governance | Yes | Change requests, escalation, status reporting |
| 12 | Terms | Yes | Validity, payment, IP, confidentiality |
| 13 | Next Steps | Yes | Concrete actions with owners and dates |
| 14 | Appendix | Optional | Technical specifications, detailed estimates, references |

---

## Problem-Agitate-Solve Framework

### Problem (Section 3, Part 1)

- State the business challenge in the client's language
- Reference specific pain points from client context
- Use present tense: "The current system requires..." not "The system has been..."

### Agitate (Section 3, Part 2)

- Quantify the cost of inaction over 6-12 months
- Categories: wasted labor hours, missed revenue, accumulated technical debt, competitive risk
- Use specific dollar figures or percentages
- "If [current state] continues for 12 months, [quantified consequence]"

### Solve (Section 4)

- Present the solution as the bridge from current state to desired state
- Lead with outcomes, follow with approach
- Every technical choice maps to a business impact
- Architecture diagram embedded (from architecture-diagram skill)

---

## Scope of Work Format

Three-column table with explicit boundaries:

| Included | Excluded | Optional |
|----------|----------|----------|
| Items the engagement delivers | Items explicitly out of scope | Items available as add-ons |
| Defined with acceptance criteria | Named to prevent scope creep | Priced separately per tier |

### Scope Rules

- Every item in "Included" has a matching entry in the Deliverables table
- "Excluded" is not optional — name specific items clients commonly assume are included
- "Optional" items appear in Enterprise tier and as add-on pricing

---

## Deliverables Table Format

| # | Deliverable | Description | Acceptance Criteria | Target Date |
|---|-------------|-------------|---------------------|-------------|
| 1 | Name | What it is | How the client verifies completion | When |

### Acceptance Criteria Rules

- Measurable and binary (pass/fail, not subjective quality)
- Client-verifiable without technical expertise where possible
- Examples: "API responds to all documented endpoints", "Dashboard loads in <3s", "Migration completes with zero data loss"

---

## Governance Section

### Change Request Process

1. Change requested in writing
2. Impact assessment within 2 business days (scope, timeline, cost)
3. Client approves or withdraws
4. Approved changes update SOW and timeline

### Status Reporting

| Cadence | Format | Audience |
|---------|--------|----------|
| Weekly | Written status report | Project stakeholders |
| Bi-weekly | Video call | Project sponsor |
| Ad hoc | Slack/email | Day-to-day contacts |

### Escalation Path

| Level | Trigger | Owner |
|-------|---------|-------|
| L1 | Task delayed >2 days | Project manager |
| L2 | Milestone at risk | Delivery lead |
| L3 | Scope or budget dispute | Executive sponsor |

---

## Terms Defaults

| Term | Default |
|------|---------|
| Proposal validity | 30 days from date |
| Payment schedule | Milestone-based (Professional tier) |
| IP ownership | Client owns deliverables, vendor retains pre-existing IP |
| Confidentiality | Mutual NDA required before engagement |
| Warranty | 30 days post-delivery for defect fixes |
