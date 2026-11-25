# Awesome-Enterprise-Search-Document-Indexing

<p align="center">

  <img src="./assets/banner.svg" alt="Top Enterprise Search & Document Indexing" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🔍 Top Enterprise Search & Document Indexing



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on AI Workplace Search, Hybrid Lexical/Vector Indexing, Permission-Aware Connectors, Multimodal Document Parsing & Self-Hosted Enterprise RAG Engines*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Enterprise Search & Document Indexing**. These tools power permission-aware workplace search across SaaS silos (Slack, Google Drive, SharePoint, Jira, Confluence), hybrid BM25 + semantic vector retrieval, multimodal PDF/OCR document indexing, and enterprise AI assistants for IT teams, search engineers, and knowledge workers.



**Examples** include Amazon Kendra (AWS), Azure AI Search, Google Cloud Search (Google Workspace), Glean, Elastic Enterprise Search, Hebbia, Algolia, Coveo, Lucidworks Fusion, and Sinequa (ChapsVision) (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for open-source workplace AI search (`OneBox`, `Onyx / Danswer`, `PipesHub`, `SurfSense`, `Khoj`), hybrid search & vector indexing engines (`OpenSearch`, `Elasticsearch`, `Vespa`, `Meilisearch`, `Typesense`, `Qdrant`, `Milvus`, `Weaviate`), and document ingestion parsers (`Apache Tika`, `Docling`, `Paperless-ngx`) — ideal for organizations seeking sovereign, RBAC-enforced enterprise search without per-seat SaaS lock-in.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics

The global enterprise search and AI document indexing market is valued at approximately **$5.8B to $7.5B in 2026** (projected to reach $11.5B–$15B+ by the mid-2030s at an 8.7%–9.3% CAGR). The sector exhibits a **moderately fragmented, bifurcated market structure**: the foundational workplace search and cloud infrastructure layers are concentrated around hyperscalers (Microsoft, Google, AWS) and breakout workplace assistants (Glean, Elastic), while the specialized document-cracking, industry-specific cognitive discovery (legal/finance), and open-source self-hosted RAG sectors remain highly fragmented among specialized innovators and open-core engines.

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted in descending order by company scale (valuation / annual revenue).*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Free Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure AI Search](https://microsoft.com)** | Microsoft's cloud search-as-a-service combining BM25 keyword + dense vector indexing, semantic reranker, and AI ingestion pipelines. | **Part of Microsoft** (~$3T+ Market Cap; ~$85B+ Azure Cloud Revenue) | **$73.73 / month** ($0.101/hour for Basic Tier with 2 GB storage and 15 indexes) | **Free Forever Tier**: 50 MB storage, 3 indexes, and 3 indexers free forever; new accounts also get a 30-day $200 Azure trial credit |
| **[Google Cloud Search](https://google.com)** | Enterprise workplace search indexing Gmail, Drive, Docs, Jira, and enterprise databases with native identity ACL enforcement. | **Part of Alphabet / Google** (~$2T+ Market Cap; ~$350B+ Revenue) | **$18.00 / user / month** (Included in Google Workspace Business Plus, billed annually; $21.60/user/mo monthly) | **14-Day Free Trial**: Full access for up to 10 users across Google Workspace Business Plus for 14 days (no permanent free tier) |
| **[Amazon Kendra](https://amazon.com)** | AWS managed intelligent search service powered by deep learning NLP, semantic document parsing, and built-in enterprise connectors. | **Part of Amazon / AWS** (~$2T+ Market Cap; ~$115B+ AWS Annual Revenue) | **$810.00 / month** ($1.125/hour for Developer Edition capacity unit covering up to 10,000 documents) | **30-Day Free Trial**: 750 hours of Kendra Developer Edition free for the first 30 days (first 10,000 documents and 4,000 queries/day) |
| **[Elastic Enterprise Search](https://elastic.co)** | Enterprise AI search platform built on Elasticsearch offering hybrid vector/keyword search, web crawlers, and workplace connectors. | **~$10B Public Market Cap** (~$1.45B Annual Revenue; NYSE: ESTC) | **$95.00 / month** (Elastic Cloud Standard Tier for managed search cluster & vector store) | **14-Day Free Trial**: Full-featured Elastic Cloud deployment for 14 days without requiring a credit card (Self-hosted core is AGPL/Elastic free) |
| **[Glean](https://glean.com)** | AI-powered enterprise work assistant and search platform connecting 100+ workplace SaaS apps with real-time permissions and agents. | **$4.6B Valuation** ($100M+ ARR; Series E) | **$45.00 / user / month** (Starting seat rate billed annually, with minimum deployment commitments typically starting at 100 seats / ~$50,000/yr) | **No Self-Serve Free Trial**: 0-day self-serve trial; enterprise pilots and guided sandbox evaluations are scoped via custom sales engagement |
| **[Algolia](https://algolia.com)** | Fast, API-first search and discovery platform combining NeuralSearch (vector + keyword), instant typo tolerance, and federated indexing. | **$2.25B Valuation** (~$150M+ ARR) | **$0.50 per 1,000 search requests** (Grow Pay-as-you-go tier beyond included free monthly allotment) | **Free Forever Tier**: 10,000 search requests/month and 100,000 indexed records free forever with no credit card required |
| **[Hebbia](https://hebbia.com)** | AI-native document search and Matrix analysis engine designed for financial services, private equity, and legal teams querying complex PDFs. | **~$700M Valuation** ($130M Series B; ~$20M+ ARR) | **$250.00 / user / month** ($3,000/seat/year starting entry tier, typically sold as mid-market packages with annual commitments) | **No Self-Serve Free Trial**: 0-day self-serve trial; proof-of-concept pilot environments require direct enterprise sales qualification |
| **[Coveo](https://coveo.com)** | AI search and generative answering platform providing unified workplace search, commerce discovery, and customer service knowledge RAG. | **~$700M Public Market Cap** (~$135M Annual Revenue; TSX: CVO) | **$600.00 / month** (Starting entry package for cloud search & connector indexing) | **14-Day Free Trial**: 14-day fully functional sandbox environment to test connectors, indexing pipelines, and query interfaces with no credit card |
| **[Sinequa](https://sinequa.com)** | Cognitive enterprise search and neural RAG engine indexing 200+ enterprise connectors across multi-terabyte internal repositories. | **~$300M Parent Group Scale** (Acquired by ChapsVision; ~$40M+ Sinequa standalone ARR) | **$3,000.00 / month** (Indicative starting entry subscription for small enterprise environments based on volume and seat bands) | **No Self-Serve Free Trial**: 0-day self-serve trial; guided proof-of-concept (POC) sandboxes provided exclusively upon qualified sales scoping |
| **[Lucidworks Fusion](https://lucidworks.com)** | Enterprise search and AI retrieval platform built on Apache Solr powering unified intranet search, digital workplace, and knowledge graphs. | **~$200M Valuation** (~$50M+ ARR; $100M+ funding) | **$2,500.00 / month** (Indicative starting cloud subscription tier based on query nodes and document index size) | **30-Day Free Trial**: 30-day technical evaluation license for containerized/self-hosted Fusion clusters (configuration locks after 30 days without license key) |



## 💻 Open-Source GitHub Projects



| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |

| :--- | :--- | :--- | :--- |

| **[OneBox (`wangzhishou/OneBox`)](https://github.com)** | **Open-Source** ($0 self-hosted; bring-your-own LLM/embedding endpoints) | **100% Free forever** self-hosted (Unlimited unified document indexing, cross-source search, and AI Q&A on your own servers) | Open-source unified enterprise search and document indexing box designed to aggregate, index, and query fragmented workplace knowledge silos. |

| **[Onyx — formerly Danswer (`onyx-dot-ai/onyx`)](https://github.com)** | **MIT / Enterprise Open-Core** ($0 self-hosted Community Edition; Cloud at $20/user/mo) | **100% Free forever** self-hosted (Unlimited users, 40+ workplace connectors for Slack/Drive/Confluence/Jira, hybrid search, and AI agents) | The leading open-source, self-hosted Glean alternative connecting workplace apps with permission-aware hybrid search and RAG chat. |
