# Hi, I'm Abhishek Kumar Rai

I work on retrieval systems and vector databases, mostly the layer where query processing, index behaviour, and search efficiency meet. I'm interested in how retrieval infrastructure holds up under real conditions: changing data, predicate filters, and the demands of downstream LLM systems, rather than just how it performs on a fixed benchmark.

I'm currently a B.Tech student in Information Technology & Mathematical Innovation at the University of Delhi, working independently on a small portfolio of research projects in vector search and retrieval, alongside coursework in algorithms, ML, and systems.

---

## Research Projects

### [Router Robustness Under Index Staleness](https://github.com/Abhishek-Kumar-Rai5/ann-router-staleness)
*Ongoing*
A C++ evaluation framework studying whether query-aware ANN search-effort routing, calibrated on a static HNSW index, remains reliable once the index evolves through insertions and deletions. Includes a fully audited negative result for a static-feature router, and an ongoing extension testing policy validity directly under controlled index evolution.

### [Filter Selectivity and Per-Query Search Effort in ANN](https://github.com/Abhishek-Kumar-Rai5/filtered-ann-search-effort)
*Ongoing*
A C++ filtered-ANN benchmark (pre-filter, post-filter, ACORN) studying how predicate selectivity and local vector structure determine the search effort needed for target recall. Includes an independently found and audited cost-accounting issue in ACORN's native effort metric, and a structural decomposition of filtered-search recall into unreachable vs. under-searched targets.

### [Per-Query Response Shapes Under Semantic Distraction](https://github.com/Abhishek-Kumar-Rai5/context-semantic-distraction)
*Independent research project*
A controlled long-context evaluation varying context size, evidence position, and semantic similarity of distractors, to characterize how individual queries — not just aggregate averages — respond as retrieved context grows.

---

## Other Work

**GSoC 2026, PEcAn Organization** — contributing to an LLM-based extraction system that converts unstructured scientific text into structured, provenance-linked records with field-level confidence estimates. Ongoing, under review, not yet merged.

A few earlier projects from before I moved toward retrieval/ANN research:

- **[ML Deployment Framework](https://github.com/Abhishek-Kumar-Rai5/ML-deployment-framework)** — a small Dockerized API for serving ML models, built to get hands-on with reproducible deployment rather than just training models in a notebook.
- **[Email Classification Pipeline](https://github.com/Abhishek-Kumar-Rai5/Email-classification-pipeline)** — a text-classification pipeline covering ingestion, preprocessing, and training/evaluation on a structured dataset.

---

## Stack

**Languages**
- C++
- Python
- SQL
- Java

**Retrieval / ANN**
- HNSW
- FAISS
- ACORN
- hnswlib
- BM25
- Dense & hybrid retrieval

**ML & Evaluation**
- scikit-learn
- Statistical testing
- Experimental design
- Error analysis

**Systems**
- CMake
- Linux
- Git
- Docker
- CI/CD

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abhik-rai)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github)](https://github.com/Abhishek-Kumar-Rai5)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:rai.abhishek5140@gmail.com)
