.. |br| raw:: html

  <br/>

Components
==========

**Sumary:** The GUT-AI initiative is subdivived into a series of **components** (i.e. subprojects) in order to build a *user-friendly* **Open-Data, Open-Source, Decentralized ecosystem** with support from the `GUT-AI Foundation <../README.rst#dao-foundation>`_). This is a list of all the components of such an ecosystem.

It is important to note that each component definition intentionally does not include *how* to be implemented, but only *what* to be implemented. The reason is that there should be **no constraints or limits** on the 'how' since new advances in Technology can potentially bring new opportunities to improve the 'how' a specific component is implemented. The 'why' each component is necessary is explained in the Summary above and also in the `Vision <../README.md#vision>`_ and `Mission <../README.md#mission>`_ of GUT-AI. The aim of the GUT-AI initiative is *not* to reinvent the wheel. If a tool or solution for something already exits, then an integration can be created for that tool or solution.

|

.. contents:: **Table of Contents**

|

List of component identifiers
-----------------------------

See `identifiers <identifiers/README.rst>`_ for the list of identifiers of all components.

Meta Component
--------------

The **Meta** component is a component about all the other components. Its repository is the current one.

Five-Layer Architecture
-----------------------

The following **Five-Layer Architecture** is used:

* Layer 1 - Foundation Layer (Physical and Data Link)
* Layer 2 - Infrastructure Layer (IaaS)
* Layer 3 - Platform Layer (PaaS)
* Layer 4 - Intelligence Layer (AIaaS)
* Layer 5 - Innovation Layer (SaaS)
|br|
**Abbreviations:** |br|
**IaaS** = Infrastructure as a Service |br|
**PaaS** = Platform as a Service |br|
**AIaaS** = AI as a Service |br|
**SaaS** = Software as a Service |br|
**FD** = Fully Decentralized |br|
**SD** = Semi-Decentralized |br|

.. raw:: html

  <p align="center"><a href="https://gut-ai.org/"><img src="https://github.com/GUT-AI/gut-ai/blob/master/images/Protocol_layers.png" alt="Protocol layers" width="550"/></a>
  </p>

.. raw:: html

  <p align="center"><a href="https://gut-ai.org/"><img src="https://github.com/GUT-AI/gut-ai/blob/master/images/Blockchain_layers.png" alt="Blockchain layers" width="550"/></a>
  </p>


Layer 1 components
------------------

Component C1.1: Distributed Smart Grids
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Bring Distributed Smart Grids into production in real life through Blockchain and AI solutions (`GUT-AI DCP <#component-c1-2-gut-ai-dcp>`_) powered by **energy storage**. Also use AI to improve Distributed Smart Grids.

**Aims:**

* No hierarchical, centralized (electricity or communication) authority for the residential and commercial consumers (i.e. non-industrial)
* Use of **grid-connected microgrid** for both electricity and communication 
* Use of specific hardware and devices
    * Distributed Energy Sources (e.g. photovoltaic panels)
    * Distributed Electricity and Energy Storage (e.g. batteries)
    * Smart Grid *connectivity* equipment (e.g. physical servers, dish antenna)
* Use of stored energy for the demands of the GUT-AI DCP through in-house physical servers in order to reduce waste of the generated energy
* Use of **Communication** for proactive and online diagnosis of transient faults and prognosis of potential blackouts
* Use of **Real-Time Pricing** through a Decentralized Exchange (DEX) for power markets
* Distributed Computer Network for **Communication, DSM** and **Real-Time Pricing**
* Support for GUT-AI DCP and other decentralized cloud providers
* Support for Internet of Things (IoT)
* Support for interoperable electric vehicles
* Support for conventional (dieasel and petrol) vehicles
* Support for Near-Zero Energy Buildings (NZEBs)
* Support for Aeroponics, Hydroponics and Aquaponics for near-zero energy farming
* Support for conventional agronomics and livestock farming
* **Maximum freedom and liberty** to each household on *how* to operate their own household as part of the whole ecosystem

Component C1.2: GUT-AI DCP
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Create a dedicated Decentralized Cloud Proivder (DCP) related to GUT-AI for the **information storage** needs. Also use AI to improve DCP.

**Aims:**

* No hierarchical, centralized authority (i.e. similar to blockchain)
* Hosting
* Databases (SQL and NoSQL)
* Data Warehouses
* Data Lakes
* Anything else that a conventional, centralized Cloud Provider can offer

