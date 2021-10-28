# ML - Architectures
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Attention Is All You Need](https://arxiv.org/abs/1706.03762)|Paper|NIPS|Transformer architecture uses attention mechanism to replace the auto-regressive way to encode sentence by RNN-based architecture. Allow for parallelization for training, inference is still autoregressive. Introduce positional embedding and layerwise normalization as well. Note that original paper's layer norm is different from many up-to-date implementation. |
|[SPECTRAL NORMALIZATION FOR GENERATIVE ADVERSARIAL NETWORKS](https://arxiv.org/pdf/1802.05957.pdf)|Paper|ICML|on reading plan|
|[Convolutional Sequence to Sequence Learning](https://arxiv.org/pdf/1705.03122.pdf)|Paper|ICML|Introduce 1-D convolution to replace recurrent structure and apply MLP  attention to attend encoder-decoder information. Achieved SOTA for en-fr translation.|
|[An Introduction to Conditional Random Fields for Relational Learning](https://people.cs.umass.edu/~mccallum/papers/crf-tutorial.pdf)|Tutorial|NA|Detailed Explanation of CRF and related models like Naive bayes, HMM, logistic regression, linear-chain and skip-chain CRF, etc.|
|[GRAPH ATTENTION NETWORKS](https://arxiv.org/pdf/1710.10903.pdf)|Paper|ICLR|Propose a architecture for graphical model to incorporate attention mechanism.|
|[Shallow-to-Deep Training for Neural Machine Translation](https://aclanthology.org/2020.emnlp-main.72.pdf)|Paper|EMNLP|Propose training procedure that iteratively add model layers with sparse block to train transformer|

[Back to index](../README.md)