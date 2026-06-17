Few-Shot Relation Extraction Fused with Prototypical Network Fusing Instance Relevance and Relation Information (IRRI)


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

