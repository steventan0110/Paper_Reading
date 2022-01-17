# NLP - Machine Translation Background
|Title|Type|Conference|Remarks
|--|--|--|--|
|[NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE](https://arxiv.org/pdf/1409.0473.pdf)|Paper|ICLR|RNN-search architecture
|[Neural Machine Translation](https://www.amazon.com/Neural-Machine-Translation-Philipp-Koehn/dp/1108497322?tag=geekyadvisor-20)|Book|NA|An introducation to NMT by professor Koehn. Start from basics of neural net to seq2seq model, and covers different basic technique for machine translation, including encoder, decoder, beam search, etc.|
|[A Survey of Deep Learning Techniques for Neural Machine Translation](https://arxiv.org/pdf/2002.07526.pdf)|Paper|NA|Survey paper that summarizes various model architecture used in NMT including RNN-Search (RNN with attention), 1-D convolution, Transformer, etc.|
|[Improving Neural Machine Translation Models with Monolingual Data](https://arxiv.org/pdf/1511.06709.pdf)|Paper|ACL|Introduce and evaluate backtranslation with Monoligunal data for NMT task.
|[Effective Approaches to Attention-based Neural Machine Translation](https://www.aclweb.org/anthology/D15-1166.pdf)|Paper|EMNLP|Analysis of different attention mechanism's effect on RNN-based network. Discussed the effect of global and local attention (use a window to contrain the source side attention range) in RNN network.
|[Dual Learning for Machine Translation](https://arxiv.org/abs/1611.00179)|Paper|NIPS|Propose a dual learning system (can be extended to close loop) for NMT where a RL's reward is introduced for each sampled sentence. The reward is computed using log-prob of the opposite direction model's translation.|
|[Bridging the Gap between Training and Inference for Neural Machine Translation](https://arxiv.org/pdf/1906.02448.pdf)|Paper|ACL|sampling context words from predicted sentences to bridge the exposure bias (training v.s. inference) in NMT. Oracle words are sampled with sentence-level optimum with BLEU and force decoding.|
|[Modeling Coverage for Neural Machine Translation](https://arxiv.org/pdf/1601.04811.pdf)|Paper|ACL|Keep track of attention history to ask model pay more attention to un-translated words, to address the over/under-translation problem. Proposed both linguistic coverage model and NN-based coverage model.|
|[Domain Adaptation and Multi-Domain Adaptation for Neural Machine Translation: A Survey](https://arxiv.org/pdf/2104.06951.pdf)|Paper|ArXiv|Long survey of domain adaptation in NMT, in various aspects.|
|[Fast and Accurate Neural Machine Translation with Translation Memory](https://aclanthology.org/2021.acl-long.246.pdf)|Paper|ACL|Proposed three methods to encode TM (from similarity by Lucene) into vectors and encode them in Example Layer which modifies Transformer decoder to take into account the TM vectors|
|[Guiding neural machine translation with retrieved translation pieces](https://aclanthology.org/N18-1120/)|Paper|NAACL|Using word alignment and similarity score to up-weight similar translation result in test time.|
|[Search Engine Guided Neural Machine Translation](https://arxiv.org/pdf/1705.07267.pdf)|Paper|AAAI|Incorporate TM in training time so that the model has access to potentially good pairs found by edit distance (fuzzy match score)|
|[Graph based Translation Memory for Neural Machine Translation](https://ai.tencent.com/ailab/nlp/en/papers/aaai2019_graph_translation.pdf)|Paper|AAAI|Encode translation memory as graphical model and use graphical attention to add it into transformer.|
|[Contrastive Learning for Many-to-many Multilingual Neural Machine Translation](https://arxiv.org/pdf/2105.09501.pdf)|Paper|Arxiv|Proposed mRASP2 training method for many-to-many translation. Where RAS is Random Aligned Substitution technique based on code-switching.|
|[Fully Non-autoregressive Neural Machine Translation: Tricks of the Trade](https://arxiv.org/pdf/2012.15833.pdf)|Paper|Arxiv|Proposed fully NAT model with knowledge distillation (from autoregressive transformer), latent variable (spherical gaussian) with ELBO loss, latent alighnment loss with CTC loss, and Glancing targets sampled from a stochastic function.|
|[Levenshtein Transformer](https://proceedings.neurips.cc/paper/2019/file/675f9820626f5bc0afb47b57890b466e-Paper.pdf)|Paper|NIPS|NAT model based on transformer and insertion/deletion opertaion guided by MDP.|
|[Lexically Constrained Neural Machine Translation with Levenshtein Transformer](https://aclanthology.org/2020.acl-main.325.pdf)|Paper|ACL|Experiments based on Levenshtein transformer with constraints added in decoding phase.|
|[Guiding Teacher Forcing with Seer Forcing for Neural Machine Translation](https://aclanthology.org/2021.acl-long.223.pdf)|Paper|ACL|Propose seer decoder to distill future information for decoder|






[Back to index](../../README.md)
