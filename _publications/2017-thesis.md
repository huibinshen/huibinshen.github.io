---
title: "Machine Learning for Small Molecule Identification"
collection: publications
permalink: /publication/2017-thesis
date: 2017-03-30
venue: 'Aalto University publication series DOCTORAL DISSERTATIONS, 25/2017'
paperurl: 'https://aaltodoc.aalto.fi/handle/123456789/24783'
citation: 'Huibin Shen (2017). &quot;Machine Learning for Small Molecule Identification&quot; <i>Aalto University publication series DOCTORAL DISSERTATIONS, 25/2017</i>'
---


Link: [[pdf]](https://aaltodoc.aalto.fi/bitstream/handle/123456789/24783/isbn9789526072920.pdf?sequence=1&isAllowed=y) 


## Abstract

Metabolites are small molecules involved in biological process of organisms. For example, ethylene serves as plants hormone to stimulate or regulate the opening of flowers, ripening of fruit and shedding of leaves. Metabolite identification is to figure out the molecular structure of the metabo-lite contained in some biological sample, which is considered as a major bottleneck for metabolo-mics. The backbone analytical technology for metabolite identification is tandem mass spectrometry. It consists two rounds of mass spectrometry: In the first round all the metabolites in a sample are measured and one particular metabolite being interested is selected and fragmented by a process of dissociation. In the second round, the fragments as well as their abundance are measured. The resulting tandem mass spectra contain the information on the structure and composition of the molecules.
 
This thesis aims to solve the problem of identifying the molecular structures that produce the observed tandem mass spectra from some biological sample. The traditional methods are mostly based on matching the observed tandem mass spectra to the reference spectra in some database. However, these methods could fail if there are no reference spectra for the molecules in the underlying sample, which is not uncommon especially considering only 220,000 spectra representing 20,000 molecules are measured and annotated according to a recent study while the number of molecules recorded in a compound database PubChem is more than 60 million. To alleviate this problem, many recent works has been focusing on the approach so called in silico fragmentation where the fragmentations are first simulated in computer for the molecules in some molecular database. Then the simulated fragments are compared to the measured tandem mass spectra.
 
The main contribution of this thesis is to open a novel direction to bridge the gap between the limited spectral database and the vast molecular database with the help of molecular fingerprints. Molecular fingerprints are a binary representation to encode the structures or properties of a molecule. Kernel based machine learning methods are used to predict the molecular fingerprints from tandem mass spectra. Then the predicted fingerprints are used to match the fingerprints of mole-cules in some molecular database to derive an identification. Multiple kernel learning are also proposed to combine different views of tandem mass spectra. Finally, a one-step approach based on input output kernel regression is also applied to solve this problem, which becomes the new state of the art as demonstrated in several benchmarks including the recent Critical Assessment of Small Molecule Identification (CASMI) 2016 challenge.

<b><span style="color:red">Best Finnish bioinformatics PhD thesis done in 2016-2017</span></b> [(Award link)](http://bioinf.fi/winner-of-the-best-thesis-award/)