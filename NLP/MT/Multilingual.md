# Low resource and Multilingual Translation
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Survey of Low-Resource Machine Translation](https://arxiv.org/pdf/2109.00486.pdf)|Paper|ArXiv|Comprehensive survey paper on current research for low resource translation. Personally care most about transfer learning in multilingual setting.
|[Transfer Learning for Low-Resource Neural Machine Translation](https://aclanthology.org/D16-1163.pdf)|Paper|EMNLP|Use parent model trained on Fr-En to help transfer knowledge.|
|[Choosing Transfer Languages for Cross-Lingual Learning](https://aclanthology.org/P19-1301.pdf)|Paper|ACL|Train multiple transfer learning models based on variuos consideration and rank the models. For MT, data-dependent features such as relative type-token ratios is most useful.|
|[Massively Multilingual Neural Machine Translation](https://arxiv.org/pdf/1903.00089.pdf)|Paper|NAACL|Experimented on 103 languages and gained improvement on low resource translation with massive multilingual model.|
|[Universal Neural Machine Translation for Extremely Low Resource Languages](https://aclanthology.org/N18-1032.pdf)|Paper|ACL|Incorporate Universal Lexical Representation (ULR, maps word from its own embedding to an univseral embedding, which in this case, is based on En) and Mixure of Language Experts into multilingual translation for low resource languages.|
|[Improving Lexical Choice in Neural Machine Translation](https://aclanthology.org/N18-1031.pdf)|Paper|ACL|Propose methods to regularize the embedding output to be less biased on frequent words and use lexical module to make model less focused on context but on direct translation.|
|[Iterative Back-Translation for Neural Machine Translation](https://aclanthology.org/W18-2703.pdf)|ACL-WMT|Iterative backtranslation for high and low resource language gain improvement|
|[Multilingual Denoising Pre-training for Neural Machine Translation](https://arxiv.org/pdf/2001.08210.pdf)|Paper|ACL|mBART, important baseline for multilingual noisy (low resource) translation|
|[Low-Resource Corpus Filtering using Multilingual Sentence Embeddings](https://arxiv.org/pdf/1906.08885.pdf)|Paper|WMT|System paper for wmt parallel corpus filtering, using margin based score and dual conditional cross-entropy.|
|[Findings of the WMT 2019 Shared Task on Parallel Corpus Filtering for Low-Resource Conditions](https://aclanthology.org/W19-5404.pdf)|Paper|WMT|Summary paper for parallel corpus filtering approach|
|[Margin-based Parallel Corpus Mining with Multilingual Sentence Embeddings](https://arxiv.org/pdf/1811.01136.pdf)|Paper|ACL|proposed margin based score for bitext mining|
|[Cross-lingual Retrieval for Iterative Self-Supervised Training](https://arxiv.org/pdf/2006.09526.pdf)|Paper|NIPS|proposed CRISS approach to iteratively mine and train mBART. Mining is based on margin-based scoring and sentence representation is achieved with mBART.|
|[Unsupervised Bitext Mining and Translation via Self-Trained Contextual Embeddings](https://arxiv.org/pdf/2010.07761.pdf)|Paper|TACL|iteratively use mBERT to provide contextual embedding and classify pseudo sentence-pairs as positive (parallel) or negative. Then use the trained classifier to mine bitext.|



[Back to index](../../README.md)
