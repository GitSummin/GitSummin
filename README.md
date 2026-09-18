<div align="center">

# Soomin Kwon

**M.S. Researcher in Statistics & Data Science at Inha University**

Reliable Generative AI · Scientific Machine Learning · Structure-Aware Prediction

[![Email](https://img.shields.io/badge/Email-kweon9209%40inha.edu-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:kweon9209@inha.edu)
[![GitHub](https://img.shields.io/badge/Open_Research_Code-GitSummin-181717?style=flat-square&logo=github)](https://github.com/GitSummin)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=oyleABkAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--7112--8618-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-7112-8618)

</div>

I study how machine-learning systems can remain **informative, reliable, and efficient when data are scarce or imbalanced, structural constraints are domain-specific, or reference evidence is incomplete**. My work connects generative modeling, scientific AI, structured prediction, and evidence-grounded language systems.

I take projects from data and leakage audits through model design, controlled evaluation, external validation, manuscript revision, intellectual-property transfer, and research-software release.

## Research at a glance

| | |
|---|---|
| **Research themes** | Data-aware generative modeling · Structure-aware prediction · Evidence-grounded AI |
| **Peer-reviewed papers** | 3 publications, including first-author and equal-contribution work |
| **Research leadership** | First or co-first author on 8 of 9 research lines |
| **Active manuscripts** | 3 under review / major revision · 2 completed |
| **Patents & registered software** | 2 patent applications · 5 registered research programs |
| **Open research software** | 7 highlighted repositories spanning generative AI, scientific ML, vision, optimization, and synthetic data |
| **R&D experience** | 12 national R&D and commissioned research projects across defense, public safety, and science/technology |
| **Education** | M.S. Statistics & Data Science, Inha University (expected Aug. 2027) |

## What I am working on now

- **Low-NFE generative modeling** — developing **GA-KROT-FM** for locality-constrained diversity in optimal-transport Flow Matching, while extending frequency-aware priors from VAEs to long-tailed diffusion through **FAP-DDPM**.
- **Structure-aware visual reasoning** — incorporating ontology constraints into scene-graph learning through curriculum, soft-target, pair-adaptive, and confidence-weighted strategies.
- **Reliable scientific AI** — revising **HDD-CMS** for reference-scarce mass spectrometry and advancing **RoMSH**, an RT-ordered mixture model for chemical-hazard prediction.
- **Adaptive evidence-grounded systems** — studying query-type-aware retrieval and claim-level verification rather than applying the same reasoning path to every question.

## Main research

| Project | Core contribution | Main result / status | Resources |
|---|---|---|---|
| **GA-KROT-FM** | Source-specific geometric gating for locality-constrained diversity in annealed OT Flow Matching | CIFAR-10, NFE=4: FID **57.26 → 28.04** and coverage **0.4855 → 0.6592** vs. independent coupling · Under review at *Expert Systems with Applications* | [Code](https://github.com/GitSummin/GA-KROT-FM) · Manuscript under review |
| **FAP-VAE** | Frequency-aware class-conditional prior adaptation for imbalanced latent learning | MNIST under 10% minority sampling: NMI **0.993**, ARI **0.983** · Published in *Neurocomputing* | [Paper](https://doi.org/10.1016/j.neucom.2026.132967) · [Code](https://github.com/GitSummin/FAP-VAE) |
| **HDD-CMS** | Molecular-graph-conditioned diffusion for generating candidate EI mass spectra under limited reference coverage | Evaluated on **5,162 molecules / 305,966 peak rows** with random and scaffold-disjoint splits · Major revision at *Journal of Cheminformatics* | [Code](https://github.com/GitSummin/HDD-CMS) |
| **RoMSH** | Hierarchical Transformer with explicit retention-time ordering and context suppression for chemical mixtures | Cross-material F1 **0.984**; field-sample AUROC **0.981** · Manuscript completed; preparing for submission to *Journal of Chemical Information and Modeling* | [Code](https://github.com/GitSummin/RoMSH) |
| **Query-Type-Aware Agentic RAG** | Eight-type routing with shared retrieval, type-conditioned synthesis, and claim-level selective revision | Hard-QA accuracy **0.817 vs. 0.683** for Basic RAG · Major revision / second-round review | Manuscript in revision |
| **B-MOD** | Bhattacharyya-distance localization objective for scale-robust object detection | Generalized across detector families and datasets · Published in *Machine Vision and Applications* | [Paper](https://doi.org/10.1007/s00138-026-01803-2) · [Code](https://github.com/GitSummin/B-MOD_Yolov4) |
| **Diff-Trans-TEL** | Context-aware diffusion–Transformer synthesis for scarce TEL targets | FID **−39.2%** vs. the GAN baseline; downstream mAP@0.5 **0.6260 → 0.6647** · Co-first author; manuscript completed | [Code](https://github.com/GitSummin/DiffTrans-TEL) |

## Publications

### Peer-reviewed

1. **S. Kwon**, S. Jo, and J. Kim. “Frequency-aware priors for variational autoencoders under class imbalance.” *Neurocomputing*, 681, 132967, 2026. **First author.** [DOI](https://doi.org/10.1016/j.neucom.2026.132967)
2. H. Kim*, **S. Kwon***, and J. Kim. “Enhancing object detection algorithm for size-insensitive performance.” *Machine Vision and Applications*, 37, Article 42, 2026. **Equal contribution.** [DOI](https://doi.org/10.1007/s00138-026-01803-2)
3. “동적계획법 기반 무기–표적 할당 최적화.” *Journal of the Korea Society for Defense Management Analysis*. **S. Kwon: third author; peer-reviewed KCI publication.**

### Under review or completed

- **S. Kwon**, H. Kim, Y. Jin, and J. Kim. “Structure-conditioned diffusion recovers mass spectra for reference-scarce compounds.” *Journal of Cheminformatics*. **First author; major revision.**
- **S. Kwon** and J. Kim. “Query-type-aware agentic RAG adapts its execution path to question complexity.” *KIPS Transactions on Computer and Communication Systems*. **First author; major revision / second-round review.**
- **S. Kwon** and J. Kim. “GA-KROT-FM: Gated annealed kernel-repulsive optimal-transport flow matching.” *Expert Systems with Applications*. **First author; under review.**
- **S. Kwon** et al. “RoMSH: RT-ordered mixture sequence modeling for hazard prediction.” **First author; manuscript completed; preparing for submission to *Journal of Chemical Information and Modeling*.**
- **S. Kwon** et al. “Context-aware diffusion-Transformer synthesis of rare TEL objects.” **Co-first author; manuscript completed; preparing for submission to *Machine Vision and Applications*.**

## Patents & registered research software

### Patent applications

| Invention | Application no. | Filed | Status |
|---|---:|---:|---|
| **Artificial Intelligence Based Ignitable Liquid Discrimination Model** | 10-2026-0141260 | Jul. 30, 2026 | Filed |
| **Method for Generating GC/MS Data of Novel Compounds Based on a Diffusion Model** | 10-2025-0082563 | Jun. 23, 2025 | Filed |

### Registered research software

| Program | Registration no. | Related research |
|---|---:|---|
| **Dynamic-programming weapon–target assignment optimization program** | C-2026-026286 | WTA-DDP |
| **Frequency-Aware Prior VAE for imbalanced image datasets** | C-2026-026287 | FAP-VAE |
| **Molecular-structure-based mass-spectrum generation and prediction program** | C-2026-026288 | HDD-CMS |
| **Chemical-mixture-sequence-based hazard prediction and classification program** | C-2026-026289 | RoMSH |
| **B-MOD multi-scale object-detection training program** | C-2026-031612 | B-MOD |

These outputs were developed as working research software and transferred as project deliverables to collaborating organizations.

## Selected R&D projects

| Project | Period / organization | Role | Research linkage |
|---|---|---|---|
| **Database construction and high-speed AI platform for gas analysis at fire/disaster scenes** | Sep. 2024–present · Science and Police Research Center | Research assistant | Led directly to **HDD-CMS** and **RoMSH**, with associated patent/software outputs |
| **Defense-specialized intelligent operation-support system (K-AIP-based GOP support)** | Jan. 2026–present · Korea Research Institute for Defense Technology Planning and Advancement | Research assistant | Led directly to **Ontology-Aware SGG** research |
| **Multi-purpose combat-drone weapon–target assignment and tiny-object identification** | Jan. 2023–Dec. 2025 · Poongsan Corporation | Research assistant | Led directly to **WTA-DDP** and **B-MOD** publications/software |
| **CBRN personal contamination detection system** | Jul. 2025–present · Agency for Defense Development (ADD) | Research assistant / administrative PI | Proposal, contract/start-up, reporting, schedule coordination, and project deliverable management |
| **Performance-evaluation methods for data generation, image enhancement, and restoration** | Apr. 2024–Nov. 2024 · Defense Agency for Technology and Quality (DTaQ) | Research assistant | Evaluation protocol work for image-generation, restoration, and quality assurance |

## Open research software

- [**GA-KROT-FM**](https://github.com/GitSummin/GA-KROT-FM) — locality-constrained, diversity-aware coupling for low-NFE Flow Matching
- [**FAP-VAE**](https://github.com/GitSummin/FAP-VAE) — frequency-aware latent-prior learning under class imbalance
- [**HDD-CMS**](https://github.com/GitSummin/HDD-CMS) — structure-conditioned diffusion for candidate EI spectrum generation
- [**RoMSH**](https://github.com/GitSummin/RoMSH) — retention-time-ordered chemical-mixture modeling
- [**DiffTrans-TEL**](https://github.com/GitSummin/DiffTrans-TEL) — diffusion–Transformer synthetic-data generation for scarce TEL targets
- [**B-MOD_Yolov4**](https://github.com/GitSummin/B-MOD_Yolov4) — distribution-aware localization for object detection
- [**WTA-DDP**](https://github.com/GitSummin/WTA-DDP) — deterministic dynamic programming for weapon-target assignment

## Research principles

- **Domain structure as an inductive bias** — encode chemical graphs, retention-time order, ontology constraints, or source-target geometry when they are part of the problem.
- **Evaluation beyond a single benchmark** — use disjoint splits, ablations, statistical comparisons, failure analysis, and external validation.
- **Reproducibility as a research output** — connect papers to readable implementations, documented data curation, auditable evaluation pipelines, and registered research software.
- **Honest evaluation** — report statistically insignificant gains, failure cases, and conditions where a competing method remains stronger instead of reducing research to a single headline metric.

## Technical stack

### Languages, frameworks, and infrastructure

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

| Area | Technologies and methods | Representative use |
|---|---|---|
| **Programming & data** | Python (primary) · SQL · Java · NumPy · pandas · SciPy | Research implementation, data processing, database-backed applications |
| **Deep learning & ML** | PyTorch · TensorFlow · scikit-learn · XGBoost · torchvision · TensorBoard | End-to-end model development across generative AI, vision, scientific ML, and sensor learning |
| **Generative AI** | VAE · conditional diffusion · Flow Matching · textual inversion · Transformer inpainting | FAP-VAE · HDD-CMS · GA-KROT-FM · Diff-Trans-TEL |
| **Computer vision** | YOLOv4 / YOLOv8 · distribution-based box losses · scene graph generation · super-resolution / inpainting evaluation · OpenCV | B-MOD · Ontology-Aware SGG · image-quality / restoration projects |
| **LLM & RAG** | Agentic RAG · query-type routing · multi-query retrieval · evidence verification · claim-level selective revision | Query-Type-Aware Agentic RAG |
| **Scientific & molecular ML** | RDKit · molecular graphs · GNNs · GC-MS / EI-MS preprocessing · NIST / MoNA conversion | HDD-CMS · RoMSH |
| **Time-series & signal processing** | MiniROCKET · Signature-Kernel GP · Wavelet-PCA · CUSUM change-point detection | Multichannel CBRN sensor modeling |
| **Optimization** | Dynamic programming · entropic optimal transport · numerical optimization | WTA-DDP · GA-KROT-FM |
| **Statistical evaluation** | paired t-test · McNemar test · 95% confidence intervals · multi-seed evaluation | Controlled comparisons, ablations, significance testing, external validation |
| **Data & research infrastructure** | MySQL · Docker · Git · multiprocessing / CPU binding · reproducible experiment pipelines | Dataset management and reproducible research workflows |
| **Web / full-stack** | Flask · SQLAlchemy ORM · SQLite · HTML · CSS · JavaScript · Figma | DOPA Time · I44U |
| **Research communication** | Matplotlib · Jupyter · LaTeX · failure analysis · external-validation design | Manuscripts, figures, ablation studies, and research reporting |

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

**Email:** [kweon9209@inha.edu](mailto:kweon9209@inha.edu) · [Google Scholar](https://scholar.google.com/citations?user=oyleABkAAAAJ) · [ORCID](https://orcid.org/0009-0003-7112-8618)
