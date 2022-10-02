Model Zoos
==========

**Summary:** This is a non-exhaustive list of *internal* and *external* model zoos.

|

.. contents:: **Table of Contents**

|

Representation Learning Models (RLMs)
-------------------------------------

**Note:** RLMs are **task-agnostic** models which are typically used at the **state of Preprocessing** (which is sometimes wrongly called "pretraining" phase). They are typically trained using *Self-Supervised Learning*, but Supervised and (narrow-sense) Unsupervised Learning can also be used. The end goal is to extract dense **representations / features / embeddings**. This is typically trained at an *external, larger* dataset than the one for the Downstream Task.

NLP
^^^

**BERT**

- Paper: `BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding <https://arxiv.org/pdf/1810.04805.pdf>`_
- Code: https://github.com/google-research/bert
- Pretrained Model: https://github.com/google-research/bert
- Released: 2019

Computer Vision
^^^^^^^^^^^^^^^




Downstream Task Models (DTMs)
----------------------------

**Note:** DTMs are **task-specific** models which are typically used at the **Downstream Task**. They are typically trained using *Supervised Learning*, but Self-Supervised and (narrow-sense) Unsupervised Learning can also be used. The end goal depends on the specific task.

NLP
^^^


Computer Vision
^^^^^^^^^^^^^^^
