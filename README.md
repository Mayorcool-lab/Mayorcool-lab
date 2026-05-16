# Dr. Oluwamayowa Joshua Ogun

**Computational Biologist · Reproducible Pipeline Engineering · Multi-Omics Analytics · Translational Science**

📍 Kiel, Germany &nbsp;|&nbsp; ✉️ oluwamayowaogun@gmail.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/oluwamayowaogun) &nbsp;|&nbsp; 🔗 [Google Scholar](https://scholar.google.com/citations?user=ZsF5IQ8AAAAJ&hl=en&authuser=2)

---

PhD-trained computational biologist specialising in **reproducible bioinformatics pipeline development** and **multi-omics data analysis** across metagenomics, single-cell and bulk transcriptomics, population genomics, and structural biology. I build scalable, automated, well-documented analytical workflows — from raw sequencing data to interpretable biological findings — and I understand the molecular biology behind every dataset I analyse.

My doctoral research at CAU Kiel characterised the **CMAH glyco-enzyme and Neu5Gc sialic acid metabolism** — connecting dietary glycan biology, gut microbiota-host interactions, and systemic immune regulation. This molecular foundation gives me a unique perspective on host-microbiome-immune system interactions that I bring to every translational analysis project.

I build workflows that are **reproducible by design** — config-driven architecture, Conda environment specifications, Snakemake DAG orchestration, version-controlled codebases, and validation documentation consistent with regulated research environments.

---

## Technical Skills

| Domain | Tools & Methods |
|--------|----------------|
| **Pipeline Engineering & Reproducibility** | Snakemake · Python · R · Bash · Git/GitHub · Conda · Linux/HPC · AWS (S3, PyAthena) · config-driven modular workflows · regulatory-grade documentation |
| **Metagenomics & Microbiome Analytics** | 16S amplicon analysis · WGS metagenomics · alpha/beta diversity · differential abundance · community profiling · functional annotation · SPAdes · Kraken2 · IQ-TREE · MAFFT · dN/dS analysis |
| **Single-Cell & Bulk Transcriptomics** | Scanpy · Seurat · Harmony · DESeq2 · CellTypist · Monocle · Trinity · scRNA-seq · bulk RNA-seq · pathway enrichment · TME deconvolution · pseudotime trajectory analysis |
| **Population Genomics & Variant Analysis** | GWAS · PLINK · VCFtools · GATK · snpEff · SIFT · PolyPhen · ConSurf · DynaMut · WGS variant calling · pathogenicity assessment |
| **ML & Statistical Analysis** | Random Forest · XGBoost · SVM · PCA · UMAP · SHAP · QSAR · pIC₅₀ prediction (R²=0.765) · patient risk stratification (76%+) · Scikit-learn · Pandas · NumPy |
| **Structural Glycobiology & Molecular Modelling** | AlphaFold2 · ColabFold · Rosetta · TrRosetta · PyMOL · GROMACS (50–200 ns MD simulations) · AutoDock Vina · MM/GBSA · active-site characterisation |
| **Data Visualisation & Communication** | Matplotlib · Seaborn · Plotly · ggplot2 · RMarkdown · Jupyter · PyMOL · publication-quality figures · stakeholder-facing report generation · ReportLab |

---

## Projects

---

### Microbiome Analytics Pipeline — Human Dietary Intervention RCT
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/ogunbiome-Insight-pipeline)

End-to-end Snakemake-orchestrated microbiome analytics pipeline applied to **Baxter et al. 2019** — a human randomised controlled trial of chicory-derived inulin supplementation in 174 healthy adults (16S rRNA amplicon sequencing, NCBI SRA: SRP128128).

**What the pipeline does:** Six analytical steps orchestrated as a Snakemake DAG — quality control and data validation, genus-level community composition analysis, differential abundance testing with volcano plot visualisation, expert biological interpretation, regulatory biomarker mapping against EFSA scientific opinions, and automated PDF report generation. Full DAG and VALIDATION.md included.

**Key findings:** Bifidobacterium (3.54x enrichment, adj.p=0.0022) and Anaerostipes (2.16x enrichment, adj.p=0.0001) identified as primary inulin responders — independently reproducing published findings and confirming the inulin → Bifidobacterium → acetate → Anaerostipes → butyrate cross-feeding cascade in vivo.

