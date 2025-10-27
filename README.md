# Single-nucleus RNA Sequencing Analysis

## Research Objectives

This analysis aimed to address two key questions using single-nucleus RNA sequencing data:

### 1. Identify and Characterize Target Subpopulation

**Goal**: Identify the neuronal subpopulation co-expressing four specific marker genes and characterize its properties.

**Target Marker Genes**:
- GABRQ 
- ADRA1A 
- FEZF2 
- VAT1L 

**Characterization metrics**:
- Cell number and proportion
- Correlation with other clusters
- Expression patterns and distribution

### 2. Identify Enriched Genes in Target Subpopulation

**Goal**: Determine which genes are significantly upregulated in the identified subpopulation compared to other cells.

**Method**: Pseudobulk differential expression analysis

---

## Analysis Performed

### Data Processing
- Loaded Seurat object containing 35,309 cells and 36,503 genes
- Converted data from RDS format to Matrix Market format for downstream analysis
- Extracted count matrix, gene annotations, and cell metadata

### Subpopulation Analysis
- Identified cells co-expressing GABRQ, ADRA1A, FEZF2, and VAT1L
- Quantified the number and proportion of target cells
- Analyzed expression patterns of marker genes across the dataset
- Assessed correlations between the target subpopulation and other cell clusters

### Differential Expression Analysis
- Performed pseudobulk aggregation for the target subpopulation
- Conducted statistical testing to identify upregulated genes
- Applied multiple testing correction for robust gene identification

---

## Results

### Subpopulation Characteristics

**[Results to be filled based on analysis outputs]**

- **Cell Count**: [N cells]
- **Proportion**: [X%] of total dataset
- **Marker Expression**: [Description of co-expression patterns]
- **Cluster Relationships**: [Correlation with other cell types]

### Enriched Genes

**[Results to be filled based on differential expression analysis]**

**Top Upregulated Genes**:
- [Gene 1]: [fold change, p-value]
- [Gene 2]: [fold change, p-value]
- [Gene 3]: [fold change, p-value]
- [...]

**Functional Interpretation**:
- [Biological pathways enriched]
- [Potential functional roles]
- [Relationship to known neuronal subtypes]


