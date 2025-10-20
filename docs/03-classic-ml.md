# Classic Machine Learning

## 2.1 Supervised Learning — Predict with Labels
Train on input-output pairs (features → label) to learn a predictive function.
- Enterprise use: Attrition prediction, resume screening, risk scoring, demand forecasting
- Skills: Feature engineering, cross-validation, bias/variance control
- Data & Cost: 1K+ labeled examples; quality trumps quantity; ~$50K–$200K
- Metrics: Accuracy, precision, recall, ROC/AUC; calibrate thresholds to business costs
- ROI examples: Attrition prediction, fraud detection (see [ROI examples](appendix-roi-examples.md))

## 2.2 Unsupervised Learning — Discover Structure
Learn from unlabeled data to find clusters, anomalies, or embeddings.
- Enterprise use: Employee/vendor segmentation, anomaly detection, survey/log analysis
- Department examples
  - HR: Skills gap analysis; engagement profiles from surveys
  - Finance: Vendor clustering; budget anomaly detection
  - Procurement: Supplier segmentation; seasonal demand patterns
  - IT: Network/user behavior anomaly detection; log error pattern discovery
- Challenge: Interpreting patterns without ground truth; requires domain validation
- Data & Cost: Often 10K+ samples for stability; ~$40K–$150K
- Timeline: ~6–12 weeks including interpretation with stakeholders
- ROI examples: Employee segmentation, fraud anomaly triage (see [ROI examples](appendix-roi-examples.md))

## 2.3 Reinforcement Learning — Learn via Feedback
An agent learns via trial-and-error to maximize a reward in an environment.
- Enterprise status: Mostly experimental for typical back-office functions
- Use cases: Dynamic resource allocation, network/logistics optimization, pricing (advanced)
- Detailed examples
  - Advanced IT Ops: Auto-scaling resources; incident response sequencing
  - Supply Chain & Logistics: Inventory/restocking policies; warehouse robotics; dynamic pricing
  - Finance (HFT): Strategy learning; dynamic portfolio rebalancing; adaptive hedging
  - Experimental HR: Interview scheduling; training path optimization; team formation
- Requirements: High-fidelity simulation; careful reward design; specialized talent
- Cost & Timeline: ~$300K–$1M+; 6–24 months; high risk/high reward
- ROI timeline: Year 1 often negative; Years 2–3 break-even if successful; Year 3+ upside
- Example — Supply chain optimization: ~$10M inventory costs; 15% reduction (~$1.5M/yr);
  ~$800K build over 18 months + ~$200K/yr maintenance (see [ROI examples](appendix-roi-examples.md))

## When to Use / Avoid
- Use: Labeled historical data for tabular predictions; when 70–85% accuracy yields value
- Avoid: No labels, perfect accuracy needed, or unstructured text/image tasks (see Deep Learning)
