<h1 align="center"><a href="https://xinji-mai.github.io/">Xinji Mai (麦新纪)</a></h1>

<p align="center">
  <b>Agentic Reinforcement Learning · Recursive Self-Improvement · LLM Post-training · Environment Scaling</b>
</p>

<p align="center">
  <a href="https://xinji-mai.github.io"><img src="https://img.shields.io/badge/Homepage-1f6feb?style=flat-square&logo=aboutdotme&logoColor=white" alt="Homepage"></a>
  <a href="https://scholar.google.com/citations?user=6yh67YwAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0009-0003-4596-5391"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"></a>
  <a href="https://dblp.org/pid/371/9725"><img src="https://img.shields.io/badge/DBLP-1a5fb4?style=flat-square&logo=dblp&logoColor=white" alt="DBLP"></a>
  <a href="https://openreview.net/profile?id=~Xinji_Mai1"><img src="https://img.shields.io/badge/OpenReview-8C1B13?style=flat-square&logo=openreview&logoColor=white" alt="OpenReview"></a>
</p>

---

### 🧑‍🔬 About Me · 关于我

I am Xinji Mai (麦新纪), also published as Shinji Mai, an Algorithm Engineer at [Tongyi Lab, Alibaba Group](https://tongyi.aliyun.com/). My research focuses on **Agentic Reinforcement Learning, Recursive Self-Improvement (RSI), Self-Evolving Agents, and LLM Post-training**.

I lead the development of the **CuES Family (CuES, CuES-plus, and CuES-Next)**, a set of scalable, environment-grounded data synthesis pipelines. They support post-training for **Qwen3.7, Qwen3.8, and Qwen4** across Cowork, productivity, and other professional settings, as well as for specialized model families such as **QwenPaw-Flash and Piccolo**.

My research aims to raise the capability ceiling of models and agents. I see data as a foundational source of model intelligence, so I focus on building training data in executable environments and using feedback to guide post-training.

My main research directions are:

- **Agentic Reinforcement Learning (Agentic RL).** I study reinforcement learning algorithms for dialogue and agentic tasks, and explore how capabilities such as code execution emerge through RL ([Agentic RL Scaling Law](https://proceedings.neurips.cc/paper_files/paper/2025/hash/0adea62f2f98c5035aded00d4b2064e6-Abstract-Conference.html)).
- **Recursive Self-Improvement (RSI).** I design algorithms and infrastructure for continual learning and autonomous improvement, from self-directed task generation, exploration, and attribution in [AgentEvolver](https://arxiv.org/abs/2511.10395) to the co-evolution of decision models and training data in [Piccolo](https://arxiv.org/abs/2611.24651).
- **LLM Post-training.** I study feedback-driven post-training and fine-tuning methods to improve training stability and learning efficiency on long-horizon tasks.
- **Environment Scaling.** I scale executable professional work environments and use verifiable feedback to build training data. This work includes [Cowork-Gym](https://arxiv.org/abs/2610.17670) and the **CuES Family**.

My long-term goal is to help realize artificial general intelligence (AGI). I hope advances in intelligence will help people and intelligent agents live more freely and on more equal terms, with the opportunity to pursue their own aspirations.

I earned my master's degree in Computer Technology from [Fudan University](https://www.fudan.edu.cn/) in June 2026 and my bachelor's degree in Microelectronics Science and Engineering from [Sun Yat-sen University](https://www.sysu.edu.cn/) in June 2023.

- 📫 Reach me: `xjmai23@m.fudan.edu.cn`

### 📚 Selected Publications · 代表论文

> See [Google Scholar](https://scholar.google.com/citations?user=6yh67YwAAAAJ) for the full list. <sup>*</sup> Equal contribution.

- **[Piccolo: Co-Evolving Decision Models and Data through Recursive Self-Improvement](https://arxiv.org/abs/2611.24651)** · *Recursive Self-Improvement*  
  Piccolo Team. Zhenqing Ling, Qirui Jiao, Daoyuan Chen, Cheng Chen, <ins>Xinji Mai</ins>, Haowen Gao, Zhuo Zhang, Xuchen Pan, Mengsu Ding, Jiaji Deng, Yuexiang Xie, Xiaoming Qin, Weirui Kuang, Zhaoyang Liu, Yaliang Li, Bolin Ding, Jingren Zhou. *arXiv 2026*.
- **[Agentic RL Scaling Law: Spontaneous Code Execution for Mathematical Problem Solving](https://proceedings.neurips.cc/paper_files/paper/2025/hash/0adea62f2f98c5035aded00d4b2064e6-Abstract-Conference.html)** · *Agentic RL*  
  <ins>Xinji Mai</ins><sup>*</sup>, Haotian Xu<sup>*</sup>, Xing W, Weinong Wang, Yingying Zhang, Wenqiang Zhang. *NeurIPS 2025*.
- **[CuES: A Curiosity-driven and Environment-grounded Synthesis Framework for Agentic RL](https://arxiv.org/abs/2512.01311)** · *Environment-grounded Data Synthesis*  
  <ins>Shinji Mai</ins><sup>*</sup>, Yunpeng Zhai<sup>*</sup>, Ziqian Chen, Cheng Chen, Anni Zou, Shuchang Tao, Zhaoyang Liu, Bolin Ding. *arXiv 2025*.
- **[AgentEvolver: Towards Efficient Self-Evolving Agent System](https://arxiv.org/abs/2511.10395)** · *Self-Evolving Agents*  
  Yunpeng Zhai<sup>*</sup>, Shuchang Tao<sup>*</sup>, Cheng Chen<sup>*</sup>, Anni Zou<sup>*</sup>, Ziqian Chen<sup>*</sup>, Qingxu Fu<sup>*</sup>, <ins>Shinji Mai</ins><sup>*</sup>, Li Yu, Jiaji Deng, Zouying Cao, Zhaoyang Liu, Bolin Ding, Jingren Zhou. *arXiv 2025*. [Code](https://github.com/modelscope/AgentEvolver).
- **[Cowork-Gym: Synthesizing Interactive Work Environments at Scale](https://arxiv.org/abs/2610.17670)** · *Environment Scaling & Post-training*  
  Anni Zou<sup>*</sup>, Cheng Chen<sup>*</sup>, Jiaji Deng<sup>*</sup>, Weikang Zhou<sup>*</sup>, <ins>Xinji Mai</ins><sup>*</sup>, Yue Wu<sup>*</sup>, Jianing Lin, Lipeng Xie, Lixiong Qin, Qingyue Zhao, Que Shen, Shuchang Tao, Xuchen Pan, Yaliang Li, Yunpeng Zhai, Yushuo Chen, Zhihai Wang, Zhuo Zhang, Zhaoyang Liu, Bolin Ding, Jingren Zhou. *arXiv 2026*.

### 🚀 Featured Projects · 代表项目

| Project | Description |
| --- | --- |
| [CuES](https://github.com/modelscope/AgentEvolver/tree/main/research/CuES) | Public implementation of the CuES paper on environment-grounded task synthesis |
| [Agentic RL Scaling Law](https://github.com/yyht/openrlhf_async_pipline) | Code for reinforcement learning with spontaneous code execution |
| [AgentEvolver](https://github.com/modelscope/AgentEvolver) | Towards an efficient self-evolving agent system |
| [CMLM-ZhongJing](https://github.com/pariskang/CMLM-ZhongJing) | The first Traditional Chinese Medicine LLM — "ZhongJing" |

### 📬 Contact · 联系方式

- 🌐 Homepage: <https://xinji-mai.github.io>
- 🎓 Google Scholar: <https://scholar.google.com/citations?user=6yh67YwAAAAJ>
- 🆔 ORCID: <https://orcid.org/0009-0003-4596-5391>
- 📖 DBLP: <https://dblp.org/pid/371/9725>
- 📝 OpenReview: <https://openreview.net/profile?id=~Xinji_Mai1>
- 🤗 Hugging Face: <https://huggingface.co/Ice-lemon>

<!--
  This README lives in the special repository named after your GitHub account (Xinji-Mai/Xinji-Mai)
  and is rendered at the top of your GitHub profile page. Edit freely.
-->
