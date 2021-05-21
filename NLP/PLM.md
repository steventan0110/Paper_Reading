# NLP - Pretrained Language Models
|Title|Type|Conference|Remarks
|--|--|--|--|
|[BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)|Paper|NAACL|Transformer-based Pretrain Model. Instead of using autoregressive way to train LM, use masks (Masked Language Model) to pretrain the model along with Next senetence prediction task. Later variations of BERT like XLNet add in permutation for MLM task to address the problem that masked words cannot infer information from each other.|
|[Load What You Need: Smaller Versions of Mutlilingual BERT](https://www.aclweb.org/anthology/2020.sustainlp-1.16.pdf)|Paper|ACL|Decrease mBERT into selected languages by reducing embedding space using selected tokens. No advanced processing step is taken to generate the smaller model.
|[How multilingual is Multilingual BERT?](https://www.aclweb.org/anthology/P19-1493.pdf)|Paper|ACL|Probing experiments for mBERT shows deeper generation than simple vocabulary memorization. Zero-shot transfer is able to map learned structure onto new vocab but not systematically transform the structures.
|[BERT has a Mouth, and It Must Speak: BERT as a Markov Random Field Language Model](https://www.aclweb.org/anthology/W19-2304.pdf)|Paper|ACL|Interpretation of BERT as MRF Language Model and propose pseudo log-likelihood learning to avoid computing normalization constant Z(theta)|
|[XLNet](https://arxiv.org/pdf/1906.08237.pdf)|x|x|x|
|[ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/pdf/1905.07129.pdf)|x|x|x|
[Back to index](../README.md)