# Hoso

**Enterprise AI Infrastructure × Plant Genetics × Agricultural AI**

I am a software/AI engineer specializing in **secure, offline-first AI infrastructure** and a researcher building a long-term portfolio around **agricultural AI**. My work bridges the gap between rigorous enterprise AI requirements (closed networks, on-premise) and field-oriented agricultural technology.

---

## 🏢 Professional Engineering: Enterprise AI Infrastructure

Currently at Athena Technologies, I specialize in delivering robust AI systems for environments with strict security and network constraints, such as financial institutions and local governments.

- **Offline-First & On-Premise AI** — Architecting and deploying AI pipelines (Local LLMs, Whisper, pyannote) on on-premise GPU systems (e.g., NVIDIA DGX Spark) completely isolated from external networks, managing local model caches and GPU optimization.
- **Secure LLM Platforms** — Building secure infrastructure for enterprise LLM/RAG platforms (like Dify) in closed networks, implementing audit logs, granular RBAC (Role-Based Access Control), and custom offline-compatible plugins.
- **LLM Quality Assurance (QA)** — Moving AI outputs from "black-box" to "auditable" by designing regression testing frameworks, automated scoring systems, and baseline comparison pipelines to establish quantitative service-in criteria.
- **High-Velocity AI-Assisted Development** — Working with AI coding agents (Claude, Codex) as co-authors on roughly 20% of commits overall and over 40% in peak delivery months. This enabled 240+ PRs and 200+ structured, team-ready issues within a 6-month period.

---

## 🌱 R&D Portfolio: Florigen AI *(in development)*

**Florigen AI** is my independent, long-term research and engineering initiative for offline-first agricultural AI. It leverages my enterprise experience in secure, offline AI infrastructure to build agricultural systems that keep working even in fields without internet access.

> Building agricultural infrastructure that works while the farmer sleeps.

### Private Product Development

Audit-oriented workflows for checking whether genotype, phenotype, sample metadata, and reference information are consistent enough to support downstream analysis without silently repairing ambiguous data.

| Project | Description | Status |
|---|---|---|
| Breeding Genomics Readiness Audit | Offline-first assessment workflow for evaluating whether breeding-genomics data is ready for downstream analysis | Pre-alpha / Private |

Product-specific decision logic, calibration, delivery workflows, and customer-sensitive assets are developed privately.

### Public Research & Engineering

Reproducible analysis of public crop genomic datasets, including WGS-to-variant pipelines, GWAS re-analysis, and genomic prediction experiments.

| Repository | Description | Status |
|---|---|---|
| [adzuki-snp-pipeline](https://github.com/hoso-jpn/adzuki-snp-pipeline) | Reproducible FASTQ-to-cohort-VCF pipeline for adzuki bean with auditable variant processing and GS-panel outputs | Public / active |
| [adzuki-gwas-analysis](https://github.com/hoso-jpn/adzuki-gwas-analysis) | Re-analysis and reproducible delivery of public GWAS results for adzuki bean water permeability | Public |
| [genomic-prediction-resnet-hybrid](https://github.com/hoso-jpn/genomic-prediction-resnet-hybrid) | ResNet + linear hybrid experiments for genomic prediction | Public |

These repositories demonstrate reproducible crop-genomics engineering on public data.

### Long-term Direction: Agricultural Physical AI

Field robotics, ROS2 / Nav2-based autonomous navigation, LiDAR/camera sensor fusion, and edge AI deployment for offline agricultural environments (e.g., autonomous weeding robots).

| Area | Status |
|---|---|
| ROS2 / Isaac Sim / Nav2 | In development |
| YOLO-based crop and weed perception | In development |
| Edge AI on embedded hardware | Planned |
| Field robotics for adzuki bean weeding | Planned |

---

## ⚙️ Engineering Principles

- **Offline-first** — Sensitive data (enterprise, research, or customer) should not require external SaaS or cloud upload.
- **Auditable & No silent repair** — Record counts, decision rules, and AI outputs should be traceable. Ambiguous data should be surfaced, not silently rewritten.
- **Reproducible** — Analysis and AI builds must be rerunnable from explicit inputs, versions, and configurations.
- **Evidence over claims** — Supported scale, accuracy, and readiness should be backed by measured evidence and explicit testing frameworks.

---

## 🔐 Open Science & IP Policy

**Open**

- Reproducible pipelines based on public data
- Generic methods intentionally extracted from product development
- Technical benchmarks

**Closed / Controlled**

- Customer data
- Proprietary SNP panel designs
- Product-specific decision logic
- Production calibration
- Customer-specific adapters
- Commercial delivery workflows

---

## 🛠 Technical Areas

**AI / Machine Learning Infrastructure**  
PyTorch · Local LLMs · Whisper · pyannote · Dify · Secure AI · Offline inference · E2E AI Evaluation

**Bioinformatics and Genomics**  
BWA · GATK · samtools · bcftools · Nextflow · GWAS · QTL analysis · Genomic selection

**Physical AI and Robotics**  
ROS2 · Isaac Sim · Nav2 · YOLO · Edge AI · Jetson

**Software Engineering**  
Python · TypeScript · Docker / GPU Containers · CI/CD · RAG Architecture

---

## 📖 Background & Links

- Plant genetics and molecular breeding research in Hokkaido, Japan (SNP calling, GWAS, flowering-time genetics for adzuki bean and soybean).
- Translating biological domain knowledge and rigorous QA practices into enterprise AI engineering.

- **GitHub:** [https://github.com/hoso-jpn](https://github.com/hoso-jpn)
- **ResearchMap:** [https://researchmap.jp/hosokawa-yusuke](https://researchmap.jp/hosokawa-yusuke)
- **LAPRAS:** [https://lapras.com/public/CEV7BBV](https://lapras.com/public/CEV7BBV)
- **Blog:** [https://blog.florigen.ai/](https://blog.florigen.ai/)
