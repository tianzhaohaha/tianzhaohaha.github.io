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

# 🙋‍♂️ <font color="#4A708B">About Me</font>

Hi! I'm **Qingyuan Liu (刘庆远)**, a Master's student in [Computer Engineering](https://compeng.columbia.edu/) at [Columbia University](https://www.columbia.edu/).

My research aims to bridge the gap between cutting-edge AI capabilities and their responsible real-world applications by building **trustworthy AI systems**. Currently, my work focuses on **efficient fine-tuning and model editing for large language models (LLMs)**, as well as **AI-generated video detection** and **controllable diffusion generation**.

I’m fortunate to be working closely with [Jiachen Gu](https://jasonforjoy.github.io/) and [Yunzhi Yao](https://yyzcowtodd.cn/) supervised by Porf. [Nanyun (Violet) Peng ](https://violetpeng.github.io/)at the **UCLA NLP Lab**. At Columbia, I had the privilege of learning from and collaborating with Prof. [Junfeng Yang](https://www.cs.columbia.edu/~junfeng/) and Prof. [Sharon Di](https://www.engineering.columbia.edu/faculty/sharon-di).

Previously, I received my Bachelor's degree from the School of Computer Science & Technology at [Huazhong University of Science and Technology (HUST)](https://english.hust.edu.cn/).

**For more details, please take a look at my [CV](https://tianzhaohaha.github.io/files/CV-Liu-24.11.pdf)** [last update: 24.12] **!!!**


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 Our work on controllable image diffusion generation got accepted by [ICLR 2025 DeLTa workshop](https://delta-workshop.github.io/)
- *2024.07*: &nbsp;🎉🎉 Happy to be included in [2024 Spring MS Honors Students](https://www.ee.columbia.edu/ms-ee-honors-program)!
- *2024.06*: &nbsp;🎉🎉 Our work Causal Adjacency Learning (CAL) got published on [ITSC 2024](https://ieee-itsc.org/2024/)
- *2024.06*: &nbsp;🎉🎉 My research on AI-Generated Video Detection **[*DIVID*](https://arxiv.org/abs/2406.09601)** was marked as [**Columbia Engineering Research Highlight**](https://www.engineering.columbia.edu/about/news/turns-out-im-not-real-detecting-ai-generated-videos)! 

# 📝 Publications 

> (*: equal contribution)

## 🎬AI-Generated Video Detection

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><img src='images/reveal_iccv-mainflow.png' alt="sym" style="width: 100%"></div></div>
<div class='paper-box-text' markdown="1">
[LAVID: An Agentic LVLM Framework for Diffusion-Generated Video Detection](https://arxiv.org/abs/2502.14994)
**Qingyuan Liu**, Yun-Yun Tsai, Ruijian Zha, Pengyuan Shi, Victoria Li and Junfeng Yang<br>




- Designed an agentic framework **LAVID** that leverage Large Vision Language Models (LVLMs) in detecting AI-generated videos. The LVLMs will call external tools to extract additional information from the video to facilitate themselves in the detection.
- Evaluation results show LAVID improves F1 score by 6.2% to 30.2% over the top baseline on the comprehensive dataset across four SOTA LVLMs.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 GenAI Workshop</div><img src='images/DIVID.png' alt="sym" style="width: 100%"></div></div>
<div class='paper-box-text' markdown="1">
[Turns Out I'm Not Real: Towards Robust Detection of AI-Generated Videos](https://arxiv.org/abs/2406.09601)



**Qingyuan Liu**, Pengyuan Shi, Yun-Yun Tsai, Chengzhi Mao, and Junfeng Yang<br>

- Developed Diffusion Reconstruction Error (DIRE) based method **DIVID** to detect AI-generate videos; achieved a detection accuracy of up to 93.7% for videos from their benchmark dataset of videos generated from Stable Vision Diffusion, Sora, Pika, and Gen-2.
- This work was marked as the **[Columbia Engineering Research Highlight](https://www.engineering.columbia.edu/about/news/turns-out-im-not-real-detecting-ai-generated-videos)**.

</div>
</div>

## 🚗Controllable Diffusion Generation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">preprint</div><img src='images/COUNTERFACT.png' alt="sym" style="width: 100%"></div></div>
<div class='paper-box-text' markdown="1">
[Graph Out-of-Distribution Generalization via Counterfactual Augmentation]()



Zhaobin Mo\*, Baohua Yan\*, **Qingyuan Liu\***, Kangrui Ruan and Xuan Di<br>

- Used the gradient of the counterfactual classifier to interfere with the sampling process of the diffusion model, thus generating diversified datasets. The model trained on the counterfactual dataset is expected to be more generalizable.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 DeLTa workshop</div><img src='images/mnist_masked_new.png' alt="sym" style="width: 100%"></div></div>
<div class='paper-box-text' markdown="1">
[BALANCED LATENT SPACE OF DIFFUSION MODELS FOR COUNTERFACTUAL GENERATION]()




Baohua Yan, **Qingyuan Liu**, Zhaobin Mo, Kangrui Ruan and Xuan Di<br>

- we propose a framework that balances the latent space by incorporating signals that facilitate the transition to new counterfactuals while preserving factual information. We first identify the cause of this imbalance as the uncontrolled signal from the counterfactuals. Based on this understanding, we introduce a balancing method within the diffusion process. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ITSC 2024</div><img src='images/CAL.png' alt="sym" style="width: 100%"></div></div>
<div class='paper-box-text' markdown="1">
[Causal Adjacency Learning for Spatiotemporal Prediction Over Graphs](https://arxiv.org/abs/2411.16142)


Zhaobin Mo*, **Qingyuan Liu\***, Baohua Yan, Longxiang Zhang, and Xuan Di<br>

- Designed the Causal Adjacency Learning (CAL) framework, enhancing model prediction performance on the ODD dataset; applied with the heuristic method which contained the correlation calculation and Condition Independence Test.
- Achieved 14.23%, 15.49%, and 50.27% RMSE improvement in SafeGraph dataset, compared with the results based on distance, correlation, and attention matrix separately.

</div>
</div>

## 🔍Other

- [Accurate face swap using cycleGAN](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12303/2642855/Accurate-face-swap-using-cycleGAN/10.1117/12.2642855.short), **Qingyuan Liu**, Yuxuan Zhou, and Shuai Bao, Proc. SPIE 12303, International Conference on Cloud Computing, Internet of Things, and Computer Applications (**CICA**), 2022

<span class='anchor' id='--selected-projects'></span>

# 📚 Selected Projects 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/BUBBLE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bubble Bobble Game**<br>

[Report](https://www.cs.columbia.edu/~sedwards/classes/2024/4840-spring/reports/Bubble-Bobble-report.pdf) \| [Presentation](https://www.cs.columbia.edu/~sedwards/classes/2024/4840-spring/reports/Bubble-Bobble-presentation.pdf)

Course Project of CSEE4840 Embedded Systems, CU ([Rated 1st](https://www.cs.columbia.edu/~sedwards/classes/2024/4840-spring/index.html))

- Designed and implemented bubble bobble game on an embedded system utilizing both the ARM CPU and the FPGA on the DE1-SoC, with a focus on efficient video and audio processing. The system is based on line buffer, integrating various hardware inputs of VGA, Game Controller, Audio Jack, and Keyboard.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/C4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Research on 5G Network Slicing System and Strategy for End Users**<br>

[Report](https://tianzhaohaha.github.io/files/作品设计文档.pdf) \| [Presentation](https://tianzhaohaha.github.io/files/面向终端用户的5G切片系统及策略研究_演示PPT.pptx)

National Second Prize (Top 3% out of 1006 teams worldwide) in C4

- Applied Reinforcement Learning method to optimize network slicing strategy; tested strategy with 12 cellphones, increasing network throughput by 69.4% and document transfer efficiency by 82.2%.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/MIPS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Microprocessor without Interlocked Pipeline Stages (MIPS) CPU Design**<br>

[Report](https://tianzhaohaha.github.io/files/CSXJ1901_U201911111_刘庆远_硬件综合训练课程设计报告.pdf)

- Designed a CPU from the scratch with MIPS framework on the Logisim platform; Practical structures have been integrated here such as Pipeline Stalling and Brach History table.

</div>
</div>

<span class='anchor' id='-honors-and-awards'></span>

# 🏆️ Honors and Awards
- *2023.10* Advanced Master Research Student. 
- *2023.8* [2024 Spring MS Honors Students](https://www.ee.columbia.edu/ms-ee-honors-program). 
- *2023.6* [Columbia Engineering Research Highlight](https://www.engineering.columbia.edu/about/news/turns-out-im-not-real-detecting-ai-generated-videos).
- *2021.10* National Second Prize in the China Collegiate Computing Contest-Network Technology Challenge (C4). 

<span class='anchor' id='-educations'></span>

# 📖 Educations
- *2023.09 - present*, [Columbia University](https://www.columbia.edu/), New York, USA
- *2019.09 - 2023.06*, [Huazhong University of Science and Technology](https://english.hust.edu.cn/), Wuhan, China
- *2016.09 - 2019.06*, [Tianjin Xinhua High School](https://zh.wikipedia.org/wiki/%E5%A4%A9%E6%B4%A5%E5%B8%82%E6%96%B0%E5%8D%8E%E4%B8%AD%E5%AD%A6), Tianjin, China

<span class='anchor' id='-visitor-map'></span>

# 🌏️ <font color="#4A708B">Visitor Map</font>

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=712&t=m&d=NdMaGhwb-9LTDJ4hxiff-LcRvQDUeyHJTqUN9kPjXi8&cmo=ff0707&cmn=ffa451'></script>

