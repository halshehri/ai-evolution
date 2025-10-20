# Classic Machine Learning

## 2.1 Supervised Learning — Predict with Labels
Train on input-output pairs (features → label) to learn a predictive function.
- Enterprise use: Attrition prediction, resume screening, risk scoring, demand forecasting
- Skills: Feature engineering, cross-validation, bias/variance control
- Data & Cost: 1K+ labeled examples; quality trumps quantity; ~$50K–$200K
- Metrics: Accuracy, precision, recall, ROC/AUC; calibrate thresholds to business costs
- ROI examples: Attrition prediction, fraud detection (see `docs/appendix-roi-examples.md`)

## 2.2 Unsupervised Learning — Discover Structure
Learn from unlabeled data to find clusters, anomalies, or embeddings.
- Enterprise use: Employee/vendor segmentation, anomaly detection, survey/log analysis
- Challenge: Interpreting patterns without ground truth; requires domain validation
- Data & Cost: Often 10K+ samples for stability; ~$40K–$150K
- ROI examples: Employee segmentation, fraud anomaly triage (see ROI appendix)

## 2.3 Reinforcement Learning — Learn via Feedback
An agent learns via trial-and-error to maximize a reward in an environment.
- Enterprise status: Mostly experimental for typical back-office functions
- Use cases: Dynamic resource allocation, network/logistics optimization, pricing (advanced)
- Requirements: High-fidelity simulation; careful reward design; specialized talent
- Cost & Timeline: ~$300K–$1M+; 6–24 months; high risk/high reward

## When to Use / Avoid
- Use: Labeled historical data for tabular predictions; when 70–85% accuracy yields value
- Avoid: No labels, perfect accuracy needed, or unstructured text/image tasks (see Deep Learning)
