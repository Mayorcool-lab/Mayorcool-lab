# Dr. Oluwamayowa Joshua Ogun

**Computational Biologist & Data Scientist · Functional Genomics · Structural Bioinformatics · ML & Analytics Pipelines**

📍 Kiel, Germany · London, UK &nbsp;|&nbsp; ✉️ oluwamayowaogun@gmail.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/oluwamayowaogun) &nbsp;|&nbsp; 🔗 [Google Scholar](https://scholar.google.com/citations?user=ZsF5IQ8AAAAJ&hl=en&authuser=2)

---

PhD-trained computational biologist with a dual strength: **deep expertise in glyco-enzyme structural modelling** and **broad capability in reproducible bioinformatics pipeline development**. I model molecular systems at atomic resolution — glyco-enzymes, inhibitor binding, mutation effects — and I build the scalable, automated workflows to analyse biological data at every scale, from single cells to populations.

My published research focuses on the **CMAH glyco-enzyme and sialic acid metabolism**, using AlphaFold, Rosetta, GROMACS, and high-throughput virtual screening. Alongside this, I develop reproducible pipelines spanning **scRNA-seq, metagenomics, population genomics, and ML-driven cheminformatics**.

Open to roles in **computational glycobiology, structural bioinformatics, enzyme engineering, bioinformatics pipeline development, and data analytics**.

---

## Core Technical Expertise

| Domain | Tools & Methods |
|--------|----------------|
| **Structural Glycobiology & Enzyme Modelling** | AlphaFold2 (ColabFold), Rosetta/TrRosetta, PyMOL, GalaxyWEB, active-site prediction, structure validation |
| **Molecular Dynamics & Free Energy** | GROMACS — RMSD, RMSF, Rg, SASA, H-bond analysis, MM/GBSA (50–200 ns simulations) |
| **Molecular Docking & Virtual Screening** | AutoDock Vina, PyRx, SiteMap, MetaPocket, MCULE (~5M compound screening) |
| **Cheminformatics & ML** | RDKit, PaDEL, ChEMBL API, QSAR, pIC₅₀ prediction, Scikit-learn, XGBoost, Random Forest |
| **Single-Cell & Bulk Transcriptomics** | Scanpy, Seurat, Harmony, DESeq2, CellTypist, Monocle, Trinity (de novo) |
| **Population Genomics & Variant Analysis** | GWAS, PLINK, VCFtools, SIFT, PolyPhen, ConSurf, DynaMut, InterProScan |
| **Metagenomics & Viral Genomics** | SPAdes, Kraken, IQ-TREE, MAFFT, RAxML, BEAST, dN/dS analysis |
| **Pipeline Engineering & Reproducibility** | Python, R, Bash, Snakemake, Conda, Git, HPC/Linux, AWS (S3, Athena) |
| **Data Analytics & Visualisation** | SQL, Power BI, Matplotlib, Seaborn, Plotly, ggplot2, RMarkdown |

---

## 🔬 Pillar 1 — Computational Glycobiology & Structural Enzyme Modelling

My core research area. Published work on glyco-enzyme structure, sialic acid metabolism, enzyme–substrate interactions, and inhibitor discovery.

---

### CMAH Inhibitor Discovery — Structure-Based Drug Design
*Published · Pathogens 2023 · [DOI: 10.3390/pathogens12050684](https://doi.org/10.3390/pathogens12050684)*

**First structural characterisation of the porcine CMAH glyco-enzyme** using AlphaFold2 with GalaxyWEB refinement. High-throughput virtual screening of ~5 million compounds, molecular docking (AutoDock Vina), and 200 ns GROMACS MD simulations with MM/GBSA binding free energy estimation identified novel enzyme inhibitors targeting sialic acid biosynthesis.

`AlphaFold2` `ColabFold` `GalaxyWEB` `AutoDock Vina` `GROMACS` `MM/GBSA` `SwissADME` `COACH` `DoGSiteScorer`

**Key outputs:** Lead inhibitor candidates validated; structure quality — Ramachandran 91.4% favoured, ProSA z-score -8.2

---

### CMAH Variant Functional Analysis — Glyco-enzyme Mutation Effects
*Published · Pathogens 2023 · [DOI: 10.3390/pathogens12040591](https://doi.org/10.3390/pathogens12040591)*

Bovine CMAH structure predicted via **Rosetta ab initio modelling** (TrRosetta/Robetta). Five non-synonymous SNPs from the 1000 Bull Genomes Project introduced via PyMOL mutagenesis. Active sites characterised with SiteMap and MetaPocket. 50 ns GROMACS MD simulations across wildtype + 5 mutant structures. **P424L identified as most pathogenic variant** by consensus of five independent tools.

`TrRosetta` `Robetta` `GalaxyWEB` `PyMOL` `GROMACS` `SiteMap` `MetaPocket` `DynaMut` `ConSurf` `SIFT` `PolyPhen`

**Key outputs:** RMSD/RMSF/Rg/SASA/H-bond profiles across 6 structures; Ramachandran 92.6% favoured, ProSA z-score -7.78

---

### Mannose-Binding Lectin In Silico Characterisation
*Published · J. Adv. Vet. Anim. Res. 2025 · [DOI: 10.5455/javar.2025.l955](https://doi.org/10.5455/javar.2025.l955)*

In silico structural characterisation of mannose-binding lectin (MBL) — a key innate immune lectin — across South African chicken breeds, integrating sequence analysis, structural prediction, and functional annotation.

---

### Porcine Sialic Acid Biology — Review
*Published · Biology 2022 · [DOI: 10.3390/biology11060903](https://doi.org/10.3390/biology11060903)*

Comprehensive review of porcine Neu5Gc sialic acid in host–pathogen interactions, xenotransplantation biology, and red meat-associated disease — establishing the biological rationale for CMAH-targeted therapeutic strategies.

---

## ⚙️ Pillar 2 — Bioinformatics Pipeline Development

Reproducible, modular, scalable pipelines across transcriptomics, metagenomics, and population genomics — built with Snakemake, Python, and Conda for HPC deployment.

---

### COVID-19 Lung scRNA-seq Analysis
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Covid-scRNA-Analysis)

Automated Scanpy workflow for immune cell annotation (CellTypist), differential gene expression, and pathway enrichment in COVID-19 lung tissue. Fully modular Snakemake pipeline — a reproducible Python-native alternative to R/Seurat workflows.

`Scanpy` `CellTypist` `Snakemake` `Python` `DEG analysis` `Pathway enrichment`

---

### Breast Cancer Tumour Microenvironment (scRNA-seq)
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/scRNA-Breast-Cancer-Analysis)

Seurat/Monocle pipeline for TME deconvolution and pseudotime trajectory analysis, identifying immunosuppressive cell populations and novel immune evasion signatures.

`Seurat` `Monocle` `Harmony` `R` `TME deconvolution` `Trajectory analysis`

---

### Bat Coronavirus Surveillance Pipeline
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/bat-coronavirus-surveillance)

Complete metagenomics-to-evolution workflow: assembled a 26.6 kb SARS-CoV-2 genome from bat metagenomic samples, reconstructed sarbecovirus phylogeny (IQ-TREE, 1000 bootstraps), and identified RBD position 498 as a positive selection hotspot — later validated by the Omicron Q498R mutation.

`SPAdes` `IQ-TREE` `MAFFT` `Snakemake` `Python` `dN/dS analysis` `Metagenomics`

---

## 💊 Pillar 3 — ML-Driven Cheminformatics & Drug Discovery

---

### Acetylcholinesterase Bioactivity Prediction
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Acetylcholinesterase-Bioactivity-Analysis)

End-to-end automated ML pipeline for pIC₅₀ prediction from ChEMBL bioactivity data. Random Forest regression model achieving **R² = 0.765**, fully automated via Snakemake + Conda.

`RDKit` `PaDEL` `ChEMBL API` `Random Forest` `Snakemake` `Conda` `QSAR`

---

### EGFR Kinase Bioactivity & CDK2 Inhibitor Classification
[![EGFR Repo](https://img.shields.io/badge/EGFR-Repo-blue)](https://github.com/Mayorcool-lab/ChEMBL-EGFR-Bioactivity-Data) [![CDK2 Repo](https://img.shields.io/badge/CDK2-Repo-blue)](https://github.com/Mayorcool-lab/CDK2-Bioactivity-Cheminformatics)

Curated and standardised kinase inhibitor datasets from ChEMBL; generated molecular fingerprints (SMILES, PaDEL) for ML bioactivity classification of EGFR and CDK2 inhibitors.

`ChEMBL API` `RDKit` `SMILES` `PaDEL` `Scikit-learn` `Molecular Fingerprints`

---

### COVID-19 Main Protease (MPro) Screening
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Covid-Mpro-ChEMBL)

Preprocessing and triage of 5,000+ MPro inhibitor candidates from ChEMBL for downstream ML-driven virtual screening.

`Pandas` `ChEMBL` `Python`

---

### Diabetes Risk Prediction
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Diabetes-Prediction-SVM)

Clinical data ML pipeline for patient risk stratification using SVM and Random Forest, achieving 76%+ accuracy with ROC validation.

`SVM` `Random Forest` `Scikit-learn` `Python`

---

## 📊 Pillar 4 — Data Analytics & Visualisation

*Skills applicable to bioinformatics analyst, clinical data, and healthcare analytics roles.*

---

### Healthcare SQL Analytics
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/healthcare-analytics-sql)

