Model Zoos
==========

**Summary:** This is a non-exhaustive list of *internal* and *external* model zoos.

|

.. contents:: **Table of Contents**

|

Representation Learning Models (RLMs)
-------------------------------------

**Note:** RLMs are **task-agnostic** models which are typically used at the **state of Preprocessing** (which is sometimes wrongly called "pretraining" phase). They are typically trained using *Self-Supervised Learning*, but Supervised and (narrow-sense) Unsupervised Learning can also be used. The end goal is to extract dense **representations / features / embeddings**. This is typically trained at an *external, larger* dataset than the one for the Downstream Task.

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

NLP
^^^

**BERT**

- Paper: `BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding <https://arxiv.org/pdf/1810.04805.pdf>`_
- Code: https://github.com/google-research/bert
- Pretrained Model: https://github.com/google-research/bert
- Released: 2019

Speech Processing
^^^^^^^^^^^^^^^^^

**HuBERT**

- Paper: ` <>`_
- Code: 
- Pretrained Model: 
- Released: 

Multimodal
^^^^^^^^^^



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
