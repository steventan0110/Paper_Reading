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
|[Modeling Coverage for Neural Machine Translation](https://arxiv.org/pdf/1601.04811.pdf)|Paper|ACL|Keep track of attention history to ask model pay more attention to un-translated words, to address the over/under-translation problem. Proposed both linguistic coverage model and NN-based coverage model.



[Back to index](../../README.md)