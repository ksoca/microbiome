# microbiome
Project Title: Full 16S rRNA gene microbiome for Ixodes ticks

Project Description: 
This repository is for full 16S gene microbiome analysis.

The microbiome is a snapshot of the full microbial composition of any tissue or organims. To date, most microbiome projects rely on select variable regions within the 16S rRNA gene. While this is useful for determining what genus, and at times species, of bacteria you may have, it can be challenging for identificaiton of numerous bacteria with highly similar sequences. In this work, we have sequenced and analyzed the full 16S rRNA microbiome of Ixodes pacificus. This species is a rising vector within tick-borne diseases and it is unknown the full complement of bacterial pathogens that can be transmitted. 

Credit: Josh P. Earl for his mentorship (jpearl01)

Citation: Socarras KM, Earl JP, Krol JE, Bhat A, Pabilonia M, Harrison MH, Lang SP, Sen B, Ahmed A, Hester M, Mell JC, Vandegrift K, Ehrlich GD. Species-Level Profiling of Ixodes pacificus Bacterial Microbiomes Reveals High Variability Across Short Spatial Scales at Different Taxonomic Resolutions. Genet Test Mol Biomarkers. 2021 Aug;25(8):551-562. doi: 10.1089/gtmb.2021.0088. PMID: 34406842; PMCID: PMC8575062.

For this project, assembly of the data required used of the MCSMRT pipeline (https://github.com/jpearl01/mcsmrt)

Afterwards, all analysis is done using R. The following files within this repository is for 16S rRNA gene microbiome analysis.

Dependencies: 
R v.3.6.3
R Studio
vegan v2.5
Pheatmap 1.0.12
ggplot2 v3.3.4

Data Prerequisites:
Microbiome data should be assembled prior to use of these RMD files. Preparation of microbiome data can be done here (https://github.com/jpearl01/mcsmrt)

Getting Started:
