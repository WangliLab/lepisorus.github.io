**CoExpNetViz: Comparative Co-expression Network Construction and Visualization Tool**

[Tzfadia et al. 2016](http://journal.frontiersin.org/article/10.3389/fpls.2015.01194/full)

I chose an easy one to read this week as I am mostly burdened with housework and child care owing to the absence of my husband at home.

I have been working on three data sets of RNAseq data on Populus and get familiar with the gene co-expression analyses. [WGCNA](https://labs.genetics.ucla.edu/horvath/CoexpressionNetwork/Rpackages/WGCNA/) was previously used in my work. As stated in the paper, compared to the existing softwares on co-expression analyses, its advantages lie in that it can generate multi-species co-expression network. The homologous genes among species will form one “family” node. This family means gene family, which could be from either  some web sources (such as [PLAZA](https://bioinformatics.psb.ugent.be/plaza/)) or self-defined. (PLAZA and CoExpNetViz are both from the bioinformatic group in Ghent University in Belgium). In this way, the co-expressed gene network is rather conserved across the species. The author also claimed that it is a way to find out the gene function in non-model species if compared the expression to that in model species.

This tool is especially helpful if we want to find the co-expressed genes with some candidate genes, which interest us, such as the sex-determination gene, the domestication gene and the drought-tolerant gene. They called the candidate genes as baits, using it to fish the co-expressed genes.

This tool may ease the co-expression analysis for researchers without bioinformatic background, as users can submit online jobs [here](http://bioinformatics.psb.ugent.be/webtools/coexpr/index.php).