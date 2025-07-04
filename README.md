# Timik-Multi-layer-Network-Analysis

This project provides code support for analyzing the community structure, distribution pattern, and network centrality of Timik Multi-level network.

## Dataset Resource
**Paper:** [https://www.nature.com/articles/sdata2017144#MOESM65](https://www.nature.com/articles/sdata2017144#MOESM65)

**Data Source:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/V6AJRV](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/V6AJRV)

## Quick Start
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

## Conclusion
In this study, we conducted a comprehensive analysis of a multi-layer social network derived from five distinct interaction types. Our investigation included classical centrality measures such as degree centrality, betweenness centrality, and eigenvector centrality, which allowed us to quantify node importance from both local and global perspectives.

We further examined the distributional characteristics of each layer to better understand the heterogeneity of node behaviors across different types of interactions. To enhance interpretability, we visualized the structural properties of the network using interactive 3D visualizations, revealing latent spatial and topological patterns.

Finally, we applied spectral clustering based on the normalized Laplacian matrix to detect communities within the fused multi-layer structure. This approach successfully uncovered cohesive subgroups, demonstrating the effectiveness of Laplacian-based embeddings in capturing multi-relational community structures.

Overall, our multi-dimensional analysis provides valuable insight into both individual-level roles and global-level modular organization within the multi-layer network.

