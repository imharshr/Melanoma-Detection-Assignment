# Melanoma Detection Assignment
> In this assignment, I build a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
    * [Dataset Description](#dataset-description)
    * [Problem Statement](#problem-statement)
* [Libraries Used](#libraries-used)
* [Conclusions](#conclusions)
* [Contact](#contact)


## General Information

### Dataset Description

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

### Problem Statement

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Libraries Used
- tensorflow
- numpy, pandas
- PIL
- matplotlib

## Conclusions
- **Conclusion 1:** Before performing any augmentation it was observed that the accuracy and validation was very low (close to **53%** and **37%** respectively)
- **Conclusion 2:** After augmenting the data, we saw a spike in the performance. We were now able to achieve an accuracy of **73%** on training and an accuracy of **68%** on the validation set.

## Contact
Created by [@imharshr](https://github.com/imharshr) - feel free to contact me!