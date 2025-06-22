
# Agentic RAG vs RAG - LangChain + Elasticsearch

This repository contains my submission for the assignment to build and compare:

- Basic RAG (Retrieval-Augmented Generation)
- Agentic RAG 
- Powered by Elasticsearch + HuggingFace Embeddings
- OpenAI is used as the language model for both pipelines



## Files Included

- `Simple_Rag.ipynb` :Basic RAG pipeline using LangChain and Elasticsearch
- `Agentic_Rag_OpenAi.ipynb` : Toolbased Agentic RAG pipeline with agent planning
- `data/*.txt` :Sample documents used for indexing and answering queries



## Comparison Summary

| Feature              | Basic RAG                          | Agentic RAG                             |
|----------------------|------------------------------------|-----------------------------------------|
| Retrieval            | Elasticsearch vector search        | Tool-based document retrieval           |
| Reasoning            | Simple LLM synthesis               | Thought → Action → Observation → Answer |
| Output Quality       | Detailed answers with context      | Concise, action-driven responses         |
| Custom Tools         | No                                 | `document_retrieval` tool             |
| LLM Used             | OpenAI GPT (via key)               | OpenAI GPT (via key)                     |

Both pipelines are implemented using LangChain and HuggingFace embeddings and use the same source documents for fair comparison.


## Demo Video

YouTube: https://youtu.be/f3f21UE7svk






