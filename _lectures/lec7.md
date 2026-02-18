---
title: "L7: Text Data I"
layout: default
nav_order: 7
---

# Lecture 7: Text Data Processing (Part I)

(Last updated: Feb 18, 2026)

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

## Additional Resources

The following videos explain some math concepts that are used in the lecture.
- [Vectors](https://www.youtube.com/watch?v=fNk_zzaMoSs)
- [Dot Product](https://www.youtube.com/watch?v=C0sPtQ3wX9o)
- [Cosine Similarity](https://www.youtube.com/watch?v=e9U0QAFbfLI)

A video that explains the attention mechanism:
- [Attention for Neural Networks, Clearly Explained!!!](https://www.youtube.com/watch?v=PSs6nxngL6k)