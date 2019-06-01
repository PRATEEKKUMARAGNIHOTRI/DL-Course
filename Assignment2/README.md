# Assignment 2

## Problem Statement


Get useful frames from the MOOCs videos, which will help students to make notes.

## Solution Overview

Five models are tested.

1. 3D_CNN.

2. A time-distributed ConvNet and passing the features to an RNN (in one network).

3. Extracting features from each frame with a ConvNet(inception net) and passing the sequence to a separate RNN 

4. 2D cnn classifier with 'n' frames window.

5. Using pytesseract (library for OCR) to get the words and monitoring the changes to determine the relevant frame. 

Since there were very less relevant frames which were leading to high data imbalance. This issue is tackled by:

1. Smoothening the labels.

2. Augmenting the data by smartly shuffeling the frames.

File Models.ipynb has first four models and the fifth one can be found in file ocrWithPytesseract.ipynb

A detailed analysis of these models and techniques can be found in **Assignment2.pdf**.