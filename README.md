# KewTreeOfLife

This repository contains the software used to construct and analyse the [Kew Tree of Life](https://treeoflife.kew.org/) ([PAFTOL](https://www.kew.org/science/our-science/projects/plant-and-fungal-trees-of-life)
 project). It contains the following folders:
* pypaftol - a submodule with programs for gene recovery and retrieval
* PhylogenomicsPipelines - a submodule with two programs, one for overseeing the gene recovery and one for creating species trees
* PAFTOL_Validation_Pipeline - a submodule for taxonomic validation of samples in a phylogenetic tree

This software has been reported in the following work:

Baker et al (2021) A comprehensive phylogenomic platform for exploring the angiosperm tree of life (submitted to [bioRxiv](https://doi.org/10.1101/2021.02.22.431589) and now published in [Systematic Biology](https://doi.org/10.1093/sysbio/syab035))

<b>Note</b>: In order to draw down the submodules into this repository you need to first clone the KewTreeOfLife repository as normal except add the --recurse-submodules flag:
```bash
git clone --recurse-submodules https://github.com/RBGKew/KewTreeOfLife.git
```
To retrieve the latest version of each submodule, you can run the second command periodically if the source module has been updated but not the module in this Kew Tree of Life repository:
```bash
git submodule update --remote <submodule_repo_name>
```
