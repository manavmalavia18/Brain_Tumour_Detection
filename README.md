# Brain Tumour Detection

## About Dataset

The image data used for this problem is the Brain MRI Images for Brain Tumor Detection dataset. It consists of MRI scans of two classes:

- NO: no tumor, encoded as 0
- YES: tumor, encoded as 1

Unfortunately, the dataset description doesn't provide information on the origin of these MRI scans.

## Approach

We will employ three models in this notebook:

1. Deep Neural Networks
2. Convolutional Neural Networks (CNNs)
3. VGG19

The contents of the notebook will be structured as follows:

1. Importing libraries
2. Loading images and creating utility functions for data augmentation
3. Image demonstration
4. CNN models
   - ResNet50V2:
     - Training without data augmentation
     - Further tuning the model with data augmentation
   - VGG19:
     - Training without data augmentation
     - Further tuning the model with data augmentation
   - InceptionV3:
     - Training without data augmentation
     - Further tuning the model with data augmentation
5. Results

## Let's get started!
