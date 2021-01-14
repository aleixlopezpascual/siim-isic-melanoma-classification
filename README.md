# siim-isic-melanoma-classification
Kaggle competition 2020-08

https://www.kaggle.com/c/siim-isic-melanoma-classification/overview/description

## Overview
In this competition, you had to identify melanoma in images of skin lesions. This is a very challenging image classification task as seen by looking at the images provided. The dataset contains images and metadata. On one hand, the images are transformed to TFRecords and used to train an ensemble of EffNets with different parameters (metadata, upsampling, crop augmentation, image size, TTA...). On the other hand, the metadata is used to train an XGBoost. Both predictions are combined using a weighted arithmetic mean.