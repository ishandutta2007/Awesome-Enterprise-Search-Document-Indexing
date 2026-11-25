# 🔍 Awesome Enterprise Search & Document Indexing

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Enterprise Search and Document Indexing Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Enterprise-Search-Document-Indexing/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Enterprise-Search-Document-Indexing?style=social" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Enterprise-Search-Document-Indexing/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Enterprise-Search-Document-Indexing?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Overview & SEO Meta Summary

A definitive, production-grade curated list of **Enterprise Search Engines**, **Document Indexing Systems**, **Workplace AI Knowledge Assistants**, and **Self-Hosted RAG Infrastructures**. 

Whether you are building permission-aware search across SaaS silos (Slack, Confluence, Google Workspace, Microsoft 365, Jira), deploying hybrid lexical (BM25) and dense vector retrieval, parsing complex multimodal PDFs/OCR tables, or replacing legacy intranet keyword search with self-hosted AI agents, this directory catalogs both leading commercial SaaS platforms and sovereign open-source projects.

### 🔑 Key Topic Tags & Capabilities
`enterprise-search` • `document-indexing` • `hybrid-search` • `rag` • `vector-search` • `bm25` • `workplace-search` • `document-parsing` • `semantic-search` • `knowledge-management` • `multimodal-retrieval`

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS / Hosted Commercial Platforms](#️-saas--hosted-commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
  - [⚡ Open-Source Hybrid Retrieval Engines & Workplace Search](#-open-source-hybrid-retrieval-engines--workplace-search)
  - [📊 Open-Source Comparison Table](#-open-source-comparison-table)
- [📈 Star History](#-star-history)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support & Thank You](#-support--thank-you)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global enterprise search and AI document indexing market is valued at approximately **$5.8B to $7.5B in 2026** (projected to reach $11.5B–$15B+ by the mid-2030s at an 8.7%–9.3% CAGR). The sector exhibits a **moderately fragmented, bifurcated market structure**: the foundational workplace search and cloud infrastructure layers are concentrated around hyperscalers (Microsoft, Google, AWS) and breakout workplace assistants (Glean, Elastic), while the specialized document-cracking, industry-specific cognitive discovery (legal/finance), and open-source self-hosted RAG sectors remain highly fragmented among specialized innovators and open-core engines.

---

## ☁️ SaaS / Hosted Commercial Platforms

*Sorted in descending order by company scale (valuation / annual revenue).*

| 🏷️ Platform | 📝 Description | 🏢 Company Scale (Valuation / Revenue) | 💵 Starting Paid Tier | 🎁 Free Tier / Free Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure AI Search](https://azure.microsoft.com/en-us/products/ai-services/ai-search)** | Microsoft's cloud search-as-a-service combining BM25 keyword + dense vector indexing, semantic reranker, and AI ingestion pipelines. | **Part of Microsoft** (~$3T+ Market Cap; ~$85B+ Azure Cloud Revenue) | **$73.73 / month** ($0.101/hour for Basic Tier with 2 GB storage and 15 indexes) | **Free Forever Tier**: 50 MB storage, 3 indexes, and 3 indexers free forever; new accounts also receive a 30-day $200 Azure trial credit |
| **[Google Cloud Search](https://cloud.google.com/products/search)** | Enterprise workplace search indexing Gmail, Drive, Docs, Jira, and enterprise databases with native identity ACL enforcement. | **Part of Alphabet / Google** (~$2T+ Market Cap; ~$350B+ Revenue) | **$18.00 / user / month** (Included in Google Workspace Business Plus, billed annually; $21.60/user/mo monthly) | **14-Day Free Trial**: Full access for up to 10 users across Google Workspace Business Plus for 14 days (no permanent free tier) |
| **[Amazon Kendra](https://aws.amazon.com/kendra/)** | AWS managed intelligent search service powered by deep learning NLP, semantic document parsing, and built-in enterprise connectors. | **Part of Amazon / AWS** (~$2T+ Market Cap; ~$115B+ AWS Annual Revenue) | **$810.00 / month** ($1.125/hour for Developer Edition capacity unit covering up to 10,000 documents) | **30-Day Free Trial**: 750 hours of Kendra Developer Edition free for the first 30 days (first 10,000 documents and 4,000 queries/day) |
| **[Elastic Enterprise Search](https://www.elastic.co/enterprise-search)** | Enterprise AI search platform built on Elasticsearch offering hybrid vector/keyword search, web crawlers, and workplace connectors. | **~$10B Public Market Cap** (~$1.45B Annual Revenue; NYSE: ESTC) | **$95.00 / month** (Elastic Cloud Standard Tier for managed search cluster & vector store) | **14-Day Free Trial**: Full-featured Elastic Cloud deployment for 14 days without requiring a credit card (Self-hosted core is AGPL/Elastic free) |
| **[Glean](https://www.glean.com)** | AI-powered enterprise work assistant and search platform connecting 100+ workplace SaaS apps with real-time permissions and agents. | **$4.6B Valuation** ($100M+ ARR; Series E) | **$45.00 / user / month** (Starting seat rate billed annually, with minimum deployment commitments typically starting at 100 seats / ~$50,000/yr) | **No Self-Serve Free Trial**: 0-day self-serve trial; enterprise pilots and guided sandbox evaluations are scoped via custom sales engagement |
| **[Algolia](https://www.algolia.com)** | Fast, API-first search and discovery platform combining NeuralSearch (vector + keyword), instant typo tolerance, and federated indexing. | **$2.25B Valuation** (~$150M+ ARR) | **$0.50 per 1,000 search requests** (Grow Pay-as-you-go tier beyond included free monthly allotment) | **Free Forever Tier**: 10,000 search requests/month and 100,000 indexed records free forever with no credit card required |
| **[Hebbia](https://www.hebbia.ai)** | AI-native document search and Matrix analysis engine designed for financial services, private equity, and legal teams querying complex PDFs. | **~$700M Valuation** ($130M Series B; ~$20M+ ARR) | **$250.00 / user / month** ($3,000/seat/year starting entry tier, typically sold as mid-market packages with annual commitments) | **No Self-Serve Free Trial**: 0-day self-serve trial; proof-of-concept pilot environments require direct enterprise sales qualification |
| **[Coveo](https://www.coveo.com)** | AI search and generative answering platform providing unified workplace search, commerce discovery, and customer service knowledge RAG. | **~$700M Public Market Cap** (~$135M Annual Revenue; TSX: CVO) | **$600.00 / month** (Starting entry package for cloud search & connector indexing) | **14-Day Free Trial**: 14-day fully functional sandbox environment to test connectors, indexing pipelines, and query interfaces with no credit card |
| **[Sinequa](https://www.sinequa.com)** | Cognitive enterprise search and neural RAG engine indexing 200+ enterprise connectors across multi-terabyte internal repositories. | **~$300M Parent Group Scale** (Acquired by ChapsVision; ~$40M+ Sinequa standalone ARR) | **$3,000.00 / month** (Indicative starting entry subscription for small enterprise environments based on volume and seat bands) | **No Self-Serve Free Trial**: 0-day self-serve trial; guided proof-of-concept (POC) sandboxes provided exclusively upon qualified sales scoping |
| **[Lucidworks Fusion](https://lucidworks.com)** | Enterprise search and AI retrieval platform built on Apache Solr powering unified intranet search, digital workplace, and knowledge graphs. | **~$200M Valuation** (~$50M+ ARR; $100M+ funding) | **$2,500.00 / month** (Indicative starting cloud subscription tier based on query nodes and document index size) | **30-Day Free Trial**: 30-day technical evaluation license for containerized/self-hosted Fusion clusters (configuration locks after 30 days without license key) |

---

## 💻 Open-Source GitHub Projects

### ⚡ Open-Source Hybrid Retrieval Engines & Workplace Search
Open-source solutions empower engineering and IT teams to implement sovereign, privacy-preserving, RBAC-compliant enterprise document search without vendor lock-in.

*Sorted in descending order by GitHub Stars. Each repository includes an official social star badge linked directly to its stargazers page.*

| 📦 Repository & Star Badge | 📜 License / Cost | 🔓 Self-Hosted Free Limit | 💡 Architectural Focus & Capabilities |
| :--- | :--- | :--- | :--- |
| **[RAGFlow](https://github.com/infiniflow/ragflow)**<br/><a href="https://github.com/infiniflow/ragflow/stargazers"><img src="https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white" alt="RAGFlow Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Unlimited documents, deep doc parsing, OCR, and citation engine) | Deep document understanding engine based on vision-language models for OCR, table structure recovery, and hybrid retrieval. |
| **[Elasticsearch](https://github.com/elastic/elasticsearch)**<br/><a href="https://github.com/elastic/elasticsearch/stargazers"><img src="https://img.shields.io/github/stars/elastic/elasticsearch?style=social&color=white" alt="Elasticsearch Stars"/></a> | **AGPL-3.0 / Elastic License** ($0 self-hosted) | **100% Free Forever** (Unlimited nodes, shards, and hybrid BM25 + dense/sparse vector retrieval) | The industry standard distributed search engine offering full-text search, dense vector nearest neighbor indexing, and ELSER semantic search. |
| **[Docling](https://github.com/DS4SD/docling)**<br/><a href="https://github.com/DS4SD/docling/stargazers"><img src="https://img.shields.io/github/stars/DS4SD/docling?style=social&color=white" alt="Docling Stars"/></a> | **MIT** ($0 self-hosted) | **100% Free Forever** (Unlimited multimodal document conversions, table extraction, and PDF parsing) | Ultra-fast document parsing and layout understanding library by IBM Research that converts PDF, DOCX, PPTX, and HTML into structured JSON/Markdown for search indexing. |
| **[Meilisearch](https://github.com/meilisearch/meilisearch)**<br/><a href="https://github.com/meilisearch/meilisearch/stargazers"><img src="https://img.shields.io/github/stars/meilisearch/meilisearch?style=social&color=white" alt="Meilisearch Stars"/></a> | **MIT** ($0 self-hosted; cloud available) | **100% Free Forever** (Unlimited self-hosted records, instant typo-tolerance, and hybrid search) | Lightning-fast, typo-tolerant search engine designed for delightful end-user search experiences with out-of-the-box vector embeddings. |
| **[LlamaIndex](https://github.com/run-llama/llama_index)**<br/><a href="https://github.com/run-llama/llama_index/stargazers"><img src="https://img.shields.io/github/stars/run-llama/llama_index?style=social&color=white" alt="LlamaIndex Stars"/></a> | **MIT** ($0 self-hosted) | **100% Free Forever** (Unlimited document ingestion, query engines, and agentic workflows) | Context-augmentation data framework providing 300+ enterprise connectors, hierarchical document indexing, and advanced hybrid retrieval strategies. |
| **[Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)**<br/><a href="https://github.com/paperless-ngx/paperless-ngx/stargazers"><img src="https://img.shields.io/github/stars/paperless-ngx/paperless-ngx?style=social&color=white" alt="Paperless-ngx Stars"/></a> | **GPL-3.0** ($0 self-hosted) | **100% Free Forever** (Unlimited archived documents, OCR processing, tagging, and full-text search) | Community-driven document management system that indexes physical scanned documents and digital PDFs with automated OCR, metadata tagging, and full-text search. |
| **[Milvus](https://github.com/milvus-io/milvus)**<br/><a href="https://github.com/milvus-io/milvus/stargazers"><img src="https://img.shields.io/github/stars/milvus-io/milvus?style=social&color=white" alt="Milvus Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Scales to billions of vectors with hybrid dense/sparse search & scalar filtering) | Highly scalable open-source vector database built for massive enterprise document embeddings, ANN search, and multi-tenant isolation. |
| **[Khoj](https://github.com/khoj-ai/khoj)**<br/><a href="https://github.com/khoj-ai/khoj/stargazers"><img src="https://img.shields.io/github/stars/khoj-ai/khoj?style=social&color=white" alt="Khoj Stars"/></a> | **AGPL-3.0** ($0 self-hosted; cloud from $8/mo) | **100% Free Forever** (Unlimited self-hosted desktop or server indexing for Obsidian, Notion, PDF, and GitHub) | An open-source, self-hostable AI second brain and desktop search agent indexing notes, documents, and web bookmarks with natural voice/chat. |
| **[Qdrant](https://github.com/qdrant/qdrant)**<br/><a href="https://github.com/qdrant/qdrant/stargazers"><img src="https://img.shields.io/github/stars/qdrant/qdrant?style=social&color=white" alt="Qdrant Stars"/></a> | **Apache-2.0** ($0 self-hosted; cloud available) | **100% Free Forever** (Unlimited vectors, hybrid dense/sparse vector search, payload filtering) | Rust-based high-performance vector search engine tailored for production RAG, hybrid BM25/sparse retrieval, and real-time payload payload filtering. |
| **[Onyx (formerly Danswer)](https://github.com/onyx-dot-app/onyx)**<br/><a href="https://github.com/onyx-dot-app/onyx/stargazers"><img src="https://img.shields.io/github/stars/onyx-dot-app/onyx?style=social&color=white" alt="Onyx Stars"/></a> | **MIT / Enterprise Open-Core** ($0 self-hosted Community; Cloud at $20/user/mo) | **100% Free Forever** (Unlimited users, 40+ workplace connectors, hybrid retrieval, and Slack bot) | The top open-source Glean alternative connecting workplace apps (Slack, Drive, Confluence, Jira, GitHub) with permission-aware hybrid search and generative Q&A. |
| **[Typesense](https://github.com/typesense/typesense)**<br/><a href="https://github.com/typesense/typesense/stargazers"><img src="https://img.shields.io/github/stars/typesense/typesense?style=social&color=white" alt="Typesense Stars"/></a> | **GPL-3.0** ($0 self-hosted; cloud available) | **100% Free Forever** (In-memory C++ engine with unlimited documents, geo-search, and vector search) | Modern, developer-friendly open-source alternative to Algolia providing sub-50ms typo-tolerant search and built-in vector search. |
| **[SurfSense](https://github.com/MODSetter/SurfSense)**<br/><a href="https://github.com/MODSetter/SurfSense/stargazers"><img src="https://img.shields.io/github/stars/MODSetter/SurfSense?style=social&color=white" alt="SurfSense Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Private local document research, NotebookLM alternative, air-gapped indexing) | Self-hosted research and document AI tool allowing users to parse, index, and query confidential enterprise files locally with cited references. |
| **[Weaviate](https://github.com/weaviate/weaviate)**<br/><a href="https://github.com/weaviate/weaviate/stargazers"><img src="https://img.shields.io/github/stars/weaviate/weaviate?style=social&color=white" alt="Weaviate Stars"/></a> | **BSD-3-Clause** ($0 self-hosted; cloud available) | **100% Free Forever** (Modular vector and inverted index engine with built-in ML model modules) | Cloud-native vector search database featuring hybrid search, multi-modal ingestion, and GraphQL/REST query APIs. |
| **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**<br/><a href="https://github.com/opensearch-project/OpenSearch/stargazers"><img src="https://img.shields.io/github/stars/opensearch-project/OpenSearch?style=social&color=white" alt="OpenSearch Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Community-driven 100% open-source fork of Elasticsearch & Kibana) | Fully open-source distributed search and analytics suite offering neural search pipelines, k-NN vector indexing, and enterprise security plugins. |
| **[Vespa](https://github.com/vespa-engine/vespa)**<br/><a href="https://github.com/vespa-engine/vespa/stargazers"><img src="https://img.shields.io/github/stars/vespa-engine/vespa?style=social&color=white" alt="Vespa Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Processes billions of documents and hundreds of thousands of queries per second) | High-scale search and computing engine built by Yahoo for complex multi-phase ranking, vector search, and structured data filtering at internet scale. |
| **[PipesHub](https://github.com/pipeshub-ai/pipeshub-ai)**<br/><a href="https://github.com/pipeshub-ai/pipeshub-ai/stargazers"><img src="https://img.shields.io/github/stars/pipeshub-ai/pipeshub-ai?style=social&color=white" alt="PipesHub Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Unified enterprise context layer with 50+ connectors and MCP agent support) | Open-source enterprise search and context layer connecting Slack, Drive, Jira, and GitHub with source-level ACL enforcement and Model Context Protocol (MCP). |
| **[Apache Tika](https://github.com/apache/tika)**<br/><a href="https://github.com/apache/tika/stargazers"><img src="https://img.shields.io/github/stars/apache/tika?style=social&color=white" alt="Apache Tika Stars"/></a> | **Apache-2.0** ($0 self-hosted) | **100% Free Forever** (Extracts metadata and text from over 1,000 different file formats) | The battle-tested enterprise toolkit that detects and extracts metadata and structured text from PDF, PPT, XLS, DOC, EPUB, and audio formats. |
| **[OneBox](https://github.com/wangzhishou/OneBox)**<br/><a href="https://github.com/wangzhishou/OneBox/stargazers"><img src="https://img.shields.io/github/stars/wangzhishou/OneBox?style=social&color=white" alt="OneBox Stars"/></a> | **Open-Source** ($0 self-hosted) | **100% Free Forever** (Unified cross-source document search box and Q&A engine) | Compact open-source enterprise search and document indexing box designed to unify internal files and data silos into a single search bar. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Enterprise-Search-Document-Indexing&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Enterprise-Search-Document-Indexing&type=date&legend=top-left)

---

## 🛠️ How to Contribute

We welcome contributions from enterprise engineers, search architects, and researchers! 

1. 🍴 Fork this repository.
2. 🌿 Create a feature branch: `git checkout -b feature/add-new-search-engine`.
3. 📝 Add your entry to either the SaaS or Open-Source section following the table format.
4. 🔗 Include accurate pricing, official URLs, and genuine star badges.
5. 🚀 Submit a Pull Request with a clear description of the project.

---

## 💖 Support & Thank You

Thank you for visiting and supporting **Awesome Enterprise Search & Document Indexing**! 🙏

If this curated repository helped you design your workplace search architecture, evaluate enterprise RAG pipelines, or choose an open-source indexing engine:
- ⭐ **Star this repository** to help other engineers and teams discover it.
- 🍴 **Fork it** to maintain your team's custom internal knowledge stacks.
- 📢 **Share it** on LinkedIn, X/Twitter, Reddit, and developer communities.
- ☕ **Buy me a coffee**: If you appreciate this continuous curation, you can support my work via the **[GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007)**. Every contribution keeps these resources actively maintained and up-to-date!

---

## ⚠️ Disclaimer

*Trademarks, product names, and company logos referenced in this repository belong to their respective owners. Pricing, feature sets, and specifications are gathered from publicly available documentation, pricing pages, and verified vendor announcements as of November 2026 and are subject to change. Please consult the respective official websites for binding enterprise quotes.*
