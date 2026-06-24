# Hi, I'm Szonja 👋

I'm an MSc Bioinformatics graduate (Wageningen University & Research) showcasing my hands-on portfolio of computational biology, data science, and AI projects. I work with real biological datasets to solve problems in genomics, structural biology, and drug discovery, and apply the same analytical rigor to data science and analytics projects in the food, nutrition, and sustainability space, building on hands-on experience from a data analytics internship in an R&D team setting at FrieslandCampina.

---

## 🧬 Bioinformatics Projects

| # | Project | What it proves |
|---|---------|---------------|
| 1 | [Differential Gene Expression Analysis](https://github.com/Szonja-L/Differential-Gene-Expression-Analysis) | Transcriptomics · NCBI GEO data access (GEOparse) · Welch's t-test · Benjamini–Hochberg FDR correction · Volcano plots, clustered heatmaps & PCA · Biomarker boxplots · Biological interpretation (proliferation, EMT, hormone-receptor & apoptosis signalling) |
| 2 | [Protein Structure Visualisation](https://github.com/Szonja-L/Protein-Structure-Visualisation) | Structural biology · PDB file parsing (BioPython `PDBParser`/`PDBIO`/`Select`) · RCSB REST API · 3D coordinate/distance geometry (NumPy) · Active-site mapping & residue polarity annotation · PyMOL scripting & ray-traced rendering · py3Dmol interactive 3D visualisation |
| 3 | [SNP & Variant Identification](https://github.com/Szonja-L/SNP-and-Variant-Identification) | Whole-genome sequencing analysis · NGS quality control (FastQC, Trimmomatic) · Reference genome alignment (BWA-MEM) · BAM processing (SAMtools sort/markdup/flagstat) · Bayesian variant calling (FreeBayes) · VCF filtering & functional annotation (SnpEff) · Antimicrobial-resistance genomics (CARD/ResFinder, QRDR mutations, efflux mechanisms) · Galaxy workflow design |
| 4 | [Basic Molecular Docking](https://github.com/Szonja-L/Basic-Molecular-Docking) | Computer-Aided Drug Discovery (CADD) · Receptor/ligand preparation (MGLTools, OpenBabel, Gasteiger charges) · AutoDock Vina docking & grid-box setup · Binding affinity (ΔG, Ki) interpretation · Drug-likeness profiling (Lipinski/Veber rules) · Structure–activity relationships (covalent vs. reversible inhibition, resistance mutations) |
| 5 | [Automated Sequence Retrieval](https://github.com/Szonja-L/Automated-Sequence-Retrieval-Python) | Bioinformatics data engineering · Biopython Entrez API (`esearch`/`efetch`) · Rate-limit-compliant batch downloading · Retry logic with exponential back-off · FASTA I/O (`SeqIO`) · Sequence metadata extraction (GC%, organism, length) · CLI design (`argparse`) · Logging & pipeline automation |
| 6 | [Multi-Omics Integration (TCGA-GBM)](https://github.com/Szonja-L/Multi-Omics-Integration) | Multi-omics data integration (MOFA+/mofapy2) · Latent factor analysis across expression, methylation & mutation data · Survival analysis (Kaplan–Meier, log-rank tests, Cox proportional hazards via lifelines) · Early/late fusion benchmarking · UMAP dimensionality reduction · Concordance-index (C-index) model evaluation |
| 7 | [PAM50 Classification & Survival Analysis](https://github.com/Szonja-L/ML-survival-analysis) | Clinical bioinformatics · ML classification (XGBoost, Random Forest) with 5-fold cross-validation · SHAP interpretability (TreeExplainer, global & per-class importance) · Survival analysis (Kaplan–Meier, Cox PH, Harrell's C-statistic) · Feature engineering (proliferation & ER-pathway gene scores) · Confusion matrices & multi-class ROC-AUC |

---

## 📊 Data Science & AI Projects

| # | Project | What it proves |
|---|---------|---------------|
| 1 | [Food Sustainability Dashboard](https://github.com/Szonja-L/Food-Sustainability-Dashboard) | Interactive dashboard development (Streamlit: multi-tab layout, session state, `st.cache_data`) · Plotly visualisation (bubble, bar & pie charts, custom hover templates) · pandas data wrangling & groupby aggregation · Data storytelling (real-world benchmarks, normalised comparisons) · Cloud deployment (Streamlit Cloud CI/CD from GitHub) |
| 2 | [End-to-End ML Pipeline with Nutritional Scoring](https://github.com/Szonja-L/End-to-end-ML-pipeline-with-nutritional-scoring) | Full ML pipeline design · Dimensionality reduction (PCA, scaling/standardisation) · Unsupervised clustering (K-means, silhouette-score model selection) · Supervised classification (Random Forest vs. logistic-regression baseline, macro-F1 optimised grid search) · Feature engineering (ratio & energy-density features) · Real-world data cleaning (unit-confusion outliers, deduplication, missingness handling) · Interactive Streamlit deployment |

*More in progress — NHANES dietary pattern clustering, food review sentiment analysis (NLP), and a RAG-based nutrition knowledge assistant are next on the roadmap.*

---

## 🎓 Thesis & Internship Portfolio

| Project | Context | What it proves |
|---------|---------|---------------|
| [Phylogenomic Evolution of Photosynthesis-Related Genes](https://github.com/Szonja-L/Phylogenomic-photosynthesis-evolution) | MSc Thesis · Plant Breeding & Biosystematics, Wageningen University & Research | Comparative & phylogenomic genome analysis across 322 angiosperm genomes · Sequence homology search & database construction (NCBI BLAST+, `blastp`) · PFAM domain validation (HMMER) · Copy-number variation analysis & statistical visualisation (R) · Synteny network construction & community detection (MCScanX, Cytoscape, MCL clustering) · Large-scale HPC computation (SLURM job submission) |
| [Nutrient Monitoring & QC Dashboard](https://github.com/Szonja-L/Nutrient-monitoring-qc-dashboard) | Data Analytics Internship, FrieslandCampina (R&D Quality Assurance) | Data harmonisation across inconsistent real-world datasets · Star-schema data modelling for BI tools · Statistical quality control (RSD%, recovery %, standard & modified Z-score outlier detection) · Time-series analysis (rolling averages, month-over-month change, regression trend analysis) · Power BI dashboard design (DAX measures, Power Query/M) · Stakeholder-facing communication, including limitations *(sanitized case study — no proprietary data)* |

---

## 🛠️ Tools & Technologies

**Languages & core libraries:** `Python` `R` `pandas` `NumPy` `SciPy` `scikit-learn` `Jupyter`

**Genomics & sequencing:** `Biopython` `NCBI Entrez/GEO` `GEOparse` `FastQC` `Trimmomatic` `BWA-MEM` `SAMtools` `FreeBayes` `SnpEff` `Galaxy (usegalaxy.eu)`

**Structural biology & drug discovery:** `RCSB PDB` `PyMOL` `py3Dmol` `AutoDock Vina` `MGLTools` `OpenBabel`

**Comparative genomics & multi-omics:** `NCBI BLAST+` `HMMER` `MCScanX` `Cytoscape` `MOFA+ (mofapy2)` `SLURM / HPC`

**Machine learning & statistics:** `XGBoost` `Random Forest` `SHAP` `lifelines (Kaplan-Meier, Cox PH)` `PCA` `K-means`

**Data viz & dashboards:** `Streamlit` `Plotly` `matplotlib` `seaborn` `Power BI` `DAX` `Power Query (M)`

**Tooling:** `Git` `GitHub Actions / Streamlit Cloud CI-CD`

---

## 📫 Connect with me

[LinkedIn](https://www.linkedin.com/in/szonjalippert/)
