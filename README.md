# Hoso

Plant Genetics × Breeding Genomics × Agricultural AI

I am building a long-term research and engineering portfolio around **agricultural AI**, with a current focus on reproducible breeding-genomics workflows and offline-first analysis systems.

My work connects three layers:

1. **Plant genetics and breeding genomics**  
   Reproducible analysis of public crop genomic datasets, including WGS-to-variant pipelines, GWAS re-analysis, and genomic prediction experiments.

2. **Breeding-data readiness and secure AI infrastructure**  
   Private product development around audit-oriented workflows for checking whether genotype, phenotype, sample metadata, and reference information are consistent enough to support downstream analysis without silently repairing ambiguous data.

3. **Agricultural Physical AI**  
   A longer-term direction toward field robotics, perception, navigation, and edge AI for offline agricultural environments.

---

## Current Direction

### Florigen AI *(in development)*

Florigen AI is a long-term research and engineering initiative for **offline-first agricultural AI**, beginning with breeding genomics and expanding toward field-scale Physical AI.

Current priorities:

- Reproducible and auditable breeding-genomics pipelines
- Offline-first genomic data readiness assessment
- Non-model crop and non-standard domain support
- Local / secure AI workflows that keep sensitive data under user control
- Evidence-backed analysis with explicit accounting, provenance, and limitations

Longer-term research directions:

- Autonomous weeding robots for row crops
- Night-time LED-controlled perception
- LiDAR and camera sensor fusion
- ROS2 / Nav2-based autonomous navigation
- Edge AI deployment on embedded hardware
- Plant-domain knowledge integration for agricultural perception and decision-making

> Building agricultural infrastructure that works while the farmer sleeps.

---

## Research & Engineering Portfolio

### Public Research & Engineering

| Repository | Description | Status |
|---|---|---|
| [adzuki-snp-pipeline](https://github.com/hoso-jpn/adzuki-snp-pipeline) | Reproducible FASTQ-to-cohort-VCF pipeline for adzuki bean with auditable variant processing and GS-panel outputs | Public / active |
| [adzuki-gwas-analysis](https://github.com/hoso-jpn/adzuki-gwas-analysis) | Re-analysis and reproducible delivery of public GWAS results for adzuki bean water permeability | Public |
| [genomic-prediction-resnet-hybrid](https://github.com/hoso-jpn/genomic-prediction-resnet-hybrid) | ResNet + linear hybrid experiments for genomic prediction | Public |

### Private Product Development

| Project | Description | Status |
|---|---|---|
| Breeding Genomics Readiness Audit | Offline-first assessment workflow for evaluating whether breeding-genomics data is ready for downstream analysis | Private / pre-alpha |

The public repositories above demonstrate reproducible crop-genomics engineering on public data. Product-specific decision logic, calibration, delivery workflows, and customer-sensitive assets are developed privately.

### Agricultural Physical AI

| Area | Status |
|---|---|
| ROS2 / Isaac Sim / Nav2 | In development |
| YOLO-based crop and weed perception | In development |
| Edge AI on embedded hardware | Planned |
| Field robotics for adzuki bean weeding | Planned |

---

## Engineering Principles

- **Offline-first** — sensitive research and customer data should not require external SaaS or cloud upload
- **Reproducible** — analysis should be rerunnable from explicit inputs, versions, and configuration
- **Auditable** — record counts, exclusions, provenance, and decision rules should be traceable
- **No silent repair** — ambiguous sample IDs, references, or metadata should be detected and surfaced rather than automatically rewritten
- **Evidence over claims** — supported scale, accuracy, and readiness should be backed by measured evidence

---

## Open Science Policy

**Open by default when appropriate**

- Reproducible pipelines and workflows based on public data
- Public-data analyses
- Technical documentation and benchmarking studies
- Generic methods intentionally separated from product-sensitive logic

**Private / controlled**

- Customer data and customer-specific adapters
- Proprietary SNP panel designs
- Product-specific decision logic and production calibration
- Commercial delivery workflows and business-sensitive assets
- Future intellectual property

---

## Technical Areas

**Bioinformatics and Genomics**  
BWA · GATK · samtools · bcftools · Nextflow · GWAS · QTL analysis · Genomic selection

**AI / Machine Learning**  
PyTorch · Deep learning · Local LLMs · Secure AI · Offline inference

**Physical AI and Robotics**  
ROS2 · Isaac Sim · Nav2 · YOLO · Edge AI · Jetson

---

## Background

- Plant genetics and molecular breeding research in Hokkaido, Japan
- SNP calling and genomic analysis for adzuki bean and soybean
- GWAS, QTL analysis, flowering-time genetics, and breeding-oriented data interpretation
- Agricultural system design and field-oriented technology development
- Currently working in AI engineering while developing Florigen AI as an independent long-term R&D initiative

---

## Links

- GitHub: https://github.com/hoso-jpn
- ResearchMap: https://researchmap.jp/hosokawa-yusuke
- LAPRAS: https://lapras.com/public/CEV7BBV
- Blog: https://blog.florigen.ai/