Layer 2 components
------------------

Component C2.1: GUT-AI Marketplace
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Create a dedicated Marketplace for products (data, software apps) and services (Contractors and Freelancers) related to GUT-AI. Each digital product will be a **module**, which will be *interoperable* and *integrable* with any other module (just like *pieces of a puzzle* or building blocks).

**Aims:**

* Open Data (e.g. datasets, pre-trained models) as modules
* Proprietary Data (e.g. datasets, pre-trained models) as modules
* Centralized and decentralized SaaS modules developed by third parties
* Centralized and decentralized PaaS modules developed by third parties
* Centralized and decentralized IaaS modules developed by third parties
* Marketplace for marketplaces by third parties for physical products (e.g. computers, physical servers, robots, photovoltaic panels)
* Contractors and Freelancers (e.g. Data Scientists, Data Engineers, Machine Learning Engineers, Blockchain Developers)
* Decentralized Exchange (DEX)
* Support for conventional (credit and debit card) payments
* Support for crypto payments

Component C2.2: Automated Data Preparation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Data Preparation using AI.

**Aims:**

* Data Collection
* Data Synthesis / Data Simulation / Adversarial Learning
* Data Fusion and Data Integration
* Data Wrangling / Data Munging
* Data Scraping
* Data Sampling
* Data Cleaning

Component C2.3: CI/CD
^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Continuous Integreation/Continuous Delivery (CI/CD) for all ML systems and also all associated systems. Also use AI to improve CI/CD (AIOps).

**Aims:**

* Reproducibility
* Replicability
* Code Version Control
* Data Version Control (for both datasets and pretrained models)
* Automatic Configurations (with default, but adjustable values)
* Machine Resource Management
* Governance and Regulatory Compliance (e.g. GDPR, HIPAA, ISOs)
* Monitoring and Reporting
* Diagnostics
* Testing and Quality Assurance (for both code and data)
* User of containers (e.g. Docker)
* User of orchestration (e.g. Kubernetes)
* Use of microservices
* Support for embedded devices and IoT devices
* Support for Tensor Computation Libraries (e.g. TensorFlow, PyTorch, MXNet, JAX)
* Support for Asynchronous Communication (e.g. ActiveMQ, RabbitMQ, Apache Kafka)
* Support for Synchronous Communication (e.g. REST, GraphQL)
* Support for Databases (SQL and NoSQL), Data Warehouses and Data Lakes
* Support for Data Workflow Management (e.g. Airflow, Kubeflow, MLflow)
* Support for High-Performance Model Serving (e.g. KServe, Seldon Core, BentoML)
* Direct integration to Top 10 *centralized* IaaS cloud providers
* Direct integration to Top 10 *decentralized* IaaS cloud providers
* Direct integration to `GUT-AI Marketplace <#component-c2-1-gut-ai-marketplace>`_ and other marketplaces
* Webhooks and API for direct integration to IaaS, PaaS, SaaS providers
* Automation, MLOps, DataOps, MoodelOps, DevOps
* Information Security, SecDevOps, DevSecOps
* Anything else reducing the *technical debt*

Component C2.4: DX
^^^^^^^^^^^^^^^^^^

**Description:** Enhance Developer Experience (DX) to make it developer-friendly for almost anyone who can write code at any level.

**Aims:**

* Separation of concerns
* Publication of optional standards and good practise guidelines
* User-friendly User Interface (UI) and Dashboards
* User-friendly configurations (e.g. using ``yaml`` and ``json``)
* Anything else reduing the *cultural debt* or improving the DX

Layer 3 components
------------------

Component C3.1: AutoDS
^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Data Science (AutoDS) by combining (internal or external) **modules** together in an adjustable way.

**Aims:**

* `Automated Data Preparation <#component-c2-2-automated-data-preparation>`_
* `AutoML <#component-c3-2-automl>`_
* `Continual Learning <#component-c3-5-continual-learning>`_
* `CI/CD <#component-c2-3-ci-cd>`_
* `Distributed Systems for ML <#component-c3-6-distributed-systems-for-ml>`_
* Sandbox for experiments

Component C3.2: AutoML
^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Machine Learning (AutoML).

**Aims:**

* `Automated Data Preprocessing <#component-c3-3-automated-data-preprocessing>`_
* `NAS <#component-c3-4-nas>`_
* Hyperparameter Optimization (HPO)

