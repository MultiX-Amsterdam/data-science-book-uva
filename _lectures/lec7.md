---
title: "L7: Text Data I"
layout: default
nav_order: 7
---

# Lecture 7: Text Data Processing (Part I)

(Last updated: Sep 27, 2026)

This lecture introduces the theory for text data processing, including preprocessing (tokenization, lemmatization, pos-tagging), word embeddings, topic modeling, sequence-to-sequence modeling, and the attention mechanism.

{: .important }
> Check the [GenAI usage policy]({{ site.baseurl }}/syllabus#policy-for-using-generative-ai-tools) if you are using the course materials with GenAI for self-study and fact-checking.

## Preparation

Read the required course readings.

## Lecture

Below are the slides:
- [Slides for Lecture 7: Text Data Processing]({{ site.baseurl }}/slides/lec7-1.pdf)

## Required Course Readings

- Section 4.4.2.1 (Tokenisation), 4.4.2.2 (Stop-word Removal), 4.4.2.3 (Lemmatisation), 4.4.2.4 (Stemming), 4.4.3.1 (Part-of-speech Tagging) in the [ML4Design lecture notes](https://surfdrive.surf.nl/files/index.php/s/RyBCGg8LJ1HgXFG) (Bozzon, 2023)
- Section 5.1 (Lexical Semantics), 5.2 (Vector Semantics: The Intuition), 5.3 (Simple count-based embeddings), 5.4 (Cosine for measuring similarity), 5.5 (Word2vec), 11.1.1 (Representing documents as vectors), and 11.1.2 (Term weighting: tf-idf and BM25) in book [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/ed3book_jan26.pdf) (Jurafsky & Martin, 2026)

## Optional Course Readings

- Section 5.5 (Maximum Likelihood Estimation) in book [Deep Learning](https://www.deeplearningbook.org/) (Goodfellow et al., 2016).
- Blei, D. M. (2012). [Probabilistic topic models](https://dl.acm.org/doi/pdf/10.1145/2133806.2133826). Communications of the ACM.
- Section 8.1 (Attention) in book [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/ed3book_jan26.pdf) (Jurafsky & Martin, 2026)
- Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). [Efficient estimation of word representations in vector space](https://arxiv.org/pdf/1301.3781.pdf). arXiv preprint arXiv:1301.3781.

## Exercises

See [Exercises]({{ site.baseurl }}/syllabus#how-to-use-exercises) about how to use the exercises.

- If we ask you to calculate the cosine similarity by writing python code, how to do that? You can use the cosine similarity exercise in the lecture slide as an example. If the vector is in a 3D or 4D space, how to do the calculation using code?
- If we ask you to calculate the softmax of an array with arbitrary length by writing python code (using numpy specifically), how to do that?
- Explain the role of the Likelihood function in training a Word2Vec model. Your explanation should clearly cover: (a) what "likelihood" means conceptually in this context, (b) how maximizing likelihood connects to predicting context words from center words, and (c) the mathematical components of the Likelihood function (and what does the mathematical components mean).
- Describe what a topic vector means conceptually. What do the numbers in a topic vector mean?
- If we give you a joint probability table, how to calculate the conditional probability?
- Describe the attention mechanism. Why do we need the attention mechanism (and not just using a simple recurrent neural network)? How to construct key, value, and query vectors? Where do they come from? How to combine them together to a final representation of a sentence, and then do the prediction of the next word?
- Why do we need cosine similarity or dot product when training word embeddings? What are their roles?
- Explain how to design a neural network architecture to train the Word2Vec model using the skip-gram approach. How does the input look like? How does the output look like? Where can we get the embedding vector? How can we train the model using which loss function? What is negative sampling and why do we need  it when training the Word2Vec model?

## Additional Resources

The following videos explain some math concepts that are used in the lecture.
- [Vectors](https://www.youtube.com/watch?v=fNk_zzaMoSs)
- [Dot Product](https://www.youtube.com/watch?v=C0sPtQ3wX9o)
- [Cosine Similarity](https://www.youtube.com/watch?v=e9U0QAFbfLI)

A video that explains the attention mechanism:
- [Attention for Neural Networks, Clearly Explained!!!](https://www.youtube.com/watch?v=PSs6nxngL6k)