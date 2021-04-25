# ML - Architectures
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Attention Is All You Need](https://arxiv.org/abs/1706.03762)|Paper|NIPS|Transformer architecture uses attention mechanism to replace the auto-regressive way to encode sentence by RNN-based architecture. Allow for parallelization for training, inference is still autoregressive. Introduce positional embedding and layerwise normalization as well. Note that original paper's layer norm is different from many up-to-date implementation. |
|[SPECTRAL NORMALIZATION FOR GENERATIVE ADVERSARIAL NETWORKS](https://arxiv.org/pdf/1802.05957.pdf)|Paper|ICML|on reading plan
|[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)|Paper|NAACL|Transformer-based Pretrain Model. Instead of using autoregressive way to train LM, use masks (Masked Language Model) to pretrain the model along with Next senetence prediction task. Later variations of BERT like XLNet add in permutation for MLM task to address the problem that masked words cannot infer information from each other. 



[Back to index](../README.md)