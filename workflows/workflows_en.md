```
Title: Biofoundry Workflows
Description: Collection of standardized workflows for biofoundry operations
Version: 0.4.1
Language: English
Suggestions:
  - https://github.com/sblabkribb/biofoundry_workflows/issues
Last updated: 2025-08-15
Categories:
  - workflows
  - biofoundry
  - lab automation
```

# Workflows

## Design

- **WD010**: General Design of Experiment 
  - This workflow provides a general-purpose approach for experimental design using the Design of Experiment methodology. It allows for the independent design of variables from various domains to optimize experimental conditions.

- **WD020**: Adaptive Laboratory Evolution Design 
  - A top-down design approach utilizing random mutations and artificial evolution. This workflow may involve the use of UV radiation or environmental stress conditions to induce artificial sequence mutations, facilitating the evolution of desired traits.

- **WD030**: Growth Media Design 
  - This workflow focuses on designing growth media for strain culture, aiming to create optimal growth conditions based on data-driven experimental design. It includes the establishment of a growth media composition database for various organisms, strains, and experiments to enhance strain growth and productivity.

- **WD040**: Parallel Cell Culture/Fermentation Design
  - This workflow involves designing conditions for large-scale culturing of proteins, enzymes, or strain activity tests. In fermentation, the Design of Experiment is used to explore initial scale-up conditions for selected strains, optimizing parameters such as media, temperature, pH, expression levels, and aeration.

- **WD050**: DNA Oligomer Pool Design
  - This workflow is dedicated to designing an oligomer pool for assembling target DNA sequences, such as genes or pathways. The oligomers typically range from 50 to 300 base pairs in length, facilitating the construction of complex DNA structures.

- **WD060**: Genetic Circuit Design
  - This workflow involves designing genetic circuits for specific purposes, such as biosensors for metabolite detection or logic gate-based cell control. It utilizes part sequences stored in a part registry and includes predictive modeling using quantified DNA parts (e.g., Cello) or tools like the RBS calculator for prokaryotic systems.

- **WD070**: Vector Design
  - This workflow covers the design process for constructing DNA in the form of plasmid vectors, BACs, YACs, HACs, etc., ensuring the correct assembly and functionality of the vector for its intended application.

- **WD080**: Artificial Genome Design
  - This workflow involves a bottom-up or middle-level design approach for creating novel genomes, such as decompression or codon redesign. It leverages data on host metabolism, essential gene information, and gene/metabolic pathway databases to inform the design process.

- **WD090**: Genome Editing Design
  - This workflow focuses on CRISPR-based genome editing design, considering factors such as CRISPR types, host species, off-target effects, and the thermodynamics and folding of RNA tertiary structures. Dedicated software is used to design target gRNAs effectively.

- **WD100**: Protein Library Design
  - This workflow is aimed at designing libraries to optimize protein activity, specificity, and expression. It utilizes various tools (e.g., Alphafold, ProteinMPNN) to facilitate protein design, including the creation of random mutation libraries.

- **WD110**: De novo Protein/Enzyme Design
  - This workflow involves the de novo design of proteins or enzymes using deep learning tools like RFdiffusion, ProteinMPNN, Alphafold.  It includes the design of biocatalysts from scratch, leveraging advanced computational models.

- **WD120**: Retrosynthetic Pathway Design
  - This workflow uses design tools to identify pathways for desired metabolic reactions leading to product chemicals (e.g., RetroPath). It supports the de novo design of optimized pathways and allows for the discovery of novel pathways through retrosynthesis, including database searches for enzyme part selection (e.g., Selenzyme).

- **WD130**: Pathway Library Design
  - This workflow involves designing libraries to optimize protein function or metabolic pathways. It uses components stored in a pre-built DNA parts bank and can generate libraries for pathway expression optimization by incorporating promoters, RBS, terminators, and other regulatory elements.

## Build

