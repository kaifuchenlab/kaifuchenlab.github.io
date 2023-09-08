---
title: research
nav:
  order: 3
  tooltip: Research description
---

# <i class="fas fa-microscope"></i>Research Summary

**We are a bioinformatics lab developing computation technology to model how cell identity is established during development and dysregulated in diseases.** We develop bioinformatics methods to understand genetic, epigenetic, and molecular signaling mechanisms in cell identity regulation. Different cell types in a healthy body share the same genetic sequence. Difference in identity of these cell types is determined by epigenetic regulation of gene expression, which represent an interaction between the genetic factor and signaling molecules in the cell. Genetic mutations and abnormal signals can lead to epigenetic dysregulation and cause cell identity dysregulation in diseases.

{%
  include figure.html
  image="images/Cell_Identity.png"
  width="60%"
  height="60%"
%}

**Major research approach in the lab:**

- Develop new bioinformatics techniques to analyze high throughput genomic, epigenomic, transcriptomic, and metabolomic data. 

- Single cell, spatial genomics, Hi-C, ChIP-seq, ATAC-seq, RNA-seq and other additional techniques to study epigenetic regulation of transcription by 3D chromatin conformation, chromatin modifications, and chromatin-binding proteins.

- High throughput profiling of RNA methylation, RNA binding proteins, and ribosomes to study post transcriptional regulation of gene expression.

- Collaborate with wet-bench labs for molecular, cellular, animal, and clinical investigations to understand mechanisms in diseases.

**Research in our lab is continuously focused on one biological insight: the regulation of cell identity genes displays a greater complexity when compared to many other genes, such as housekeeping genes.** Our computational modeling revealed that the statistical distribution of the breadth of H3K4me3 modification on chromatin follows a bimodal pattern (Nature Genetics, 2015). The cell identity genes in a cell tend to show a broad H3K4me3 pattern (broad but low-density), covering both promoter and gene body region . For instance, the CD4 locus shows broad H3K4me3 in CD4+ T cells. In contrast, the majority (~95%) of expressed genes, such as housekeeping genes, show a sharp H3K4me3 pattern (narrow but high-density) in the promoter only. This observation echoes several reports by other laboratories, e.g., reports regarding H3k4me3 breadth by the Brunet lab (Cell, 2014) and super-enhancer by the Young Lab (Cell, 2013). We further observed that cell identity genes tend be regulated by a subset of super-enhancers marked by the binding of CTCF (GPB, 2021), and display a low RNA stability mediated by co-transcriptional RNA m6A modification (Nucleic Acids Research, 2023). These findings together demonstrated that cell identity genes undergo a faster expression turnover, which includes both frequent transcription and frequent mRNA decay when compared to the other genes expressed at the level like cell identity genes. We thus developed CEFCIG, an artificial intelligent technology to uncover cell identity genes based on the greater complexity of their expression regulation(Nature Communications, 2020). The research in this direction is of broad significance to a wide spectrum of research communities, as it addresses the most pressing constraints and fundamental aspects of technologies for cell identity conversion and removes critical barriers impeding the development of cell therapy. As a proof of principle, our application of this new technology to endothelial cells has revealed MECOM as an endothelial cell lineage regulator (Nature Communications, 2020; Nature Communications, 2023). 

{%
  include figure.html
  image="images/CIG.png"
  width="100%"
  height="100%"
%}

**Our findings are providing the rationale to target the regulation complexity of cell identity genes in diseases associated with cell identity dysregulation.** The greater complexity for expression regulation at cell identity genes renders extra sensitivity of these genes to manipulation of the associated molecular mechanism. For instance, when we knock out the H3K4me3 methyltransferase MLL4, the genes marked with broad H3K4me3 appeared more vulnerable when compared to genes marked with sharp H3K4me3, leading to tumorigenesis and thus loss of the normal cell identity (Molecular Cell, 2018). Also, as the lower RNA stability of cell identity genes is mediated by the extra sensitivity of these genes to the RNA m6A modification catalyzed by METTL3, knockdown of METTL3 posed a stronger effect on RNA stability of cell identity genes when compared to the rest of genes (NAR, 2023). As MLL4 and METTL3 might also modify many other expressed genes, a crucial risk in theory to target these enzymes was a potentially broad side effect. Our findings suggest that targeting MLL4 and METTL3 with a moderate dosage might have a preferential effect on cell identity genes and ignorable effect on the rest of the genes, providing a strong rationale to target them in diseases associated with cell identity dysregulation.


