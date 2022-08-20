# Diabetic Retinopathy Classifier
Used Machine Learning techniques to classify Diabetic diseases.

## Technologies

- fastai:  version 1.0.52
- PyTorch:  version  1.0.0
- Python:  version 3.6

## Details

A SqueezeNet pretrained on the ImageNet dataset was used to train the classifier.

Training was done with [Kaggle Kernels](https://kaggle.com/kernels). Training history is provided in [history.csv](notebooks/history.csv)

The dataset came from the [Diabetic Retinopathy Kaggle Competition](https://kaggle.com/c/diabetic-retinopathy-detection), with the files cropped to remove any black space, and resized to a width of 1024 (and maintaining the aspect ratio), before being loaded in fastai.


The dataset was hosted in Kaggle Datasets.


