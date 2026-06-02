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

<a href="https://scholar.google.com/citations?user=j2QZb90AAAAJ&hl=en"><img src="https://img.shields.io/endpoint?url={{ url }}&label=Google%20Scholar%20Citations&logo=googlescholar&logoColor=white&labelColor=4285F4&color=success&style=flat-square" alt="Google Scholar Citations"></a>

I am a Ph.D. student in Computer Science at Brigham Young University (BYU). I received my M.S. in Computer Science and Engineering from the University of Notre Dame, and my B.Eng. in Computer Science from Beijing Jiaotong University.

My research is in AI/ML, with a focus on Large Language Models (LLMs), Vision-Language and Multimodal Large Language Models (VLMs/MLLMs), computer vision, and trustworthy AI. I am particularly interested in post-training and reasoning distillation, test-time scaling, multimodal hallucination mitigation, and image forensics. I work day-to-day with PyTorch, Hugging Face Transformers, vLLM, DeepSpeed, and PEFT/LoRA, building reproducible distributed training and evaluation pipelines.

I am actively seeking research internships in LLMs, VLMs, multimodal reasoning, generative AI, and AI safety. I am always happy to connect and discuss related ideas.


# 🔥 News
- *2026.02*: &nbsp;🎉 *FRAME* was accepted to the **CVPR 2026 SAFE Workshop**.
- *2026.01*: &nbsp;🎉 *ICPO* was accepted to **ICLR 2026**.


# 📝 Publications 

(\* denotes equal contribution)

## Image Forensics & Multimodal AI Safety

- **[FRAME: Forensic Routing and Adaptive Multi-path Evidence Fusion for Image Manipulation Detection](https://arxiv.org/abs/2605.12826v1)**  
  **Kaixiang Zhao**, Tianrun Yu, Aoxu Zhang, Junhao Su, Porter Jenkins, Amanda Hughes  
  *CVPR 2026 SAFE Workshop*

- **[TIGER: Traceable Inference with Graph-Based Evidence Routing for Mitigating Hallucinations in Multimodal Generation](https://arxiv.org/abs/2606.00232)**  
  **Kaixiang Zhao**, et al.  
  *EMNLP 2026 (under review)*

## LLM Reasoning, Distillation & Test-Time Optimization

- **[LARK: Learnability-Grounded Trajectory Selection for Efficient Reasoning Distillation](https://arxiv.org/abs/2605.30651)**  
  Tianrun Yu, **Kaixiang Zhao**, et al.  
  *NeurIPS 2026 (under review)*

- **[Provable and Practical In-Context Policy Optimization for Self-Improvement](https://arxiv.org/abs/2603.01335)**  
  Tianrun Yu, Yuxiao Yang, Zhaoyang Wang, **Kaixiang Zhao**, Porter Jenkins, Xuchao Zhang, Chetan Bansal, Huaxiu Yao, Weitong Zhang  
  *ICLR 2026*

## Trustworthy AI & Model Security

- **[A Survey on Model Extraction Attacks and Defenses for Large Language Models](https://dl.acm.org/doi/10.1145/3711896.3736573)**  
  **Kaixiang Zhao**, Lincan Li, Kaize Ding, Neil Zhenqiang Gong, Yue Zhao, Yushun Dong  
  *KDD 2025 Tutorial*

- **[A Systematic Survey of Model Extraction Attacks and Defenses: State-of-the-Art and Perspectives](https://arxiv.org/abs/2508.15031)**  
  **Kaixiang Zhao**, Lincan Li, Kaize Ding, Neil Zhenqiang Gong, Yue Zhao, Yushun Dong  
  *Preprint*

- **[GraphIP-Bench: How Hard Is It to Steal a Graph Neural Network, and Can We Stop It?](https://arxiv.org/abs/2605.12827)**  
  **Kaixiang Zhao**, Bolin Shen, Yuyang Dai, Shayok Chakraborty, Yushun Dong  
  *Preprint*

- **[Intellectual Property in Graph-Based Machine Learning as a Service: Attacks and Defenses](https://arxiv.org/abs/2508.19641)**  
  Lincan Li, Bolin Shen, Chenxi Zhao, Yuxiang Sun, **Kaixiang Zhao**, Shirui Pan, Yushun Dong  
  *Preprint*

## Federated Learning

- **[When the Server Steps In: Calibrated Updates for Fair Federated Learning](https://arxiv.org/abs/2601.05352)**  
  Tianrun Yu, **Kaixiang Zhao**, Cheng Zhang, Anjun Gao, Yueyang Quan, Zhuqing Liu, Minghong Fang  
  *WiOpt 2026*


# 📖 Educations
- *2025.08 - 2028.05 (Expected)*, Ph.D. in Computer Science, Brigham Young University, Provo, USA
- *2023.08 - 2025.08*, M.S. in Computer Science and Engineering, University of Notre Dame, USA
- *2020.09 - 2024.06*, B.Eng. in Computer Science, Beijing Jiaotong University, Beijing, China


# 🛠 Skills
- **Programming & Systems**: Python, C/C++, Bash, SQL, Git, Linux, CUDA, Docker, Slurm, LaTeX
- **ML/DL Frameworks**: PyTorch, Hugging Face Transformers, JAX, TensorFlow, vLLM, DeepSpeed, Accelerate, PEFT/LoRA, FlashAttention, NumPy, Pandas, scikit-learn
- **LLMs & Post-Training**: supervised fine-tuning, instruction tuning, reasoning distillation, chain-of-thought reasoning, test-time scaling, policy/preference optimization, model evaluation
- **VLMs, Vision & Multimodal AI**: Vision-Language Models, Multimodal LLMs, computer vision, generative AI, image/audio-text modeling, image forensics, cross-modal consistency, hallucination mitigation
- **Research Engineering**: distributed training, multi-GPU inference, model serving, retrieval-augmented generation, embeddings & vector search, reproducible evaluation pipelines, benchmark design, ablation studies
