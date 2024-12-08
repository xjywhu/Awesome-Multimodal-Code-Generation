<div align="center">
  <h1>👨‍💻 Awesome MLLM for Code</h1>
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="https://img.shields.io/badge/PRs-Welcome-red">
    <img src="https://img.shields.io/badge/PRs-Welcome-red" alt="PRs Welcome">
  </a>
  <a href="https://img.shields.io/github/last-commit/xjywhu/Awesome-Multimodal-LLM-for-Code?color=green">
    <img src="https://img.shields.io/github/last-commit/xjywhu/Awesome-Multimodal-LLM-for-Code?color=green" alt="Last Commit">
  </a>
</div>

![](mllm-code-logo.svg)


This repo includes papers about methods, benchmarks and evaluation for code generation under multimodal scenarios:
- UI Code Generation: Web front-end code generation, Mobile app UI code generation, etc。
- Scientific Code Generation: plot, chart, formula, etc.
- Visually Rich Programming: programming problems with image examples.
- Logo.
- Program repair under above scenarios.

[comment]: <> (multimodal code generation such as UI code generation, scientific plots code generation and so on.)

---

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## 1. Web/UI Code Generation


1. [**Design2Code: How Far Are We From Automating Front-End Engineering?.**](https://arxiv.org/abs/2403.03163) *Chenglei Si, Yanzhe Zhang, Zhengyuan Yang, Ruibo Liu, Diyi Yang
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NoviScl/Design2Code)](https://github.com/NoviScl/Design2Code)

2. [**Automatically Generating UI Code from Screenshot: A Divide-and-Conquer-Based Approach.**](https://arxiv.org/abs/2406.16386) *Yuxuan Wan, Chaozheng Wang, Yi Dong, Wenxuan Wang, Shuqing Li, Yintong Huo, Michael R. Lyu
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/DCGen)](https://github.com/WebPAI/DCGen)

3. [**Web2Code: A Large-scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs.**](https://arxiv.org/abs/2406.20098) *Sukmin Yun, Haokun Lin, Rusiru Thushara, Mohammad Qazim Bhat, Yongxin Wang, Zutao Jiang, Mingkai Deng, Jinhong Wang, Tianhua Tao, Junbo Li, Haonan Li, Preslav Nakov, Timothy Baldwin, Zhengzhong Liu, Eric P. Xing, Xiaodan Liang, Zhiqiang Shen
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MBZUAI-LLM/web2code)](https://github.com/MBZUAI-LLM/web2code)

4. [**Prototype2Code: End-to-end Front-end Code Generation from UI Design Prototypes**](https://arxiv.org/abs/2405.04975) *Shuhong Xiao, Yunnong Chen, Jiazhi Li, Liuqing Chen, Lingyun Sun, Tingting Zhou
.* Arxiv 2024.

5. [**Bridging Design and Development with Automated Declarative UI Code Generation**](https://arxiv.org/abs/2409.11667) *Ting Zhou, Yanjie Zhao, Xinyi Hou, Xiaoyu Sun, Kai Chen, Haoyu Wang
.* Arxiv 2024.

6. [**Sketch2Code: Evaluating Vision-Language Models for Interactive Web Design Prototyping**](https://arxiv.org/abs/2410.16232) *Ryan Li, Yanzhe Zhang, Diyi Yang .* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SALT-NLP/Sketch2Code)](https://github.com/SALT-NLP/Sketch2Code)

7. [**Interaction2Code: How Far Are We From Automatic Interactive Webpage Generation?**](https://arxiv.org/abs/2411.03292) *Jingyu Xiao, Yuxuan Wan, Yintong Huo, Zhiyao Xu, Michael R.Lyu
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WebPAI/Interaction2Code)](https://github.com/WebPAI/Interaction2Code)




## 2. Scientific Plots Code Generation

1. [**Plot2Code: A Comprehensive Benchmark for Evaluating Multi-modal Large Language Models in Code Generation from Scientific Plots.**](https://arxiv.org/abs/2405.07990) *Chengyue Wu, Yixiao Ge, Qiushan Guo, Jiahao Wang, Zhixuan Liang, Zeyu Lu, Ying Shan, Ping Luo
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/Plot2Code)](https://github.com/TencentARC/Plot2Code)

2. [**MatPlotAgent: Method and Evaluation for LLM-Based Agentic Scientific Data Visualization.**](https://arxiv.org/abs/2402.11453) *Zhiyu Yang, Zihan Zhou, Shuo Wang, Xin Cong, Xu Han, Yukun Yan, Zhenghao Liu, Zhixing Tan, Pengyuan Liu, Dong Yu, Zhiyuan Liu, Xiaodong Shi, Maosong Sun
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/MatPlotAgent)](https://github.com/thunlp/MatPlotAgent)

3. [**ChartMimic: Evaluating LMM's Cross-Modal Reasoning Capability via Chart-to-Code Generation.**](https://arxiv.org/abs/2406.09961) Chufan Shi, Cheng Yang, Yaxin Liu, Bo Shui, Junjie Wang, Mohan Jing, Linran Xu, Xinyu Zhu, Siheng Li, Yuxiang Zhang, Gongye Liu, Xiaomei Nie, Deng Cai, Yujiu Yang
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ChartMimic/ChartMimic)](https://github.com/ChartMimic/ChartMimic)

4. [**From Words to Structured Visuals: A Benchmark and Framework for Text-to-Diagram Generation and Editing.**](https://arxiv.org/abs/2411.11916) Jingxuan Wei, Cheng Tan, Qi Chen, Gaowei Wu, Siyuan Li, Zhangyang Gao, Linzhuang Sun, Bihui Yu, Ruifeng Guo
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

5. [**Is GPT-4V (ision) All You Need for Automating Academic Data Visualization? Exploring Vision-Language Models’ Capability in Reproducing Academic Charts.**](https://aclanthology.org/2024.findings-emnlp.485/) Zhehao Zhang, Weicheng Ma, Soroush Vosoughi
.* EMNLP 2024 (Findings). &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zzh-SJTU/AcademiaChart)](https://github.com/zzh-SJTU/AcademiaChart)





## 3. Visually Rich Programming

1. [**MMCode: Evaluating Multi-Modal Code Large Language Models with Visually Rich Programming Problems.**](https://arxiv.org/abs/2404.09486) *Kaixin Li, Yuchen Tian, Qisheng Hu, Ziyang Luo, Jing Ma
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/happylkx/MMCode)](https://github.com/happylkx/MMCode)

2. [**HumanEval-V: Evaluating Visual Understanding and Reasoning Abilities of Large Multimodal Models Through Coding Tasks.**](https://arxiv.org/abs/2410.12381) *Fengji Zhang, Linquan Wu, Huiyu Bai, Guancheng Lin, Xiao Li, Xiao Yu, Yue Wang, Bei Chen, Jacky Keung
.* Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HumanEval-V/HumanEval-V-Benchmark)](https://github.com/HumanEval-V/HumanEval-V-Benchmark)

3. [**DynEx: Dynamic Code Synthesis with Structured Design Exploration for Accelerated Exploratory Programming.**](https://arxiv.org/pdf/2410.00400) *Jenny Ma, Karthik Sreedhar, Vivian Liu, Sitong Wang, Pedro Alejandro Perez, Riya Sahni, Lydia B. Chilton
.* Arxiv 2024.


## 4. Logo Code Generation

1. [**LogoMotion: Visually Grounded Code Generation for Content-Aware Animation.**](https://arxiv.org/abs/2405.07065) *Vivian Liu, Rubaiat Habib Kazi, Li-Yi Wei, Matthew Fisher, Timothy Langlois, Seth Walker, Lydia Chilton
.* Arxiv 2024.

2. [**Chat2SVG: Vector Graphics Generation with Large Language Models and Image Diffusion Models.**](https://arxiv.org/abs/2411.16602) *Ronghuan Wu, Wanchao Su, Jing Liao
.* Arxiv 2024.




## 5. Program Repair

1. [**SWE-bench Multimodal: Do AI Systems Generalize to Visual Software Domains?**](https://arxiv.org/abs/2410.03859) *John Yang, Carlos E. Jimenez, Alex L. Zhang, Kilian Lieret, Joyce Yang, Xindi Wu, Ori Press, Niklas Muennighoff, Gabriel Synnaeve, Karthik R. Narasimhan, Diyi Yang, Sida I. Wang, Ofir Press
.* Arxiv 2024.

2. [**DesignRepair: Dual-Stream Design Guideline-Aware Frontend Repair with Large Language Models**](https://arxiv.org/abs/2411.01606) * Mingyue Yuan, Jieshan Chen, Zhenchang Xing, Aaron Quigley, Yuyu Luo, Gelareh Mohammadi, Qinghua Lu, Liming Zhu.* ICSE 2025.  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DesignRepair2024/DesignRepair2024)](https://github.com/DesignRepair2024/DesignRepair2024)


## 6. General Benchmark

1. [**Image2Struct: Benchmarking Structure Extraction for Vision-Language Models**](https://arxiv.org/abs/2410.22456) *Josselin Somerville Roberts, Tony Lee, Chi Heem Wong, Michihiro Yasunaga, Yifan Mai, Percy Liang
.* Arxiv 2024.

