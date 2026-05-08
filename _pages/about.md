---
permalink: /
title: ""
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

My name is Qiyuan Chen (陈启源) and I am currently a second-year Ph.D. student at the College of Computer Science and Technology, Zhejiang University, supervised by [Prof. Jian Wu](https://person.zju.edu.cn/0004274). Before that, I got my B.Sc. degree from the School of Mathematics and Statistics, Central China Normal University, under the guidance of [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm) and [Dr. Haitong Yang](http://cs.ccnu.edu.cn/info/1158/2237.htm).

My current research interests primarily include: **<span style="color:#FA7F6F">Machine Learning (ML)</span>** and **<span style="color:#82B0D2">Natural Language Processing (NLP)</span>**. Specifically,

- Semi-Supervised Learning and Long-Tailed Learning
- Tabular Data Prediction and Synthesis
- Preference Optimization in LLMs/VLMs



**Feel free to contact me if your research lies within these or related areas!**

And I work really closely with [Qian Shao](https://abeier87.github.io/), [Hongsen Huang](https://github.com/SirlyDreamer), [Jiahe Chen](https://jiahechen2002.github.io/) and [Zepeng Li](https://lzzppp.github.io/).

In my spare time, I really enjoy developing interesting websites and tools using FastAPI and Vue.js, and I'm also interested in DevOPS (CI/CD, container, etc.). If you're interested, check out my projects on my [GitHub](https://github.com/qychen2001).

I also enjoy digital devices (mechanical keyboards, NAS, etc.), badminton, running and chess in my spare time.

<font color="red">
<span id="lastCommitTime"></span>
</font>

# 🔥 News

- _2026.04_, One paper on Vision-Language Reward Modeling is accepted by **ACL 2026 Main**. See you in San Diego!

- _2026.02_, One paper on Long-Tailed Semi-Supervised Learning is accepted by **ICLR 2026**. Congratulations to Qian Shao!

- _2025.08_, One paper on Synthetic Preference Data is accepted by **EMNLP 2025 Main**. See you in Soochow!

- _2025.05_, One paper on Object Hallucination is accepted by **TOMM**. Thanks for all collaborators!


# 📝 Publications

<span style="color:blue">(\*: Equal contribution; $\dagger$: Corresponding author(s))</span>

## 2026

- [Learning What Matters: Dynamic Dimension Selection and Aggregation for Interpretable Vision-Language Reward Modeling](https://arxiv.org/abs/2604.05445) [**<span style="color:#82B0D2">NLP</span>**]; **Qiyuan Chen**, Hongsen Huang, Jiahe Chen, Qian Shao, Jintai Chen, Hongxia Xu, Renjie Hua, Ren Chuan, Jian Wu; **ACL**; 2026.

- [CoLA: Co-Calibrated Logit Adjustment for Long-Tailed Semi-Supervised Learning](https://openreview.net/pdf?id=pI9n8wAR80) [**<span style="color:#FA7F6F">ML</span>**]; Qian Shao, **Qiyuan Chen\***, Jiahe Chen, Zepeng Li, Qianqian Tang, Hongxia Xu, Jian Wu; **ICLR**; 2026. [CCF A; TH-CPL A]

- [DREAM: Distribution-aware Re-sampling with Equiangular Alignment Mechanism for Long-Tailed Semi-Supervised Learning]() [**<span style="color:#FA7F6F">ML</span>**]; Qian Shao, Jiahe Chen, **Qiyuan Chen\***, Qianqian Tang, Jintai Chen, Hongxia Xu, Jiangrui Kang, Jian Wu; **ICME**; 2026. [CCF B]

## 2025

- [Icon $^2$: Aligning Large Language Models Using Self-Synthetic Preference Data via Inherent Regulation](https://arxiv.org/abs/2509.05605) [**<span style="color:#82B0D2">NLP</span>**]; **Qiyuan Chen**, Hongsen Huang, Qian Shao, Jiahe Chen, Jintai Chen, Hongxia Xu, Renjie Hua, Ren Chuan, Jian Wu; **EMNLP**; 2025. [CCF B; TH-CPL A]

- [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation](https://dl.acm.org/doi/10.1145/3742434) [**<span style="color:#82B0D2">NLP</span>**]; Xiaoye Qu, **Qiyuan Chen\***, Wei Wei, Jiashuo Sun, Daizong Liu, Yu Cheng; **ACM TOMM**; 2025. [CCF B; TH-CPL B]

- [AI Approaches for Predicting Progression to Acute Coronary Syndrome among Stable Coronary Heart Disease Patients](https://www.nature.com/articles/s44325-025-00094-2) [**<span style="color:#FA7F6F">ML</span>**]; Haozhong Ma, Hexiang Bai, Jiahuan Yan, **Qiyuan Chen**, Zihan Ma, Shuo Tong, Yuxuan Zhan, Ruijia Wu, Hongxia Xu, Jian Wu; **npj Cardiovascular Health**; 2025.

- [CC-GSEO-Bench: A Content-Centric Benchmark for Measuring Source Influence in Generative Search Engines](http://arxiv.org/abs/2509.05607) [**<span style="color:#82B0D2">NLP</span>**]; **Qiyuan Chen**, Jiahe Chen, Hongsen Huang, Qian Shao, Jintai Chen, Renjie
Hua, Hongxia Xu, Ruijia Wu, Ren Chuan, Jian Wu; **arXiv**; 2025.

- [MM-DADM: Multimodal Drug-Aware Diffusion Model for Virtual Clinical Trials](https://arxiv.org/pdf/2502.07297); [**<span style="color:#FA7F6F">ML</span>**]; Qian Shao, Bang Du, Zepeng Li, **Qiyuan Chen**, Jiahe Chen, Hongxia Xu, Jimeng Sun, Jian Wu, Jintai Chen; **arXiv**; 2025.

- [Curing Semantic Drift: A Dynamic Approach to Grounding Generation in Large Vision-Language Models](https://arxiv.org/abs/2506.21509) [**<span style="color:#82B0D2">NLP</span>**]; Jiahe Chen, Jiaying He, **Qiyuan Chen**, Qian Shao, Jiahe Ying, Hongxia Xu, Jintai Chen, Jianwei Zheng, Jian Wu; **arXiv**; 2025.

## 2024

- [Enhancing Semi-Supervised Learning via Representative and Diverse Sample Selection](https://arxiv.org/abs/2409.11653) [**<span style="color:#FA7F6F">ML</span>**]; Qian Shao, Jiangrui Kang, **Qiyuan Chen\***, Zepeng Li, Hongxia Xu, Yiwen Cao, Jiajuan Liang, Jian Wu; **NIPS**; 2024. [CCF A; TH-CPL A]

- [Cross-Table Pretraining towards a Universal Function Space for Heterogeneous Tabular Data](https://arxiv.org/abs/2406.00281) [**<span style="color:#FA7F6F">ML</span>**]; Jintai Chen, Zhen Lin, **Qiyuan Chen**, Jimeng Sun; **arXiv**; 2024.

- [Take Your Steps: Hierarchically Efficient Pulmonary Disease Screening via CT Compression](https://openreview.net/forum?id=JLyiMGQoqZ) [**<span style="color:#FA7F6F">ML</span>**]; Qian Shao, Kai Zhang, Bang Du, Zepeng Li, Yixuan Wu, **Qiyuan Chen**, Jian Wu, Jintai Chen; **KDD-AIDSH**; 2024. [KDD Workshop]

- [Can a Deep Learning Model be a Sure Bet for Tabular Prediction?](https://arxiv.org/abs/2301.02819v4) [**<span style="color:#FA7F6F">ML</span>**]; Jintai Chen, Jiahuan Yan, **Qiyuan Chen**, Danny Chen, Jian Wu, Jimeng Sun; **KDD**; 2024. [CCF A; TH-CPL A]

- [Mind's Mirror: Distilling Self-Evaluation Capability and Comprehensive Thinking from Large Language Models](https://arxiv.org/abs/2311.09214) [**<span style="color:#82B0D2">NLP</span>**]; Weize Liu, Guocong Li, Kai Zhang, Bang Du, **Qiyuan Chen**, Xuming Hu, Hongxia Xu, Jintai Chen, Jian Wu; **NAACL**; 2024. [CCF B; TH-CPL B]

<!-- TEMPLATE:

* [Title](url) [**<span style="color:#82B0D2">NLP</span>**]; Author; **Conference/Journal**; Year. [CCF x; TH-CPL x] -->

# 💻 Projects

<!-- <span style="color:blue">($\dagger$: Founder; $\ddagger$: Main contributor)</span> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">3.4K stars</div><img src='images/camel_back.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Luotuo: An Instruction-following Chinese Language model, LoRA tuning on LLaMA](https://github.com/LC1332/Luotuo-Chinese-LLM)

Ziang Leng, Qiyuan Chen $\dagger$, Cheng Li

This project contains multiple sub-projects. For more sub-projects, please view the project [homepage](https://github.com/LC1332/Luotuo-Chinese-LLM).

- [LuotuoEmbedding: Generative Text Embedding Model distilled from OpenAI API](https://github.com/LC1332/Luotuo-Text-Embedding)

- [LuotuoQA: Better Conversational Question Answering Model with Answer Completion](https://github.com/LC1332/Luotuo-QA)
</div>
</div> -->

## 1. [Luotuo: An Instruction-following Chinese Language model, LoRA tuning on LLaMA ![](https://img.shields.io/github/stars/LC1332/Luotuo-Chinese-LLM)](https://github.com/LC1332/Luotuo-Chinese-LLM) (Founder)

**<span style="color:red">This project has already received over 3.5k stars.</span>**

This project contains multiple sub-projects. For more sub-projects, please view the project [homepage](https://github.com/LC1332/Luotuo-Chinese-LLM).

- [LuotuoEmbedding: Generative Text Embedding Model distilled from OpenAI API](https://github.com/LC1332/Luotuo-Text-Embedding)

- [LuotuoQA: Better Conversational Question Answering Model with Answer Completion](https://github.com/LC1332/Luotuo-QA)

## 2. [Poco: Your Pocket Coworker ![](https://img.shields.io/github/stars/poco-ai/poco-claw)](https://github.com/poco-ai/poco-claw)

A more beautiful and easier-to-use alternative to OpenClaw. It features a nicer Web UI, built-in IM support, and a sandboxed runtime for improved safety. Under the hood, it is powered by a Claude Code–based agent.

**Competition Awards:**
- AI Hackathon Tour, Hangzhou Station — 3rd Place
- AI Hackathon Tour, Zhejiang University Station — 1st Place
- AI Hackathon Tour, National Finals — 3rd Place

# 🏅 Honors and Awards

- _2024.05_, Outstanding Graduates (Undergraduate)
- _2023.11_, Principal’s Scholarship (Undergraduate) (ONLY 10 people in the whole school each year)
- _2021.11_, China Undergraduate Mathematical Contest in Model (CUMCM), First Prize, under the guidance of [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm)
- _2019.11_, The 19th Awarding Program For Future Scientists (The largest pre-college scientific research event in China), Second Prize

# 📝 Selected Blogs

## RL

- [Detailed Explanation of PPO and GRPO](https://qychen2001.github.io/blog/p/%E8%AF%A6%E8%A7%A3ppo%E4%B8%8Egrpo/)

- [Comprehensive Overview: From PPO/DPO to GRPO and Its Variants](https://qychen2001.github.io/blog/p/%E8%AF%A6%E7%BB%86%E6%A2%B3%E7%90%86-ppo/dpo-%E5%88%B0-grpo-%E5%8F%8A%E5%85%B6%E5%8F%98%E4%BD%93/)

## Agent

# 📖 Educations

- _2024.09 - 2029.06 (expected)_, Ph.D. in Artificial Intelligence, [College of Computer Science and Technology](http://www.cs.zju.edu.cn/csen/), Zhejiang University. Supervised by [Prof. Jian Wu](https://person.zju.edu.cn/0004274) and [Dr. Jintai Chen](https://whatashot.github.io/).

- _2020.09 - 2024.06_, B.Sc. in Statistics, [School of Mathematics and Statistics](http://maths.ccnu.edu.cn/), Central China Normal University. Advised by [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm) and [Dr. Haitong Yang](http://cs.ccnu.edu.cn/info/1158/2237.htm). Thanks to [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm), I was able to spend four unforgettable and wonderful years there.

# 🔎 Reviews

- Review for Conferences: ACL, EMNLP, NIPS, AAAI
- Review for Journals: JBHI

<div align="center">
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
This homepage is visited <font color="purple" size="5"><span id="busuanzi_value_site_pv"></span></font> times
</div>

<div>

<script>
async function fetchLastCommitTime() {
    const owner = 'qychen2001';
    const repo = 'qychen2001.github.io';
    const url = `https://api.github.com/repos/${owner}/${repo}/commits`;
    try {
        const response = await fetch(url);
        if (!response.ok) {
            throw new Error(`Failed to fetch data from GitHub: ${response.statusText}`);
        }
        const data = await response.json();
        const lastCommitDate = new Date(data[0].commit.committer.date);
        document.getElementById('lastCommitTime').textContent = `Last Updated in ${lastCommitDate.toLocaleDateString()}`;
    } catch (error) {
        console.error('Error fetching commit time:', error);
        // document.getElementById('lastCommitTime').textContent = 'Failed to fetch commit time.';
    }
}
fetchLastCommitTime();
</script>
</div>
