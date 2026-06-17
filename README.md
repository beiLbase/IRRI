
<p style="font-family: Microsoft YaHei, sans-serif; font-size: 28px; font-weight: bold;">
项目介绍（大号加粗字体）
</p>

<span style="font-size: 16px; font-weight: normal;">
这里是普通正文文字，用于描述项目用途、安装步骤、使用方法，字体更小且无加粗，和上方标题形成明显层级区分。
</span>

## 功能列表
- <span style="font-size: 20px; font-weight: bold;">快速部署</span>：<span style="font-size:15px;font-weight:normal;">一行命令完成环境配置，无需复杂依赖安装</span>
- <span style="font-size: 20px; font-weight: bold;">跨平台兼容</span>：<span style="font-size:15px;font-weight:normal;">Windows / MacOS / Linux 全系统适配</span>

<p align="left" style="font-family: SimHei; font-size: 30px; color: #238636; font-weight: 700;">
Few-Shot Relation Extraction Fused with Prototypical Network Fusing Instance Relevance and Relation Information (IRRI)
</p>




Task

designing a query-aware prototypical network learning

integrating query-aware prototypical network with relational information


Acknowledgements

This repository contains the implementation of IRRI, a few-shot relation extraction model developed as part of my doctor's dissertation. The model constructs a query-aware prototypical network by dynamically modeling the relevance between query instances and supporting instances, and assigns differentiated weights to each supporting instance, thereby constructing a weighted class prototype with stronger discriminativeness and higher robustness. Furthermore, this method designs an adaptive fusion module to dynamically adjust the fusion ratio between the query-aware prototype representation and relation information according to the task context, generating the final prototype representation. The related works are listed below in acknowledgment of their contributions.


Related Works
FewRel: A Large-Scale Supervised Few-Sample Relation Classification Dataset with State-of-the-Art Evaluation Results 

By Xu Han, Hao Zhu, Pengfei Yu, Ziyun Wang, Yuan Yao, Zhiyuan Liu, Maosong Sun. EMNLP 2018.

DOI: https://doi.org/10.18653/v1/D18-1514

The dataset: https://github.com/thunlp/FewRel

