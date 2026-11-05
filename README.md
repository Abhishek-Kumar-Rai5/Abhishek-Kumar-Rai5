# Hi, I'm Abhishek Kumar Rai

I am an undergraduate student pursuing a B.Tech in Information Technology & Mathematical Innovation at the Cluster Innovation Centre, University of Delhi.

My interests lie in **systems engineering, data systems, AI infrastructure and distributed data-intensive computing**. I am particularly interested in the engineering foundations behind modern computational workloads: how data is stored and retrieved, how systems process requests efficiently, how workloads are distributed, and how infrastructure maintains performance and reliability under changing conditions.

I enjoy working at the intersection of algorithms and systems engineering, moving beyond theoretical approaches to investigate their actual behaviour through implementation, controlled experimentation, benchmarking, and performance analysis.

My current research work has primarily involved approximate nearest-neighbour search, retrieval infrastructure, and machine learning evaluation. These projects have helped me investigate practical questions around index evolution, search-effort allocation, filtering, computational efficiency, and the reliability of evaluation pipelines.

I am interested in extending this foundation towards **distributed systems, scalable AI infrastructure, high-performance computing, and the backend systems supporting large-scale AI workloads**.

---

## Research Interests

- **AI Infrastructure and Systems:** Infrastructure for AI workloads, distributed inference, model serving, and efficient execution.
- **Distributed Systems and Data Infrastructure:** Distributed computing, scalable data processing, storage systems, and fault-tolerant architectures.
- **Performance Engineering:** Systems optimisation, profiling, computational efficiency, and latency-throughput trade-offs.
- **Information Retrieval Infrastructure:** Approximate nearest-neighbour search, vector retrieval, index structures, and query processing.
- **High-Performance Computing:** Parallel computing, efficient resource utilisation, and performance-oriented system design.
- **Reliable Systems and Evaluation:** Experimental methodology, benchmarking, reproducibility, and the evaluation of computational systems.

---

## Research Projects

### [Router Robustness Under Index Staleness](https://github.com/Abhishek-Kumar-Rai5/ann-router-staleness)
*Ongoing research*

A C++ evaluation framework investigating whether query-aware ANN search-effort routing, calibrated on a static HNSW index, remains reliable as the index evolves through insertions and deletions.

Includes an audited negative result for a static-feature router and an ongoing extension evaluating policy validity under controlled index evolution.

**Focus:** Retrieval infrastructure, HNSW index evolution, adaptive query processing, and search-effort allocation.

### [Filter Selectivity and Per-Query Search Effort in ANN](https://github.com/Abhishek-Kumar-Rai5/filtered-ann-search-effort)
*Ongoing research*

A C++ filtered-ANN benchmark studying how predicate selectivity and local vector structure determine the search effort required to achieve target recall.

Evaluates pre-filtering, post-filtering, and ACORN, including an independently identified and audited issue in ACORN's native effort accounting. Also develops a structural decomposition of filtered-search recall loss into graph unreachability and navigational failure.

**Focus:** Retrieval systems, graph-based search, query processing, and performance evaluation.

### Sensitivity-Weighted Drift Prioritisation for Production ML
*Research report finalised; paper in preparation*

An empirical evaluation of sensitivity-weighted drift prioritisation against seven baselines across sixteen experiments and three model families.

The proposed sensitivity weighting did not outperform drift-only prioritisation in the tested settings. During the investigation, I identified and corrected six evaluation defects, including a normalisation bug that inverted drift rankings. I also reduced PSI computation time by **364×** while preserving identical outputs, with the implementation validated through 486 passing tests.

**Focus:** Production ML systems, distribution shift, evaluation reliability, and computational optimisation.

### Search-Effort Policy Validity Under HNSW Index Evolution
*Research project; paper in preparation*

A pre-registered evaluation of fixed-effort and query-adaptive ANN search under controlled HNSW index updates, covering thirty index states and three seeds on SIFT1M.

The study distinguishes computational-cost drift from recall-contract drift and evaluates whether adaptive policies maintain their predefined efficiency targets as the index changes.

**Focus:** Retrieval infrastructure, systems behaviour under changing workloads, and experimental evaluation.

---

## Research Experience

### Google Summer of Code 2026 — PEcAn Organization

Contributing to SAGE, an LLM-assisted scientific information extraction system for agronomic and ecological literature.

The workflow converts unstructured scientific documents into structured, provenance-linked experimental records, combining LLM-based extraction, automated validation, and human review.

This work has given me practical experience with LLM-assisted data processing, document systems, evidence traceability, and the engineering challenges of building dependable AI-powered workflows.

*Contribution ongoing; under review and not yet merged.*

---

## Other Engineering Work

- **[ML Deployment Framework](https://github.com/Abhishek-Kumar-Rai5/ML-deployment-framework)** — A Dockerised API for serving machine learning models, developed to explore reproducible deployment and backend integration.
- **[Email Classification Pipeline](https://github.com/Abhishek-Kumar-Rai5/Email-classification-pipeline)** — A machine learning pipeline covering data ingestion, preprocessing, training, and evaluation.

---

## Technical Stack

**Programming:** C++, C, Python, Java, SQL

**Systems & Infrastructure:** Linux, CMake, Docker, Git, FastAPI, REST APIs, CI/CD

**Retrieval & Data Systems:** HNSW, FAISS, ACORN, hnswlib, BM25, dense and hybrid retrieval

**Machine Learning & AI:** scikit-learn, LLM APIs, RAG, structured extraction, model evaluation

**Research & Performance Evaluation:** Experimental design, statistical testing, benchmarking, profiling, error analysis

---

## Education & Achievements

**B.Tech — Information Technology & Mathematical Innovation**  
Cluster Innovation Centre, University of Delhi

- CGPA: 8.77/10.0
- Top 10% academic standing across the first two years
- NITORI Scholarship for Academic Excellence, MEXT Japan, in collaboration with the University of Delhi
- Google Summer of Code 2026 participant — PEcAn Organization
- Twice selected for the University of Delhi VCIS Internship Scheme
- 3rd Place — Hack-4-Viksit-Bharat Hackathon

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/abhik-rai)
- [GitHub](https://github.com/Abhishek-Kumar-Rai5)
- [Email](mailto:rai.abhishek5140@gmail.com)
