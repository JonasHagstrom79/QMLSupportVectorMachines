# QMLSupportVectorMachines in Colab

This notebook demonstrates how to implement a Support Vector Machine (SVM) in Google Colab for data classification.

## Contents

* Generating synthetic data
* Defining the loss function (hinge loss)
* Minimizing the loss function using the L-BFGS-B optimizer from `scipy.optimize`
* Visualizing the results

## Requirements

* Python 3
* NumPy
* Matplotlib
* SciPy

## How to run

1. Open the notebook in Google Colab.
2. Run all the code cells in order.
3. Observe the visualization of the trained SVM model.

## Details

The notebook begins by generating synthetic data with two classes. It then defines the hinge loss function used to train the SVM model. Next, `scipy.optimize.minimize` with the L-BFGS-B algorithm is used to minimize the loss function and find the optimal support vector. Finally, the results
