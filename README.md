This repository contains files about simple machine learning models for image classification. Models are trained on CIFAR-10 dataset found here on Kaggle: https://www.kaggle.com/datasets/swaroopkml/cifar10-pngs-in-folders/download?datasetVersionNumber=1. 
Dataset is composed as follows:
- 10 image categories;
- images are 32 x 32 x 3 (32 by 32 pixels RGB);
- train set contains 50000 images (5000 for each category);
- test set contains 10000 images (1000 for each category);

I decided to use machine learning classification algorithms viewd during IT CODING class at university. In particular the algorithms are: KNN, Logistic regression and random forest. Each algorithm has been tuned according to f1 global score. 
- Directory "train" contains train images
- Directory "test" contains test images
- Directory "data" contains pickle files used to load train and test set in a fast way.
- Notebooks "KNN", "KNN_PCA", "Logistic_Regression", "Logistic_Regression_PCA", 
