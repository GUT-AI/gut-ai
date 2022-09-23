Components
==========

**Sumary:** The GUT-AI initiative is subdivived into a series of components (i.e. sub-projects) in order to build a *user-friendly* **Open-Data, Open-Source, Decentralized ecosystem** under the umbrella of the [GUT-AI Foundation](../README.md#dao-foundation). This is a list of all the components of such an ecosystem.

It is important to note that each component definition intentionally does not include *how* to be implemented, but only *what* to be implemented. The reason is that there should be **no constraints or limits** on the 'how' since new advances in Technology can potentially bring new opportunities to improve the 'how' a specific component is implemented. The 'why' each component is necessary is explained above and also in the [Vision](../README.md#vision) and [Mission](../README.md#mission) of GUT-AI. The aim of the GUT-AI initiative is *not* to reinvent the wheel. If a tool or solution for something already exits, then an integration can be created for that tool or solution.

|

.. contents:: **Table of Contents**

|

List of component identifiers
-----------------------------

See [identifiers](identifiers/README.md) for the list of identifiers of all components.

Meta Component
--------------

The **Meta** component is a component about all the other components. Its repository is the current one.

Five-Layer Architecture
-----------------------

The following **Five-Layer Architecture** is used:

* Layer 1 - Energy Layer (Physical and Data Link)
* Layer 2 - Infrastructure Layer (IaaS)
* Layer 3 - Platform Layer (PaaS)
* Layer 4 - Intelligence Layer (AIaaS)
* Layer 5 - Innovation Layer (SaaS)

**Abbreviations:**<br>
**IaaS** = Infrastructure as a Service <br>
**PaaS** = Platform as a Service <br>
**AIaaS** = AI as a Service <br>
**SaaS** = Software as a Service <br>

Layer 1 components
------------------

### Component C1.1: Distributed Smart Grids

**Description:** Bring Distributed Smart Grids into production in real life through Blockchain and AI services ([GUT-AI DCP](#component-c21-gut-ai-dc)) powered by __energy storage__. Also use AI to improve Distributed Smart Grids.

**Aims:**

* No hierarchical, centralized (electricity or communication) authority for the non-commercial, household consumers
* Use of __grid-connected microgrid__ for both electricity and communication 
* Use of specific hardware and devices
  * Distributed Renewable Energy Sources (e.g. photovoltaic panels)
  * Distributed Electricity and Energy Storage (e.g. batteries)
  * Smart Grid *connectivity* equipment (e.g. physical servers, dish antenna)
* Automated Demand-Side Management (DSM) to flatten load curve and eliminate peak load
* Use of stored energy and __valley filling DSM__ for the demands of the GUT-AI DCP through in-house physical servers
* Use of __Communication__ for proactive and online diagnosis of transient faults and prognosis of potential blackouts
* Use of __Real-Time Pricing__ through a Decentralized Exchange (DEX) for power markets
* Distributed Computer Network for __Communication, DSM__ and __Real-Time Pricing__
* Support for GUT-AI DCP and other decentralized cloud providers
* Support for interoperable electric vehicles
* Support for conventional (dieasel and petrol) vehicles
* Support for Near-Zero Energy Buildings (NZEBs)
* Support for Aeroponics, Hydroponics and Aquaponics for near-zero energy farming
* Support for conventional agronomics and livestock farming
* __Maximum freedom and liberty__ to each household on *how* to operate their own household as part of the whole ecosystem

### Component C1.2: GUT-AI DCP

**Description:** Create a dedicated Decentralized Cloud Proivder (DCP) related to GUT-AI for the __information storage__ needs.

**Aims:**

* Hosting
* Databases (SQL and NoSQL)
* Data Warehouses
* Data Lakes
* Anything else that a conventional, centralized Cloud Provider can offer

Layer 2 components
------------------

### Component C2.1: GUT-AI Marketplace

**Description:** Create a dedicated Marketplace for products (data, software apps) and services (Contractors and Freelancers) related to GUT-AI. Each digital product will be a __module__, which will be *interoperable* and *integrable* with any other module (just like *pieces of a puzzle*).

**Aims:**

* Open Data (e.g. datasets, pre-trained models) as modules
* Proprietary Data (e.g. datasets, pre-trained models) as modules
* Centralized and decentralized SaaS modules developed by third parties
* Centralized and decentralized PaaS modules developed by third parties
* Centralized and decentralized IaaS modules developed by third parties
* Marketplace for marketplaces by third parties for physical products (e.g. computers, physical servers, robots, photovoltaci panels)
* Contractors and Freelancers (e.g. Data Scientists, Data Engineers, Machine Learning Engineers, Blockchain Developers)

### Component C2.2: Automated Data Preparation

**Description:** Perform Automated Data Preparation using AI.

**Aims:**

* Data Collection
* Data Synthesis / Data Simulation / Adversarial Learning
* Data Fusion and Data Integration
* Data Wrangling / Data Munging
* Data Scraping
* Data Sampling
* Data Cleaning

### Component C2.3: CI/CD

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
* Support for Asynchronous Communication (e.g. ActiveMQ, RabbitMQ, Apache Kafka)
* Support for Synchronous Communication (e.g. REST, GraphQL)
* Support for Databases (SQL and NoSQL), Data Warehouses and Data Lakes
* Support for Data Workflow Management (e.g. Airflow, Kubeflow, MLflow)
* Support for Model Serving (e.g. KFServing, Seldon Core, BentoML)
* Direct integration to Top 10 *centralized* IaaS cloud providers
* Direct integration to Top 10 *decentralized* IaaS cloud providers
* Direct integration to [GUT-AI Marketplace](#component-c13-gut-ai-marketplace) and other marketplaces
* Webhooks and API for direct integration to IaaS, PaaS, SaaS providers
* Automation, MLOps, DataOps, MoodelOps, DevOps
* Information Security, SecDevOps, DevSecOps
* Anything else reducing the *technical debt*

### Component C2.4: DX

**Description:** Enhance Developer Experience (DX) to make it developer-friendly for almost anyone who can write code at any level.

**Aims:**

* Separation of concerns
* User-friendly User Interface (UI) and Dashboards
* User-friendly configurations (e.g. using `yaml` and `json`)
* Anything else reduing the *cultural debt* or improving the DX

Layer 3 components
------------------

### Component C3.1: AutoDS

**Description:** Perform Automated Data Science (AutoDS) by combining (internal or external) __modules__ together in an adjustable way.

**Aims:**

* [Automated Data Preparation](#component-c14-automated-data-preparation)
* [AutoML](#component-c22-automl)
* [Continual Learning](#component-c25-continual-learning)
* [CI/CD](#component-c15-cicd)

### Component C3.2: AutoML

**Description:** Perform Automated Machine Learning (AutoML).

**Aims:**

* [Automated Data Preprocessing](#component-c23-automated-data-preprocessing)
* [NAS](#component-c24-nas)

### Component C3.3: Automated Data Preprocessing

**Description:** Perform Automated Data Preprocessing.

**Aims:**

* Automated Feature Selection
* Automated Feature Extraction
    * Rule-based AI 
    * Representation Learning (Supervised, Unsupervised, Self-Supervised)
        * Data Augmentation / Contrastive Learning
        * Feature Construction / Generative Learning
        * Adversarial Learning

### Component C3.4: NAS

**Description:** Perform Neural Architecture Search (NAS).

**Aims:**

* Automated Model Selection
  * Search space
  * Architecture Optimization
  * Hyperparameter Optimization
* Automated Model Estimation

### Component C3.5: Continual Learning

**Description:** Perform Continual Learning.

**Aims:**

* Automated Model Retraining

### Component C3.6: Distributed Systems for ML

**Description:** Introduce and perform Distributed Systems that are *model-specific* for ML and especially for __Gradient-Based Optimization__ methods.

**Aims:**
* Support for *generic* Distributed Systems (e.g. Horovod, DeepSpeed)
* Devise new *ML-specific* architectures (similar to Petuum V2)

### Component C3.7: Solve memory bottleneck

**Description:** Solve the issue of memory bottleneck in order to enable the Inference of Deep Learning models in embedded devices.

**Aims:**

* Model Compression and Weight Sharing
* Nodes Pruning and Weight Pruning
* Quantized Training
* Huffman Coding
* Representation disentanglement on the sparse weight matrix
* Structured Sparsity Learning (StSL)
* Soft-Weight Sharing
* Variational Dropout
* Structured Bayesian Pruning
* Bayesian Compression
* Lottery Ticket Hypothesis
* [NAS](#component-c24-nas)
* Start with no connections, and add complexity as needed (e.g. Weighted Agnostic Neural Networks)
* Bayesian Neural Networks (BNNs)

Layer 4 components
------------------

### Component C4.1: Automated Scientific Discovery

**Description:** Perform Automated Scientific Discovery.

**Aims:** TODO

### Component C4.2: MTSU

**Description:** Perform Multitask Scence Understanding (MTSU) by applying Multitak Learning on Computer Visions tasks from a still and immobile camera.

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

### Component C4.3: Grounded CV

**Description:** Perform Grounded Computer Vision (Grounded CV) by applying Grounded Cognition on Computer Visions tasks from a single mobile robot or a single aerial robot (drone).

**Aims:**

* Simultaneous Localization and Mapping (SLAM).
* 3D Scene Reconstruction
* Surface Reconstruction
* Structure from Motion
* Feature Matching
* Active Tracking

### Component C4.4: ASR

**Description:** Perform Automatic Speech Recognition (ASR).

**Aims:** TODO

### Component C4.5: TTS

**Description:** Perform Text-to-Speech (TTS).

**Aims:** TODO

### Component C4.6: SER

**Description:** Perform Speech Emotion Recognition (SER).

**Aims:** TODO

### Component C4.7: MT

**Description:** Perform Machine Translation (MT).

**Aims:** TODO

### Component C4.8: TOD

**Description:** Perform Task-Oriented Dialog (TOD) using Multitak Learning.

**Aims:**

- Natural Language Understanding (NLU)
    - Named-Entity Recognition / Entities Extraction
    - Intent Classification / Intent Detection
- Dialog Manager
- Natural Language Generation (NLG)

### Component C4.9: QA

**Description:** Perform open-domain Question-Answering (QA).

**Aims:** TODO

### Component C4.10: Grounded QA

**Description:** Perform Grounded Question-Answering (Grounded QA).

**Aims:** TODO

### Component C4.11: VSPT

**Description:** Perform Visuo-spatial Perpsective-Taking (VSPT).

**Aims:** TODO

### Component C4.12: Multi-Robot Path Planning

**Description:** Perform Multi-Robot Path Planning.

**Aims:** TODO

### Component C4.13: Multi-Robot Target Detection and Tracking

**Description:** Perform Multi-Robot Target Detection and Tracking.

**Aims:** TODO

### Component C4.14: Anomaly Detection

**Description:** Perform Anomaly Detection.

**Aims:** TODO

### Component C4.15: Recommender Engines

**Description:** Implement Recommender Engines.

**Aims:** TODO

Layer 5 components
------------------

### Component C5.1: Automated Protoyping

**Description:** Perform Automated Protoyping.

**Aims:**

* Ideation and Creation

### Component C5.2: Automated UX

**Description:** Perform Automated User Experience (Automated UX) during Product Discovery and Product Development.

**Aims:**

* Automated User Research
* Automated User Validation
* Automated UX Research

### Component C5.3: Automated Marketing

**Description:** Perform Automated Marketing.

**Aims:** TODO

### Component C5.4: Automated Sales

**Description:** Perform Automated Sales.

**Aims:** TODO

### Component C5.5: Automated Customer Support

**Description:** Perform Customer Support.

**Aims:** TODO

### Component C5.6: Automated Governance and Compliance

**Description:** Perform Automated Governance and Compliance for the Blockchain and AI era.

**Aims:** TODO

### Component C5.7: Portfolio Management

**Description:** Perform Portfolio Management for the Blockchain and AI era.

**Aims:** TODO