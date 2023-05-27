---
title: "TF-IDF"
date: 2023-05-17
categories: text mining
---

__TF-IDF__ stands for __Term Frequency-Inverse Document Frequency
- A measure used in information retrieval and text mining
- How important a word is to a document in a collection or corpus

The measure is a combination of two components:
__Term Frequency (TF)
- A measure of how frequently a term appears in a document
__Inverse Document Frequency (IDF)
- A measures how important a term is
- Certain terms may appear a lot of times but have little importance
- Thus, we need to weigh down the frequent terms while scaling up the rare ones

__Caculating TF-IDF score
- Multiply the term's TF score by its IDF score
- `TF-IDF = TF * IDF`

__Document Frequency (DF)
- The count of documents in the corpus that contain the term (t)
- The Inverse Document Frequency (idf) is then calculated as the logarithm of the total number of documents in the corpus divided by the Document Frequency
