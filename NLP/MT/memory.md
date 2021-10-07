# NLP - Translation Memory
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Fast and Accurate Neural Machine Translation with Translation Memory](https://aclanthology.org/2021.acl-long.246.pdf)|Paper|ACL|Proposed three methods to encode TM (from similarity by Lucene) into vectors and encode them in Example Layer which modifies Transformer decoder to take into account the TM vectors|
|[Guiding neural machine translation with retrieved translation pieces](https://aclanthology.org/N18-1120/)|Paper|NAACL|Using word alignment and similarity score to up-weight similar translation result in test time.|
|[Search Engine Guided Neural Machine Translation](https://arxiv.org/pdf/1705.07267.pdf)|Paper|AAAI|Incorporate TM in training time so that the model has access to potentially good pairs found by edit distance (fuzzy match score)|
|[Graph based Translation Memory for Neural Machine Translation](https://ai.tencent.com/ailab/nlp/en/papers/aaai2019_graph_translation.pdf)|Paper|AAAI|Encode translation memory as graphical model and use graphical attention to add it into transformer.|
|[Boosting Neural Machine Translation with Similar Translations](https://aclanthology.org/2020.acl-main.144/)|Paper|ACL|Compare different distance measurement for retrieving translation memory and showed that TM helps models to learn to "copy" and have more contextual info.






[Back to index](../../README.md)
