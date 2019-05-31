# Assignment 1

## Problem Statement


Most of the deep learning models don't generalize across datasets. This leads to serious issues regarding their deployment in real life scenarioes.
Here is one such problem. Using BRATS(containing brain MRI scans) data, I have to make a model to do correct predictions on the data collected from nearby Hospital.

## Solution Overview

I made a robust model by:

1. Performing Bayesian hyperparameter optimization over Unet.

2. Made the model unlearn intensity based mapping by calculative data augmentation.

3. Performed histogram matching to match the statistics of data provided by Professor and BRATS data.

4. And Also some standard preprocessing techniques.

Not only this, I also found that my model was also robust against the extra structures present in the images collected from Hospital.

A detailed analysis of these techniques can be found in **Assignment1.pdf**.