# Machine Learning-Based Grouping

This repository contains a preliminary machine learning grouping exploration.
The data used are biological strategies from asknature.org, but it can be replaced with strategies extracted with GPT from PeTaL's biological research paper dataset.

The two approaches included K-means clustering and Topic Modeling with BERTopic.
Note, please clone and run each notebook to understand the results and experiments.

### Clustering

With K-means clustering, the word represntation investigated was TF-IDF.
How to choose number of clusters:

- Within-Cluster-Variation, Between-Cluster-Variation, and CH-index with elbow method on Scree Plot. A monte carlo simulation was run to collect these numbers.
- Silhouette Analysis

I started to investigate other approaches for word representation, such as gensim's word2vec.

### Topic Modeling

The more promising method seemed to be topic modeling with BERTopic.
Please check the beginning of the notebook for more details.
