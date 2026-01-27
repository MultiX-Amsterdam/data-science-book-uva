---
title: "L7: Text Data I"
layout: default
nav_order: 7
nav_exclude: true
---

# Lecture 7: Text Data Processing (Part I)

(Last updated: Jan 30, 2025)

This lecture introduces the theory for text data processing, including preprocessing (tokenization, lemmatization, pos-tagging), word embeddings, topic modeling, sequence-to-sequence modeling, and the attention mechanism.

{: .important }
> Check the [GenAI usage policy]({{ site.baseurl }}/syllabus#policy-for-using-generative-ai-tools) if you are using the course materials with GenAI for self-study and fact-checking.

## Preparation

Watch the following videos to understand some math concepts that will be used in this lecture:
- [Vectors](https://www.youtube.com/watch?v=fNk_zzaMoSs)
- [Dot Product](https://www.youtube.com/watch?v=C0sPtQ3wX9o)
- [Cosine Similarity](https://www.youtube.com/watch?v=e9U0QAFbfLI)

## Lecture

Below are the slides:
- [Slides for Lecture 7: Text Data Processing]({{ site.baseurl }}/slides/lec7-1.pdf)

## Additional Resources

A video that explains the attention mechanism:
- [Attention for Neural Networks, Clearly Explained!!!](https://www.youtube.com/watch?v=PSs6nxngL6k)

The following paper explains Topic Modeling and the intuitions:
- [Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77-84.](https://www.cs.columbia.edu/~blei/papers/Blei2012.pdf)

The following paper explains how to train word embeddings using Word2Vec:
- [Mikolov, T., et al. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.](https://arxiv.org/pdf/1301.3781.pdf)

The following paper explains how to use the attention mechanism for document classification:
- [Yang, Z., Yang, D., Dyer, C., He, X., Smola, A., & Hovy, E. (2016, June). Hierarchical attention networks for document classification. In Proceedings of the 2016 conference of the North American chapter of the association for computational linguistics: human language technologies (pp. 1480-1489).](https://aclanthology.org/N16-1174/)

The Hugging Face website below documents a list of state-of-the-art Transformer-based models:
- [Transformers: State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX](https://huggingface.co/transformers/v4.7.0/)