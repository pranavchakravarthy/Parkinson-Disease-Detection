# Parkinson-Disease-Detection

### Pattern Recognition and Machine Learning

Major Project done under the guidance of Prof. Richa Singh at IIT Jodhpur.

## Abstract

- The goal of this study was to develop a supervised learning model for classifying the Medical
  Subjects into two classes based on their status of Parkinson’s disease.
  
- The dataset contains various audio parameters of the voice recordings of the patients.
  
- The dataset is biased with Recording containing 23 Positive patients out of the total 31.
  
- Hence, we have used both accuracy and F1 score as the measures. We have applied dimensionality reduction and feature selection methods and have later trained several models on them.
  
- For this project, we adhered to the entire Supervised Machine Learning pipeline.
  

## Introduction

In this study, we made an effort to classify the patients into healthy and sick using various
supervised learning algorithms. At the very beginning, we have tried Linear Discriminant
analysis to find out if the data is linearly separable. Then, we went ahead with Independent
Component analysis along with Naive Bayes Classification to see whether this method works.
We have then proceeded to try the Sequential Forward Feature selection algorithm with
Decision Tree Classifier as the base model. We have also applied PCA on the dataset to reduce
the dimensionality.
The various Classification Models that we have used are:

```
1. LDA Classifier
2. Naive Bayes Classifier
3. Random Decision Forest (Bagging)
4. Boosting (XGBoost)
5. KNN Classifier
6. Support Vector Machine
7. Multi-Layer Perceptron
```

We have measured the performance of these models by their accuracy and F1 Score since it is
a dataset of a very rare disease (Parkinson's disease).

Since the dataset is biased with the recordings containing 23 Positive patients out of the total
31, with a total of 195 recordings, we have used stratified train-test splits to maintain the ratio of
positive to negative class distribution in the training and test sets.

## Authors

- Pranav Chakravarthy
- Harsh Tomar
- Krishna Gaurang
