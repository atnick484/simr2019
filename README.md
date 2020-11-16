PARTICIPANT: Andrew Nickerson

RESEARCH ADVISORS: Larry Kalesinskas, Purvesh Khatri, PhD

TITLE: Large-scale meta-analysis of chromatin immunoprecipitation-sequenced data to
exhibit histone modification relationships


Chromatin immunoprecipitation-sequencing (ChIP-Seq) is a method that allows
for the identification of histone modification regions. Sequenced reads contain tags that
denote the position of antibody markers, which provide peaks, or sites where histone
modifications occur. Large public datasets of ChIP-Seq data exist, provided by large
consortia such as ENCODE and Roadmap, which can be leveraged to understand both
the epigenetic and transcriptomic basis of disease and cell type. However, to date,
ChIP-Seq analysis has largely focused on single experiments and has yet to be
examined across experiments.

To have a more systems-level view of biology, we downloaded and processed
2000 ChIP-seq experiments, each of which contained peak data from a single histone
modification and cell type in humans. For each peak, we mapped the histone
modification to its nearest gene in hg19. We consolidated these data into a
well-designed and robust SQL database called ChIP-Map and generated figures for
quality control. Having ChIP-Seq data in a database allowed for quick filtering, querying,
subsetting, and the application of methods to understand ChIP-Seq data across
experiments. To highlight the utility of ChIP-Map, we examined multiple B-cell histone
modification experiments and found genes that are highly conserved across histone
modifications and genes that are unique to a particular histone modification, building
networks, heatmaps, and other figures to examine these relationships. By Venn
diagramming certain histone modifications that showed overlap in our heatmap, we
found that H3K4me3, H2AFZ, and H3K9ac were mapped near 197 of the same genes.
Pathway enrichment analysis revealed many of these genes are involved in mRNA
splicing, reaffirming the transcriptional involvement of histone modifications. In the
future, we would proceed further with network analysis to identify important
histone/gene/cell type relationships as well as develop a web app to allow others to
easily explore these data.
