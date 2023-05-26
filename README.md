# 2023 Oksuz and Henninger et al. TF-RNA

# About

This repository contains code related to the manuscript "Transcription factors interact with RNA to regulate genes" on bioRxiv (DOI: https://doi.org/10.1101/2022.09.27.509776).

## Contents
1.	**rna_curvefit.ipynb** - A notebook for fitting protein-RNA binding isotherms from fluorescence anisotropy data. Fits the fraction of bound RNA as a function of protein concentration at constant RNA concentration.  

2.	**curvefit_stats.ipynb** - A notebook for fitting protein-RNA binding isotherms from fluorescence anisotropy data for two samples, then conducting a two-tail Student's t-test for equivalence between the Kds.  

3.	**xcorr_proteome.ipynb** - A notebook for finding cross-correlation between the charge pattern of the HIV-1 Tat ARM and sequences in the proteome. This script is used to identify ARMS in TFs and proteome-wide based off of a user-defined threshold for the cross-correlation. 

4.	**orthodb.ipynb** - A notebook for finding the vertebrate orthologs of human TFs using the OrthoDB v10 interface. Returns a separate FASTA file for each ortholog.

5.	**shannon.ipynb** - A notebook for calculating the Shannon entropy (a metric for evolutionary conservation) of amino acid residues in TFs across all OrthoDB vertebrate orthologs. Compares the Shannon entropy of ARM sequences to the entropy of the remainder of the protein.