- **WB005**: Nucleotide Quantification
  - This workflow quantifies nucleic acids (DNA, RNA, and oligonucleotides) and assesses purity using UV absorbance (A260/A280, A260/A230) and fluorometric dye-based assays with spectrophotometers or microplate readers. It can support 96/384-well plate formats for high-throughput normalization and quality control prior to downstream steps such as assembly, PCR, sequencing, and cloning.

- **WB010**: DNA Oligomer Assembly
  - This workflow focuses on assembling DNA oligomers into sequences that are several kilobases in length. The procedure typically begins with an oligomer pool and involves precise techniques to ensure accurate assembly of the desired DNA sequence.

- **WB020**: DNA Library Construction
  - This workflow involves creating designed DNA mutant libraries, metagenomic libraries, or pathway libraries. It includes methods such as combinatorial and random mutagenesis to generate diverse DNA libraries for various applications.

- **WB025**: Sequencing Library Preparation
  - This workflow prepares DNA or cDNA/RNA libraries for next-generation sequencing (NGS). Typical steps include fragmentation (or amplicon input), end-repair/A-tailing, adapter ligation, and barcoding/indexing (native barcode multiplexing), followed by cleanup, size selection, quantification, and normalization/pooling. It supports 96/384-well automation and outputs sequencing-ready, quality-controlled libraries for downstream NGS runs.

- **WB030**: DNA Assembly
  - This workflow is dedicated to assembling double-stranded DNA fragments into sequences that are several kilobases or larger. It includes the assembly of multiple DNA fragments, such as parts or operon-level sequences, in a specific order to achieve the desired genetic construct.

- **WB040**: DNA Purification
  - This workflow refines crude DNA extracts to achieve high purity suitable for downstream applications. It typically involves methods like column chromatography, magnetic beads, or precipitation to remove contaminants such as proteins, RNA, and salts.

- **WB045**: DNA Extraction
  - This workflow focuses on releasing DNA from biological samples (e.g., cultured cells, tissues) through lysis and initial separation from major cellular components like proteins and lipids.

- **WB050**: RNA Extraction
  - This workflow involves the isolation of RNA from biological samples, such as cells or tissues, to enable downstream applications like gene expression analysis, reverse transcription PCR (RT-PCR), or next-generation sequencing (NGS). It ensures the integrity and quality of the extracted RNA for accurate analysis.

- **WB060**: DNA Multiplexing
  - This workflow focuses on selecting cells grown on solid or liquid media and assigning arbitrary barcodes for identification. Amplified DNA with barcode primers is obtained from cultured cells, and the barcoded DNA is pooled for the next step of next-generation sequencing (NGS).

- **WB070**: Cell-free Mixture Preparation
  - This workflow involves preparing master solutions for cell-free reactions. It includes collecting and processing large-scale cultures of specific strains to create the cell extract for cell-free systems, encompassing stages such as cell lysis, purification, and separation.

- **WB080**: Cell-free Protein/Enzyme Expression
  - This workflow is dedicated to mixing target DNA with cell-free reaction reagents to produce quantities of proteins or enzymes under specific conditions suitable for high-throughput assays. It ensures efficient expression and activity of the target proteins or enzymes.

- **WB090**: Protein Purification
  - This workflow involves purifying target proteins or enzymes to high purity. It can be conducted using automated equipment capable of handling 96-well plates for high-throughput purification, ensuring the quality and functionality of the purified proteins.

- **WB100**: Growth Media Preparation and Sterilization
  - This workflow covers the large-scale production, sterilization, and aseptic storage of designed solid and liquid media. It includes sterilizing media and fermentation equipment to maintain sterility and prevent contamination.

- **WB110**: Competent Cell Construction
  - This workflow involves creating competent cells for transformation. It can be performed manually in bulk or using automated equipment to produce plate-based competent cells, ensuring high transformation efficiency.

- **WB120**: Biology-mediated DNA Transfers
  - This workflow focuses on transforming designed vector plasmids into cells. It includes 96/384-well plate-based automated or semi-automated transformation procedures, as well as conjugation or other DNA transfer protocols (e.g., phage-mediated).

