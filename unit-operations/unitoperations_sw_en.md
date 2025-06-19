```
title: Biofoundry Unit-operations
description: Collection of standardized Unit-operations
version: 0.2
language: English
suggestions:
  - https://github.com/sblabkribb/biofoundry_workflows/issues
date: 2025-02-22
categories:
  - unit-operations
  - biofoundry
  - lab automation
  - software
status: draft
```

# Unit-operations

## Software

- **US010**: DNA Oligomer Pool Design
  - **Software**: Dsembler, DNAWorks
  - **Description**: A software package that designs DNA oligomers which are pooled in a single tube. It optimizes the selection and combination of oligomers for efficient DNA assembly and synthesis.

- **US020**: Primer Design
  - **Software**: SnapGene, Primer3, OligoAnalyzer
  - **Description**: Designing primers regarding melting temperature and structure. The primers are used for mutant generation, PCR primers, and other molecular biology applications, ensuring specificity and efficiency in amplification.

- **US030**: Vector Design
  - **Software**: VectorNTI, SnapGene, Geneious
  - **Description**: Designing vector maps regarding inserts and a plasmid backbone. This might include primer design and DNA assembly processes, facilitating the construction of functional genetic vectors for cloning and expression.

- **US040**: Sequence Optimization
  - **Software**: GeneOptimizer, JCat
  - **Description**: Modifying codon usage of a DNA sequence to maximize protein expression in a specific host. This software ensures optimal translation efficiency and protein yield by adapting sequences to host-specific codon preferences.

- **US050**: Synthesis Screening
  - **Software**: UltraSEQ, Common Mechanism, FAST-NA
  - **Description**: Tools for screening potentially dangerous DNA sequences. These tools help ensure biosafety by identifying sequences that may pose risks in synthetic biology applications.

- **US060**: Structure-based Sequence Generation
  - **Software**: ProteinMPNN
  - **Description**: Generating sequences based on protein structures using AI models. This software aids in designing novel proteins with desired structural and functional properties.

- **US070**: Protein Structure Prediction
  - **Software**: Alphafold, Rosettafold, I-TASSER
  - **Description**: Predicting protein structures using AI models. These tools provide insights into protein folding and stability, supporting protein engineering and drug discovery efforts.

- **US080**: Protein Structure Generation
  - **Software**: RFdiffusion
  - **Description**: Generating protein structures using AI models. This software facilitates the design of new proteins and enzymes with specific catalytic or binding functions.

- **US090**: Retrosynthetic Pathway Design
  - **Software**: RetroPath2.0, ECREACT, BioNavi-NP
  - **Description**: To predict biosynthetic pathways using tools for checking reaction feasibilities and for novel pathway discovery. These tools support metabolic engineering by identifying efficient routes for chemical synthesis.

- **US100**: Enzyme Identification
  - **Software**: DeepEC, Selenzyme, SoluProt
  - **Description**: To search for enzymes from databases or to predict enzyme properties such as reactivities for selecting proper enzymes in pathways. This software aids in enzyme discovery and characterization for biocatalysis.

- **US110**: Sequence Alignment
  - **Software**: BLAST, MUSCLE
  - **Description**: Exploring and comparing sequence similarity using alignment algorithms. These tools are essential for identifying homologous sequences and understanding evolutionary relationships.

- **US120**: Sequence Trimming and Filtering
  - **Software**: Trimmomatic, Cutadapt, Porechop, Filtlong
  - **Description**: Preprocessing for removing low-quality long/short-read sequences. This step is crucial for ensuring data quality in sequencing projects.

- **US130**: Sequence Mapping and Alignment
  - **Software**: BWA, Bowtie2, Minimap2, GraphMap
  - **Description**: Mapping long/short-read sequences to reference sequences. These tools are used for genome assembly, variant calling, and transcriptomics.

- **US140**: Sequence Assembly
  - **Software**: Velvet, SOAP, Quast, Canu, Flye
  - **Description**: Assembling long/short-read sequences for complete gene, pathway, and chromosome. This software supports the reconstruction of genomes and metagenomes.


- **US145**: Metagenomic Assembly
  - **Software**: MetaSPAdes, MEGAHIT
  - **Description**: Assembling metagenomic data to reconstruct genomes from complex microbial communities. This software supports environmental and clinical metagenomics studies.


- **US150**: Sequence Quality Control
  - **Software**: FastQC, MultiQC, NanoPlot, pycoQC
  - **Description**: Performing quality control (QC) on long/short-read fastq and fast5 files. QC is essential for identifying and correcting errors in sequencing data.

