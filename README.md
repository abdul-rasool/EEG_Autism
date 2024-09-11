# ASD_Classification_EEG

EEFM: An Encoder-Ensemble Fusion Model for Autism Disorder Detection Using Feature-Enhanced EEG Signals

### What is EEFM?

An Encoder-Ensemble Fusion Model (EEFM) designed to enhance ASD diagnosis using EEG data. The EEFM integrates feature engineering with a sophisticated fusion network architecture, initially extracting a diverse range of time and frequency domain characteristics from EEG signals. This approach aids in determining the nuanced and heterogeneous patterns associated with ASD, leveraging ensemble learning and autoencoder techniques to capture complex relationships within the data. Specifically, an LSTMautoencoder captures temporal and spatial patterns, followed by an XGBoost Regressor for nonlinear relationship modeling and a linear regression model for boundary interpretation.

# Installation 

This repository contains codes for the autism classification into ASD and TD by using open-source datasets and a deep-ensemble learning approach.

Initially, the feature extraction files have been provided with the suffix _Features.ipynb. These files will read through the raw ASD datasets and generate the output feature Excel files. The files will be stored in Google Drive in the folders specified within the codes.

Following the generation of features, there are individual files provided for each of the models to be tested. The codes ask for accessing Google Drive upon execution, and the featured data contained in the corresponding folders is read. The data is then passed through the model GB, XGB etc. All the results are displayed as output cells.

The files with the suffix _Gen_Results have been used to generate supplementary results for analysis that have been added to the paper.

### Datasets

The datasets are available as follows:

1. Dataset 1: https://nda.nih.gov/edit_collection.html?id=2021 
2. Dataset 2: https://nda.nih.gov/edit_collection.html?id=2288

The data used in this study were obtained with permission (DAR ID: 18847) from the NIH-supported National Institute of Mental Health Data Archive (NDA). 

# Citation

The findings and contributions are being submitted to a high-quality SCI journal. 


