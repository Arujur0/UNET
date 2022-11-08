# UNET
An implementation of a basic U-NET for segmentation of cell images.

## Introduction
This is a basic implementation of the U-NET architecture from [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/pdf/1505.04597.pdf).

## Data 
The dataset sampled for the task of segmentation has been listed in the data\cells folder. It consists of 38 samples of ground truth masks and cell images. 
### Data Augmentation
To increase the number of samples and to improve model performance, four data augmentation techniques were employed. They are:
