# CV - Image Captioning
|Title|Type|Conference|Remarks
|--|--|--|--|
|[Deep Visual-Semantic Alignments for Generating Image Descriptions](https://cs.stanford.edu/people/karpathy/cvpr2015.pdf)|Paper|IEEE|Use CNN to represent image feature, combine with RNN-based architecture to compute alignment score for image-sentence pair. Many future works are inspired from this paper wtih modification on models for encoder and decoder side, as well as modification on the way to align/attend image and sentences.|
|[Multimodal Transformer with Multi-View Visual Representation for Image Captioning](https://arxiv.org/pdf/1905.07841.pdf)|Paper|IEEE|Explore self-attention and co-attention for image-caption task. Encoder consists of Faster R-CNN (Aligned multi-view encoder also explored) with Transformer encoder block. Decoder consists of Glove embedding + LSTM to transform the dimension and a normal Transformer decoder block.|
|[On the Automatic Generation of Medical Imaging Reports](https://arxiv.org/pdf/1711.08195.pdf)|Paper|ACL|Introduce co-attention for ChestX-Ray dataset. Tags and image features are co-atteneded then put into sentence LSTM, which controls the topic to be generated. The Word LSTM then generate the paragraph according to the topic vector by sentence LSTM.|


[Back to index](../README.md)