- **WB125**: Colony Picking
  - This workflow isolates single bacterial colonies from solid media after transformation or screening and transfers them to liquid media or fresh plates using automated colony pickers or manual pipetting. It supports 96/384-well array formats, barcode/sample tracking, and rule- or image-based selection (e.g., size, color, fluorescence). Outputs are clonal cultures suitable for downstream verification (e.g., genotyping, sequencing) and protein expression analysis.

- **WB130**: Solid Media Cell Culture
  - This workflow involves culturing cells on solid media. It includes post-transformation growth, activity screening, or single-cell/colony isolation from solid medium, ensuring optimal growth conditions for the cultured cells.

- **WB140**: Liquid Media Cell Culture
  - This workflow covers growing cells in liquid media. It includes inoculum culture and subsequent batch culture processes in liquid medium, optimizing conditions for cell growth and productivity.

- **WB150**: PCR-based Target Amplification
  - This workflow utilizes designed primers and Polymerase Chain Reaction (PCR) to specifically amplify a target gene sequence from complex templates such as genomic DNA or metagenomic samples, enabling gene screening and retrieval.

## Test

- **WT010**: Nucleotide Sequencing
  - This workflow runs next-generation sequencing (NGS) instruments to generate raw data (e.g., fastq files) from sequencing-ready libraries. It covers flow cell/chip loading, run setup, on-instrument QC/monitoring, and data offloading/demultiplexing. Transcriptome-scale assays (e.g., RNA-seq) are executed here once libraries have been prepared in the dedicated library preparation workflow. For Sanger sequencing, this involves preparing DNA templates and primers, performing cycle sequencing reactions, and basecalling on capillary electrophoresis equipment to generate .ab1 chromatogram files. Typical applications include targeted gene/plasmid verification and small-scale sequencing; transcriptome-scale RNA sequencing is performed via NGS workflows (e.g., RNA-seq).

- **WT012**: Targeted mRNA Expression Measurement
  - This workflow measures specific transcript levels from RNA samples using targeted assays such as RT-qPCR, qPCR, and digital PCR (ddPCR). It supports absolute (standard curve/copy number) and relative (ΔΔCt) quantification with appropriate reference genes, and enables high-throughput measurements in 96/384-well plates with automated liquid handling. Outputs include per-gene expression levels, fold-changes across conditions, and QC metrics such as amplification efficiency and melt-curve specificity, complementing NGS-based transcriptome profiling.

- **WT015**: Nucleic Acid Size Verification
  - This workflow verifies the size and assesses the integrity of nucleic acid fragments (DNA or RNA) using electrophoretic separation techniques. Methods such as traditional agarose gel electrophoresis or capillary electrophoresis are employed to separate fragments based on size. Common applications include verifying PCR product sizes, confirming plasmid construction/linearization, checking restriction digest completeness, and assessing RNA quality. 

- **WT020**: Protein Expression Measurement
  - This workflow focuses on quantifying the expression levels of target proteins or enzymes. It includes measurements using techniques such as gel electrophoresis or automated capillary electrophoresis systems. High-throughput proteomics approaches like LC-MS can be integrated, allowing for detailed identification and quantification of protein expression and post-translational modifications.

- **WT030**: Protein/Enzyme Activity Measurement
  - This workflow is dedicated to measuring the activity of purified proteins or enzymes using general or specific methods (e.g., biosensors, chromatography, pNP assays). The method used is largely dependent on the specific protein or enzyme activity being analyzed, ensuring accurate and reliable results.

- **WT040**: Parallel Cell-free Protein/Enzyme Reaction
  - This workflow involves expressing and simultaneously measuring the activity of target proteins or enzymes in a cell-free reaction system under specific conditions. It allows for high-throughput screening and optimization of reaction conditions to enhance protein or enzyme performance.

