# Deep Learning

## Feedforward Networks (Tabular, Non-Linear)
- Use when classic ML (e.g., XGBoost) plateaus and small gains are valuable
- Data: Larger datasets (50K+ samples) and careful regularization
- Trade-offs: Longer development/tuning; lower interpretability vs linear models

## CNNs (Convolutional Neural Networks)
- Use cases: Document/image processing (OCR, classification), quality control, visual inspection
- Approach: Prefer transfer learning; 1K–10K images per class often sufficient
- Tooling: PyTorch/TensorFlow, torchvision, OpenCV, Tesseract/EasyOCR
- ROI: Receipt processing and document digitization examples (see ROI appendix)

## RNNs/LSTMs (Sequential)
- Use cases: Time series and sequences where order matters; many NLP tasks now use Transformers
- Guidance: Establish baselines (Prophet/ARIMA) before using LSTMs; handle missing/irregular intervals carefully
- Status: Narrowing scope; consider Transformers for language and some time series

## When to Use / Avoid
- Use: Unstructured data (images/signals), complex temporal patterns, or high-value small accuracy gains
- Avoid: Small datasets, strict interpretability/regulatory needs, or very short timelines
