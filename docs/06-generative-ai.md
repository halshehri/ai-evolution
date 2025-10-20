# Generative AI

## What It Is
Transformer-based models that generate text, code, and images. In enterprises, Retrieval‑Augmented Generation (RAG) is the most valuable and controllable pattern.

## RAG Pattern (Conceptual)
1) Search vector store of authoritative documents → 2) Retrieve top passages → 3) Compose prompt with query + retrieved text → 4) Generate grounded, cited answers
```
[User Question]
   ↓
[Vector Search over Enterprise Docs] → [Top‑k Passages]
   ↓                                  ↘
     [Prompt Composer: Query + Passages + Instructions]
                      ↓
                [LLM Generation]
                      ↓
           [Answer with Citations/Links]
```

## Use Cases
- HR: Draft performance reviews and policies; job descriptions; learning content
- Legal: Contract templates; drafting assistance; clause comparison with citations
- Finance: Narrative reporting; budget justifications; variance explanations
- Admin: Meeting summaries; SOP and process documentation; email drafting

## Developer Snapshot
- Difficulty: Medium; focus on prompt design, retrieval quality, and HITL review
- Fine-tuning: LoRA/QLoRA when domain style/terminology matters; 1K+ examples
- Tooling: LangChain/LlamaIndex; FAISS/Chroma/Weaviate/Pinecone; Transformers/PEFT
- Evaluation: Groundedness, faithfulness, factuality, safety; integrate eval + guardrails
- Inference costs: ~$50–$5,000/month depending on traffic/model size
- Timeline: ~6–16 weeks for integration, tuning, and safety testing

## ROI Examples
- Performance review “cold‑start” reduction with HITL can save ~70% drafting time (see [ROI examples](appendix-roi-examples.md))
