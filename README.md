# Decision Tree From Scratch
**Mushroom Classification Decision Tree Model**

This repository contains a decision tree model implemented from scratch for classifying mushrooms as edible or poisonous. The classification is performed by calculating entropy and information gain based on various attributes of the mushrooms.

## Introduction

The objective of this project is to develop a reliable decision tree model that can accurately classify mushrooms as either edible or poisonous. Decision trees are a popular machine learning algorithm for classification tasks as they provide interpretable and understandable results.

> Note: The dataset used is for illustrative purposes only. It is not meant to be a guide on identifying edible mushrooms.

## Decision Tree Implementation

The decision tree model in this repository is built from scratch, without relying on external libraries or pre-built implementations. The implementation follows the principles of entropy and information gain to construct an optimal decision tree.

The decision tree algorithm consists of the following steps:

1. Data Preprocessing: The mushroom dataset is preprocessed to ensure that it is suitable for training the decision tree. This includes, encoding categorical attributes.

2. Entropy Calculation: Entropy is a measure of impurity in a dataset. The entropy of the target variable (edibility) is calculated before and after each attribute split to determine the information gain.

3. Information Gain Calculation: Information gain quantifies the reduction in entropy achieved by splitting the dataset based on a particular attribute. The attribute with the highest information gain is selected as the splitting criterion at each node of the decision tree.

4. Tree Construction: The decision tree is constructed recursively by splitting the dataset based on the selected attribute and creating child nodes for each unique attribute value. This process continues until a stopping criterion is met, such as reaching a maximum depth or having pure leaf nodes.

## Conclusion

This repository provides a decision tree model implemented from scratch for classifying mushrooms as edible or poisonous. By utilizing entropy and information gain, the decision tree algorithm produces accurate and interpretable results. Feel free to explore the code and adapt it to your own datasets or classification tasks.

If you have any questions or suggestions, please don't hesitate to reach out.
