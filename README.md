# comp3314-ML-CIFAR10
The code and the report for HKU COMP3314 image classification Kaggle contest. \
Author: Huang Junran*, Sun Xueli*, Zhen Qi*

### Challenge Setting
In this challenge, we are given the CIFAR-10 image dataset. The goal is to reach 70\% classification accuracy on the private testing set, *without using deep learning architecture such as RNN, CNN, transformer, etc.*

### Features
1. Data Augmentation: horizontal flipping, random rotation
2. Feature Extraction: Mean RGB, Color Histogram, HOG, EOH, HUM, SIFT
3. Dimensionality Reduction: PCA
4. Model Selection: rbf SVM
5. Fine-tuning

### Achievement
By data augmentation and integrated feature extraction, we achieve the accuracy of 71.837% on private test set, without using any Deep Learning structure.
