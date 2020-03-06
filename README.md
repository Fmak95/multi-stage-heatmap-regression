# Multi Stage Heatmap Regression
Detecting Facial Keypoints using a Multi-Stage Heatmap Regression Network. 

**NOTE:** The notebook might be easier to read on the Kaggle kernel <a href="https://www.kaggle.com/fmak95/facial-keypoint-detection">here.</a>

## Introduction
This github repo stores my notebook in which I introduced a way of predicting facial keypoints via heatmap regression. I utilize a popular deep learning architecture called: Convolutional Pose Machines which essentially takes RGB images as input and outputs a collection of heatmaps.

The heatmaps can be viewed as a probability distribution of the likelihood that a keypoint resides at every pixel. This technique is very popular in computer vision applications such as human pose estimation.
