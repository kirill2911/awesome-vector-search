# Awesome Vector Search (Open-Source, 2024+)

Curated list of **open-source vector-native databases, databases with vector column support, vector search & indexing libraries, cloud services, benchmarks, and research papers**.  
All GitHub links for databases & libraries; lists ordered by **fork count (descending)**.

---

## Vector-Native Databases  
> Purpose-built systems where **vector search is a first-class, core workload**.

| Name (GitHub) | Stars | Forks | Last Commit | Status | Description |
|---------------|-------|-------|-------------|--------|-------------|
| **[Milvus](https://github.com/milvus-io/milvus)** | ~43k | ~4k | 2026-01 | Active | Distributed, cloud-native vector database |
| **[Qdrant](https://github.com/qdrant/qdrant)** | ~29k | ~2k | 2025-10 | Active | Rust-powered vector DB with hybrid filtering |
| **[ChromaDB](https://github.com/chroma-core/chroma)** | ~26k | ~2k | 2026-01 | Active | Embedding-first vector store for LLM/RAG workloads |
| **[Weaviate](https://github.com/weaviate/weaviate)** | ~16k | ~1k | 2026-01 | Active | Schema-aware vector DB with GraphQL |
| **[LanceDB](https://github.com/lancedb/lancedb)** | ~9k | ~730 | 2026-01 | Active | Data-lake-native vector database built on Apache Arrow |
| **[Vespa](https://github.com/vespa-engine/vespa)** | ~7k | ~700 | 2026-02 | Active | Large-scale search engine with native vector support |
| **[Endee.io](https://github.com/endee-io/endee)** | ~1k | ~150 | 2026-02 | Active | cost-efficient, high-throughput vector search - scaling to 100M+ vectors per node |
| **[Vald](https://github.com/vdaas/vald)** | ~2k | ~90 | 2026-01 | Active | Kubernetes-native distributed vector search |

---

## Databases with Vector Column / Extension Support  
> General-purpose databases that **add vector similarity search as a feature or extension**.

| Name (GitHub) | Stars | Forks | Last Commit | Status | Description |
|---------------|-------|-------|-------------|--------|-------------|
| **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** | ~46k | ~8k | 2026-01 | Active | Columnar analytical DB with native vector search functions |
| **[DuckDB](https://github.com/duckdb/duckdb)** | ~36k | ~3k | 2026-01 | Active | Analytical DB with integrated vector similarity search |
| **[pgvector](https://github.com/pgvector/pgvector)** | ~20k | ~1k | 2026-01 | Active | PostgreSQL extension for vector similarity |
| **[Redisearch](https://github.com/redisearch/redisearch)** | ~6k | ~570 | 2025-11 | Active | Redis module supporting ANN vector search |
| **[pgvectorscale](https://github.com/timescale/pgvectorscale)** | ~3k | ~120 | 2025-11 | Active | Production-grade scaling & indexing layer for pgvector |

---

## Vector Search & Indexing Libraries (ordered by forks)

| Name (GitHub) | Stars | Forks | One-liner |
|---------------|-------|-------|-----------|
| **[FAISS](https://github.com/facebookresearch/faiss)** | ~39k | ~4k | High-performance similarity search (CPU/GPU) |
| **[Annoy](https://github.com/spotify/annoy)** | ~14k | ~1k | Tree-based ANN optimized for read-heavy workloads |
| **[hnswlib](https://github.com/nmslib/hnswlib)** | ~7k | ~1.3k | Header-only HNSW ANN index |
| **[ScaNN](https://github.com/google-research/google-research/tree/master/scann)** | ~3k | ~600 | Google’s scalable ANN library |
| **[NMSLIB](https://github.com/nmslib/nmslib)** | ~5k | ~470 | Flexible ANN search library |
| **[DiskANN](https://github.com/microsoft/DiskANN)** | ~2k | ~400 | Disk-based ANN for billion-scale vectors |
| **[USearch](https://github.com/unum-cloud/usearch)** | ~4k | ~300 | SIMD-optimized vector search |
| **[NGT](https://github.com/yahoojapan/NGT)** | ~1.5k | ~250 | Graph-based ANN index |
| **[Autofaiss](https://github.com/criteo/autofaiss)** | ~1k | ~80 | Automatic FAISS index configuration |

---

## Cloud Services (Open-Source Core / Hosted)

> Managed offerings built on open-source vector engines.

- **[Qdrant Cloud](https://qdrant.tech/)** – Managed Qdrant with scaling & backups  
- **[Zilliz Cloud](https://zilliz.com/)** – Managed Milvus service  
- **[Weaviate Cloud](https://weaviate.io/)** – Hosted Weaviate with enterprise integrations  
- **[LanceDB Cloud](https://lancedb.com/)** – Managed LanceDB optimized for analytics  
- **[Endee Cloud](https://endee.io/)** – Managed Endee.io vector database service  

---

## Benchmarking Tools

| Name (GitHub) | Description |
|---------------|-------------|
| **[ANN-Benchmarks](https://github.com/erikbern/ann-benchmarks)** | De-facto standard ANN algorithm benchmark |
| **[VectorDBBench](https://github.com/zilliztech/VectorDBBench)** | Benchmark framework for vector databases |
| **[VIBE-Benchmark](https://github.com/microsoft/vibe-benchmark)** | Benchmark suite for vector index quality & speed |
| **[annlite-benchmark](https://github.com/jina-ai/annlite-benchmark)** | Lightweight ANN benchmarking suite |

---

## Research Papers & Links

| Title | Link |
|-------|------|
| **Efficient and Robust Approximate Nearest Neighbor Search Using HNSW** | https://arxiv.org/abs/1603.09320 |
| **FAISS: A Library for Efficient Similarity Search and Clustering** | https://arxiv.org/abs/1702.08734 |
| **ScaNN: Efficient Vector Similarity Search at Scale** | https://arxiv.org/abs/1908.10396 |
| **DiskANN: Fast & Accurate Billion-Point NN Search** | https://arxiv.org/abs/2011.01608 |
| **Product Quantization for Nearest Neighbor Search** | https://hal.inria.fr/inria-00514496 |
| **VIBE: Vector Index Benchmark for Embeddings (2025)** | https://arxiv.org/abs/2505.17810 |
| **MicroNN: On-Device Disk-Resident Updatable Vectors (2025)** | https://arxiv.org/abs/2504.05573 |

---

## Notes

- Open-source only
- Actively maintained in **2024–2026**
- Fork counts are approximate and used for relative ordering