**Reproducibility standards:** Config-driven architecture (no hardcoding), Conda environment specification, Snakemake DAG for deterministic execution, VALIDATION.md documenting independent reproduction of published findings — principles consistent with translational and regulated research environments including pre-IND computational documentation standards.

`Python 3.11` `Snakemake` `pandas` `matplotlib` `scipy` `scikit-bio` `ReportLab` `16S amplicon` `RCT data` `EFSA regulatory mapping` `Conda` `Git`

---

### Bat Coronavirus Surveillance — WGS Metagenomics and Phylogenomics
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/bat-coronavirus-surveillance)

Complete whole genome shotgun — WGS — metagenomics-to-evolution workflow. Assembled a **26.6 kb SARS-CoV-2 genome** from bat metagenomic samples using SPAdes, performed taxonomic profiling (Kraken2), reconstructed sarbecovirus phylogeny (IQ-TREE, 1000 bootstraps), and conducted dN/dS positive selection analysis across the full spike protein.

**Key finding:** Identified receptor binding domain — RBD — position 498 as a positive selection hotspot. **This prediction was subsequently validated by the Omicron Q498R mutation** — demonstrating the predictive value of evolutionary metagenomics for pandemic surveillance.

**Transferable capability:** Full WGS metagenomics pipeline from raw sequencing data through genome assembly, taxonomic classification, phylogenetic reconstruction, and evolutionary analysis. Core computational skills directly applicable to clinical metagenomic surveillance, microbiome WGS profiling, and strain-level community analysis.

`SPAdes` `Kraken2` `IQ-TREE` `MAFFT` `RAxML` `BEAST` `Snakemake` `Python` `dN/dS selection analysis` `WGS metagenomics` `Phylogenomics`

---

### COVID-19 Lung Tissue — Single-Cell Immune Profiling
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Covid-scRNA-Analysis)

Automated Scanpy workflow for immune cell annotation using CellTypist, differential gene expression analysis, and pathway enrichment in COVID-19 lung tissue. Fully modular Snakemake pipeline — a reproducible Python-native alternative to R/Seurat for clinical single-cell datasets.

**Biological findings:** Characterised macrophage polarisation states, NK cell dysfunction, and T cell exhaustion signatures in severe COVID-19 lung tissue. Identified differentially expressed genes and enriched pathways in disease-associated immune populations.

**Clinical relevance:** Host transcriptomic response profiling directly applicable to clinical immunology datasets — cancer immunotherapy cohorts, transplant medicine, autoimmune disease — wherever immune cell state characterisation from single-cell sequencing data is required.

`Scanpy` `CellTypist` `DESeq2` `Snakemake` `Python` `scRNA-seq` `Immune cell annotation` `Pathway enrichment` `Differential expression`

---

### Breast Cancer Tumour Microenvironment — scRNA-seq TME Deconvolution
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/scRNA-Breast-Cancer-Analysis)

Seurat and Monocle pipeline for tumour microenvironment — TME — deconvolution and pseudotime trajectory analysis in breast cancer single-cell RNA-seq data. Identified immunosuppressive cell populations, exhausted T cell states, and novel immune evasion signatures within the TME.

**Biological findings:** Characterised cancer-associated fibroblast — CAF — heterogeneity, tumour-associated macrophage — TAM — polarisation, and regulatory T cell — Treg — enrichment as immunosuppressive mechanisms within the breast cancer TME. Pseudotime trajectory analysis revealed differentiation pathways of tumour-infiltrating lymphocytes — TILs.

**Transferable capability:** TME deconvolution methodology directly applicable to any solid tumour immunology context — renal cell carcinoma, melanoma, non-small cell lung cancer — wherever understanding the immune cell landscape within the tumour is clinically relevant.

`Seurat` `Monocle` `Harmony` `R` `scRNA-seq` `TME deconvolution` `Pseudotime trajectory` `TIL characterisation` `Immune evasion`

---

