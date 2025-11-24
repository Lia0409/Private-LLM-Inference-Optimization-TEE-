# A List of Papers on LLM Inference Optimization

This repository collects papers on two main topics:
1. **Secure Inference via TEE-Shielded DNN Partitioning**: Explores methods that partition a Deep Neural Network (DNN) between a resource-constrained secure environment (like a TEE) and a powerful untrusted host (like a GPU). The core idea is to offload the bulk of computation to the GPU while executing only a small, critical portion of the model within the TEE. 
2.  **Efficient Inference for Large Language Models**: Focuses on techniques to optimize the performance (latency, throughput, memory) of Large Language Models (LLMs) on various hardware. 

---

## Contents

- [Secure Inference via TEE-Shielded DNN Partitioning](#secure-inference-via-tee-shielded-dnn-partitioning)
- [Efficient Inference for Large Language Models](#efficient-inference-for-large-language-models)

---

## Secure Inference via TEE-Shielded DNN Partitioning


### 2025
- Sun, Tong, Bowen Jiang, Hailong Lin, et al. “TensorShield: Safeguarding On-Device Inference by Shielding Critical DNN Tensors with TEE.” arXiv:2505.22735. Preprint, arXiv, May 28, 2025. https://doi.org/10.48550/arXiv.2505.22735. (ACM CCS'25)
  - **Code:** [https://github.com/suntong30/TensorShield](https://github.com/suntong30/TensorShield)
- Li, Ding, Ziqi Zhang, Mengyu Yao, Yifeng Cai, Yao Guo, and Xiangqun Chen. “TEESlice : Protecting Sensitive Neural Network Models in Trusted Execution Environments When Attackers Have Pre-Trained Models.” ACM Transactions on Software Engineering and Methodology 34, no. 6 (2025): 1–49. https://doi.org/10.1145/3707453.
  - **Code:** [https://github.com/ziqi-zhang/TAOISM](https://github.com/ziqi-zhang/TAOISM)
- Sun, Yu, Gaojian Xiong, Jianhua Liu, Zheng Liu, and Jian Cui. “TSQP: Safeguarding Real-Time Inference for Quantization Neural Networks on Edge Devices.” 2025 IEEE Symposium on Security and Privacy (SP), May 2025, 2114–32. https://doi.org/10.1109/SP61157.2025.00001.
  - **Code:** [https://github.com/D1aoBoomm/TSQP](https://github.com/D1aoBoomm/TSQP)
- Bai, Juyang, Md Hafizul Islam Chowdhuryy, Jingtao Li, Fan Yao, Chaitali Chakrabarti, and Deliang Fan. “Phantom: Privacy-Preserving Deep Neural Network Model Obfuscation in Heterogeneous TEE and GPU System.” 2025, 5565–82. https://www.usenix.org/conference/usenixsecurity25/presentation/bai-juyang
  - **Code:** [https://github.com/ASU-ESIC-FAN-Lab/PHANTOM_USENIX](https://github.com/ASU-ESIC-FAN-Lab/PHANTOM_USENIX)
- Moon, Myungsuk, Minhee Kim, Joonkyo Jung, and Dokyung Song. “ASGARD: Protecting On-Device Deep Neural Networks with Virtualization-Based Trusted Execution Environments.” Paper presented at Network and Distributed System Security Symposium, San Diego, CA, USA. Proceedings 2025 Network and Distributed System Security Symposium, Internet Society, 2025. https://doi.org/10.14722/ndss.2025.240449.
  - **Code:** [https://github.com/yonsei-sslab/asgard](https://github.com/yonsei-sslab/asgard)



### 2024

- Zhang, Ziqi, Chen Gong, Yifeng Cai, et al. “No Privacy Left Outside: On the (In-)Security of TEE-Shielded DNN Partition for On-Device ML.” 2024 IEEE Symposium on Security and Privacy (SP), IEEE, May 19, 2024, 3327–45. https://doi.org/10.1109/SP54263.2024.00052.
- Zhang, Zheng, Na Wang, Ziqi Zhang, et al. “GroupCover: A Secure, Efficient and Scalable Inference Framework for On-Device Model Protection Based on TEEs.” Proceedings of the 41st International Conference on Machine Learning, PMLR, July 8, 2024, 59992–60003. https://proceedings.mlr.press/v235/zhang24bn.html.
  - **Code:** [https://github.com/ZzzzMe/GroupCover](https://github.com/ZzzzMe/GroupCover)
- Liu, Ziyu, Tong Zhou, Yukui Luo, and Xiaolin Xu. “TBNet: A Neural Architectural Defense Framework Facilitating DNN Model Protection in Trusted Execution Environments.” Proceedings of the 61st ACM/IEEE Design Automation Conference, ACM, June 23, 2024, 1–6. https://doi.org/10.1145/3649329.3658251.


### 2023

- Sun, Zhichuang, Ruimin Sun, Changming Liu, Amrita Roy Chowdhury, Long Lu, and Somesh Jha. “ShadowNet: A Secure and Efficient On-Device Model Inference System for Convolutional Neural Networks.” 2023 IEEE Symposium on Security and Privacy (SP), May 2023, 1596–612. https://doi.org/10.1109/SP46215.2023.10179382.
  - **Code:** [https://github.com/RiS3-Lab/ShadowNet](https://github.com/RiS3-Lab/ShadowNet)
- Zhou, Tong, Yukui Luo, Shaolei Ren, and Xiaolin Xu. “NNSplitter: An Active Defense Solution for DNN Model via Automated Weight Obfuscation.” Proceedings of the 40th International Conference on Machine Learning, PMLR, July 3, 2023, 42614–24. https://proceedings.mlr.press/v202/zhou23h.html.
  - **Code:** [https://github.com/Tongzhou0101/NNSplitter?utm_source=catalyzex.com](https://github.com/Tongzhou0101/NNSplitter?utm_source=catalyzex.com)


### 2022


- Shen, Tianxiang, Ji Qi, Jianyu Jiang, et al. “SOTER: Guarding Black-Box Inference for General Neural Networks at the Edge.” 2022, 723–38. https://www.usenix.org/conference/atc22/presentation/shen. (USENIX ATC 22)
  - **Code:** [https://github.com/hku-systems/SOTER](https://github.com/hku-systems/SOTER)
- Hou, Jiahui, Huiqi Liu, Yunxin Liu, Yu Wang, Peng-Jun Wan, and Xiang-Yang Li. “Model Protection: Real-Time Privacy-Preserving Inference Service for Model Privacy at the Edge.” IEEE Transactions on Dependable and Secure Computing 19, no. 6 (2022): 4270–84. https://doi.org/10.1109/TDSC.2021.3126315.


### 2021

- Ng, Lucien K. L., Sherman S. M. Chow, Anna P. Y. Woo, Donald P. H. Wong, and Yongjun Zhao. “Goten: GPU-Outsourcing Trusted Execution of Neural Network Training.” Proceedings of the AAAI Conference on Artificial Intelligence 35, no. 17 (2021): 14876–83. https://doi.org/10.1609/aaai.v35i17.17746.
  - **Code:** [https://github.com/goten-team/Goten](https://github.com/goten-team/Goten)
-  Hashemi, Hanieh, Yongqin Wang, and Murali Annavaram. “DarKnight: An Accelerated Framework for Privacy and Integrity Preserving Deep Learning Using Trusted Hardware.” MICRO-54: 54th Annual IEEE/ACM International Symposium on Microarchitecture, ACM, October 18, 2021, 212–24. https://doi.org/10.1145/3466752.3480112.



### 2018

- Tramer, Florian, and Dan Boneh. “Slalom: Fast, Verifiable and Private Execution of Neural Networks in Trusted Hardware.” Paper presented at International Conference on Learning Representations. September 27, 2018. https://openreview.net/forum?id=rJVorjCcKQ.
  - **Code:** [https://github.com/ftramer/slalom](https://github.com/ftramer/slalom)
 
## Secure Inference via TEE-Shielded LLM Partitioning


- Li, Qinfeng, Zhiqiang Shen, Zhenghan Qin, et al. “TransLinkGuard: Safeguarding Transformer Models Against Model Stealing in Edge Deployment.” Proceedings of the 32nd ACM International Conference on Multimedia, ACM, October 28, 2024, 3479–88. https://doi.org/10.1145/3664647.3680786. ![Focus](https://img.shields.io/badge/LLM-blue)

- Wang, Xunjie, Jiacheng Shi, Zihan Zhao, Yang Yu, Zhichao Hua, and Jinyu Gu. “TZ-LLM: Protecting On-Device Large Language Models with Arm TrustZone.” arXiv:2511.13717. Preprint, arXiv, November 17, 2025. (EUROSYS ’26)https://doi.org/10.48550/arXiv.2511.13717.  ![Focus](https://img.shields.io/badge/LLM-blue)
  - **Code:** [https://zenodo.org/records/17213486](https://zenodo.org/records/17213486)

- Xiong, Gaojian, Yu Sun, Jianhua Liu, Jian Cui, and Jianwei Liu. “LoRO: Real-Time on-Device Secure Inference for LLMs via TEE-Based Low Rank Obfuscation.” Paper presented at The Thirty-ninth Annual Conference on Neural Information Processing Systems. October 29, 2025. https://openreview.net/forum?id=de07K7kreI.  ![Focus](https://img.shields.io/badge/LLM-blue)
  - **Code:** [https://github.com/D1aoBoomm/LoRO](https://github.com/D1aoBoomm/LoRO)


 
## Efficient Inference for Large Language Models


- Zhou, Zixuan, Xuefei Ning, Ke Hong, et al. “A Survey on Efficient Inference for Large Language Models.” arXiv:2404.14294. Preprint, arXiv, July 19, 2024. https://doi.org/10.48550/arXiv.2404.14294.
- Wang, Wenxiao, Wei Chen, Yicong Luo, et al. “Model Compression and Efficient Inference for Large Language Models: A Survey.” arXiv:2402.09748. Preprint, arXiv, February 15, 2024. https://doi.org/10.48550/arXiv.2402.09748.

- Li, Jinhao, Jiaming Xu, Shan Huang, et al. “Large Language Model Inference Acceleration: A Comprehensive Hardware Perspective.” arXiv:2410.04466. Preprint, arXiv, June 13, 2025. https://doi.org/10.48550/arXiv.2410.04466.
  - **Code:** [https://github.com/Kimho666/LLM_Hardware_Survey](https://github.com/Kimho666/LLM_Hardware_Survey)
- Liu, Jiacheng, Peng Tang, Wenfeng Wang, et al. “A Survey on Inference Optimization Techniques for Mixture of Experts Models.” arXiv:2412.14219. Preprint, arXiv, January 22, 2025. https://doi.org/10.48550/arXiv.2412.14219.
  - **Code:** [https://github.com/MoE-Inf/awesome-moe-inference?utm_source=catalyzex.com](https://github.com/MoE-Inf/awesome-moe-inference?utm_source=catalyzex.com)
  - **Code:** [https://github.com/MoE-Inf/awesome-moe-inference/](https://github.com/MoE-Inf/awesome-moe-inference/)




