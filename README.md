# A Machine Learning Framework for Identification of Sex- and Disease-Specific Signatures in Parkinson’s and Alzheimer’s Single-Cell RNA-seq Data


*Dataset_Preprocessing_and_Random_Forest_Alzheimers.ipynb*
- End-to-end data import, QC (mitochondrial filters, gene/count thresholds), normalization, HVG selection, and PCA/UMAP for the Alzheimer’s single-cell dataset. Includes code to train sex- and disease-stratified Random Forests on Alzheimer’s data, rank feature importances, and generate heatmaps of top genes

*Dataset_Preprocessing_and_Random_Forest_Parkinsons.ipynb*
- Analogous preprocessing pipeline (QC, normalization, HVG, dimensionality reduction) and RF generation applied to the Parkinson’s single-cell dataset.

*Comparing_Alz_Parkinsons_Results.ipynb*
- Extraction of top Random-Forest predictor genes for each cell type/sex in both diseases, calculation of shared-gene overlaps and Jaccard indices, and summary visualizations.

*May7_vae_alzheimers.ipynb*
- Multi-task VAE implementation on Alzheimer’s HVGs, including auxiliary sex/disease heads, training routines, embedding extraction, and t-SNE/UMAP visualization.

*May6_vae_parkinsons.ipynb*
- Multi-task VAE implementation on Parkinson’s HVGs, including auxiliary sex/disease heads, training routines, embedding extraction, and t-SNE/UMAP visualization.

*RandomForest_Visualizations_all_cells_Alzheimers.ipynb*
- Code to load the outputs of trained sex- and disease-stratified Random Forests on Alzheimer’s data, rank feature importances, and generate visualizations (including heatmaps of top genes).

*RandomForest_Visualizations_all_cells_Parkinsons.ipynb*
- Equivalent RF visualization pipeline applied to the Parkinson’s dataset, highlighting sex-biased and disease-biased predictors.
