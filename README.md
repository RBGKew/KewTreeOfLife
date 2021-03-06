# KewTreeOfLife

This repository contains the software used to construct and analyse the [Kew Tree of Life](https://treeoflife.kew.org/) ([PAFTOL](https://www.kew.org/science/our-science/projects/plant-and-fungal-trees-of-life)
 project). It contains the following folders:
* pypaftol - a submodule with programs for gene recovery and retrieval
* PhylogenomicsPipelines - a submodule with two programs, one for overseeing the gene recovery and one for creating species trees
* PAFTOL_Validation_Pipeline - a submodule for taxonomic validation of samples in a phylogenetic tree

This software has been reported in the following work:

Baker et al (2021) A comprehensive phylogenomic platform for exploring the angiosperm tree of life (submitted to [bioRxiv](https://doi.org/10.1101/2021.02.22.431589) and Systematic Biology)

<b>Note</b>: In order to draw down the submodules into this repository you need to first clone the KewTreeOfLife repository as normal, then update each of the submodules otherwise the submodule folders will remain empty:
```
git clone --recurse-submodules https://github.com/RBGKew/KewTreeOfLife.git
git submodule update --remote <submodule_repo_name>
```
To retrieve the latest version of each submodule, you can run the second command periodically if the source module has been updated but not the module in this Kew Tree of Life repository.
