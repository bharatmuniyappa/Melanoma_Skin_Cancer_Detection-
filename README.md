# Melanoma Skin Cancer Detection Model
> Deep Learning Model to detect Skin Cancer using Tensorflow,Keras and CNN To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:

  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion

## Conclusions
- Model 1: There is extreme difference between training and validation accuaracy.The model performs well on training dataset and not perform well on validation dataset. The odel was Overfitting.
- Model 2: Signs of underfitting because if less data.
- Model 3: In this model class rebalance helped us to improve the accuracy.We observed the model was no more underfitting, with training accuracy of 88%.We observed that validation accuracy was 87% which was very close to training accuracy. There is no overfitting too.

## Technologies Used
- The model has been build on Google Colab platform.

## Acknowledgements
I would like to thank Upgrad and IIT-B for giving me this opportunity to work on Melanoma Skin Cancer Detection Assignment.

## Contact
* [Bharat M](https://github.com/bharatmuniyappa/)