Clinical KPI analysis covering billing, CPT codes, and net collections using SQL Server and T-SQL. Designed to surface actionable utilisation metrics from healthcare data.

`SQL Server` `T-SQL` `Clinical KPIs` `Healthcare Analytics`

---

### Loan Default Risk Dashboard
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Loan-Default-Risk-Analysis-Powerbi)

Interactive Power BI dashboard for credit risk pattern assessment, combining SQL-based data preparation with visual analytics for data-driven lending decisions.

`SQL` `Power BI` `Credit Risk` `Interactive Dashboard`

---

### E-commerce Funnel & Conversion Analysis
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Ecommerce-Conversion-Analysis)

Customer conversion funnel analysis and segmentation analytics using Python and Power BI, delivering funnel optimisation insights.

`Python` `Power BI` `Segmentation` `Funnel Analysis`

---

### Workforce Layoffs SQL Analysis
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/SQL-Layoffs-Analysis)

Workforce trend analysis using MySQL with visualisations to identify patterns in global layoff data.

`MySQL` `SQL` `Data Visualisation`

---

## 📚 Publications

1. **Ogun OJ, Thaller G, Becker D.** Molecular Structural Analysis of the Porcine CMAH–Native Ligand Complex and High Throughput Virtual Screening to Identify Novel Inhibitors. *Pathogens* **2023**, 12(5), 684. [DOI](https://doi.org/10.3390/pathogens12050684)

2. **Ogun OJ, Soremekun OS, Thaller G, Becker D.** An In Silico Functional Analysis of Non-Synonymous SNPs of Bovine CMAH Gene and Potential Implication in Pathogenesis. *Pathogens* **2023**, 12(4), 591. [DOI](https://doi.org/10.3390/pathogens12040591)

3. **Ogun OJ, Thaller G, Becker D.** An Overview of the Importance and Value of Porcine Species in Sialic Acid Research. *Biology* **2022**, 11(6), 903. [DOI](https://doi.org/10.3390/biology11060903)

4. **Idowu PA, Mpofu TJ, Zishiri OT, Ogun OJ, et al.** Gene Sequencing and In Silico Characterisation of Mannose-Binding Lectin in South African Chicken Breeds. *J. Adv. Vet. Anim. Res.* **2025**, 12(3), 941. [DOI](https://doi.org/10.5455/javar.2025.l955)

5. **Ganapathymadam SK, Joshi A, Akhtar N, Ogun OJ, Kaushik V.** Antiviral Peptide Synthesis and Validation to Target Fish Nervous Necrosis Virus (NNV) Coat Protein. *AIP Conference Proceedings* **2023**, 2800(1), 020019.

---

## Technical Toolkit

```
Structural Biology       AlphaFold2 · ColabFold · Rosetta · TrRosetta · PyMOL · GalaxyWEB
Molecular Dynamics       GROMACS · RMSD · RMSF · Rg · SASA · MM/GBSA (50–200 ns)
Docking & Screening      AutoDock Vina · PyRx · SiteMap · MetaPocket · MCULE
Cheminformatics          RDKit · PaDEL · ChEMBL API · SMILES · SwissADME · ADME
Transcriptomics          Scanpy · Seurat · Harmony · DESeq2 · Monocle · CellTypist · Trinity
Metagenomics             SPAdes · Kraken · IQ-TREE · MAFFT · RAxML · BEAST · dN/dS
Population Genomics      PLINK · VCFtools · SIFT · PolyPhen · ConSurf · DynaMut · InterProScan
ML & AI                  Scikit-learn · XGBoost · Random Forest · QSAR · SHAP · TensorFlow (basic)
Data Analytics           SQL · Power BI · Excel · T-SQL · MySQL
Workflows                Python · R · Bash · Snakemake · Conda · Git · HPC/Linux · AWS
Visualisation            PyMOL · ggplot2 · Matplotlib · Seaborn · Plotly · Power BI · RMarkdown
```

---

## Open to Opportunities In

- 🔬 Computational glycobiology & glycoenzyme engineering
- 🧬 Antibody glycoengineering & Fc glycan structural modelling
- ⚙️ General bioinformatics pipeline development (transcriptomics, genomics, metagenomics)
- 💊 Structure-based drug discovery & enzyme inhibitor design
- 🤖 AI-enabled structural bioinformatics & protein design
- 🏭 Industrial enzyme engineering (biotech / pharma)
- 📊 Bioinformatics analyst & clinical/healthcare data analytics

---

📬 **Get in touch:** [LinkedIn](https://www.linkedin.com/in/oluwamayowaogun) &nbsp;|&nbsp; oluwamayowaogun@gmail.com

![Profile Views](https://komarev.com/ghpvc/?username=Mayorcool-lab&style=flat-square&color=blue)
