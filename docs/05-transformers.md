# Transformers

## What They Are
Self-attention enables parallel processing, long-range dependencies, and transfer learning. Foundation for modern language models across text and, increasingly, vision.

## Enterprise Use Cases
- HR/Admin: Policy Q&A, summarization, job description generation, feedback analysis
- Legal: Contract analysis, case-law research, due diligence, compliance scanning
- Finance: Narrative report generation, risk assessment, regulatory preparation, market/news summarization
- Procurement: RFP parsing, vendor analysis, contract review support, supply risk monitoring

## Developer Snapshot
- Training from scratch: impractical for most teams
- Practical paths: prompting + retrieval; fine-tuning with LoRA/QLoRA on 1K–10K examples
- Costs & Timeline: ~$100K–$500K for integrated fine-tuned systems; 8–20 weeks
- Tooling: Hugging Face Transformers/PEFT, PyTorch/TensorFlow; ONNX/vLLM for serving

## Business Impact & ROI
- Contract analysis “copilot” can accelerate legal review significantly (see [ROI examples](appendix-roi-examples.md))
- Human-in-the-loop remains essential for high-stakes outputs

## When to Use / Avoid
- Use: Long-document understanding, context-sensitive analysis, search + summarization
- Avoid: Keyword search or rule-based parsing already sufficient; extreme budget constraints
