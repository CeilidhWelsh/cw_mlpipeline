# cw_mlpipeline

This repository contains all of the files created for my research to date. 

## Genomics 
The Genomics directory provides example files for those used in the genome wide association analysis. This includes shell scripts for running the SNPTEST software, an example sample file for patient coviarates and toxicity endpoints, and a jupyter notebook containing the python code used to create the sample files. This directory also contains the code used for the analysis of the output data from the SNPTEST software for graphs and data visualisation.

## Image Registration 
The image registration directory includes one file that provides code for; image registration on both the original and cropped planning and relapse scans; spatial mapping of a specified structure set (in this case the thyroid outline); the visualisation of both the cropped image registration results and the spatial mapping fo the recurrence thyroid onto the planning thyroid outline; and the extraction of the voxel-level dose values from within the transformed thyroid structure on the planning scan. 

## Machine Learning Models 
The ML model directory contains jupyter notebooks for the preliminary work with K-Nearest Neighbour, Decision Tree and Random Forest ML models. Data Visualisation (primarily using boxplots) to compare variables for patients with/without recurrence can be found in the KNN model notebook. Each model analysed variable correlations, standardisation and scaling, imputation of missing data and hyperparameter optimisation. After training and testing all the models and analysing the metrics associated with model performance, the Random Forest model was further developed to included majority and minority class sampling as the VoxTox data for recurrence is a significantly imbalanced dataset. 
