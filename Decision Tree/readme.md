Welcome to a new tutorial on Decision Tree from scratch. In the Machine Learning from Scratch series, it’s our fourth algorithm where we have covered all mathematical concepts and a project from scratch with detailed explanation. 

# INTRODUCTION

A decision tree is essentially a series of if-then statements, that, when applied to a record in a data set, results in the classification of that record. Therefore, once you’ve created your decision tree, you will be able to run a data set through the program and get a classification for each individual record within the data set. What this means to you, as a manufacturer of quality widgets, is that the program you create from this article will be able to predict the likelihood of each user, within a data set, purchasing your finely crafted product.

A decision tree is a type of supervised learning algorithm (having a pre-defined target variable) that is mostly used in classification problems. It works for both categorical and continuous input and output variables. In this technique, we split the population or sample into two or more homogeneous sets (or sub-populations) based on the most significant splitter/differentiator in input variables.

# HOW DECISION TREE WORKS ??

The understanding level of the Decision Trees algorithm is so easy compared with other classification algorithms. The decision tree algorithm tries to solve the problem, by using tree representation. Each internal node of the tree corresponds to an attribute, and each leaf node corresponds to a class label.

# Decision Tree Algorithm Pseudocode

    1 Place the best attribute of the dataset at the root of the tree.
    2 Split the training set into subsets. Subsets should be made in such a way that each subset contains data with the same value for an attribute.
    3 Repeat step 1 and step 2 on each subset until you find leaf nodes in all the branches of the tree.
   
![](https://aihubprojects.com/wp-content/uploads/2020/07/weatherdectree.gif)

Decision tree models can be used for both classification and regression. The algorithms for building trees break down a data set into smaller and smaller subsets while at the same time an associated decision tree is incrementally developed. The final result is a tree with decision nodes and leaf nodes. A decision node has two or more branches. Leaf node represents a classification or decision (used for regression). The topmost decision node in a tree that corresponds to the best predictor (most important feature) is called a root node. Decision trees can handle both categorical and numerical data.

![](https://aihubprojects.com/wp-content/uploads/2020/07/rsz_screenshot_from_2020-07-09_12-52-251.png)

[Read Full Tutorial ...](https://aihubprojects.com/decision-tree-from-scratch/)
