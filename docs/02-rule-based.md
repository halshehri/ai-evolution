# Rule-Based Systems (Symbolic AI)

## What They Are
Explicitly encoded human logic (if-then rules) rather than learned models. Deterministic, auditable, and easy to debug; ideal for compliance and policy enforcement.

## Enterprise Use Cases
- HR
  - Benefits eligibility checkers (e.g., tenure ≥ 90 days AND status = full-time → eligible)
  - Policy enforcement for time-off requests and onboarding workflows
- Finance
  - Expense approvals (e.g., amount > $500 OR category = Travel → manager approval)
  - Invoice auto-approval below thresholds for pre-approved vendors
  - Basic fraud flags for out-of-pattern transactions
- Procurement
  - Vendor selection decision trees (delivery, price, quality scoring)
  - Purchase order routing by amount/category; renewal alerts (e.g., 60-day notices)
- Legal & Admin
  - Contract/document routing (e.g., contract value > $50K → legal review)
  - Completeness checks and policy compliance gates
  - Access control by role and jurisdiction

## Developer Snapshot
- Difficulty: Very Low; similar to building deterministic workflows/conditionals
- Data: Minimal; rules are authored with domain experts
- Cost & Timeline: $10K–$30K; 2–6 weeks typical
- Maintenance: Can grow in complexity if rules change frequently

## Open-Source Tools
- PyKnow (Python forward-chaining), Drools (Java BRMS), BPM suites with rules engines

## Business Impact & ROI
- Outcomes: 60–80% time savings, 100% consistent application, complete audit trail
- Example — HR Benefits Processing
  - Manual: ~15 min/enrollment → Automated: ~2 min
  - Volume: ~200 enrollments/month → ~43 hours saved/month
  - Savings: ~$2,150/month at $50/hr → ~$25,800 annually
  - Build cost: ~$20,000 → >100% first‑year ROI (see [ROI examples](appendix-roi-examples.md))

## When to Use / Avoid
- Use: Deterministic, auditable logic; stable policy enforcement; low data settings
- Avoid: Logic is fuzzy, must adapt from data, or rules churn rapidly
