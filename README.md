# AEGIS
Analysis of Epistasis &amp; Genomic Interacting Sites

This archive contains the script used to detect epistasis as well as all the sequence alignments and corresponding trees described in the paper.

The R script to detect epistatic sites (aegis.R) has two sections: (1) detection of epistasis on the maximum likelihood (ML) tree and (2) detection of epistasis on the bootstrapped trees. The script assumes that both FastTree (http://meta.microbesonline.org/fasttree/) and BayesTraits (http://www.evolution.rdg.ac.uk/BayesTraits.html) are in your path.

The scripts used for simulations are located in the simulation sub-directory, which contains another README file with specific details.

The data analyzed in this study are located in the data sub-directory. The naming convention of the sequences alignments follows that used in the paper (see Materials and Methods). All alignments used are in the FASTA format. All trees except the one for the Koel13HA data set were estimated by FastTree (see Materials and Methods); these are unrooted trees, that are rooted by the R script (see Materials and Methods). We only conducted the bootstrap analyses for the Gong13NP data set, so that this data set includes both the ML and the bootstrapped trees. The XML file was used to generate the dated tree for the Koel13HA data set in BEAST. 
