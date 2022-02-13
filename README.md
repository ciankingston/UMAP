# uniform_manifold_approximation_and_projection

Written with python 3.7.3

Both scripts require 'identifiers' and 'descriptors' excel files. Note the scripts are currently set up for analysis of the kraken phosphine library (https://chemrxiv.org/engage/chemrxiv/article-details/60c757f9702a9bdb7018cbd4).

umap_score_plots_4_1_22.ipynb contains code for a variety of 2- and 3-dimensional UMAP score plots

umap_cluster_4_1_22.ipynb contains code for k-means and HDBSCAN clustering. This script will be updated to include the functions currently in the PCA clustering script (printing molecules in clusters, printing molecules closest to centroids, etc.).

umap_interactive_12_2_22.ipynb contains code for interactive plots within the notebook, including for k-means and HDBSCAN clustered data. Built using molplotly (https://github.com/wjm41/molplotly) and mols2grid (https://github.com/cbouy/mols2grid).
