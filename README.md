# Hemalatha Ponnam
### Bioinformatics · Research Computing · HPC Automation · Scientific Python

I build **reproducible biological-data workflows** and **reliable scientific software**, from public RNA-seq analyses and machine-learning pipelines to Linux/HPC automation, testing, and monitoring.

**M.S. Bioinformatics & Computational Biology — Saint Louis University (2026)**  
**Current:** HPC Engineering Intern, Washington University in St. Louis (Aug 2026–present)

## Selected work

| Project | Evidence and impact | Stack |
| --- | --- | --- |
| [NAFLD RNA-seq transcriptomics](https://github.com/Hemalatha18-bio/nafld-rnaseq-transcriptomics) | Reproducible analysis of **216 public liver samples** (GSE135251); DESeq2 fibrosis comparison identified **551 genes** at FDR < 0.05 and `|log2FC| ≥ 1` | R, DESeq2, Python, GO enrichment, Snakemake, CI |
| [Research Computing DevOps Lab](https://github.com/Hemalatha18-bio/research-computing-devops) | Sanitized examples of compute-node automation, health checks, structured metrics, dashboard design and incident runbooks | Ansible, Bash, Linux, Python, pytest, GitHub Actions |
| [FASTQ Interleaving CLI](https://github.com/Hemalatha18-bio/fastq-interleaving-cli) | Usable paired-end FASTQ CLI with gzip support, mate validation, failure-safe cleanup, sample data and automated tests | Python, Biopython, pytest, CI |
| [Colorectal Cancer Metagenomics](https://github.com/Hemalatha18-bio/colorectal-cancer-metagenomics-pipeline) | Executable downstream abundance-table demo with FDR-controlled tests and leakage-aware ML; example results are **not** clinical findings | Python, SciPy, scikit-learn, Snakemake, SLURM |
| [Alzheimer's Gene Prediction ML](https://github.com/Hemalatha18-bio/alzheimers-gene-prediction-ml) | Reproducible *example-data* model comparison, repeated cross-validation, preprocessing within folds and explainability | Python, scikit-learn, XGBoost, SHAP, CI |
| [DIA-PASEF Proteomics Analysis](https://github.com/Hemalatha18-bio/dia-pasef-proteomics-analysis) | Reproducible downstream DIA-NN-style QC and Q-value reporting demonstration | Python, proteomics QC, Snakemake, SLURM |

### Public-data result snapshot

[![NAFLD RNA-seq differential expression volcano plot](https://raw.githubusercontent.com/Hemalatha18-bio/nafld-rnaseq-transcriptomics/main/figures/snapshot/volcano_deseq2.png)](https://github.com/Hemalatha18-bio/nafld-rnaseq-transcriptomics)

*F3–F4 vs F0–F1 fibrosis contrast, based on public GEO GSE135251 processed counts. This is observational research, not a clinical test.*

## Technical toolkit

- **Bioinformatics:** RNA-seq, NGS/FASTQ, gene expression, metagenomics, proteomics QC, FDR-aware analysis
- **Programming & analysis:** Python, R, pandas, NumPy, SciPy, scikit-learn, XGBoost, SHAP
- **HPC & automation:** Linux, Bash, SLURM, Ansible, Docker, Snakemake
- **Software quality:** Git/GitHub, pytest, GitHub Actions, input validation, reproducibility, documentation
- **Monitoring & operations:** Datadog dashboard concepts, infrastructure health checks, troubleshooting runbooks

## What I work on

At WashU IT, my focus includes translating repeatable procedures into Ansible-based automation, supporting Datadog monitoring and operational documentation, and troubleshooting research-computing workflows. **Employer-specific infrastructure, credentials, and configurations are not published here.**

My portfolio deliberately distinguishes **verified real-public-data results** from **small synthetic/example-data software demos**. See each repository's README for its execution steps, evidence, and limitations.

## Publication

Co-author, *Isolation of Peroxidase Enzyme from Various Vegetables and Coupling to IgG*. **Nepal Journal of Science and Technology**, 22(1), 144–153.

## Explore

- [Browse all repositories](https://github.com/Hemalatha18-bio?tab=repositories)
- [Start with the reproducible NAFLD analysis](https://github.com/Hemalatha18-bio/nafld-rnaseq-transcriptomics)
- [Explore the research-computing lab](https://github.com/Hemalatha18-bio/research-computing-devops)
