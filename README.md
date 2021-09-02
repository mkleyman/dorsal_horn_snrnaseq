
## Macaque Dorsal Horn SnRNAseq Analysis

The code and jupyter notebooks to go along with the manuscript: Comparison of the Cellular and Molecular Atlases of the Macaque and Mouse Dorsal Horns 
manuscript. This github details the analysis performed on single nucleus RNA-seq data sampled from the Rhesus macaque dorsal. The resulting analysis yielded precise gene markers for all neural cell types in the macaque dorsal horn and a comparison of the expression patterns with their homologous mouse cell types. You can follow along the analysis with the Jupyter notebooks below. 
## Requirements 

* R>4.0.5

* python>3.8.1


The rest of the requirements can be found below:

*python : conda_env.yml
*R: R_installed_packages.csv

## Computational Workflow

The analysis was composed of the following steps and can be viewed in the analysis jupyer notebooks.

| Computational Step   | Associated Notebook  |
| ------------- | -----:|
| Empty Droplet Removal    | [qc_analysis.ipynb](qc_analysis.ipynb) |
| Doublet Removal    | [[qc_analysis.ipynb](qc_analysis.ipynb)   |   
| Preclustering  |   [preclustering.ipynb](preclustering.ipynb) |
| Normalization | [normalization.ipynb](normalization.ipynb) |
|Biological Replicate Integration | [integration_analysis.ipynb](integration_analysis.ipynb)   |
|Marker Gene Analysis | [integration_analysis.ipynb](integration_analysis.ipynb)   |
|Mouse Comparative Analysis | [mouse_comparison.ipynb](mouse_comparison.ipynb)   |


Data will be available via SRA and GEO soon!




