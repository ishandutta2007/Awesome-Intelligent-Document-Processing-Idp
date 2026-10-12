# Awesome-Intelligent-Document-Processing-Idp

## Top Intelligent Document Processing (IDP) Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Document Classification, Data Extraction & Workflow Automation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Intelligent Document Processing (IDP)**. These tools use OCR, computer vision, NLP, and large language models to automatically classify, extract, and validate data from unstructured documents — invoices, receipts, contracts, forms, and claims — feeding structured data into downstream systems without manual data entry.



**Examples** include Salesforce Intelligent Document Processing, ABBYY Vantage, Rossum, Hyperscience, Kofax TotalAgility, AWS Textract, Google Document AI, Azure AI Document Intelligence, Infrrd, and Ocrolus (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom extraction schemas, and transparent document workflows — ideal for organizations prioritizing data sovereignty, developers building document automation pipelines, and teams avoiding per-page API costs.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Intelligent Document Processing](https://www.salesforce.com/)**  

  IDP capabilities within Salesforce ecosystem for extracting data from documents and feeding it into CRM workflows.



- **[ABBYY Vantage](https://www.abbyy.com/)**  

  Enterprise IDP platform with pre-trained document skills, low-code skill designer, and human-in-the-loop validation.



- **[Rossum](https://rossum.ai/)**  

  AI-powered document parsing platform specializing in transactional documents with a collaborative validation interface.



- **[Hyperscience](https://www.hyperscience.com/)**  

  Enterprise automation platform with document processing, data extraction, and human-in-the-loop review workflows.



- **[Kofax TotalAgility](https://www.kofax.com/)**  

  Intelligent automation platform with document capture, process orchestration, and analytics capabilities.



- **[AWS Textract](https://aws.amazon.com/textract/)**  

  Managed ML service for extracting text, handwriting, tables, and forms from documents with no ML experience required.



- **[Google Document AI](https://cloud.google.com/document-ai)**  

  Document understanding platform with pre-trained processors for invoices, receipts, forms, and OCR.



- **[Azure AI Document Intelligence](https://azure.microsoft.com/en-us/products/ai-services/ai-document-intelligence)**  

  Cloud-based document analysis with prebuilt and custom models for structured data extraction.



- **[Infrrd](https://www.infrrd.ai/)**  

  IDP platform with proprietary computer vision and NLP for structured and unstructured document processing.



- **[Ocrolus](https://www.ocrolus.com/)**  

  Document automation platform for financial services with human-in-the-loop verification.



## Open-Source GitHub Projects



- **[DocStrange](https://github.com/NanoNets/docstrange)**  

  Extract and convert data from any document, image, PDF, Word doc, PPT, or URL into Markdown, JSON, CSV, or HTML with intelligent structured data extraction. Features universal input (PDF, DOCX, PPTX, XLSX, images, URLs), dual processing modes (cloud API or 100% private local processing), schema-based extraction, advanced OCR with multiple engine fallbacks, table and structure recognition, and built-in web UI. Cloud API offers 10,000 documents/month free with authentication .



- **[Docling](https://github.com/DS4SD/docling)**  

  Open-source document parsing library with lightweight local-friendly extraction for digital-born PDFs. Produces clean Markdown output optimized for LLM workflows. Best for clean, text-layer documents rather than degraded scans .



- **[OpenDataLoader PDF](https://github.com/opendataloader-project/opendataloader-pdf)**  

  Open-source PDF data extraction tool from Hancom achieving #1 performance in benchmarks for reading order, table, and heading extraction accuracy (0.90 overall). Features hybrid engine combining AI and direct extraction, OCR for scanned documents, table extraction with merged cell support, formula extraction, chart analysis, and Apache 2.0 license. Integrates with LangChain, LlamaIndex, and supports Model Context Protocol for AI agents .



- **[DocTR](https://github.com/mindee/doctr)**  

  Open-source OCR library from Mindee supporting PyTorch and TensorFlow. Key strength is structured output with JSON containing blocks, lines, words, and bounding boxes. Features table detection with dense grid output (loads directly into pandas), reading order linearization, and export to Markdown, AsciiDoc, HTML, or XML. Ideal for document automation pipelines requiring layout preservation .



- **[DocSlight](https://github.com/ComPDFKit/docslight)**  

  Open-source AI document parsing from ComPDF (KDAN ecosystem). Features auto-switch between local (free, offline, CPU) and cloud (high-accuracy, API key, GPU) modes. Local mode uses PaddleOCR with basic layout analysis; cloud mode adds VLM OCR for complex layouts, tables, formulas, and multi-column documents. Supports PDF, images, Office files, with Markdown/JSON/Text output, bounding box traceability, and LangChain/LlamaIndex integration .



- **[Unstract](https://github.com/Zipstack/unstract)**  

  LLM-driven unstructured data extraction platform built for API deployment and ETL pipeline workflows. Featured in GitHub's #idp topic with 7,140+ stars .



- **[PaddleOCR-VL](https://github.com/PaddlePaddle/PaddleOCR)**  

  Open-source vision-language OCR model with ONNX export support. Features host-side KV-cached decode loop, multiple quantization options (fp32, q8, quint8, q4), and support for API providers (Gemini, OpenAI) when local GPU isn't available. Ideal for teams wanting SOTA OCR without per-page API billing .



- **[MantisFetch](https://pypi.org/project/mantisfetch/)**  

  Document processing API with browser sessions, document library, and LLM-based summarization. Features multi-step web automation, document parsing (PDF, DOCX, PPTX, XLSX, CSV, HTML), section-based retrieval for RAG, table extraction with column statistics, and OCR model fallback configuration .



### Additional Strong Open-Source Options



- **[Qwen2.5-VL / Qwen3-VL](https://github.com/QwenLM/Qwen2.5-VL)** — Alibaba's vision-language models with native document understanding. Reaches ~75% on DocVQA (GPT-4o-level). Apache 2.0 licensed. Available in 7B, 32B, and 72B sizes .

- **[Florence-2](https://github.com/microsoft/Florence-2)** — Microsoft's compact VLM (0.23B/0.77B) for OCR with visual localization. Returns text coordinates, useful for label and screenshot processing. MIT licensed .

- **[SmolVLM2](https://github.com/huggingface/smolvlm2)** — Hugging Face's compact VLM family (256M, 500M, 2.2B) for efficient document understanding. 2.2B achieves 72.9% on OCRBench. Apache 2.0 licensed .

- **[GOT-OCR 2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)** — End-to-end OCR model handling standard text, scene text, charts, formulas (LaTeX output), and sheet music .

- **[Kraken](https://github.com/mittagessen/kraken)** — Specialist OCR for historical documents, manuscripts, and right-to-left scripts. Best for archive digitization .

- **Vector Databases** — Qdrant, Weaviate, Milvus for document embedding and semantic search in RAG pipelines.

- **Workflow Orchestration** — Apache Airflow, Prefect for scheduling document processing pipelines.



**Frameworks for building custom systems**: Combine **DocStrange** for schema-based extraction, **DocTR** or **PaddleOCR-VL** for OCR, **OpenDataLoader PDF** for PDF parsing, **DocSlight** for hybrid local/cloud processing, and **Qdrant + LangChain** for RAG workflows to build a complete self-hosted IDP stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- IDP tools must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, HIPAA), and document retention policies.

- Self-hosted open-source solutions require proper security hardening, GPU infrastructure planning, and model monitoring.



---



**Made for document automation engineers, data teams, operations managers, and developers building intelligent document processing platforms.**  

Let's make intelligent document processing more open, accurate, and data-sovereign.
