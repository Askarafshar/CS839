## [Class Project] COMP SCI 839: Modern Data Management and Machine Learning Systems

### Title: Constant-space tunable-accuracy insertion-robust learned range indices

### Abstract:

B-tree is a data structure that permits mapping a key to its position in a sorted array of keys. It is a cumulative distribution function (CDF) of a sample space of keys. The learned range index (Kraska et al., 2018) proposes the use of a machine learning model to approximate the CDF of the key space. One of the main limitations of the original learned index framework as proposed in (Kraska et al.,2018) is that it assumes the underlying data distribution (key space) to be static, which implies that a learned range index does not support any form of insertions or deletions in the key space. We address this challenge by extending the learned range index to accommodate a dynamic data distribution. Our learned index architecture accounts for various insertion and lookup patterns, by using a mixture-of-experts model trained on a training cache of recently accessed keys, and a feedback mechanism that allows the learned range index to optimize for different data access patterns. Furthermore, we analyze various conditions and parameter settings that affect the accuracy of our learned range index architecture, and show that our architecture has a tunable accuracy that allows for trading off space consumption. 

[Fulltext](https://github.com/Askarafshar/CS839/blob/main/doc/cs839001_project.pdf)

