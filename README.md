# HUMAN-CELL-TYPES-SVM
Train a model using human cell records, and classify cells to whether the samples are benign or malignant using SVM (Support Vector Machines).

I am using a dataset that is publicly available from the UCI Machine Learning Repository. The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics.
The Dataset is avilable at - https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/ML0101ENv3/labs/cell_samples.csv
About Dataset :
The ID field contains the patient identifiers. The characteristics of the cell samples from each patient are contained in fields Clump to Mit. The values are graded from 1 to 10, with 1 being the closest to benign.
The Class field contains the diagnosis, as confirmed by separate medical procedures, as to whether the samples are benign (value = 2) or malignant (value = 4).
Column name  : ID, Clump, UnifSize, UnifShape, MargAdh, SingEpiSize, BareNuc, BlandChrom, NormNucl, Mit and we have to predict the Class.
Class 2 : Benign
Class 4 : Malignant
