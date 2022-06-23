# Info

This project is a simple implementation of machine learning on the fetal health classification dataset that can be found on kaggle.com [https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification].

In this project, I will use machine learning to predict the fetal health by using features from cardiotocographic (CTG) data.

## How to Use

To run the notebooks, put the data found under the link posted above inside the `data/` folder.

## How to Read

If you're interested in my work, you can go through the Fetal_Health.ipynb notebook. It contains a condensed version of my work on data exploration, feature selection, feature engineering and model training, as well as some work on data clustering. However, extensive clustering and deep learning are not (yet) implemented in this project. The other notebooks are a more extensive representation of my reasoning and are meant to complete the documentation, they do not contain additional information that is relevant to the reader and can be skipped if no details are required.

## TL;DR

By means of machine learning I was able to sufficiently predict the health of a fetus by using CTG values, achieving over 90% in specificity and sensitivity for the categories `normal` and `pathological`, `suspect` was harder to distinguish, as was to be expected. By using rigorous feature selection methods I was able to condense the feature space down to only twelve input features. While linear models showed good responses, especially support vector machines, Random Forests were the most powerful prediction algorithms in this project.
