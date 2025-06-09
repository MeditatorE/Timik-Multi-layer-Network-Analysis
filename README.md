# Timik-Multi-layer-Network-Analysis

This project provides code support for analyzing the community structure, distribution pattern, and network centrality of Timik Multi-level network.

## 0.Dataset Resource
**Paper:** [https://www.nature.com/articles/sdata2017144#MOESM65](https://www.nature.com/articles/sdata2017144#MOESM65)

**Data Source:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/V6AJRV](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/V6AJRV)

## 1.Quick Start
0. [Download dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/V6AJRV)
1. Clone this repo
```
git clone https://github.com/MeditatorE/Timik-Multi-layer-Network-Analysis.git
cd Timik-Multi-layer-Network-Analysis-main
```

2. Download **[Jupyter notebook](https://jupyter.org)** and run
```
jupyter notebook
```

3. Run [Mutilayer_analysis.ipynb](https://github.com/MeditatorE/Timik-Multi-layer-Network-Analysis/blob/main/Mutilayer_analysis.ipynb) first
4. Run any other .ipynb file you like:
#### File Description 
- `Mutilayer_analysis.ipynb`: Files used to analyze node centrality, including multi-level and single-level degree centrality, between centrality, eigenvector centrality. It is recommended to run it first before other files.

- `Mutilayer_centrally_3D.ipynb`: Used to improve between centrality and realize 3D visualization of network structure.

- `Mutilayer_analysis_new.ipynb`: Contains comprehensive analysis and visualization of network centrality at each layer.

- `Commuity_algrithm.ipynb`: Community identification algorithm based on spectral clustering and its 3D visualization.
  
- `distribution.ipynb`: Analysis and visualization of network distribution.

- `html`: Contains 3D visualization images of the centrality analysis and community identification results of multi-layer networks. **Please download .html and open it with your browser.**

- `figures`: Contains visualization of centrality analysis of a single-layer network.

- `table`: Contains the top 100 most central points in different centrality analyses of single-layer networks and multi-layer networks stored in .csv file format.

