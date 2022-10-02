Model Zoos
==========

**Summary:** This is a non-exhaustive list of *internal* and *external* model zoos.

|

.. contents:: **Table of Contents**

|

Representation Learning Models (RLMs)
-------------------------------------

**Note:** RLMs are **task-agnostic** models which are typically used at the **state of Preprocessing** (which is sometimes incorrectly called "pretraining" phase). They are typically trained using *Self-Supervised Learning*, but Supervised and (narrow-sense) Unsupervised Learning can also be used. The end goal is to extract dense **representations / features / embeddings**. This is typically trained at an *external, larger* dataset than the one for the Downstream Task.

.. raw:: html

  <p align="center"><img src="https://raw.githubusercontent.com/GUT-AI/gut-ai/master/images/Preprocessing.png" alt="Logo" width="300"/>
  </p>

Computer Vision
^^^^^^^^^^^^^^^

**ViT**

- Paper: `An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale <https://arxiv.org/pdf/2010.11929.pdf>`_
- Code: https://github.com/google-research/vision_transformer
- Pretrained Model: https://github.com/google-research/vision_transformer
- Released: 2020
- Learning: Supervised
- Architecture: Transformer

**BEiT**

- Paper: `BEiT: BERT Pre-Training of Image Transformers <https://arxiv.org/pdf/2106.08254.pdf>`_
- Code: https://github.com/microsoft/unilm/tree/master/beit
- Pretrained Model: https://github.com/microsoft/unilm/tree/master/beit
- Released: 2021
- Learning: Self-Supervised
- Architecture: Transformer

**DeiT 3**

- Paper: `DeiT III: Revenge of the ViT <https://arxiv.org/pdf/2204.07118.pdf>`_
- Code: https://github.com/facebookresearch/deit
- Pretrained Model: https://github.com/facebookresearch/deit
- Released: 2022
- Learning: Self-Supervised
- Architecture: Transformer

NLP
^^^

**BERT**

- Paper: `BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding <https://arxiv.org/pdf/1810.04805.pdf>`_
- Code: https://github.com/google-research/bert
- Pretrained Model: https://github.com/google-research/bert
- Released: 2019
- Learning: Self-Supervised
- Architecture: Transformer

Speech Processing
^^^^^^^^^^^^^^^^^

**HuBERT**

- Paper: `HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units <https://arxiv.org/pdf/2106.07447.pdf>`_
- Code: https://github.com/facebookresearch/fairseq/tree/main/examples/hubert
- Pretrained model: https://github.com/facebookresearch/fairseq/tree/main/examples/hubert
- Released: 2021
- Learning: Self-Supervised
- Architecture: Transformer

Multimodal
^^^^^^^^^^

**ViLBERT**

- Paper: `ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks <https://arxiv.org/pdf/1908.02265.pdf>`_
- Code: https://github.com/facebookresearch/vilbert-multi-task
- Pretrained model:
- Released: 2019
- Learning: Self-Supervised
- Architecture: Transformer

**MMFT-BERT**

- Paper: `MMFT-BERT: Multimodal Fusion Transformer with BERT Encodings for Visual Question Answering <https://arxiv.org/pdf/2010.14095.pdf>`_
- Code: https://github.com/aurooj/MMFT-BERT
- Pretrained model:
- Released: 2020
- Learning: Self-Supervised
- Architecture: Transformer

**ViLT**

- Paper: `ViLT: Vision-and-Language Transformer Without Convolution or Region Supervision <https://arxiv.org/pdf/2010.14095.pdf>`_
- Code: https://github.com/dandelin/vilt
- Pretrained model: https://github.com/dandelin/vilt
- Released: 2021
- Learning: Self-Supervised
- Architecture: Transformer

Downstream Task Models (DTMs)
----------------------------

**Note:** DTMs are **task-specific** models which are typically used at the **Downstream Task**. They are typically trained using *Supervised Learning*, but Self-Supervised and (narrow-sense) Unsupervised Learning can also be used. The end goal depends on the specific task.

.. raw:: html

  <p align="center"><img src="https://github.com/GUT-AI/gut-ai/blob/master/images/DownstreamTask.png" alt="Logo" width="300"/>
  </p>


Computer Vision
^^^^^^^^^^^^^^^

NLP
^^^


Speech Processing
^^^^^^^^^^^^^^^^^

Multimodal
^^^^^^^^^^
