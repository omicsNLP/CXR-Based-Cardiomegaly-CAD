# CXR-Based-Cardiomegaly-CAD
Code for "Designing a computer-assisted diagnosis system for cardiomegaly detection and radiology report generation"
[![DOI:10.1101/2024.09.02.24311997](http://img.shields.io/badge/DOI-10.1101/2024.09.02.24311997-blue.svg)](https://doi.org/10.1101/2024.09.02.24311997)

The files contained in this repository support the above study. 

1. ResNet50 Model Training.ipynb
   
   Contains code used for training the two ResNet50 models (Model 1 and Model 2).
   
   Create folders containing training images first.
   
   Replace the placeholder within the code with the training directory path.
   
   Install necessary packages if missing (such as torch).
   
   Train models.
   

2. ResNet50 Model Testing.ipynb

   Contains code used for testing ResNet50 models.

   Create folders containing testing images first using information provided within the augmented MIMIC metadata csv file.

   Replace the placeholder within the code with the testing directory path.

   Install necessary packages if missing.

   Test models.
   

3. Cardiomegaly Model Development and Testing.ipynb

   Contains code used for creating and testing the cardiomegaly CAD model.

   Download images used in model development and testing with information provided within the augmented MIMIC metadata csv file.

   Perform segmentation on CXR images to obtain lung/heart masks.

   Run code to obtain CTR and create/test the cardiomegaly classification model.

The code was originally hosted in [here](https://github.com/jz4520/CXR-Based-Cardiomegaly-CAD-).
