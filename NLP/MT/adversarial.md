# NLP - Adversarial Attack on Machine Translation
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Robust Neural Machine Translation with Doubly Adversarial Inputs](https://arxiv.org/pdf/1906.02443.pdf)|Paper|ACL|Gradient-based whitebox attack on NMT, embedding is perturbed based on model's loss as well as language model's loss (to control the direction of adversarial generation).|
|[AdvAug: Robust Adversarial Augmentation for Neural Machine Translation](https://arxiv.org/abs/2006.11834)|Paper|ACL|Modification on the Robust NMT with Doubly Adversarial Inputs by introducing vicinity and data mixup (from CV field) to generate better adversarial samples. 
|[On Adversarial Examples for Character-Level Neural Machine Translation](https://arxiv.org/abs/1806.09030)|Paper|COLING|Adding gradients to traditional blackbox attack with insert/delete/replacement by maximizing a directional derivate along the operation's vector.|
|[A Reinforced Generation of Adversarial Examples for Neural Machine Translation](https://arxiv.org/abs/1911.03677)|Paper|ACL|Introduce Actor-Critic RL network to generate adversarial samples for NMT and uses a discriminator to defend on the adversarial smaples.|
|[On Evaluation of Adversarial Perturbations for Sequence-to-Sequence Models](https://arxiv.org/abs/1903.06620)|Paper|NAACL-HLT|Propose an evaluation metric to measure the effect of adversarial attacks, enforce the semantic similarity by different constraints like KNN, CharSwap and compared the training results with and without those constraints.
|[Evaluating Robustness to Input Perturbations for Neural Machine Translation](https://www.aclweb.org/anthology/2020.acl-main.755.pdf)|Paper|ACL|Evaluate model robustness and consistence against simple blackbox attack (insert/delete/replacement by char).
|[Training on Synthetic Noise Improves Robustness to Natural Noise in Machine Translation](https://www.aclweb.org/anthology/D19-5506.pdf)|Paper|Workshop on Noisy User-generated Text| Test different noise's effect on BLEU score difference and robustness of model. Robustness is measured by BLEU difference of model trained with/without noises tested on noisy data.

[Back to index](../../README.md)