# Awesome Explainable/Interpretable Transfer Learning (XTL)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Papers and resources collection about interpretable/explainable transfer learning (XTL)

# Contents
- [Awesome Explainable/Interpretable Transfer Learning (XTL)](#awesome-explainableinterpretable-transfer-learning-xtl)
- [Contents](#contents)
- [Papers](#papers)
  - [Explainable/Interpretable AI (XAI)](#explainableinterpretable-ai-xai)
  - [Explainable/Interpretable Transfer Learning (XTL)](#explainableinterpretable-transfer-learning-xtl)
- [Datasets](#datasets)
  - [XAI](#xai)
  - [XTL](#xtl)
- [Lectures and Tutorials](#lectures-and-tutorials)
- [Other Resources](#other-resources)

# Papers

## Explainable/Interpretable AI (XAI)

**Conference**
- HIVE: Evaluating the Human Interpretability of Visual Explanations [[2022 ECCV]](https://arxiv.org/pdf/2112.03184.pdf) [[Github]](https://github.com/princetonvisualai/HIVE) [[Project]](https://princetonvisualai.github.io/HIVE/)
- B-cos Networks: Alignment is All We Need for Interpretability [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Bohle_B-Cos_Networks_Alignment_Is_All_We_Need_for_Interpretability_CVPR_2022_paper.pdf)
- HINT: Hierarchical Neuron Concept Explainer [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_HINT_Hierarchical_Neuron_Concept_Explainer_CVPR_2022_paper.pdf)
- Interpretable Part-Whole Hierarchies and Conceptual-Semantic Relationships in Neural Networks [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Garau_Interpretable_Part-Whole_Hierarchies_and_Conceptual-Semantic_Relationships_in_Neural_Networks_CVPR_2022_paper.pdf)
- Deformable_ProtoPNet_An_Interpretable_Image_Classifier_Using_Deformable_Prototypes [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Donnelly_Deformable_ProtoPNet_An_Interpretable_Image_Classifier_Using_Deformable_Prototypes_CVPR_2022_paper.pdf)
- Proto2Proto: Can you recognize the car, the way I do? [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Keswani_Proto2Proto_Can_You_Recognize_the_Car_the_Way_I_Do_CVPR_2022_paper.pdf)
- Dynamic Prototype Convolution Network for Few-Shot Semantic Segmentation [[2022 CVPR]](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Dynamic_Prototype_Convolution_Network_for_Few-Shot_Semantic_Segmentation_CVPR_2022_paper.pdf)
- Invertible Concept-based Explanations for CNN Models with Non-negative Concept Activation Vectors [[2021 AAAI]](https://arxiv.org/pdf/2006.15417.pdf)
- Interpretable Compositional Convolutional Neural Networks [[2021 IJCAI]](https://www.ijcai.org/proceedings/2021/0409.pdf)
- Graph-based High-Order Relation Discovery for Fine-grained Recognition [[2021 CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhao_Graph-Based_High-Order_Relation_Discovery_for_Fine-Grained_Recognition_CVPR_2021_paper.pdf)
- Neural Prototype Trees for Interpretable Fine-grained Image Recognition [[2021 CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Nauta_Neural_Prototype_Trees_for_Interpretable_Fine-Grained_Image_Recognition_CVPR_2021_paper.pdf)
- XProtoNet: Diagnosis in Chest Radiography with Global and Local Explanations [[2021 CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Kim_XProtoNet_Diagnosis_in_Chest_Radiography_With_Global_and_Local_Explanations_CVPR_2021_paper.pdf)
- StyleMix: Separating Content and Style for Enhanced Data Augmentation [[2021 CVPR]](https://openaccess.thecvf.com/content/CVPR2021/papers/Hong_StyleMix_Separating_Content_and_Style_for_Enhanced_Data_Augmentation_CVPR_2021_paper.pdf)
- ProtoPShare: Prototypical Parts Sharing for Similarity Discovery in Interpretable Image Classification [[2021 KDD]](https://dl.acm.org/doi/abs/10.1145/3447548.3467245)
- Towards Interpretable Deep Metric Learning with Structural Matching [[2021 ICCV]](https://arxiv.org/pdf/2108.05889.pdf) [[Code]](https://github.com/wl-zhao/DIML)
- Explaining in Style: Training a GAN to explain a classifier in StyleSpace [[2021 ICCV]](https://arxiv.org/pdf/2104.13369.pdf) [[Project]](https://explaining-in-style.github.io) [[Code]](https://github.com/google/explaining-in-style)
- This Looks Like That: Deep Learning for Interpretable Image Recognition [[2019 NIPS]](https://proceedings.neurips.cc/paper/2019/file/adf7ee2dcf142b0e11888e72b43fcb75-Paper.pdf) [[Code]](https://github.com/cfchen-duke/ProtoPNet)
- Adaptive Activation Thresholding: Dynamic Routing Type Behavior for Interpretability in Convolutional Neural Networks [[2019 ICCV]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Sun_Adaptive_Activation_Thresholding_Dynamic_Routing_Type_Behavior_for_Interpretability_in_ICCV_2019_paper.pdf) [[Code]](https://github.com/sunyiyou/dynamic-k-activation)
- Interpretable and Steerable Sequence Learning via Prototypes [[2019 KDD]](https://dl.acm.org/doi/abs/10.1145/3292500.3330908)
- Interpretable Basis Decomposition for Visual Explanation [[2018 ECCV]](https://people.csail.mit.edu/bzhou/publication/eccv18-IBD)

**Journal**
- Hierarchical Prototype Learning for Zero-Shot Recognition [[2019 TMM]](https://arxiv.org/pdf/1910.11671.pdf)

**Preprint**

**Workshop**
- This Looks Like That... Does it? Shortcomings of Latent Space Prototype Interpretability in Deep Networks [[2021 ICML Workshop]](https://icml2021-xai.github.io) [[Github]](https://github.com/fanconic/this-does-not-look-like-that)

## Explainable/Interpretable Transfer Learning (XTL)

**Conference**
- Independent Prototype Propagation for Zero-Shot Compositionality [[2021 NIPS]](https://openreview.net/pdf?id=9Oolof9tfnD) [[Code]](https://github.com/FrankRuis/protoprop)
- ToAlign: Task-oriented Alignment for Unsupervised Domain Adaptation [[2021 NIPS]](https://arxiv.org/pdf/2106.10812.pdf) [[Code]](https://github.com/microsoft/UDA)
- Visualizing Adapted Knowledge in Domain Transfer [[2021 CVPR]](https://arxiv.org/abs/2104.10602) [[Code]](https://github.com/hou-yz/DA_visualization)


**Journal**

**Preprints**

# Datasets
## XAI
- Caltech-UCSD Birds-200-2011 (CUB-200) [[2011]](https://authors.library.caltech.edu/27452/)

## XTL


# Lectures and Tutorials

# Other Resources
