# Cell-Classification

## Problem Statement

This challenge consists of cellular images of 14 different types of cells. Your job to build a model that classifies the given test images into one of the 14 categories (enumerated from 1 to 14).

Number of training images : 10,600

Number of testing images : 15,984

### Dataset

The dataset contains 4 files
  - train_final.zip : This file contains all the training images.
  - test_final.zip : This file contains all the testing images.
  - train.csv : Labels associated with training images.
  - sample.csv : Sample submission file.

### Approach
● Built a classification model using fast ai
framework that classifies cellular images into
14 dierent types
● Used transfer learning on Ecientnet and
mixnet_ml architecture pre trained on
ImageNet
● Fine tuned using discriminative learning rate
for dierent layers
● Achieved an accuracy of 93% upon ensembling
the models

