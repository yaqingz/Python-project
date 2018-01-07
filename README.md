# Python-project
Study of gene mutation on DNA sequences data

BACKGROUND
Gene tests have been processed in all subjects in phase I trial. Portions of a gene have been sequenced for a group of subjects. These have been compared to a standard reference via BLAST to identify specific mutations (SNPs). The haploids appear as separate hits against the reference to see if differences are hetero- or homozygous (different or matching alleles). 
In the data file, each subjects were assigned a query name and reference sequence is following.

OBJECTIVE
The aim of this study is to identify a certain type of mutation in the DNA sequence of each subject and mark them. 

METHOD
There are 5 mutation position in searching list: T134A, G769C, A990C, G1051A and T1941A, and the gene data for each subject were collected from gene suquence test. The position of these mutations can be explained by its marks, for instance, for the mutation position T134A, the base group T in reference sequence at 134 position changed to A.
After identify the mutation for all subjects, the result will be output, marking the mutation as 0 (no difference from reference), 1 (heterozygous, suggesting mutation only appearing in one allele) and 2 (homozygous, suggesting mutation appearing in both alleles.
