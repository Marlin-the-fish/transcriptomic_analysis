Multi-Dataset DEG Analysis and Functional Enrichment

This repository contains R scripts and outputs for differential gene expression (DEG) analysis, functional enrichment, 
and protein-protein interaction (PPI) network analysis across multiple GEO datasets related to neural differentiation 
and neurodegeneration.

Datasets Analyzed

GEO ID     | Description                       | Comparison            
---------- | --------------------------------- | ----------------------
GSE27334   | P19.6 cell neural differentiation | Treated vs. Untreated
GSE68290   | iPSC-derived neurons              | ATRA 48h vs. EtOH    
GSE132903  | Human brain tissue (AD vs. ND)    | Alzheimer’s vs. Normal

Technical Achievements

- Performed differential expression analysis using limma
- Annotated probes to gene symbols and Entrez IDs
- Mapped overlapping DEGs across 3 datasets
- Conducted GO, KEGG, and DO enrichment analysis using clusterProfiler and DOSE
- Extracted genes from specific KEGG pathways
- Built STRING-based PPI networks and identified hub genes
- Visualized key sub-networks and gene connectivity

Key Resultsa

Top 10 Hub Genes (based on PPI degree):  
PLCG2, MAP2K1, GNAQ, GSK3B, FOXO1, MET, PLCB1, PIK3CB, PPP3CA, CCND1
