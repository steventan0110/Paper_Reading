# NLP - Machine Translation Background
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Optimizing Data Usage via Differentiable Rewards](https://arxiv.org/pdf/1911.10088.pdf)|Paper|ICML|Propose a data filtering mechanism by using gradient of NMT as the reward for a RL agent. Further study applies on multilingual data (multiDDS)|
|[BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension](https://arxiv.org/pdf/1910.13461.pdf)|Paper|ACL|BART introduce different noises into pre-train stage of a transformer based model. Noise includes: text infilling (replace several tokens with only one mask), token deletion, doc rotation, sent permutation, etc. For translation task in fine-tune stage, use different encoder to learn a different word embedding.|
|[Multilingual Denoising Pre-training for Neural Machine Translation](https://arxiv.org/pdf/2001.08210.pdf)|Paper|EMNLP| Apply BART on multilingual context and train the model to predict original text of that language|
|[MTNT: A Testbed for Machine Translation of Noisy Text](https://arxiv.org/pdf/1809.00388.pdf)|Paper|ACL|Propose MTNT noisy dataset as a test bed for denoising methods. system pretrained on europarl and wmt15 fr-en (and another system on en-ja with other datasets).|
|[On the Impact of Various Types of Noise on Neural Machine Translation](https://arxiv.org/pdf/1805.12282.pdf)|Paper|ACL|Analyze the impact of different noise (such as misaligned sentences/words, wrong languages, etc) on SMT and NMT.|

[Back to index](../../README.md)
