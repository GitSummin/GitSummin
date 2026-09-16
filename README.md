<div align="center">

# Soomin Kwon

**M.S. Researcher in Statistics & Data Science at Inha University**

Reliable Generative AI · Scientific Machine Learning · Structure-Aware Prediction

[![Email](https://img.shields.io/badge/Email-kweon9209%40inha.edu-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:kweon9209@inha.edu)
[![GitHub](https://img.shields.io/badge/Open_Research_Code-GitSummin-181717?style=flat-square&logo=github)](https://github.com/GitSummin)
[![Research Portfolio](https://img.shields.io/badge/Research_Portfolio-Download_PDF-B31B1B?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://github.com/GitSummin/GitSummin/raw/main/Research_Portfolio_Soomin_Kwon.pdf?download=1)

</div>

I study how machine-learning systems can remain **informative, reliable, and efficient when data are scarce or imbalanced, structural constraints are domain-specific, or reference evidence is incomplete**. My work connects generative modeling, scientific AI, structured prediction, and evidence-grounded language systems.

I take projects from data and leakage audits through model design, controlled evaluation, external validation, manuscript revision, and research-software release.

## Research at a glance

| | |
|---|---|
| **Research themes** | Data-aware generative modeling · Structure-aware prediction · Evidence-grounded AI |
| **Peer-reviewed papers** | 2 publications (first author / equal contribution) |
| **Active manuscripts** | 3 under review or major revision · 2 completed |
| **Open research software** | 5 highlighted repositories spanning generative AI, scientific ML, vision, and optimization |
| **Education** | M.S. Statistics & Data Science, Inha University (expected Aug. 2027) |

## What I am working on now

- **Low-NFE generative modeling** — developing GA-KROT-FM for locality-constrained diversity in optimal-transport Flow Matching, while extending frequency-aware priors from VAEs to long-tailed diffusion through **FAP-DDPM**.
- **Structure-aware visual reasoning** — incorporating ontology constraints into scene-graph learning through curriculum, soft-target, pair-adaptive, and confidence-weighted strategies.
- **Reliable scientific AI** — revising **HDD-CMS** for reference-scarce mass spectrometry and advancing **RoMSH**, an RT-ordered mixture model for chemical-hazard prediction.
- **Adaptive evidence-grounded systems** — studying query-type-aware retrieval and claim-level verification rather than applying the same reasoning path to every question.

## Main research

| Project | Core contribution | Main result / status | Resources |
|---|---|---|---|
| **GA-KROT-FM** | Source-specific geometric gating for locality-constrained diversity in annealed OT Flow Matching | CIFAR-10, NFE=4: FID **57.26 → 28.04** and coverage **0.4855 → 0.6592** vs. independent coupling · Under review at *Expert Systems with Applications* | Manuscript under review |
| **FAP-VAE** | Frequency-aware class-conditional prior adaptation for imbalanced latent learning | MNIST under 10% minority sampling: NMI **0.993**, ARI **0.983** · Published in *Neurocomputing* | [Paper](https://doi.org/10.1016/j.neucom.2026.132967) · [Code](https://github.com/GitSummin/FAP-VAE) |
| **HDD-CMS** | Molecular-graph-conditioned diffusion for generating candidate EI mass spectra under limited reference coverage | Evaluated on **5,162 molecules / 305,966 peak rows** with random and scaffold-disjoint splits · Major revision at *Journal of Cheminformatics* | [Code](https://github.com/GitSummin/HDD-CMS) |
| **RoMSH** | Hierarchical Transformer with explicit retention-time ordering and context suppression for chemical mixtures | Cross-material F1 **0.984**; field-sample AUROC **0.981** · Manuscript completed | [Code](https://github.com/GitSummin/RoMSH) |
| **Query-Type-Aware Agentic RAG** | Eight-type routing with shared retrieval, type-conditioned synthesis, and claim-level selective revision | Hard-QA accuracy **0.817 vs. 0.683** for Basic RAG · Major revision | Manuscript in revision |
| **B-MOD** | Bhattacharyya-distance localization objective for scale-robust object detection | Generalized across detector families and datasets · Published in *Machine Vision and Applications* | [Paper](https://doi.org/10.1007/s00138-026-01803-2) · [Code](https://github.com/GitSummin/B-MOD_Yolov4) |

## Publications

### Peer-reviewed

1. **S. Kwon**, S. Jo, and J. Kim. “Frequency-aware priors for variational autoencoders under class imbalance.” *Neurocomputing*, 681, 132967, 2026. **First author.** [DOI](https://doi.org/10.1016/j.neucom.2026.132967)
2. H. Kim*, **S. Kwon***, and J. Kim. “Enhancing object detection algorithm for size-insensitive performance.” *Machine Vision and Applications*, 37, Article 42, 2026. **Equal contribution.** [DOI](https://doi.org/10.1007/s00138-026-01803-2)

### Under review or completed

- **S. Kwon**, H. Kim, Y. Jin, and J. Kim. “Structure-conditioned diffusion recovers mass spectra for reference-scarce compounds.” *Journal of Cheminformatics*. **First author; major revision.**
- **S. Kwon** and J. Kim. “Query-type-aware agentic RAG adapts its execution path to question complexity.” *KIPS Transactions on Computer and Communication Systems*. **First author; major revision.**
- **S. Kwon** and J. Kim. “GA-KROT-FM: Gated annealed kernel-repulsive optimal-transport flow matching.” *Expert Systems with Applications*. **First author; under review.**
- **S. Kwon** et al. “RoMSH: RT-ordered mixture sequence modeling for hazard prediction.” **First author; manuscript completed.**
- **S. Kwon** et al. “Context-aware diffusion-Transformer synthesis of rare TEL objects.” **Co-first author; manuscript completed.**

## Open research software

- [**FAP-VAE**](https://github.com/GitSummin/FAP-VAE) — frequency-aware latent-prior learning under class imbalance
- [**HDD-CMS**](https://github.com/GitSummin/HDD-CMS) — structure-conditioned diffusion for candidate EI spectrum generation
- [**RoMSH**](https://github.com/GitSummin/RoMSH) — retention-time-ordered chemical-mixture modeling
- [**B-MOD_Yolov4**](https://github.com/GitSummin/B-MOD_Yolov4) — distribution-aware localization for object detection
- [**WTA-DDP**](https://github.com/GitSummin/WTA-DDP) — deterministic dynamic programming for weapon-target assignment

## Research principles

- **Domain structure as an inductive bias** — encode chemical graphs, retention-time order, ontology constraints, or source-target geometry when they are part of the problem.
- **Evaluation beyond a single benchmark** — use disjoint splits, ablations, statistical comparisons, failure analysis, and external validation.
- **Reproducibility as a research output** — connect papers to readable implementations, documented data curation, and auditable evaluation pipelines.

## Technical stack

### Languages, frameworks, and infrastructure

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

| Area | Technologies and methods |
|---|---|
| **Programming & data** | Python · Java · SQL · NumPy · pandas · SciPy |
| **Deep learning & ML** | PyTorch · TensorFlow · torchvision · scikit-learn · TensorBoard |
| **Scientific & graph ML** | RDKit · NetworkX · GeomLoss · molecular graphs · optimal transport |
| **Computer vision** | OpenCV · pycocotools · scikit-image · image generation · object detection |
| **Generative & language AI** | Diffusion models · Flow Matching · VAEs · Transformers · RAG · agentic workflows |
| **Databases & engineering** | MySQL · Docker · Git · Linux · Conda · reproducible experiment pipelines |
| **Analysis & communication** | Matplotlib · Jupyter · LaTeX · statistical testing · ablation and failure analysis |

## Certifications & honors

### Professional certifications

| Certification | Date awarded |
|---|---|
| **Big Data Analysis Engineer** (빅데이터분석기사) | Dec. 19, 2025 |
| **SQL Developer (SQLD)** | Oct. 6, 2023 |
| **Computer Specialist in Spreadsheet & Database, Level 1** (컴퓨터활용능력 1급) | Aug. 4, 2023 |
| **Advanced Data Analytics Semi-Professional (ADsP)** | Mar. 24, 2023 |

### Honors & competitions

- **Excellence Award, Planning Division** — Inha University–Sejong University Joint Academic Festival, Aug. 2023
- **Advanced to the final round** — 11th Software Development Security Competition (소개딩), 2024

## Education

**M.S. in Statistics and Data Science**, Inha University  
Mar. 2026 – Aug. 2027 (expected) · Data Science Track · Advisor: Prof. Jaeoh Kim

**B.S. in Data Science; Double Major in AI Engineering**, Inha University  
Mar. 2022 – Feb. 2026 · Graduated first in the department · GPA: 4.25/4.50

## Contact

I am interested in research conversations and collaborations around reliable generative modeling, scientific AI, and structure-aware learning.

**Email:** [kweon9209@inha.edu](mailto:kweon9209@inha.edu)
