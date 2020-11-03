# Severstal Image Classification

## Summary
Inside this document you will find a capstone project for the final project of Machine Learning Nanodegree. It is included below a brief introduction to the problem statement, objectives, methods for problem solving and the results at the end. The first part is dedicated to explain and explore the chosen dataset, which includes pre-operations (cleaning and wrangling). The second part shows the machine learning classical steps: preparing data, splitting data in training, selecting a model and then feeding with data. The third and last part shows the results and final remarks.

## Overview

The classification system proposed in this project consists of 2 step classification: (i) first step is a binary classification to predict if an image has a defect or not; (ii) second part is a multiclass classification to predict which class is the most probable.the figure below shows a diagram for the classification strategy in this work and a sample of binary mask.

<p align="center">
  <img src="https://github.com/ricterra/severstal-image-classification/blob/main/photos/schematic.png" width="700" title="Classification Scheme">
</p>
<p align="center">
  <img src="https://github.com/ricterra/severstal-image-classification/blob/main/photos/binary_mask.png" width="500" title="Binary Mask">
</p>

## Architecture
<p align="left">
  <img src="https://github.com/ricterra/severstal-image-classification/blob/main/photos/folder.png" width="200" title="Architecture">
</p>
    
## Files
**1-EDA.ipynb** : This is the first notebook of this study, it is dedicated to EDA (exploratory data analysis) of Severstal data, including data cleaning.

**2-MaskVisualization.ipynb** : This is the second notebook of this study, it is dedicated to build and visualize mask based on encoded pixels of Severstal data.

**3- Classification.ipynb** : This is the third notebook of this study, it is dedicated to classification system and metrics analytics.

**train.csv** : original .csv file listing image names, classes and pixels for defects.

**sample_submission.csv** : original .csv listing testing images

**df_master.csv** : master list created in EDA notebook for use in notebook [2] and [3].

## References
[1] Severstal: Steel Defect Detection. <https://www.kaggle.com/c/severstal-steel-defect-detection>

[2] Understanding Semantic Segmentation with UNET. <https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47>

[3] Generating masks from Encoded Pixels — Semantic Segmentation. <https://medium.com/analytics-vidhya/generating-masks-from-encoded-pixels-semantic-segmentation-18635e834ad0>

[4] Keras Optimizers. <https://keras.io/api/optimizers/adam/>

[5] Effect of batch size on training dynamics. <https://medium.com/mini-distill/effect-of-batch-size-on-training-dynamics-21c14f7a716e>


