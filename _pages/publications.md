---
permalink: /publications/
title: "Publications & Projects"
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<br>

<img src="{{ base_path }}/images/tcnet.png"
width="800" style="float: center; margin-right: 30px;"> 

**(Project,2026) TCNet: Interpretable Sensor Feature Correction for LLM-Aided Healthcare**
  - LLMs cannot directly process raw sensor data, but they can reason about interpretable statistics such as means, trends, and distributions. However, these statistical features are sensitive to noise, rotation, and other distortions. We propose TCNet, a lightweight neural network that corrects statistical IMU features under rotation and noise distortions while preserving their interpretability. TCNet achieves state-of-the-art performance on 5 public human activity recognition (HAR) benchmarks and enables robust, interpretable activity recognition for clinical diagnosis—serving as an innovative framework that feeds cleaned, human-understandable features to LLMs.

 <br>

<img src="{{ base_path }}/images/MANet.jpg"
width="800" style="float: center; margin-right: 30px;"> 

**(Project,2025) Understanding conversation without listening to it.**
  - What if we could understand conversation without listening to what people say? Our work uses a soft wearable sensor to capture vocal vibrations from the body, enabling the inference of conversational structures such as solo speech, dyadic exchange, and group interaction without recording audio.
 

 <br>

<img src="{{ base_path }}/images/gkgnet_arch.png"
width="800" style="float: center; margin-right: 30px;"> 

**(ECCV, 2024) GKGNet: Group K-Nearest Neighbor based Graph Convolutional Network for Multi-Label Image Recognition** 
  - **Ruijie Yao**, Sheng Jin, Lumin Xu, Wang Zeng, Wentao Liu, Chen Qian, Ping Luo, Ji Wu
  - [Paper](https://arxiv.org/pdf/2308.14378)  [Code](https://github.com/jin-s13/GKGNet) [Youtube](https://www.youtube.com/watch?v=oRIfIU0afgE)

  - Images often contain multiple objects whose regions are irregular and scattered, making grid-based representations suboptimal. We introduce GKGNet, a graph-based model that links semantic labels with image patches through dynamic graph construction, enabling more flexible multi-label image recognition.

 <br>

<img src="{{ base_path }}/images/unifs_arch.jpg"
width="800" style="float: center; margin-right: 30px;"> 

**(ECCV, 2024) UniFS: Universal Few-shot Instance Perception with Point Representations**
  - Sheng Jin\*, **Ruijie Yao\***, Lumin Xu, Wentao Liu, Chen Qian, Ji Wu, Ping Luo
  - [Paper](https://arxiv.org/abs/2404.19401)  [Code](https://github.com/jin-s13/UniFS) [Youtube](https://www.youtube.com/watch?v=f1rI7ym5tSs&list=LL)
  - Instance perception tasks such as detection, segmentation, pose estimation, and counting are usually treated as separate problems. We introduce UniFS, a universal few-shot framework that reformulates these tasks through dynamic point representation learning, enabling a single model to generalize across diverse instance perception tasks with minimal supervision.

 <br>

<img src="{{ base_path }}/images/spine.png"
width="800" style="float: center; margin-right: 30px;"> 

**(Project,2022~2024) Vertebral Body Detection System for Spinal X-rays**
  - Weishi Li, Ji Wu, Nanfang Xu, Shanshan Liu, Chenyi Guo, **Ruijie Yao** (First Student Inventor)
  - High-accuracy spine detection from cervical to lumbar and sacral angles, 
applied in hospitals with six patents earned.

