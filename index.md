---
layout: default
---

## About me

I recently completed my MSc in Bioinformatics at Saarland University,  where I focused on applying machine learning to problems in computational biology and cheminformatics.

My research experience spans few-shot learning for toxicity prediction, molecular representation learning, multi-omics data analysis, and molecular property prediction. I currently work as a student research assistant at the Chair of Data-Driven Drug Design, contributing to computational research projects involving machine learning and molecular data.

## Education

### MSc in Bioinformatics

**[Saarland University](https://www.uni-saarland.de/en/home.html)**  
*April 2024 – October 2026 · Saarbrücken, Germany*

- **Current grade:** 1.6 (final thesis grade pending)
- **Master's thesis:** Assessing Few-Shot Learning Techniques for Hormone-Related Toxicity Prediction

### BSc in Bioinformatics

**[Lebanese American University](https://www.lau.edu.lb/)**  
*August 2019 – August 2022 · Beirut, Lebanon*

- **GPA:** 3.87/4.00 — High Distinction
- **Bachelor's thesis:** Binding mechanism analysis and 3D QSAR studies on sulfonamide scaffold Lp-PLA2 inhibitors

## Work experience

### Student Research Assistant

**[Volkamer Lab](https://volkamerlab.org/), Chair of Data-Driven Drug Design, Saarland University**  
*January 2026–Present · Germany*

**Hormone-related toxicity prediction benchmark**

Contributed to an ongoing study benchmarking molecular representations and machine-learning pipelines for predicting activity in hormone-related ToxCast assays.

- Performed domain adaptation of a pretrained transformer and generated molecular embeddings
- Adapted and executed existing benchmarking workflows on an HPC cluster and contributed to reviewing the results and manuscript
- Implemented reviewer-requested experiments using an updated version of TabPFN and CheMeleon, a pretrained Chemprop model fine-tuned on the study data

**Related publication:** [*A Comprehensive Evaluation of Machine Learning Pipelines for Hormone-related Toxicity Prediction*](https://doi.org/10.21203/rs.3.rs-10470980/v1) — Research Square preprint, under revision at the *Journal of Cheminformatics*.

**Surfactant property prediction**

Independently developing machine-learning workflows to predict critical micelle concentration (CMC) and air–water surface tension (AWST) from small datasets within the [EU RADAR project](https://www.radar-project.eu/). The predictions will help experimental collaborators prioritize candidate surfactants for laboratory testing.

### Student Research Assistant

**[Chair of Computational Biology](https://www-cbi.cs.uni-saarland.de/), Saarland University**  
*November 2024–November 2025 · Germany*

Investigated how transcript levels relate to protein abundance using matched transcriptomic and proteomic data from 10 CPTAC cancer cohorts.

- Curated and preprocessed multi-omics data and developed gene-specific regression models using each gene’s own transcript and the transcripts of its STRING protein-interaction partners
- Analyzed the resulting models to distinguish self-driven and interactor-driven proteins and investigated their relationships with protein complexes, biological pathways, cancer hallmarks, and RNA stability
- Used Python, scikit-learn, PyTorch, statistical analyses, clustering, and dimensionality reduction to model, validate, interpret, and visualize the results
- Conducted the project’s computational work from data curation and model development through statistical analysis, visualization, validation, and manuscript preparation and revision through publication

**Related publication:** [*Relating Transcriptomics to Protein Abundance Reveals Self-Driven vs. Interactor-Driven Proteins*](https://doi.org/10.1002/pro.70806), *Protein Science*, 2026.

**[Code and processed data](https://doi.org/10.5281/zenodo.21417532)**

## Research projects

### Master's Thesis: Assessing Few-Shot Learning Techniques for Hormone-Related Toxicity Prediction

**Chair of Data-Driven Drug Design, Saarland University**  
*2026 · Saarbrücken, Germany*

**Supervisors:** Prof. Dr. Andrea Volkamer, Prof. Dr. Kerstin Lenhof, Lisa-Marie Rolli

Investigated machine-learning approaches for toxicity prediction under limited-data conditions, using hormone-related assays from the ToxCast dataset.

- Implemented and evaluated transfer learning, model-agnostic meta-learning (MAML), and multi-task learning approaches.
- Compared different learning strategies and experimental conditions to investigate their performance in low-data settings.

**Related presentation:** [ELLIS Summer School](#presentations-and-training) — poster on the robustness of few-shot learning for low-data toxicity prediction.

### Bachelor's Thesis: Binding mechanism analysis and 3D QSAR studies on sulfonamide scaffold Lp-PLA2 inhibitors

**Lebanese American University**  
*2022 · Lebanon*

**Supervisor:** Dr. Joseph Rebehmed

**Project collaborator:** Reine Mansour

Investigated the binding mechanisms and structure–activity relationships of sulfonamide-scaffold inhibitors of lipoprotein-associated phospholipase A2 (Lp-PLA2), a potential therapeutic target involved in inflammatory pathways.

- Analyzed protein–ligand interactions and compared crystal structures of Lp-PLA2 bound to inhibitors with different potencies.
- Performed sequence conservation analysis using PSI-BLAST, MAFFT, ConSurf, and UCSF Chimera to investigate the evolutionary conservation of binding-site residues.
- Developed and evaluated comparative molecular field analysis (CoMFA) models using Open3DQSAR and partial least-squares (PLS) regression to investigate the relationship between molecular interaction fields and inhibitory activity.

## Publications

1. **Loulwah Arnaout**, Volkhard Helms, Aram Papazian.  
   [*Relating Transcriptomics to Protein Abundance Reveals Self-Driven vs. Interactor-Driven Proteins*](https://doi.org/10.1002/pro.70806).  
   *Protein Science*, 35(10), e70806, 2026.  
   [Code and processed data](https://doi.org/10.5281/zenodo.21417532)

2. Lisa-Marie Rolli, **Loulwah Arnaout**, Andrea Volkamer.  
   [*A Comprehensive Evaluation of Machine Learning Pipelines for Hormone-related Toxicity Prediction*](https://doi.org/10.21203/rs.3.rs-10470980/v1).  
   Research Square preprint, 2026. Under revision at the *Journal of Cheminformatics*.  
   [Code and data](https://github.com/volkamerlab/ToxCastBenchmark)

## Presentations and training

### [ELLIS Summer School: Trustworthy and Responsible AI for Drug Discovery](https://pharma-science-hub.com/summerschools/2026-ellis-summerschool-trustworthy-responsible-ai-drug-discovery/)

**Saarland University**  
*24–28 August 2026 · Saarbrücken, Germany*

Presented the poster *“Assessing Robustness of Few-Shot Learning for Low-Data Toxicity Prediction”* and delivered a one-minute pitch introducing the work.

## Skills

- **Programming:** Python, R, Java, SQL, Bash
- **Machine learning & data analysis:** PyTorch, scikit-learn, regression, classification, transfer learning, meta-learning, multi-task learning, model evaluation
- **Cheminformatics & molecular modeling:** RDKit, PyMOL, UCSF Chimera, AutoDock Tools, Open3DQSAR, BIOVIA Discovery Studio, Schrödinger Maestro
- **Bioinformatics:** Seurat, ArchR, sequence alignment, protein–protein interaction networks, multi-omics data analysis
- **Computing & development:** Git, Linux, HPC computing, Jupyter Notebooks
- **Languages:** Arabic (native), English (C1), French (B2), German (B1)

## Awards

### Baccalaureate Scholarship

**Lebanese American University**  
*August 2019–August 2022*

Partial tuition scholarship awarded upon admission after achieving **18/20** in the Lebanese Baccalaureate, ranking **11th in Beirut and 30th nationwide**. Retained throughout the bachelor’s degree subject to continued academic performance.

### Full Merit Scholarship

**Al-Makassed Philanthropic Association of Beirut**  
*September 2013–June 2019*

Full-tuition scholarship awarded for ranking first across my grade cohort and maintained throughout the stated period.

### Valedictorian

**KBWH – Makassed**  
*2019 · Beirut, Lebanon*

Graduated first in my cohort and delivered the valedictory address at the graduation ceremony. Also received the **Administrative Board Award** for academic excellence and exemplary conduct.

<!-- TODO: Additional Experience & Activities / Selected Coursework Projects (optional) -->

## Contact

[Email](mailto:arnaoutloulwa@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/loulwah-arnaout/) ·
[Google Scholar](https://scholar.google.com/citations?user=7RHPyjMAAAAJ&hl=en) ·
[ORCID](https://orcid.org/0009-0003-3766-2630) ·
[GitHub](https://github.com/loulwah-arnaout)

<!-- TODO: Add a downloadable CV after completing the one-page version. -->
