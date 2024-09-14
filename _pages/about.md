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

My name is Qiyuan Chen (陈启源) and I am currently a first-year Ph.D. student at the College of Computer Science and Technology, Zhejiang University, co-supervised by [Prof. Jian Wu](https://person.zju.edu.cn/0004274) and [Dr. Jintai Chen](https://whatashot.github.io/). Before that, I got my B.Sc. degree from the School of Mathematics and Statistics, Central China Normal University, under the guidance of [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm) and [Dr. Haitong Yang](http://cs.ccnu.edu.cn/info/1158/2237.htm).

My current research interests primarily include: **<span style="color:#8ECFC9">Machine Learning (ML)</span>**, **<span style="color:#82B0D2">Natural Language Processing (NLP)</span>** and **<span style="color:#FA7F6F">Multi Modal Learning (MM)</span>**. Specifically,

- Tabular Data Prediction and AutoML for Tabular Data
- Multi Modal Learning and its Applications in Medical
- Methods and Applications for Synthetic Data Generation
- Applications of LLMs (RAG, Agent, etc.) in Real-world Scenarios

**Feel free to contact me if your research lies within these or related areas!**

And I work really closely with [Qian Shao](https://abeier87.github.io/), [Hongsen Huang](https://github.com/SirlyDreamer) and [Zepeng Li](https://lzzppp.github.io/).

In my spare time, I really enjoy developing interesting websites and tools using FastAPI and Vue.js, and I'm also interested in DevOPS (CI/CD, container, etc.). If you're interested, check out my projects on my [GitHub](https://github.com/qychen2001).

I also enjoy digital devices (mechanical keyboards, NAS, etc.), badminton, running and chess in my spare time.

<div align="center">
<font color="red" size="3">
<span id="lastCommitTime"></span>
</font>
</div>

# 🔥 News

- _2024.05_, One paper on Tabular Data Prediction is accepted by **KDD 2024**.

- _2024.03_, One paper on Large Language Model Distillation is accepted by **NAACL 2024**.

- _2023.11_, I am honored to have been awarded the [Principal's Scholarship](https://mp.weixin.qq.com/s/B5e4NmFgpNsbQKAxiPb_lQ).

# 📝 Publications

<span style="color:blue">(\*: Equal contribution; $\dagger$: Corresponding author(s))</span>

## 2024

<!-- * [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation]() **<span style="color:#FA7F6F">MM</span>**]; Xiaoye Qu, **Qiyuan Chen\***, Wei Wei, Jiashuo Sun, Daizong Liu, Yu Cheng; **ACM TOMM**; 2024. [CCF B; TH-CPL B] -->

- [Alleviating Hallucination in Large Vision-Language Models with Active Retrieval Augmentation](https://arxiv.org/abs/2408.00555) [**<span style="color:#FA7F6F">MM</span>**]; Xiaoye Qu, **Qiyuan Chen\***, Wei Wei, Jiashuo Sun, Daizong Liu, Yu Cheng; **arXiv**; 2024.

- [Cross-Table Pretraining towards a Universal Function Space for Heterogeneous Tabular Data](https://arxiv.org/abs/2406.00281) [**<span style="color:#8ECFC9">ML</span>**]; Jintai Chen, Zhen Lin, **Qiyuan Chen**, Jimeng Sun; **arXiv**; 2024.

- [Take Your Steps: Hierarchically Efficient Pulmonary Disease Screening via CT Compression](https://openreview.net/forum?id=JLyiMGQoqZ); Qian Shao, Kai Zhang, Bang Du, Zepeng Li, Yixuan Wu, **Qiyuan Chen**, Jian Wu, Jintai Chen; **KDD-AIDSH**; 2024. [KDD Workshop]

- [Can a Deep Learning Model be a Sure Bet for Tabular Prediction?](https://arxiv.org/abs/2301.02819v4) [**<span style="color:#8ECFC9">ML</span>**]; Jintai Chen, Jiahuan Yan, **Qiyuan Chen**, Danny Chen, Jian Wu, Jimeng Sun; **KDD**; 2024. [CCF A; TH-CPL A]

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

## 2. [AInterview](https://github.com/qiyuan-chen/ChatInterview) (Team Lead, Main Contributor)

**You can check out the [DEMO](http://14.103.48.72/) here.**

This is a web-based tool that utilizes Large Language Models (LLMs) to help job seekers **practice for interviews** using state-of-the-art technologies such as **RAG and Agent**.

As the team lead, I spearheaded both the **architectural design** and the development of backend algorithms.

**NOTE: Due to privacy considerations, this project will be fully open-sourced in the second half of 2024.**

## 3. [PyTorch Frame ![](https://img.shields.io/github/stars/pyg-team/pytorch-frame)](https://github.com/pyg-team/pytorch-frame) (Contributor)

Added additional model and dataset support for Pytorch Frame.

# 🏅 Honors and Awards

- _2024.05_, Outstanding Graduates (Undergraduate)
- _2023.11_, Principal’s Scholarship (Undergraduate) (ONLY 10 people in the whole school each year)
- _2021.11_, China Undergraduate Mathematical Contest in Model (CUMCM), First Prize
- _2019.11_, The 19th Awarding Program For Future Scientists (The largest pre-college scientific research event in China), Second Prize

# 📖 Educations

- _2024.09 - 2029.06 (expected)_, Ph.D. in Artificial Intelligence, [College of Computer Science and Technology](http://www.cs.zju.edu.cn/csen/), Zhejiang University. Supervised by [Prof. Jian Wu](https://person.zju.edu.cn/0004274) and [Dr. Jintai Chen](https://whatashot.github.io/).

- _2020.09 - 2024.06_, B.Sc. in Statistics, [School of Mathematics and Statistics](http://maths.ccnu.edu.cn/), Central China Normal University. Advised by [Prof. Bo Li](http://maths.ccnu.edu.cn/info/1040/18436.htm) and [Dr. Haitong Yang](http://cs.ccnu.edu.cn/info/1158/2237.htm).

<!--
# 💬 Invited Talks

- *2023.11*, NLP Discuss, CCNU. [[Slides]](https://github.com/qiyuan-chen/qiyuan-chen.github.io/blob/main/talks/nlp-discuss-20231124.pdf)

-->

# 🎒 Visiting and Internship

- _2024.06 - 2024.09_, Visiting Scholar, Medical Big Data Center, Guangdong Academy of Medical Sciences, had the honor of working with [Prof. Huiying Liang](http://cmu.teacher.360eol.com/teacherBasic/preview?teacherId=16017).

# 🔎 Reviews

- Review for Conferences: ACL, EMNLP
- Review for Journals:

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
        document.getElementById('lastCommitTime').textContent = `Last Updated in ${lastCommitDate.toLocaleString()}`;
    } catch (error) {
        console.error('Error fetching commit time:', error);
        // document.getElementById('lastCommitTime').textContent = 'Failed to fetch commit time.';
    }
}
// 调用函数
fetchLastCommitTime();
</script>
</div>
