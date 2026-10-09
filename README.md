# Veeranjan Reddy

**Senior AI/ML Engineer** · Generative AI, LLMs, RAG & AI agents · MLOps · 8+ years in healthcare, banking and legal tech

I build production AI systems for regulated industries: LLM and RAG applications, tool-calling agents with evaluation and guardrails, predictive models with governed MLOps, and the Spark data pipelines underneath them.

**Stack:** Python · SQL · PyTorch · Scikit-learn · XGBoost · Hugging Face · LangChain/LangGraph · Azure OpenAI · Amazon Bedrock · Databricks (Mosaic AI, Vector Search, Unity Catalog) · MLflow · FastAPI · Docker · Kubernetes · Terraform · Spark/PySpark · AWS · Azure · GCP

## Portfolio

These are representative projects I wrote on **synthetic data**. They contain no employer or client code or data; each shows a pattern I have used in production work.

| Repository | What it demonstrates |
|---|---|
| [clinical-rag-eval](https://github.com/veeranjanreddy-86/clinical-rag-eval) | RAG over clinical-style policy documents: BM25/embeddings retrieval, cited answers, PHI redaction, refusal when unsupported, and an evaluation harness (recall@k, MRR, citation precision, refusal accuracy) behind a FastAPI service |
| [claims-triage-agent](https://github.com/veeranjanreddy-86/claims-triage-agent) | Tool-calling agent for claim-denial triage: typed tools, allowlist and step budget, prompt-injection and PHI guardrails, JSONL tracing, and scenario-based evaluation |
| [fraud-mlops-pipeline](https://github.com/veeranjanreddy-86/fraud-mlops-pipeline) | Imbalanced fraud model (XGBoost, SMOTE) with MLflow tracking and registry, alias-based promotion gates, FastAPI scoring and PSI drift monitoring |
| [lakehouse-medallion-pipeline](https://github.com/veeranjanreddy-86/lakehouse-medallion-pipeline) | PySpark bronze/silver/gold pipeline for CDC data: quarantine, late-event handling, SCD Type 2, data-quality gates, idempotent re-runs, plus a mapping to Databricks |

Every repo includes tests, CI (GitHub Actions), a Dockerfile, a configuration template and a README covering design decisions and limitations.

## Contact

[LinkedIn](https://www.linkedin.com/in/veeranjan-r-07634813a) · veeranjanreddy86@gmail.com · Open to W-2 / full-time AI/ML Engineer roles in the U.S. (remote, hybrid or relocation)
