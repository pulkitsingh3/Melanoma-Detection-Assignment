# Melanoma-Detection-Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Technologies Used
- Build a multiclass classification model using a custom convolutional neural network in TensorFlow. 
- Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- Train the first model for ~20 epochs.
- Chose an appropriate data augmentation strategy.
- Model Building & training on the augmented data.
- Train the second model for ~20 epochs.
- Model Building & training on the rectified class imbalance data.
- Train the second model for ~30 epochs.

## Conclusions
- Finding on the first base model
  - The model is not overfitting but accuracy is very small.
- Finding from second Model
  - There is no improvement in accuracy.
  - We can increase the epochs to increase the accuracy so it's too early for judgement.
- Final finding on the rectified class imbalance data
  - Accuracy on training data has increased by using Augmentor library.
  - Losses on training data has decresed by using Augmentor library.

## Acknowledgements
- Thank to Google Colab and GPU runtime.