### CMAH Inhibitor Discovery — Structure-Based Drug Design
*Published · Pathogens 2023 · [DOI: 10.3390/pathogens12050684](https://doi.org/10.3390/pathogens12050684)*

**First structural characterisation of the porcine CMAH glyco-enzyme** — CMP-N-acetylneuraminic acid hydroxylase — the enzyme responsible for Neu5Gc sialic acid biosynthesis — using AlphaFold2 with GalaxyWEB structural refinement. High-throughput virtual screening of approximately five million compounds using MCULE, molecular docking with AutoDock Vina, and 200 ns GROMACS molecular dynamics simulations with MM/GBSA binding free energy estimation identified novel enzyme inhibitors targeting sialic acid biosynthesis.

**Structure quality:** Ramachandran plot 91.4% favoured. ProSA z-score -8.2. Both values confirming high-quality predicted structure.

**The molecular biology relevance:** Neu5Gc sialic acid sits at the molecular interface of dietary glycan metabolism, gut microbiota interactions, and systemic immune regulation. Gut bacteria expressing sialidases — enzymes that cleave sialic acids from mucosal glycoproteins — directly modulate the sialylation landscape of the gut epithelium, influencing Siglec inhibitory receptor signalling on T cells and NK cells. This connection between glycan biology and immune regulation informs my perspective on microbiome-immune axis research.

`AlphaFold2` `ColabFold` `GalaxyWEB` `AutoDock Vina` `GROMACS` `MM/GBSA` `PyMOL` `SwissADME` `Python` `Structure-based drug design` `Virtual screening`

---

### CMAH Variant Functional Analysis — Glyco-enzyme Pathogenicity Assessment
*Published · Pathogens 2023 · [DOI: 10.3390/pathogens12040591](https://doi.org/10.3390/pathogens12040591)*

Bovine CMAH structure predicted via Rosetta ab initio modelling — TrRosetta/Robetta. Five non-synonymous SNPs — single nucleotide polymorphisms — from the 1000 Bull Genomes Project introduced via PyMOL mutagenesis. Active sites characterised with SiteMap and MetaPocket. 50 ns GROMACS molecular dynamics simulations across wildtype and five mutant structures. **P424L identified as the most pathogenic variant** by consensus of five independent pathogenicity prediction tools — SIFT, PolyPhen, PROVEAN, PANTHER, SNPs&GO.

**Methodological contribution:** Developed a custom consensus analytical framework combining five independent pathogenicity prediction tools — going beyond any single existing tool to produce a more robust variant effect assessment. This approach of combining multiple independent methods into a consensus score is directly applicable to any computational variant interpretation problem.

**Key metrics:** RMSD — Root Mean Square Deviation — RMSF — Root Mean Square Fluctuation — Rg — Radius of Gyration — SASA — Solvent Accessible Surface Area — and H-bond profiles characterised across all six structures. Ramachandran plot 92.6% favoured. ProSA z-score -7.78.

`TrRosetta` `Robetta` `GalaxyWEB` `PyMOL` `GROMACS` `SiteMap` `MetaPocket` `DynaMut` `ConSurf` `SIFT` `PolyPhen` `Python`

---

### Automated ML Bioactivity Prediction Pipeline — Acetylcholinesterase
[![Repo](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/Mayorcool-lab/Acetylcholinesterase-Bioactivity-Analysis)

End-to-end automated machine learning pipeline for pIC₅₀ — negative log of the half-maximal inhibitory concentration — prediction from ChEMBL bioactivity data. Molecular fingerprints generated using RDKit and PaDEL — Pharmaceutical Data Exploration Laboratory — descriptor calculator. Random Forest regression model achieving **R² = 0.765**. Fully automated via Snakemake and Conda — reproducible from raw ChEMBL data to trained model and predictions without manual intervention.

**Methodological relevance:** Demonstrates custom script development beyond existing off-the-shelf tools — feature engineering, model training, validation, and automated reporting in a single reproducible pipeline. The QSAR — Quantitative Structure-Activity Relationship — framework is directly applicable to any biological activity prediction problem including drug-microbiome metabolite interactions and biomarker prediction from omics data.

`RDKit` `PaDEL` `ChEMBL API` `Random Forest` `Scikit-learn` `Snakemake` `Conda` `Python` `QSAR` `pIC₅₀ prediction` `ML pipeline`

---

### Population-Scale GWAS and Variant Analysis Pipeline
*Supporting Pathogens 2023 publications*

Automated whole genome sequencing — WGS — processing pipeline for variant calling and functional annotation across **2,724 whole genomes** from the 1000 Bull Genomes Project. Variant calling with GATK — Genome Analysis Toolkit — functional annotation with snpEff, and pathogenicity assessment using a custom consensus framework combining five independent tools — SIFT, PolyPhen, PROVEAN, PANTHER, SNPs&GO.

**Scale and reproducibility:** Processing 2,724 genomes requires pipeline automation that handles failures gracefully, processes samples in parallel, and produces consistent, documented outputs. Snakemake DAG orchestration enabled reproducible large-scale variant analysis without manual intervention at any step.

`GATK` `snpEff` `PLINK` `VCFtools` `SIFT` `PolyPhen` `ConSurf` `DynaMut` `InterProScan` `Bash` `Python` `Snakemake` `HPC`

---

## Publications

1. **Ogun OJ, Thaller G, Becker D.** Molecular Structural Analysis of the Porcine CMAH–Native Ligand Complex and High Throughput Virtual Screening to Identify Novel Inhibitors. *Pathogens* **2023**, 12(5), 684. [DOI](https://doi.org/10.3390/pathogens12050684)

2. **Ogun OJ, Soremekun OS, Thaller G, Becker D.** An In Silico Functional Analysis of Non-Synonymous SNPs of Bovine CMAH Gene and Potential Implication in Pathogenesis. *Pathogens* **2023**, 12(4), 591. [DOI](https://doi.org/10.3390/pathogens12040591)

3. **Ogun OJ, Thaller G, Becker D.** An Overview of the Importance and Value of Porcine Species in Sialic Acid Research. *Biology* **2022**, 11(6), 903. [DOI](https://doi.org/10.3390/biology11060903)

4. **Idowu PA, Mpofu TJ, Zishiri OT, Ogun OJ, et al.** Gene Sequencing and In Silico Characterisation of Mannose-Binding Lectin in South African Chicken Breeds. *J. Adv. Vet. Anim. Res.* **2025**, 12(3), 941. [DOI](https://doi.org/10.5455/javar.2025.l955)

5. **Ganapathymadam SK, Joshi A, Akhtar N, Ogun OJ, Kaushik V.** Antiviral Peptide Synthesis and Validation to Target Fish NNV Coat Protein. *AIP Conference Proceedings* **2023**, 2800(1), 020019.

---

## Technical Toolkit

| Category | Tools |
|----------|-------|
| Pipeline Engineering | Python · R · Bash · Snakemake · Conda · Git/GitHub · Linux/HPC · AWS (S3, PyAthena) |
| Metagenomics | SPAdes · Kraken2 · IQ-TREE · MAFFT · RAxML · BEAST · MetaPhlAn · dN/dS analysis |
| Transcriptomics | Scanpy · Seurat · Harmony · DESeq2 · Monocle · CellTypist · Trinity · scRNA-seq · bulk RNA-seq |
| Population Genomics | GATK · PLINK · VCFtools · snpEff · SIFT · PolyPhen · ConSurf · DynaMut · InterProScan |
| Structural Biology | AlphaFold2 · ColabFold · Rosetta · TrRosetta · PyMOL · GROMACS · AutoDock Vina · MM/GBSA |
| ML & Statistics | Scikit-learn · XGBoost · Random Forest · SVM · PCA · UMAP · SHAP · QSAR · TensorFlow (basic) |
| Visualisation | Matplotlib · Seaborn · Plotly · ggplot2 · RMarkdown · Jupyter · PyMOL · ReportLab |

---

## Open to Opportunities In

- ⚙️ Bioinformatics pipeline development — metagenomics, transcriptomics, multi-omics, population genomics
- 🦠 Microbiome therapeutics — computational analysis in translational and regulated environments
- 🎗️ Cancer computational biology — TME characterisation, immunogenomics, spatial transcriptomics
- 🔬 Computational glycobiology — sialic acid biology, glyco-enzyme biology, host-microbiome immune interactions
- 💊 Structure-based drug discovery and enzyme inhibitor design
- 🤖 AI-enabled bioinformatics — foundation models, ML for biological data, reproducible AI pipelines
- 📊 Translational multi-omics — clinical trial data analysis, biomarker discovery, regulated environments

---

📬 **Get in touch:** [LinkedIn](https://www.linkedin.com/in/oluwamayowaogun) &nbsp;|&nbsp; oluwamayowaogun@gmail.com

![Profile Views](https://komarev.com/ghpvc/?username=Mayorcool-lab&style=flat-square&color=blue)
