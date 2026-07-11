# End-to-End NGS Data Analysis Pipeline

This project demonstrates a complete Next-Generation Sequencing (NGS) data analysis workflow, covering everything from raw data processing to variant identification.

### Workflow & Pipeline Steps
1. **Data Acquisition:** Obtained raw sequencing data (FastQ files).
2. **Initial Quality Control:** Performed quality analysis using **FastQC**.
3. **Data Trimming:** Used **Trimmomatic** to remove adapter sequences and low-quality bases.
4. **Post-Trimming QC:** Re-evaluated data quality to ensure clean reads.
5. **Alignment:** Mapped cleaned reads to the reference genome using alignment tools.
6. **Variant Calling:** Identified genetic variants using **bcftools**.
7. **Visualization:** Interpreted the final genomic data using **IGV (Integrative Genomics Viewer)**.

### Tools and Technology
* **Environment:** Linux (WSL)
* **Quality Control:** FastQC, Trimmomatic
* **Alignment/Processing:** Samtools
* **Variant Calling:** bcftools
* **Visualization:** IGV

### Conclusion
This project provides a comprehensive overview of how NGS data is processed in a bioinformatics pipeline. This pipeline establishes a robust methodology for analyzing genomic variations.
