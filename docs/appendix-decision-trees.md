# Appendix: Decision Trees

## General AI Method Selection
Start
├── Is the problem deterministic with clear rules?
│   └── Yes → Rule-Based Systems
├── Do you have labeled historical data?
│   └── Yes → Supervised Learning
├── Large unlabeled data to discover patterns?
│   └── Yes → Unsupervised Learning
├── Is the data sequential or time-based?
│   └── Yes → RNN/LSTM or Transformers (time series)
├── Need to generate text/code/images?
│   └── Yes → Generative AI
├── Actions in steps with a reward to optimize?
│   └── Yes → Reinforcement Learning
└── Default → Descriptive analytics or Rule-Based

## Document Automation
Need to process documents?
├── Scanned or image-based?
│   └── Yes → CNN (OCR + preprocessing)
├── Mostly text (contracts, reports)?
│   └── Yes
    ├── Need summaries or answers?
    │   └── Transformers (GPT/BERT)
    ├── Need structured fields?
    │   └── NER with Transformers
    └── Otherwise → Classic NLP or Rule-based parsing

## Build vs Buy
Have a clear, stable use case?
├── Yes
│   ├── Can simple rules solve it?
│   │   └── Rule-Based System
│   └── Do you have in-house data?
│       ├── Yes → Train or fine-tune
│       └── No → Pre-trained models/APIs (with caution)
└── No
    ├── Prototype with pre-trained GenAI
    └── Validate ROI before full build

## ML Algorithm Selection (Detailed)
Supervised vs. Unsupervised?
- Supervised
  - Target continuous
    - If linear: Linear Regression
    - Else: Decision Tree/Random Forest/Gradient Boosting/SVR/NN Regression
  - Target categorical
    - Large/complex: Neural Networks/Deep Learning
    - Else: Logistic Regression/Decision Tree/Random Forest/SVM/Naive Bayes
- Unsupervised
  - Goal: group similar points → Clustering (K-Means/Hierarchical/DBSCAN)
  - Goal: reduce dimensions → PCA/t-SNE/UMAP
  - Goal: associations → Apriori/Eclat
- Reinforcement Learning
  - Q-Learning, Deep Q-Learning, SARSA, Policy Gradients

Source consolidation: merged from Decision Tree document and guide variants.

