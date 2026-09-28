---
title: "L2: Fundamentals"
layout: default
nav_order: 2
---

# Lecture 2: Data Science Fundamentals

(Last updated: Jan 27, 2026)

This lecture recaps the fundamentals of data science, such as table operations, classification, and regression.

{: .important }
> Check the [GenAI usage policy]({{ site.baseurl }}/syllabus#policy-for-using-generative-ai-tools) if you are using the course materials with GenAI for self-study and fact-checking.

## Preparation

Read the required course readings.

## Lecture

Below are the slides:
- [Slides for Lecture 2-1: Data Science Fundamentals (Preprocessing)]({{ site.baseurl }}/slides/lec2-1.pdf)
- [Slides for Lecture 2-2: Data Science Fundamentals (Modeling)]({{ site.baseurl }}/slides/lec2-2.pdf)

Below is the link to the online notebook:
- [Python Coding Warm-Up Online Notebook](https://multix.io/python-warm-up/docs/python-warm-up.html)

Follow the steps on the [notebook page](https://multix.io/python-warm-up/docs/python-warm-up.html) to set up the notebook.

## Required Course Readings

- The following sections in book [An Introduction to Statistical Learning](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html) (James et al., 2013)
  - 2.2.1 (Measuring the Quality of Fit)
  - 3.1.1 (Estimating the Coefficients)
  - 3.1.3 (Assessing the Accuracy of the Model)
  - 9.1.1 (What Is a Hyperplane?)
  - 9.1.2 (Classification Using a Separating Hyperplane)

## Optional Course Readings

- Section 5.3 (Hyperparameters and Validation Sets, including 5.3.1) in book [Deep Learning](https://www.deeplearningbook.org/) (Goodfellow et al., 2016).
- Section 4.5.1 (Rosenblatt's Perceptron Learning Algorithm) in book [The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf.download.html) (Hastie et al., 2009)

## Exercises

See [Exercises]({{ site.baseurl }}/syllabus#how-to-use-exercises) about how to use the exercises.

- If we give you two numpy arrays: one is the prediction of a model (either regression or classification), and one is the ground truth, how to compute the evaluation metrics (either F-score or R-squared) by writing Python code?
- Explain the intuition of precision, recall, and f-score. What does a high-precision and a low-recall model mean? Conversely, what does a low-precision and a high-recall model mean?
- Explain the intuition of the R-squared metric. What does it mean geometrically if we plot the regression line on a 2D plot, where the x-axis is the feature, and the y-axis is the prediction or ground truth? What does it mean when having a bad R-squared value? Can we always use R-squared to determine if there is a pattern in the data, and why?
- Describe how to construct a linear classifier. How to represent the linear classifier using math equations? Give an example of the metric for determining whether the linear classifier work well or not. What is the function that you need to optimize (in mathematical form)? Do the same exercise for the linear regression model.
- Describe the procedure of computing permutation feature importance. What to do if we have high-correlated features? Why do we need to run the permutation and compute the importance for multiple times for one feature?
- Explain why do we need to map raw data into data points in a high-dimensional space? What do the axes in the high-dimensional space mean?
- What are the typical assumptions for linear regression?

## Additional Resources

Below are website for data visualization inspirations:
- [Seaborn: Statistical Data Visualization](https://seaborn.pydata.org/tutorial.html)
- [Exploratory Data Analysis by the US EPA](https://www.epa.gov/caddis-vol4/exploratory-data-analysis)
- [Examples of Data Exploration by the Statistics Netherlands](https://www.cbs.nl/en-gb)
- [Examples of Data Visualization](https://flowingdata.com/)

Below are interesting data science case studies:
- [Case Studies of Satelite Image Analysis](https://earthengine.google.com/case_studies/)
- [Case Studies of Machine Learning and Design](https://machinelearning.design/)

The textbook below contains more information about how to select models:
- Section 11.8 Comparing Different Models in book: [Introduction to Statistics and Data Analysis](https://link.springer.com/book/10.1007/978-3-319-46162-5)

The websites below contains exercises for Python pandas:
- [Pandas exercises on GitHub](https://github.com/guipsamora/pandas_exercises)
- [Pandas exercises on Kaggle](https://www.kaggle.com/code/icarofreire/pandas-24-useful-exercises-with-solutions)
- [Pandas exercises on W3Schools](https://www.w3schools.com/python/pandas/pandas_exercises.asp)
- [Pandas exercises by UC Berkeley School of Information](https://ischoolonline.berkeley.edu/blog/python-pandas-practice-problems/)
- [Pandas exercises on GeeksforGeeks](https://www.geeksforgeeks.org/pandas-practice-excercises-questions-and-solutions/)
- [Pandas exercises on w3resource](https://www.w3resource.com/python-exercises/pandas/index.php)