- **WT045**: Mammalian Cell Cytotoxicity Assay
  - This workflow quantifies viability and cytotoxic effects in mammalian/eukaryotic cells induced by proteins, small molecules, or gene perturbations using colorimetric/fluorometric/luminescent assays (e.g., MTT/MTS/Resazurin, LDH release, ATP-based luminescence) and imaging-based markers (e.g., Annexin V/PI, caspase activity, live/dead staining). It supports endpoint or kinetic measurements in 96/384-well formats with appropriate positive/negative controls and normalization, reporting viability percentage, apoptosis/necrosis markers, and dose–response metrics such as IC50 with QC parameters (e.g., Z'-factor).

- **WT046**: Microbial Viability and Cytotoxicity Assay
  - This workflow measures growth inhibition and viability of microbial cells (e.g., bacteria, yeast) under treatment with compounds, proteins, or genetic perturbations. It includes OD600 growth curves/kinetics, broth microdilution for MIC/MBC determination, CFU enumeration, resazurin/ATP-based viability assays, membrane integrity dyes (e.g., PI/SYTOX), and time-kill/biofilm susceptibility when applicable. It supports 96/384-well high-throughput formats and automated liquid handling, reporting MIC/MBC, percent inhibition/viability, growth rate or area-under-the-curve, and dose–response parameters (e.g., IC50) with assay QC (e.g., Z'-factor).

- **WT050**: Sample Pretreatment
  - This workflow covers the separation and preprocessing of metabolites from cultured media using centrifugation, cell lysis, and cell removal steps before purification and analysis. It is applicable in processes such as proteomics, lipidomics, metabolomics, and transcriptomics, ensuring samples are prepared for accurate downstream analysis.

- **WT060**: Metabolite Measurement
  - This workflow focuses on quantifying metabolites using techniques such as GC-MS, LC-MS, and spectroscopy after high-throughput pretreatment. It includes fast measurement of single or complex components and unknown compound analysis, providing detailed metabolic profiles.

- **WT070**: High-throughput Single Metabolite Measurement
  - This workflow involves analyzing and measuring a single type of metabolite in a well-plate format using techniques like biosensors or other biochemical assays, such as high-throughput LC-MS. It enables rapid and efficient metabolite quantification in large sample sets.

- **WT080**: Image Analysis
  - This workflow is dedicated to analyzing cell growth, morphology, chromatin structure, organelle, and sub-cellular protein localization using high-throughput optical devices, such as microscopes. It includes sample preparation steps for imaging analysis, ensuring high-quality and reproducible results.

- **WT085**: Mycoplasma Contamination Test
  - This workflow screens mammalian cell cultures for mycoplasma contamination using rapid biochemical assays (e.g., ATP-based luminescence), targeted PCR/qPCR of mycoplasmal DNA, and culture-based confirmation when required. It supports routine high-throughput screening in 96/384-well formats with appropriate positive/negative controls, and reports qualitative/quantitative results with action thresholds for quarantine, decontamination, or discard prior to critical downstream experiments.

- **WT090**: High-speed Cell Sorting
  - This workflow involves sorting cells based on target metabolite or cell activity using genetic circuits that convert the activity into a detectable signal. It enables the isolation of specific cell populations for further analysis or experimentation.

- **WT100**: Micro-scale Parallel Cell Culture
  - This workflow covers culturing cells in 0.2 ml–1.5 ml 96 deep well plates. The process includes treatments to induce protein or cell activity, allowing for high-throughput screening and optimization of culture conditions.

- **WT110**: Micro-scale Parallel Cell Fermentation
  - This workflow involves performing fermentation in 0.8 ml–2.5 ml volumes while monitoring key parameters such as optical density (OD), pH, temperature, and dissolved oxygen (DO). It allows for precise control and optimization of fermentation conditions.

- **WT120**: Parallel Cell Fermentation
  - This workflow is dedicated to performing fermentation in 15 ml–250 ml volumes while monitoring key parameters in real-time, such as OD, pH, temperature, and DO. It supports the scale-up of fermentation processes and optimization of production conditions.

- **WT130**: Parallel Mammalian Cell Fermentation
  - This workflow involves culturing animal cells in 15 ml volumes to explore conditions for maximizing protein production. It includes real-time monitoring of key parameters such as OD, pH, temperature, and DO to ensure optimal growth and productivity.

- **WT140**: Lab-scale Fermentation
  - This workflow covers performing fermentations of less than 10L while monitoring key parameters such as pH, temperature, and dissolved oxygen (DO). It supports the development and optimization of fermentation processes at a laboratory scale.

- **WT150**: Pilot-scale Fermentation
  - This workflow involves performing fermentations between 10L and 500L while monitoring key parameters such as pH, temperature, and DO. It facilitates the transition from lab-scale to industrial-scale fermentation processes.

- **WT160**: Industrial-scale Fermentation
  - This workflow is dedicated to performing fermentations of more than 500L while monitoring key parameters such as pH, temperature, and DO. It supports large-scale production and optimization of fermentation processes for industrial applications.

## Learn 

- **WL010**: Sequence Variant Analysis
  - This workflow is designed for verifying the sequence of template DNA, including target genes, pathways, and plasmids. It is essential for activities such as gene cloning and assembly, and includes the comparison and analysis of sequence variants to ensure accuracy and integrity.

- **WL020**: Genome Resequencing Analysis
  - This workflow focuses on analyzing single nucleotide polymorphisms (SNPs) and other genome variations in organisms with reference genomes. It provides insights into genetic diversity and evolutionary relationships, aiding in the understanding of genomic changes.

- **WL030**: De novo Genome Analysis
  - This workflow involves analyzing the genome of new organisms without reference genomes. It includes de novo genome assembly from next-generation sequencing (NGS) data, enabling the discovery of novel genes and genomic structures.

- **WL040**: Metagenomic Analysis
  - This workflow is dedicated to analyzing large volumes of metagenomic sequence data. It includes raw data collection, gene and strain identification, and functional predictions. Machine learning or AI algorithms can be used to identify candidate enzymes from metagenomes, facilitating the exploration of microbial diversity and function.

- **WL050**: Transcriptome Analysis
  - This workflow focuses on analyzing transcriptomes (mRNA) from target organisms under different conditions. It includes mRNA sequence analysis and differential expression analysis (DEG), providing insights into gene expression patterns and regulatory mechanisms.

- **WL055**: Single Cell Analysis
  - This workflow focuses on analyzing individual cells to understand cellular heterogeneity and functional characteristics. It includes techniques such as single-cell RNA sequencing, single-cell ATAC-seq, and other omics approaches. The workflow supports the identification of rare cell populations, lineage tracing, and the study of cellular responses to various stimuli. Advanced data analysis tools and machine learning algorithms are employed to interpret complex single-cell data.

- **WL060**: Metabolic Pathway Optimization Model Development
  - This workflow involves analyzing measured metabolite data, including preprocessing and flux analysis. Specialized software can be used to develop machine learning and AI models using labeled data from metabolic pathway gene sequences and the corresponding metabolite products, optimizing metabolic pathways for desired outcomes.

- **WL070**: Phenotypic Data Analysis
  - This workflow covers the processing and analysis of phenotypic data, including growth rates, morphological traits, metabolic activity, and image-based phenotypic data. It integrates statistical analysis, image processing, and machine learning to extract quantitative features, identify patterns, and establish phenotype-genotype relationships.

- **WL080**: Protein/Enzyme Optimization Model Development
  - This workflow is aimed at developing models to optimize characteristics (such as activity, solubility) of target proteins by utilizing phenotypic and sequence data obtained from protein/enzyme expression and activity measurements. It includes protein structure and function analysis, leveraging pre-trained models or publicly available models (e.g., Alphafold2, Rosettafold, MPNN), and can be used for designing libraries of new functional proteins. Models include statistical, machine leanring, and AI models. 

- **WL090**: Fermentation Optimization Model Development
  - This workflow involves exploring optimal conditions for target compound production based on fermentation data for a given strain. It includes simulation models based on reaction formulas from the process, aiding in the optimization of fermentation conditions for enhanced production efficiency.

- **WL100**: Foundation Model Development
  - This workflow focuses on training foundation models using large sequence datasets such as protein databases or metagenomic coding sequences (CDS). It supports the development of robust models for various applications in bioinformatics and synthetic biology.
