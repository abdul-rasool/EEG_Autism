# ASD_Classification
This repository contains codes for the classification of ASD by using open-source datasets and a deep+ensemble learning approach

Initially, the feature extraction files have been provided with the suffix _Features.ipynb. These files will read through the raw ASD datasets and generate the output feature Excel files. The files will be stored in Google Drive in the folders specified within the codes.

The datasets are available as follows:

Dataset 2: https://drive.google.com/drive/folders/1zZ1XT-SPy-OYX4o9IGwqfl6Jw97Pjl66?usp=sharing
Dataset 1: TD: https://drive.google.com/drive/folders/18-Xj9v6aqb_x8Jj0Y62BPaKa_RfCb218?usp=sharing
ASD: https://drive.google.com/drive/folders/14WU7mHeqfHgo_BmnjC9nbJy6hT9mlpzl?usp=sharing


Following the generation of features, there are individual files provided for each of the models to be tested. The codes ask for accessing Google Drive upon execution, and the featured data contained in the corresponding folders is read. The data is then passed through the model GB, XGB etc. All the results are displayed as output cells.

The files with the suffix _Gen_Results have been used to generate supplementary results for analysis that have been added to the paper.