Component C3.3: Automated Data Preprocessing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Data Preprocessing.

**Aims:**

* Automated Feature Selection
* Automated Feature Extraction
    * Rule-based AI 
    * Representation Learning (Supervised, Unsupervised, Self-Supervised)
        * Data Augmentation / Contrastive Learning
        * Feature Construction / Generative Learning
        * Adversarial Learning
* Representation disentanglement
* Representation Transfer
* Multimodal Representation Learning
* Self-Supervised Learning (for efficient RL Downstream Tasks)

Component C3.4: NAS
^^^^^^^^^^^^^^^^^^^

**Description:** Perform Neural Architecture Search (NAS).

**Aims:**

* Automated Model Selection
    * Search space
    * Architecture Optimization
* Automated Model Estimation

Component C3.5: Continual Learning
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Continual Learning.

**Aims:**

* Automated Model Retraining
* Intra-Agent Transfer Learning in RL
* Causal Learning (to address the *Moravec's Paradox*)
* `Memory Bottleneck <#component-c3-7-memory-bottleneck>`_
* Meta Learning
* Multitask Learning
* Transfer Learning
* Few-Shot Learning
* Zero-Shot Learning
* Continual AutoML

Component C3.6: Distributed Systems for ML
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Introduce and perform Distributed Systems that are *model-specific* for ML and especially for **Gradient-Based Optimization** methods.

**Aims:**

* Support for *generic* Distributed Systems (e.g. Horovod, DeepSpeed)
* Devise new *ML-specific* architectures (similar to Petuum V2)
* Large-Scale ML

Component C3.7: Memory Bottleneck
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Solve the issue of **memory bottleneck** in order to enable the Inference of Deep Learning models in embedded devices (while also addressing *Moravec's Paradox*).

**Aims:**

* Model Compression and Weight Sharing
* Nodes Pruning and Weight Pruning
* Product Quantization (or Vevtor Quantization)
* Precision Quantization (or Scalar Quantization)
* Huffman Coding
* Representation disentanglement on the sparse weight matrix
* Structured Sparsity Learning (StSL)
* Soft-Weight Sharing
* Variational Dropout
* Structured Bayesian Pruning
* Knowledge distillation
* Bayesian Compression
* Lottery Ticket Hypothesis
* `NAS <#component-c3-4-nas>`_
* Start with no connections, and add complexity as needed (e.g. Weighted Agnostic Neural Networks)
* Weighted Linear Finite-State Machines (WLFSM)
* Bayesian Neural Networks (BNNs)
* Automated extraction of compressed knowledge
* Automated Indexing, Caching and Searching (of compressed knowledge)
* Compressed Feature Extraction (i.e. Compression of Representation Learning Models)
* Competitive Learning

Component C3.8: Multi-tool CMS
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Multi-tool Content Management System (CMS) for anything *external* to the company.

**Aims:**

* Headless CMS with independent web front-ends
* E-Commerce functionality
* Payments functionality
* Website builder using drag-and-drop elements
* Privacy-aware (GDPR-compliant)
* Plugins

Component C3.9: Multi-tool CRM
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Multi-tool Customer Relationaship Management (CRM) software for anything *internal* to the company.

**Aims:**

* Headless CRM with independent web front-ends
* Client database & Contact Management
* Payments functionality
* Quotation, Invoicing, Billing & Accounting
* Marketing Automation & Lead Management
* Workflow Automation
* Customer Support & Helpdesk
* Enterprise Management System (ERP)
* Inventory
* Contract Management
* Privacy-aware (GDPR-compliant)
* Plugins

Component C3.10: Multi-tool Task Management
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Multi-tool Task Management software for building software products.

**Aims:**

* Task Creation and Assignment
* Time Tracking and Progress Monitoring
* Bug Tracking and Issue Management
* Integration with Version Control
* Release Planning and Management
* Agile boards (Scrum and Kanban)
* Roadmaps
* Plugins

Layer 4 components
------------------

Component C4.1: Automated Scientific Discovery
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Scientific Discovery.

**Aims:** 

* `AutoML <#component-c3-2-automl>`_
* Automated Scientific Discovery using *model-based* Reinforcement Learning
* Automated Scientific Discovery using *model-free* Reinforcement Learning
* Automated Scientific Discovery using *Dynamical Systems*
* Representation disentanglement to find neural state variables
* Automated extraction of compressed knowledge
* Automated extraction of 'learnable' rules (i.e. 'oscillatory' determinism) in accordance with GUT and TLKA theory
* Causal Learning (to address the *Moravec's Paradox*)
* Representation disentanglement
* Explainable AI (XAI)
    * Counterfactuals
    * Factuals


Component C4.2: MTSU
^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Multitask Scence Understanding (MTSU) by applying Multitak Learning on Computer Visions tasks on a *still and immobile* camera.

**Aims:**

* Object Detection
* Object Recognition
* Face Recognition
* Image Segmentation (Semantic and Instance)
* Image Captioning and Image Categorization
* Visual Relationship Detection
* Action Classification
* Activity Recognition
* Pose Estimation
* Super-Resolution
* Denoising
* Image Acquisition and Reconstruction
* Image Restoration
* Image Generation
* Image Registration
* Domain Adaptation
* Multi-Object Motion Detection and Tracking
* Vision-Based Motion Analysis
* Vision as Inverse Graphics
* Image Synthesis
* Video Synthesis

Component C4.3: Grounded CV
^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Grounded Computer Vision (Grounded CV) by applying *Grounded Cognition* on Computer Visions tasks on *multiple mobile* robots or  *multiple aerial* robots (drones) or a combination of them (but using only a *single* modality, i.e. images or video).

**Aims:**

* `MTSU <#component-c4-2-mtsu>`_
* Simultaneous Localization and Mapping (SLAM).
* 3D Scene Reconstruction
* Surface Reconstruction
* Structure from Motion
* Feature Matching
* Active Tracking
* Exploration
* Navigation

Component C4.4: ASR
^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automatic Speech Recognition (ASR).

**Aims:** 

* End-to-End ASR
* ASR as Inverse TTS

Component C4.5: TTS
^^^^^^^^^^^^^^^^^^^

**Description:** Perform Text-to-Speech (TTS).

**Aims:** 

* End-to-End TTS
* Multimodal TTS

Component C4.6: SER
^^^^^^^^^^^^^^^^^^^

**Description:** Perform Speech Emotion Recognition (SER).

**Aims:** 

* Perform Unsupervised Learning to learn a hierarchical model about the number of emotions
* Representation disentanglement of lingustic (lexical) and paralinguistic (non-lexical) features
* End-to-End SER

Component C4.7: MT
^^^^^^^^^^^^^^^^^^

**Description:** Perform Machine Translation (MT) using Multitask Learning for various languages.

**Aims:** 

* End-to-End MT

Component C4.8: TOD
^^^^^^^^^^^^^^^^^^^

**Description:** Perform Task-Oriented Dialogue (TOD) using Multitak Learning.

**Aims:**

- Natural Language Understanding (NLU)
    - Named-Entity Recognition / Entities Extraction
    - Intent Classification / Intent Detection
- Dialogue Manager
- Natural Language Generation (NLG)

Component C4.9: QA
^^^^^^^^^^^^^^^^^^

**Description:** Perform open-domain Question-Answering (QA), aka Non-Task-Oriented Dialogue.

**Aims:** 

* ML-based QA (Corpus-based or Image-based)
    * Retrieval-based models (using Utterance selection)
    * Generative models
* QA as Inverse Question Generation

Component C4.10: VSPT
^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Visuo-spatial Perpsective-Taking (VSPT).

**Aims:** 

* Level 1 (L1) VSPT
* Level 2 (L2) VSPT

Component C4.11: Multi-Agent Communication
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Implement Multi-Agent Communication.

**Aims:** 

* Communication among agents in Deep RL
* Interpretation of emergent communication (among heterogenous or homogeneous agents)
* Body language
* Sign language
* Inter-Agent Transfer Learning in RL
    * Inverse Reinforcement Learning (IRL)
    * Imitation Learning
    * Learning from Demonstrations

Component C4.12: Multi-Robot Path Planning
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Multi-Robot Path Planning  (i.e. *visuo-motor* abilities).

**Aims:** 

* `MTSU <#component-c4-2-mtsu>`_
* Object-Goal Navigation
* Collision Avoidance
* Path Planning
* `Multi-Agent Communication <#component-c4-11-multi-agent-communication>`_

Component C4.13: Multi-Robot Target Detection and Tracking
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Multi-Robot Target Detection and Tracking.

**Aims:** 

* Target Detection
* Target Tracking
* `Multi-Agent Communication <#component-c4-11-multi-agent-communication>`_

Component C4.14: Anomaly Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Anomaly Detection.

**Aims:** 

* Anomaly Detection

Component C4.15: Recommender Engines
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Implement Recommender Engines.

**Aims:** 

* Recommender Engines

Component C4.16: Grounded QA
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Grounded Question-Answering (**Grounded QA**) by applying *Grounded Cognition* on QA tasks on multiple mobile robots or multiple aerial robots (drones) or a combination of them using *Multimodal Learning* (i.e. *visuo-linguistic* abilities).

**Aims:** 

* `QA <#component-c4-9-qa>`_
* `VSPT <#component-c4-10-vspt>`_
* `Multi-Agent Communication <#component-c4-11-multi-agent-communication>`_
* `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_

Component C4.17: Grounded NLP
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Grounded Natural Language Processing (Grounded NLP) by applying *Grounded Cognition* on NLP tasks on multiple mobile robots or multiple aerial robots (drones) or a combination of them using *Multimodal Learning*.

**Aims:** 

* `ASR <#component-c4-4-asr>`_
* `TTS <#component-c4-5-tts>`_
* `SER <#component-c4-6-ser>`_
* `MT <#component-c4-7-mt>`_
* `TOD <#component-c4-8-tod>`_
* `QA <#component-c4-9-qa>`_
* `VSPT <#component-c4-10-vspt>`_
* `Multi-Agent Communication <#component-c4-11-multi-agent-communication>`_
* `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_
* `Multi-Robot Target Detection and Tracking <#component-c4-13-multi-robot-target-detection-and-tracking>`_
* Multimodal Image and Video Description
* Text-to-Image and Text-to-Video Generation
* Text-to-Audio Generation (not just speech)
* Learning to follow instructions

Component C4.18: AGI and ASI
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Artificial General Intelligence (AGI) and Artificial Super-Intelligence (ASI).

**Aims:** 

* Grounded NLP
* Grounded CV
* `VSPT <#component-c4-10-vspt>`_
* `Multi-Agent Communication <#component-c4-11-multi-agent-communication>`_
* `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_
* `Multi-Robot Target Detection and Tracking <#component-c4-13-multi-robot-target-detection-and-tracking>`_
* Embedded Simulations


Layer 5 components
------------------

Component C5.1: Automated Prototyping
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Protoyping during Product Discovery.

**Aims:**

* Automated Ideation and Creation

Component C5.2: Automated UX
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated User Experience (Automated UX) during Product Discovery and Product Development.

**Aims:**

* Automated User Research
* Automated User Validation
* Automated UX Research
* Multiple A/B experiments

Component C5.3: Automated Marketing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Marketing.

**Aims:** 

* Customized campaigns

Component C5.4: Automated Sales
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Sales.

**Aims:** 

* Customized cross-sell and up-sell

Component C5.5: Automated Customer Support
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Customer Support.

**Aims:** 

* Customized support

Component C5.6: Automated Governance and Compliance
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Automated Governance and Compliance for the Blockchain and AI era.

**Aims:** 

* Automated Contracts and Compliance Reporting
* Automated Planning and Strategy
* Automated Risk Management
* Customized Privacy and Security

Component C5.7: Portfolio Management
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Portfolio Management for the Blockchain and AI era.

**Aims:** 

* Customized portfolios for the needs of the user (retail or insitutional)

Component C5.8: Air Traffic Management
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Air Traffic Management for airports.

**Aims:** 

* Scheduler: Airport Gate Assignment Problem (AGAP)
* Controller: `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_


Component C5.9: Traffic Light Management
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Traffic Light Management for electric and conventional vehicles.

**Aims:** 

* Controller: `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_

Component C5.10: Medical Imaging
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Medical Imaging on multiple biomedical modalities.

**Aims:** 

* MR data
* CT data
* Ultrasound data
* Data fusion

Component C5.11: Bioinformatics
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Bioinformatics on biological, biochemical and biophysical data.

**Aims:** 

* Genomics
* Proteomics
* Metabolomics
* Metagenomics
* Phenomics
* Transcriptomics
* Multiomics


Component C5.12: Autonomous driving
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Description:** Perform Autonomous driving for self-driving vehicles.

**Aims:** 

* `Grounded CV <#component-c4-3-grounded-cv>`_
* `Multi-Robot Path Planning <#component-c4-12-multi-robot-path-planning>`_
* `Grounded NLP <#component-c4-17-grounded-nlp>`_
