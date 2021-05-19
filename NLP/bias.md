# NLP - Debiasing
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Mitigating Gender Bias in Natural Language Processing: Literature Review](https://arxiv.org/ftp/arxiv/papers/1906/1906.08976.pdf)|Paper|ACL| Survey paper on gender bias and debiasing techniques present for NLP systems|
|[CrowS-Pairs: A Challenge Dataset for Measuring Social Biases in Masked Language Models](https://arxiv.org/pdf/2010.00133.pdf)|Paper|EMNLP|Propose a dataset with 9 categories of bias. Use `pseudo-log-likelihood` MLM scoring to score the probability of unmordified token conditioning on mordified tokens.|
|[Stereotype and Skew: Quantifying Gender Bias in Pre-trained and Fine-tuned Language Models](https://www.aclweb.org/anthology/2021.eacl-main.190.pdf)|Paper|EACL| Analysis gender bias in famous PLMs like RoBERTa, BERT, XLM, ALBERT, etc. and attempts to debiase with online skewness mitigation and data augmentation techniques.|
|[Gender Bias in Contextualized Word Embeddings](https://arxiv.org/pdf/1904.03310.pdf)|Paper|ACL|showed gender bias of ELMo model on WinoBias |
|[Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods](https://www.aclweb.org/anthology/N18-2003.pdf)|Paper|ACL|Propose coreference benchmark for gender bias evaluation ande debiasing methods|
|[Unmasking the Mask – Evaluating Social Biases in Masked Language Models](https://arxiv.org/pdf/2104.07496.pdf)|Paper|ArXiv|Test MLM Language models' bias level with crows-pair scoring methods and proposed all unmasked likelihood methods to score the dataset.|
[Counterfactual Data Augmentation for Mitigating Gender Stereotypes in Languages with Rich Morphology](https://www.aclweb.org/anthology/P19-1161v2.pdf)|Paper|ACL|Generate counterfactual data through dependency graph and Markov random field to inflict the gender related part of training sentences.|
|[Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings](https://www.aclweb.org/anthology/N19-1062.pdf)|Paper|ACL| Analyze gender, racial, and religiously bias in embedding trained on RedditL2Corpus. Propose soft debiasing methods, a linear transformation that preserve embed inner product while minizing projection onto bias subspace. |
|[Disentangling Document Topic and Author Gender in Multiple Languages: Lessons for Adversarial Debiasing](https://www.aclweb.org/anthology/2021.wassa-1.6.pdf)|Paper|ACL|experiment on adversarial debiasing methods that perform gradient update on feature extractor by regular and adversarial samples. Experiment focus only on the topic classification task|
|[Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://arxiv.org/pdf/1707.09457.pdf)|Paper|EMNLP|propose a corpus-level constraint method (named RBA) to debias structural prediction in NLP task, inspired from Lagrangian relaxation
[Back to index](../README.md)