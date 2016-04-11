This is the first draft of TEA

# TEA: The Epigenomics analysis for Arabidopsis thaliana.

#### Abstract
#### Introduction/Background 

We proposed a workbench for plant methylation analysis. Genomic DNA is treated with sodium bisulfite to convert non-methylated cytosines to uracil while methylated cytosines remain unchanged. Coupled with high-throughput platforms such as microarrays or next generation sequencing (NGS) to allow massively parallel whole genome-wise methylation analysis.

#### Implementation: Ensembl Database Prepoccess step epimolas.jar-mtable

Gene annotation is downloaded from ensembl (release) and tair (http://www.arabidopsis.org) website. The procedure is here. Raw fastq data is first aligned to reference genome with Bismark, BS Seeker2 or other mapping tools. Those tools generate three methylation patterns (CG/CHG/CHH) on single base resolution with BAM intermediate files. Output format of two popular alignment program is supported, CGmap (BS Seeker2) and CX_report (Bismark). Methylation profile of each gene is generated through one Java utility (EpiMolas.jar), the file is then uploaded to TEA for whole genome bisulfite sequencing (WGBS) analysis. 

#### Results: Interpretation


#### Browse: Full-text Search, Ensembl gene annotation 

Gene profile is available. <check gdetail.php and detail.php>

#### Analysis: DMGs, mC threshold, Gene list enrichment analysis (GO, KEGG) 

* DMGs

Differentially methylated genes (DMGs) is select and filtered

? statistical testing

* mC threshold

* gene list enrichment

#### Visulization: Venn Diagram, Heatmap, KEGG Pathway, Circos plot, BioDalliance Browser, boxplot


#### Discussion


#### Comparison table: Arabidopsis Information Resource, Ensembl Plant, Galaxy, other analysis pipeline


#### Conclusion A Resource for WGBS, RRBS annotation and analysis


#### Suppl. Methods

