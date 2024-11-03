# YouTube Spam Classification

## Overview

This project aims to classify YouTube comments as spam or non-spam using various machine learning models. The models implemented include Naive Bayes, Support Vector Machine (SVM), Decision Tree, and Logistic Regression. The dataset used for training and testing the models is the YouTube Spam Collection dataset, sourced from the Machine Learning Repository.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Modeling Techniques](#modeling-techniques)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)

## Introduction

The increase in user-generated content on platforms like YouTube has led to a significant rise in spam comments. This project focuses on identifying and classifying these comments to enhance user experience. By employing various machine learning algorithms, we can effectively discern spam from genuine interactions.

## Dataset

The dataset utilized for this project is the **YouTube Spam Collection**, which contains a comprehensive collection of YouTube comments labeled as spam or non-spam. The dataset is publicly available and can be found in the [Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection).

## Modeling Techniques

We implemented the following machine learning algorithms for spam classification:

1. **Naive Bayes**: A probabilistic classifier based on Bayes' theorem, known for its simplicity and effectiveness in text classification tasks.
2. **Support Vector Machine (SVM)**: A powerful classification technique that works well in high-dimensional spaces, particularly effective in binary classification problems.
3. **Decision Tree**: A tree-structured model that makes decisions based on feature values, providing a clear visual representation of decision-making.
4. **Logistic Regression**: A statistical model that uses a logistic function to model a binary dependent variable, effective for classification tasks.

## Results

All models demonstrated strong performance, achieving over 90% accuracy:

- **Decision Tree**: 92.9%
- **Naive Bayes**: 92.6% (notably effective for spam identification)
- **Support Vector Machine (SVM)**: 93.5%
- **Logistic Regression**: 94.6% (highest accuracy)

After evaluating the models, we tested them on random phrases, revealing that **Naive Bayes excelled in spam detection**, effectively identifying spam phrases with a more aggressive approach, while SVM and Decision Tree models were more conservative in their predictions.

## Conclusion

This project successfully highlights the effectiveness of various machine learning algorithms in classifying YouTube comments as spam or non-spam. While all models performed admirably, **Naive Bayes stood out for its reliability in spam detection tasks due to its consistent performance.**

## Contributing

Contributions are welcome! If you'd like to improve this project, please feel free to submit a pull request or open an issue.
