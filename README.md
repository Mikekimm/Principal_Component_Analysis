Principal Component Analysis

This project implements PCA from the group and covers all the mathematical foundations and provides practical insights into dimensionality reduction techniques.

Source: https://www.kaggle.com/datasets/mahmoudsaeed99/african-economy-from-1980-to-2022?resource=download
Data collected by a student from African Leadership University
Author: Michael Kimani
Github: Mikekimm

Tasks done:
Building the PCA from scratch
I built the covariance matrix manually
Perform eigendecomposition to extract eigenvalues and eigenvectors
I projected the data into principal component space
Implemented Inverse transformation

The Dynamic Component Section
I automatically selected the number of components based on variance thresholds
I analyzed trade-off between dimensionality and information retention
I visualized how variance changes as i added components

Performing Optimization
I implemented PCA using Singular Value Decomposition for numerical stability.
I used a batch processing to make it memory efficient

Key Findings I Found out:
The result matched scikit-learn with numerical precision
Processes 5,000 samples under one second
This approach reduced data dimensionality significantly

Tech I Used:
Python
Numpy
Pandas
Matplotib and Seaborn
Jupyter Notebook

To try it yourself
gitclone https://github.com/Mikekimm/Principal_Component_Analysis.git
cd Principal-Components-Analysis
Pip install numpy pandas matplotlib seaborn scikit- learn
jupyter  notebook PCA_Assignment.ipynb


This data was collected by a student from African Leadership University
I focused on African development data.

Running the Code:
Open the notebook and run all the cells. Each section is well documented
