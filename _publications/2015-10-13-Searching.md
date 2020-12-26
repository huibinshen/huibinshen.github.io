---
title: "Searching molecular structure databases with tandem mass spectra using CSI: FingerID"
collection: publications
permalink: /publication/2016-06-15-Fast
date: 2016-06-15
venue: 'Bioinformatics'
paperurl: 'https://academic.oup.com/bioinformatics/article/32/12/i28/2288626?login=true'
citation: 'Céline Brouard, <b>Huibin Shen</b>, Kai Dührkop, Florence d'Alché-Buc, Sebastian Böcker, Juho Rousu. (2017). &quot;Fast metabolite identification with input output kernel regression&quot; <i>Bioinformatics</i>'
---


Click title for more detail.

## Abstract

Motivation: An important problematic of metabolomics is to identify metabolites using tandem mass spectrometry data. Machine learning methods have been proposed recently to solve this problem by predicting molecular fingerprint vectors and matching these fingerprints against existing molecular structure databases. In this work we propose to address the metabolite identification problem using a structured output prediction approach. This type of approach is not limited to vector output space and can handle structured output space such as the molecule space.

Results: We use the Input Output Kernel Regression method to learn the mapping between tandem mass spectra and molecular structures. The principle of this method is to encode the similarities in the input (spectra) space and the similarities in the output (molecule) space using two kernel functions. This method approximates the spectra-molecule mapping in two phases. The first phase corresponds to a regression problem from the input space to the feature space associated to the output kernel. The second phase is a preimage problem, consisting in mapping back the predicted output feature vectors to the molecule space. We show that our approach achieves state-of-the-art accuracy in metabolite identification. Moreover, our method has the advantage of decreasing the running times for the training step and the test step by several orders of magnitude over the preceding methods.