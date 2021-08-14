# Classification Pathology Plants
This challenge is to correctly classify a series of pathologies in the leaves of apple tree. the database can be found at https://www.kaggle.com/c/plant-pathology-2021-fgvc8/data 

## Goal

The main goal of this exercise is to achieve the highest accuracy in the classification of the pathologies, distributed in 5 categories (C1 to C5), while C0 are the healthy leaves. 

## Models and evaluation

Convolutional networks are studied using knowledge transfer with a ResNet50 architecture, under two types of models to be compared. The F1-macro-average will be used to compare the performance of the models.
