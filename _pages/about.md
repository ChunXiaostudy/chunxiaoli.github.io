---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I'm Xiaoxiao Wang, a master's student at the University of Chinese Academy of Sciences (UCAS), majoring in Operations Research and Cybernetics, under the supervision of Prof. Yingjie Tian. I am currently a research intern at Qiyuan National Lab, advised by Dr. Yao Zhu.

My research interests broadly include multimodal reasoning, vision-language models (VLMs), and text-to-motion generation. I am particularly passionate about building intelligent systems that combine perception and reasoning, and aim to enhance their robustness, controllability, and generalization ability in real-world scenarios.

I am currently seeking PhD opportunities, and hope to continue exploring the intersection of vision, language, and motion under world-class mentorship and collaborative research environments.


# 🔥 News
- *2025.03*: 🎉 Our paper **"Towards Annotation-Free Evaluation: KPA-Score for Human Keypoint Detection"** was submitted to **ICCV 2025**! (First author)
- *2025.03*: 🎉 Our paper **"Bridging the Gap Between Ideal and Real-world Evaluation: Benchmarking
AI-Generated Image Detection in Challenging Scenarios"** was submitted to **ICCV 2025**! (Co-first author)
- *2025.3*: 🎉 One paper on **Noise Diffusion for Enhancing Semantic Faithfulness in Text-to-Image Synthesis** accepted to **CVPR 2025**! (Third author)
- *2024.11*: 🎉 Our work on **An Efficient Framework for Enhancing Discriminative Models via Diffusion Techniques** has been accepted by **AAAI 2025**! (Co-first author)

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025 (Under Review)</div>
      <img src='images/kpa_score.png' alt="KPAScore" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Towards Annotation-Free Evaluation: KPAScore for Human Keypoint Detection**](#)

**Xiaoxiao Wang**, Chunxiao Li, Peng Sun, Boming Miao, Yunjian Zhang, Yao Zhu

- We propose *KPA-Score*, a new annotation-free evaluation metric for keypoint detection based on vision-language models (VLMs). Our method simulates human judgment through binary response probability and correlates strongly with mAP, achieving 0.71 correlation without using ground-truth annotations.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025 (Under Review)</div>
      <img src='images/bench.png' alt="Fake Image Detection Benchmark" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Bridging the Gap Between Ideal and Real-world Evaluation: Benchmarking AI-Generated Image Detection in Challenging Scenarios**](#)

Chunxiao Li\*, **Xiaoxiao Wang**\*, Meiling Li, Boming Miao, Peng Sun, Yunjian Zhang, Xiangyang Ji, Yao Zhu

- We introduce a new benchmark for AI-generated image detection that incorporates real-world distortions such as social media compression and re-digitization. Extensive experiments reveal performance gaps in existing detectors and VLMs. We also propose a robustness-aware in-context few-shot prompting method for improved detection accuracy.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVPR 2025</div>
      <img src='images/cvpr.png' alt="Noise Diffusion" width="90%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**Noise Diffusion for Enhancing Semantic Faithfulness in Text-to-Image Synthesis**](https://arxiv.org/abs/xxxx.xxxxx)

Boming Miao, Chunxiao Li, **Xiaoxiao Wang**, Andi Zhang, Rui Sun, Zizhe Wang, Yao Zhu

- We propose a simple yet effective method to optimize the latent noise of diffusion models using VLM-guided question-answering, aiming to improve semantic faithfulness of generated images. Our method is model-agnostic, training-free, and improves both VQA and CLIP-based alignment scores.
</div>
</div>
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2025</div>
      <img src='images/aaai.png' alt="Diffusion Framework for Classification" width="90%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[**An Efficient Framework for Enhancing Discriminative Models via Diffusion Techniques**](#)

Chunxiao Li\*, **Xiaoxiao Wang**\*, Boming Miao, Chuanlong Xie, Zizhe Wang, Yao Zhu

- Inspired by brain-like reasoning, we design a plug-and-play diffusion-enhanced framework for classification tasks. Low-confidence samples are reprocessed via conditional denoising paths, leading to consistent improvements across ImageNet-1K, CIFAR-10/100, and multiple robustness benchmarks.
</div>
</div>

# 🎖 Honors and Awards
- *2021.10* 🥇 First Prize (Beijing), National Undergraduate Mathematics Competition

- *2021.09* 🏆 Second Prize (National), China Undergraduate Mathematical Contest in Modeling (CUMCM)

- *2020.12* 🥉 Third Prize (National), China Undergraduate Statistical Modeling Competition

- *2021.12* 🥉 Third Prize (National), China Undergraduate Statistical Modeling Competition

# 📖 Educations
- *2023.09 – 2026.06 (expected)*, 🎓 M.Sc. in Operations Research and Cybernetics, University of Chinese Academy of Sciences. 
- *2019.09 – 2023.06*, 🎓 B.Sc. in Information and Computing Science & B.Mgt. in Big Data Management, University of Science and Technology Beijing.

## 🌱 Interests
I love modern dance, classical Chinese dance, and ballet—not just for their beauty, but for how they train the mind to flow with the body. Yoga and Pilates are my go-to rituals for balance and clarity, especially on long coding nights. I also enjoy hiking into the unknown, camera in hand, chasing light and capturing quiet moments. These passions keep me grounded, curious, and full of creative energy—both in research and in life.


