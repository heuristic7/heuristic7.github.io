---
layout: post
title: Thoughts on Machine Learning, Deep Learning
---

Here are a few thoughts on Machine Learning and Deep Learning that I have encountered and gathered. Hopefully, it will help your journey through this amazing world of Computer Science, Math and Data Science, and many many more. A certain mathematical rigour is expected of Machine Learning practitioners and so it helps to brush up on essentials of probability theory, discrete math, and statistics. 

Remember the following structure that Deep Learning and Neural Networks are fully contained within Machine Learning. 

We'll start off with a simple understanding of Machine Learning in layman terms. The crux of ML is to learn from data, a notion of the relationship within the contained data, that is extensible to as yet unseen data. Some of the common tasks addressable using ML are:
- Regression (prediction of output values)
- Classification (prediction of category)
- Ranking (ranked list of items)
- Clustering
- Dimensionality Reduction

The supplied data is usually composed of "training data" and "validation data". The trained model (which is simply an aggregation of parameter values - matrices or vectors or scalars) is then applied on an unseen data (called "test data") to make predictions. The exact nature of predictions will vary depending on the task - if it is ranking the output could be a ranked listing of the inputs, if it is clustering then the output could be a cluster association or membership for a new input value etc.

It is very helpful to approach certain problems with a probabilistic perspective so as to tease out various relationships. As an example, if one desires to parse out the causal factors of an input vector 'x', one could assume that the causal factors were an unknown hidden vector 'h'. Then one can create a model that then attempts to learn a vector 'h' for each of the training samples. The 'h' vector is then used to create the labeled output for each of the inputs 'x', as in a labeled supervised learning setting. 

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
