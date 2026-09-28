---
title: "L3: Structured Data I"
layout: default
nav_order: 3
---

# Lecture 3: Structured Data Processing (Part I)

(Last updated: Sep 27, 2026)

This lecture explains the theory of Decision Tree and Random Forest models that are used in the structured data processing module.

{: .important }
> Check the [GenAI usage policy]({{ site.baseurl }}/syllabus#policy-for-using-generative-ai-tools) if you are using the course materials with GenAI for self-study and fact-checking.

## Preparation

Read the required course readings.

## Lecture

Below are the slides:
- [Slides for Lecture 3: Structured Data Processing (Decision Tree, Random Forest, and PCA)]({{ site.baseurl }}/slides/lec3-1.pdf)

## Required Course Readings

- Section 3.1, 3.2, 3.3, and 3.4 (including 3.4.1 and 3.4.2) about decision tree learning in book [Machine Learning](http://www.cs.cmu.edu/~tom/files/MachineLearningTomMitchell.pdf) (Mitchell, 1997)
- Section 8.2.1 (Bagging) and 8.2.2 (Random Forests) in book [An Introduction to Statistical Learning](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html) (James et al., 2013)

## Optional Course Readings

- Section 5.4 (Estimators, Bias and Variance) in book [Deep Learning](https://www.deeplearningbook.org/) (Goodfellow et al., 2016).
- Section 2.2.2 (The Bias-Variance Trade-Off) and 12.2 (Principal Components Analysis, including 12.2.1, 12.2.2 ) in book [An Introduction to Statistical Learning](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html) (James et al., 2013)

## Exercises

See [Exercises]({{ site.baseurl }}/syllabus#how-to-use-exercises) about how to use the exercises.

- Explain the procedure for training a decision tree. How does the training data look like? How to pick the feature to split a node? Which metric to use for node splitting? After splitting a node, what to do for splitting other nodes (using what kind of logic in programming)? What is the tree doing when we think about how the model cuts a high-dimensional space (with data points) into which kind of structure? How to prevent the tree from overfitting? What to do when we have features with continuous values?
- What is a good strategy to do hyper-parameter tuning? How should you split the dataset? Which part of the dataset split should be used for hyper-parameter tuning?
- Explain the difference between a feedforward neural network and a recurrent neural network. What are the differences between their inputs? Are there any differences in the neural net architecture?
- Explain the procedure of constructing a random forest. What are the underlying small models in a random forest? How to train each small model? How to aggregate the output from these small models?
- Compared with a decision tree model, what are the advantages of a random forest in terms of bias and variance tradeoff? Also, describe the underlying statistical theory that makes random forest work well.
- If we give you the probabilities of seeing each side of a two-sided coin, how to compute entropy by writing Python code? What about a dice that has four sides and six sides?
- Describe PCA conceptually. Given a coordinate system with many data points, what does PCA do to the coordinate system? Is PCA doing something to the origin of the coordinate system, and in which way? Think about what will happen after PCA if you look at the data on the principal component axes.
- Explain what under-fitting and over-fitting mean in terms of bias, variance, and model complexity. What does a high-bias and low-variance model mean intuitively? Also, what does a low-bias and high-variance model mean? Think about the situation when we run the experiment infinite number of times (so we have infinite number of datasets and models).

## Additional Resources

Below are videos from StatQuest that explains the Decision Tree model and PCA nicely:
- [Decision and Classification Trees, Clearly Explained](https://www.youtube.com/watch?v=_L39rN6gz7Y)
- [Principal Component Analysis (PCA), Step-by-Step](https://www.youtube.com/watch?v=FgakZw6K1QQ)