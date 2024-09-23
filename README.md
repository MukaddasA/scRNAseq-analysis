

## Overview
This project investigates the potential use of two FDA-approved antibody therapies, Trastuzumab and Bevacizumab, in additional cancers by analyzing available single-cell RNA-seq (scRNA-seq) data from cancer cell lines.

The Key Scientific Question(KSQ): Using available scRNA-seq data from cancer cell lines, how would you explore the use of the following FDA-approved antibody therapies in additional cancers?

- **Trastuzumab**: Targets HER2 and is primarily used in treating HER2-positive breast and gastric cancers.
- **Bevacizumab**: Targets VEGF and is approved for use in a range of cancers, including colorectal, lung, glioblastoma, breast, liver, and kidney cancers.

## Breakdown of Key Scientific Question(KSQ)

### Cancer Cell Lines

#### What They Are and How They’re Used in Research
- **Cancer cell lines** are collections of cancer cells that can grow continuously in lab conditions. They originate from tumor samples and are cultured to study cancer biology, test potential therapies, and investigate genetic changes.
  
#### Limitations and Advantages of Using Cell Lines
- **Advantages**:
  - Easy to manipulate and study.
  - Provide a renewable source of cells for experiments.
  - Facilitate reproducible results across laboratories.
  
- **Limitations**:
  - May not fully represent the heterogeneity seen in actual tumors.
  - Can acquire additional mutations over time in culture.
  - Lack the complex tumor microenvironment present in vivo.

### scRNA-seq Data

#### What it is and How it Differs from Bulk RNA-seq
- **Single-cell RNA sequencing (scRNA-seq)** is a powerful tool used to study gene expression at the level of individual cells. This allows scientists to detect differences between cells in the same tissue or tumor, providing insights into cellular heterogeneity.
- **Bulk RNA-seq** captures the average gene expression of all cells in a sample, offering a broader view but potentially missing important cell-to-cell variability.

#### Processes Involved in scRNA-seq:
1. **Isolation of Single Cells**: Cells are isolated from a tissue or tumor sample.
2. **RNA Extraction and Sequencing**: The RNA of each cell is extracted, converted to cDNA, and sequenced.
3. **Data Analysis**: Gene expression is analyzed across the individual cells, allowing researchers to cluster cells, identify differentially expressed genes, and perform trajectory analysis to explore cell evolution.

#### How to Analyze and Interpret This Data
- **Clustering**: Grouping cells with similar gene expression profiles.
- **Differential Gene Expression**: Identifying genes that show different levels of expression between cell types or conditions.
- **Trajectory Analysis**: Tracking how cells change over time or in response to treatments.

#### Available Databases for Cancer Cell Line scRNA-seq Data
- **Cancer Cell Line Encyclopedia (CCLE)**: Offers scRNA-seq data for many cancer cell lines.
- **Human Cell Atlas**: Contains single-cell data from a variety of tissues, including cancerous samples.
- **Broad Institute Single Cell Portal**: A collection of single-cell datasets, including cancer-related data.

### Antibody Therapies

#### How They Work
- **Antibody therapies** are designed to target specific proteins found on cancer cells. These lab-engineered antibodies can:
  - Block growth signals.
  - Mark cells for immune system destruction.
  - Deliver toxic substances directly to cancer cells.

#### Why They’re Specific to Certain Cancers
- Cancer cells often express unique or overexpressed proteins (e.g., HER2 or VEGF) that distinguish them from normal cells. Antibody therapies are designed to target these specific proteins, minimizing damage to healthy cells.

#### Mechanism of Action for Trastuzumab and Bevacizumab
- **Trastuzumab (Herceptin)**: Targets HER2, which is overexpressed in certain breast and gastric cancers. Trastuzumab blocks signals that promote cancer cell growth and recruits the immune system to destroy these cells.
- **Bevacizumab (Avastin)**: Targets VEGF, a protein involved in angiogenesis (the formation of new blood vessels). By inhibiting VEGF, Bevacizumab cuts off the blood supply to tumors, starving them of nutrients.

### HER2 and VEGF

#### Their Roles in Cancer Biology
- **HER2**: A receptor that promotes cell division. Overexpression of HER2 is linked to aggressive growth in certain cancers, like breast and gastric cancers.
- **VEGF**: Plays a crucial role in angiogenesis, allowing tumors to develop the blood vessels needed for growth and metastasis.

#### Expression Patterns in Different Cancer Types
- **HER2**: Overexpressed in some breast, gastric, and other cancer types.
- **VEGF**: Upregulated in many solid tumors, such as colon, lung, and kidney cancers.

#### How Targeting These Proteins Affects Cancer Cells
- **HER2 Targeting (Trastuzumab)**: Blocking HER2 inhibits the signals that drive cancer cell growth, leading to cell death.
- **VEGF Targeting (Bevacizumab)**: Inhibiting VEGF prevents the formation of blood vessels, starving the tumor and slowing its growth.

## References
- Li, L., Xiong, F., Wang, Y. et al. (2021). Applications of single-cell RNA sequencing in cancer research: A systematic review. *J Exp Clin Cancer Res*, 40, 163. [https://doi.org/10.1186/s13046-021-01955-1](https://doi.org/10.1186/s13046-021-01955-1)
- Ren, L., Li, J., Wang, C. et al. (2021). Single-cell RNA sequencing for breast cancer: Present and future. *Cell Death Discov.*, 7, 104. [https://doi.org/10.1038/s41420-021-00485-1](https://doi.org/10.1038/s41420-021-00485-1)
- Hwang, B., Lee, J. H., & Bang, D. (2018). Single-cell RNA sequencing technologies and bioinformatics pipelines. *Exp Mol Med*, 50(8), 96. [https://doi.org/10.1038/s12276-018-0071-8](https://doi.org/10.1038/s12276-018-0071-8)
- Scott, A. M., Wolchok, J. D., & Old, L. J. (2012). Antibody therapy of cancer. *Nature Rev Cancer*, 12(4), 278-287. [https://doi.org/10.1038/nrc3236](https://doi.org/10.1038/nrc3236)
- Arteaga, C. L., & Engelman, J. A. (2014). ERBB receptors: From oncogene discovery to mechanism-based cancer therapeutics. *Cancer Cell*, 25(3), 282-303. [https://doi.org/10.1016/j.ccr.2014.02.025](https://doi.org/10.1016/j.ccr.2014.02.025)
- Barretina, J., et al. (2012). The Cancer Cell Line Encyclopedia enables predictive modeling of anticancer drug sensitivity. *Nature*, 483(7391), 603-607. [https://doi.org/10.1038/nature11003](https://doi.org/10.1038/nature11003)
- Maadi, H., Soheilifar, M. H., Choi, W. S., Moshtaghian, A., & Wang, Z. (2021). Trastuzumab mechanism of action; 20 years of research to unravel a dilemma. *Cancers*, 13(14), 3540. [https://doi.org/10.3390/cancers13143540](https://doi.org/10.3390/cancers13143540)
