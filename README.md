# 📚 Understanding RAG: Recent Literature Review & Best Practices

This repository aims to synthesize **recent developments in Retrieval-Augmented Generation (RAG)**, focusing on:

- How RAG is implemented in the latest research and applications
- Requirements and characteristics of datasets suitable for RAG
- Commonly used tools, technologies, and methodologies
- Strategies and suggestions to improve RAG pipelines

---

## 🔍 Objectives

1. **Survey** and analyze recent (2023–2025) academic and industrial papers using RAG.
2. **Extract** key information about:
   - RAG architectures
   - Dataset design and preprocessing
   - Popular frameworks, models, and retrievers
   - Evaluation metrics
3. **Propose** actionable suggestions to improve and extend RAG pipelines.

---

## 📄 Literature Summary Table

| Title                                | Link to the Source                           | Link to the Repo/Code                                | Year |
|-------------------------------------|----------------------------------------------|------------------------------------------------------|------|
| RAG at Scale: Efficient QA          | [Source](https://arxiv.org/abs/2305.XXXX)    | [Repo](https://github.com/org/rag-at-scale)          | 2023 |
| Multi-hop RAG with Dense Retrieval  | [Source](https://arxiv.org/abs/2402.XXXX)    | [Repo](https://github.com/org/multihop-rag)          | 2024 |
| Dataset Construction for RAG        | [Source](https://arxiv.org/abs/2310.XXXX)    | [Repo](https://github.com/org/rag-dataset-builder)   | 2023 |
| Improving RAG with Feedback Loops   | [Source](https://arxiv.org/abs/2501.XXXX)    | [Repo](https://github.com/org/rag-feedback-pipeline) | 2025 |

> 🔁 Please contribute by adding new papers and filling out the table above!

---

## 🧠 Key Questions Explored

### 1. How is RAG used in recent literature?

- Document-based QA
- Long-context summarization
- Code generation with retrieval
- Domain-specific knowledge grounding (medical, legal)

### 2. What are the requirements for datasets in RAG?

- Chunked, semantically rich documents
- Metadata for filtering/ranking
- Precomputed embeddings or vector indices
- Ground truth answers for evaluation

### 3. Which technologies/tools/methodologies are most used?

| Category             | Tools/Technologies                                                                 |
|----------------------|-------------------------------------------------------------------------------------|
| Language Models      | OpenAI GPT-4, Mistral, LLaMA, T5, FLAN                                             |
| Retrievers           | FAISS, Elasticsearch, Weaviate, BM25, ColBERT                                     |
| Frameworks           | LangChain, Haystack, LlamaIndex, HuggingFace Transformers                         |
| Evaluation           | Exact Match, F1 Score, ROUGE, BLEU, Retrieval Precision/Recall                    |

### 4. How to improve the RAG pipeline?

- Hybrid retrieval (dense + sparse)
- Better chunking & context compression
- Re-ranking retrieved passages with rerankers (e.g., Cohere, BGE)
- Feedback loops and iterative retrieval (e.g., Self-RAG)
- Fine-tuning retrievers on domain-specific corpora
- Latency-optimized serving (e.g., pre-caching, GPU inference)

---

## 📁 Project Structure

```bash
├── papers/                 # PDFs or notes for referenced papers
├── src/                    # Any scripts (e.g., parser, retriever test)
├── notebooks/              # Analysis notebooks
├── data/                   # Example datasets or samples
├── README.md               # This file
