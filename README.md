# High-Throughput-Analysis of Spinacia oleracea Genome
## Credits
This analysis was performed by Anne-Sophie Chys and Ruben Olbrechts as a part of a project of High Throughput analysis at the university of applied sciences Howest.

## Introduction
This repository contains the scripts and data used for analyzing the Spinacia oleracea genome. The SP75 Genome data was obtained from the SpinachBase, and the analysis was performed using the latest version of the bioinformatics software tools.

## Prerequisites
The following tools were used for this analysis:

* HISAT2 for genome alignment
* FeatureCounts for gene expression quantification
* MultiQC for quality control and report generation

## Data
The raw fastq files were first trimmed using Trimmomatic and the resulting files were then used for alignment and quantification.

## Scripts
The `scripts`directory contains the following scripts used for the analysis:

differential_expression_trimmed.sh:
differential_expression_untrimmed.sh:

## Results

## Usage
To reproduce the analysis, clone this repository and run the scripts in the following order:

1. `hisat2_alignment`: Align the reads to the SP75 genome.
2. `featurecounts_quantification`: Quantify the expression levels of the genes.
3. `multiqc_report`: Generate a report of the analysis results.

## References
* SpinachBase: https://spinachbase.org/  
* HISAT2: https://ccb.jhu.edu/software/hisat2/index.shtml  
* FeatureCounts: http://subread.sourceforge.net/  
* MultiQC: https://multiqc.info/
