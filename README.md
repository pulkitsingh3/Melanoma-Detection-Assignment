# Project Name
> Outline a brief description of your project.


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
- Train the model for ~20 epochs.
- Chose an appropriate data augmentation strategy to resolve underfitting/overfitting.
- Model Building & training on the augmented data.
- Model Building & training on the rectified class imbalance data.

## Conclusions
- Finding on the first base model
  - The model is overfitting because we can see difference in loss functions in training and validation.
  - The difference in accuracy of training and validation data is large enough which showes overfitting of model.
- Finding from Second Model
  - There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation.
  - We can increase the epochs to increase the accuracy so it's too early for judgement.
- Final findings on the rectified class imbalance data
