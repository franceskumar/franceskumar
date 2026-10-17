<p align="center">
  <img src="https://raw.githubusercontent.com/franceskumar/franceskumar/main/assets/header.svg" alt="Frances K — AI / LLM Engineer. RAG, agentic systems, and LLM evaluation." width="100%" />
</p>

<p align="center">
  <strong>AI / LLM Engineer at LTIMindtree</strong><br />
  Building document intelligence systems for enterprise insurance workflows.
</p>

## About me

I'm Frances, an AI engineer with 2+ years of production experience building retrieval-augmented generation and multi-agent LLM systems. My work spans document preparation, retrieval, agent orchestration, evaluation, and API serving.

I focus on making answers traceable to their sources, keeping outputs structured, and measuring quality alongside latency.

## What I've built in production

**AI Engineer · LTIMindtree · August 2024–present**

- **Enterprise retrieval:** Designed and deployed a pgvector-backed RAG system indexing millions of insurance documents, achieving **sub-90 ms p95 retrieval latency**.
- **Document automation:** Built LangGraph pipelines to parse, validate, and audit documents, reducing manual processing effort by **45%**.
- **Data preparation:** Developed Python pipelines for text cleaning, chunking, and PII masking to prepare domain corpora for LLM grounding.
- **Evaluation and observability:** Integrated Ragas and LangSmith to track hallucination rate, context precision, and token latency.
- **Production integration:** Served GenAI workflows through async FastAPI and REST APIs within existing cloud architecture.

## Technical toolkit

| Area | Technologies |
| --- | --- |
| LLMs and agents | LangGraph, LangChain, LlamaIndex, tool calling, structured outputs, prompt engineering |
| Retrieval | Hybrid dense–sparse search, embeddings, chunking, pgvector, Pinecone, Chroma, FAISS |
| Evaluation | Ragas, LangSmith, MLflow |
| Models and adaptation | PyTorch, Hugging Face Transformers, PEFT / LoRA |
| Serving | Python, async FastAPI, vLLM, Docker, REST APIs |
| Data and languages | SQL, PostgreSQL, MS SQL Server, C# / .NET, Java |

## Featured public project

### [PolicyLens · Insurance RAG](https://github.com/franceskumar/insurance-rag)

A local document assistant for exploring insurance policy wording with inspectable source citations.

- Upload text-based PDF, DOCX, Markdown, and text policies.
- Search passages with BM25 and limit questions to a specific policy.
- Inspect source excerpts, section headings, and original PDF page numbers.
- Run without an API key in evidence-extraction mode, or configure Ollama / OpenAI for generated answers.
- Includes document management, recent questions, Markdown export, and **31 integration tests**.

**Stack:** Python · FastAPI · SQLite · BM25 · JavaScript

*PolicyLens is a standalone demo with fictional sample policies. It is separate from the production work described above.*

## Project experience

**Multi-Agent RAG & Document Intelligence System**

Built a document assistant combining hybrid retrieval with multi-step LangGraph workflows. Used Pydantic schemas and tool-use guardrails to constrain outputs, Docker and async FastAPI for serving, and Ragas / LangSmith to assess answer relevance, faithfulness, and token latency.

## Education

**B.Tech · Computer Science and Engineering**

Madanapalle Institute of Technology & Science · Class of 2024

---

Interested in RAG, document intelligence, or evaluating agentic systems? Explore [my repositories](https://github.com/franceskumar?tab=repositories) and [PolicyLens](https://github.com/franceskumar/insurance-rag).
