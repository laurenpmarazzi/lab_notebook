---
layout: tasks
title : "To Do for Project One"
category: project01
---

## Project 1

- [x] Filter expressed genes for CNV loss and chromatin modification
- [x] Calculate Z-score of each gene with CNV and methylation data
- [x] First Order Connectivity with BiNOM
	- [x] Ranked by p-value from DEG analysis
	- [x] Ranked by Z-score from CNV and methylation data
		- [x] **Use this list!**
- [x] Second order Connectivity with BiNOM
	- [x] Use list ranked by Z-score
	- [x] Ngene = 250, LCC = 30
- [x] Weighted sums
	- [x] Compare to ASCN EMT and innate imunity hallmarks of cancer
	- [x] Compare to complete ASCN hallmark of cancer list
	- [x] Compare to breast cancer disease ontology
- [x] Run TRANSFAC on 75 SOC largest connected component genes
- [x] Run TF analysis with IPA
- [x] Filter TFs with ChIP-seq or Bisulfite data and make sure they cover all downstream genes
- [x] Edit TRANSPATH workflow to incorporate protein expression data (as weights) and mutational data
- [x] Run ReKINect and figure out how to incorporate mutational data
- [x] Mutation Exploration
- [x] Run TRANSPATH
	- Use all expressed proteins as context genes!
- [x] Assemble network in Cytoscape and add atlas of cancer nodes
- [x] Calculate FVS
- [x] Run Signal Flow
- [x] Analyze readout nodes

- [ ] Start planning Boolean Network