- **US160**: Demultiplexing
  - **Software**: bcl-convert, Guppy
  - **Description**: Separating NGS reads based on native or user-defined barcodes. This process is critical for handling multiplexed sequencing data.

- **US170**: Variant Calling
  - **Software**: GATK, bcftools, Sniffles, Longshot
  - **Description**: Detecting variants based on read mapping. These tools are used for identifying SNPs, indels, and structural variants in genomic data.

- **US180**: RNA-Seq Analysis
  - **Software**: DESeq2/EdgeR (R), Galaxy, HISAT2
  - **Description**: Processing and analyzing transcriptomic data to quantify gene expression levels, identify splice variants, and detect differential gene expression. This software supports functional genomics studies.

- **US185**: Gene Set Enrichment Analysis
  - **Software**: GSEA, DAVID
  - **Description**: Analyzing gene expression data to identify enriched biological pathways. This software supports functional genomics and systems biology research.

- **US190**: Proteomics Data Analysis
  - **Software**: MaxQuant, Perseus, Proteome Discoverer
  - **Description**: Processing and interpreting data from mass spectrometry to identify and quantify proteins, understand modifications, and assess protein interactions. These tools are essential for proteomics research.

- **US200**: Phylogenetic Analysis
  - **Software**: MEGA, PhyML
  - **Description**: Determining the evolutionary relationships among species or sequences by constructing phylogenetic trees based on sequence similarities and differences. This software supports evolutionary biology studies.

- **US210**: Metabolic Flux Analysis
  - **Software**: COBRA Toolbox, FBA, CellNetAnalyzer
  - **Description**: Modeling and analyzing metabolic pathways, providing insights into cellular metabolism and pathway optimization. These tools are used for metabolic engineering and systems biology.

- **US220**: Deep Learning Data Preparation
  - **Software**: pytorch::DataLoader, Huggingface::datasets
  - **Description**: Preparing and batching datasets for AI model training and evaluation. This software supports machine learning workflows in bioinformatics.

- **US230**: Sequence Embedding
  - **Software**: ProtT5, ProtBERT, ESM
  - **Description**: Biological sequence embedding procedure. This process is used for transforming sequences into numerical representations for machine learning applications.

- **US240**: Deep Learning Model Training
  - **Software**: CNN, LSTM, Transformer, Bayesian opt.
  - **Description**: Model training procedure using training data. This software supports the development of AI models for various bioinformatics tasks.

- **US250**: Model Evaluation
  - **Software**: scikit-learn, TensorBoard
  - **Description**: Utilizing model evaluation metrics (accuracy, precision, recall, F1 score, etc.). This software is used for assessing the performance of machine learning models.

- **US260**: Hyperparameter Tuning
  - **Software**: Optuna, HyperOpt
  - **Description**: Efficiently exploring the search space using Bayesian optimization techniques. This software supports the optimization of machine learning models.

- **US270**: Model Deployment
  - **Software**: TorchScript, FastAPI
  - **Description**: Deploying trained models as services. This software supports the integration of AI models into production environments.

- **US280**: Monitoring and Reporting
  - **Software**: Prometheus, Grafana
  - **Description**: Monitoring and visualizing performance and resource usage of AI models. This software supports the maintenance and optimization of deployed models.

- **US290**: Phenotype Data Preprocessing
  - **Software**: R, Python
  - **Description**: Preprocessing measured and collected phenotype data. It involves cleaning, organizing, and transforming raw phenotype datasets for downstream analysis.

- **US300**: XCMS Analysis
  - **Software**: XCMS (R)
  - **Description**: Analyzing and visualizing chromatographically separated and single-spectra mass spectral data. This software supports metabolomics research.

- **US310**: Flow Cytometry Analysis
  - **Software**: flowcore, flowworkspace (R), flowJo
  - **Description**: Analyzing and visualizing flow cytometry data. This software supports immunology and cell biology research.

- **US320**: DNA Assembly Simulation
  - **Software**: pyDNA (python)
  - **Description**: Simulating DNA assembly such as Golden Gate and Gibson for increasing assembly success rate. This software supports synthetic biology and genetic engineering.


- **US325**: Gene Editing Simulation
  - **Software**: CRISPResso, CHOPCHOP
  - **Description**: Simulating gene editing outcomes using CRISPR technology. This software helps predict off-target effects and optimize guide RNA design for precise genome editing.


- **US330**: Well Plate Mapping
  - **Software**: Well plate mapping software
  - **Description**: Software for mapping well plate source plates to destination plates. This tool supports high-throughput screening and assay development.

- **US340**: Computation
  - **Software**: Computer
  - **Description**: A general process of data collection, preprocessing, and analysis steps. This software supports a wide range of bioinformatics and computational biology applications.