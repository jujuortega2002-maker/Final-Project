# Final-Project
Background:
The data consist of 6 samples from the organism Zaire ebolavirus. This organism is a negative-sense single-stranded RNA virus that causes severe hemorrhagic fever in humans and other primates. The virus belongs to the family Filoviridae and is known for causing outbreaks with high mortality rates.
According to Feldmann and Geisbert (2011), Ebola virus is transmitted through direct contact with infected bodily fluids and can spread rapidly during outbreaks. 
Citation:
Feldmann H, Geisbert T
Ebola haemorrhagic fever
The Lancet, 2010; 377, 849-862

Purpose:
The purpose of this project was to create a phylogenetic tree from 6 samples of Zaire ebolavirus in order to determine the evolutionary relationships between the samples.

Methods:
Next-generation sequencing (NGS) reads from 6 viral samples were assembled into contigs using MEGAHIT. The assembled contigs were imported into R and analyzed using the DECIPHER and Biostrings packages.
Sequences were aligned using the AlignSeqs function in DECIPHER, and the alignment was visualized using BrowseSeqs. A phylogenetic tree was generated using the maximum likelihood (ML) method with the Treeline function.
Because the assemblies did not produce contigs larger than 5000 bp, all contigs were included in the alignment and phylogenetic analysis.
(link for alignment html)
(link for R Script) 

Results:
[Phylogenetic Tree](phylogenetic_tree.png)
Samples 1 and 6 were the most closely related. Sample 2 and 3 also clustered together closely. Samples 4 and 5 formed a seperate branch from the other samples, suggesting they are more genetically distinct.
Based on the phylogenetic tree, the samples likely originated from approximately 3 different viral lineages or individuals. 
