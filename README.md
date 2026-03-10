# DeepLabCutRotarod
DeepLabCut analysis for the paper "Somatostatin interneurons select dorsomedial striatal representations of the initial motor learning phase"

# Instructions 

## Python environment
To run the notebooks please install the following libaries:

- numpy
- matplotlib
- pandas
- imageio
- picle
- scipy
- sklearn

## Notebooks

This repository contains three notebooks.
  
Please pay attention to change the main directory in all notebooks

Notebooks have to be run in the following order:

- Data_cleaning : to clean the original data exctracted with DeepLabCut
- Compute_silhouette_plot_selected : compute the silhouette index and plot the selected scatterplot
- Stats_silhouette_permtest : make permutation test and asses significant differnces between the two groups


   
