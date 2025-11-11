# Off2OnRL-awesome-papers [Offline Online Reinforcement Learning]


This is a collection of reasearch and review papers for **Offline to Online Reinforcement Learning (RL)** (or **Offline Online RL**). Feel free to star and fork. This site is mainly inspired by the [Awesome Offline RL list](https://github.com/hanjuku-kaso/awesome-offline-rl), please see them if you interested in newest research papers related to Offline RL too.


Maintainers:
- [Linh LPV](https://linhlpv.github.io/) (A2I2, Deakin University)


Please feel free to [pull request](https://github.com/linhlpv/Off2OnRL-awesome-papers/pulls) with the intructions provided in [Contributing](https://github.com/linhlpv/awesome-offline-to-online-RL-papers/blob/main/CONTRIBUTING.md).
```
Format:
- [title](paper linnk) [links]
    - author 1, author 2, et al. arXiv/conferences/journals, month/year.
```

For any questions, feel free to contact: l.le@deakin.edu.au

Credit: 
- The Contributing instruction is based on the workflow of [awesome-exploration-rl
](https://github.com/opendilab/awesome-exploration-rl).

## Table of Contents
- [Papers](#papers)
    - [Offline to Online](#offline-to-online)
    - [Preprints](#preprints)
    - [Submitted ICLR 2026](#submitted-iclr-2026)
    - [2025](#2025)
        - [NeurIPS 2025](#neurips-2025)
        - [ICML 2025](#icml-2025)
        - [IJCAI 2025](#ijcai-2025)
        - [AAAI 2025](#aaai-2025)
        - [ICLR 2025](#iclr-2025)
    - [2024](#2024)
        - [NeurIPS 2024](#neurips-2024)
        - [ICML 2024](#icml-2024)
        - [IJCAI 2024](#ijcai-2024)
        - [AAAI 2024](#aaai-2024)
        - [ICLR 2024](#iclr-2024)
        - [Underreviewed ICLR 24](#underreviewed-iclr-24)
    - [2023](#2023)
        - [NeurIPS 2023](#neurips-2023)
        - [ICML 2023](#icml-2023)
        - [IJCAI 2023](#ijcai-2023)
        - [AAAI 2023](#aaai-2023)
        - [ICLR 2023](#iclr-2023)
        - [ICRA 2023](#icra-2023)
    - [2022](#2022)
        - [NeurIPS 2022](#neurips-2022)
        - [ICML 2022](#icml-2022)
        - [IJCAI 2022](#ijcai-2022)
        - [AAAI 2022](#aaai-2022)
        - [ICLR 2022](#iclr-2022)
        - [CORL 2022](#corl-2022)
        - [RSS 2022](#rss-2022)
    - [Multi-Agent Reinforcement Learning](#multi-agent-reinforcement-learning)
    - [Journal Papers](#journal-papers)


## Papers
<!-- ### Surveys
- [Pretraining in Deep Reinforcement Learning: A Survey](https://arxiv.org/abs/2211.03959)
    - Zhihui Xie, Zichuan Lin, Junyou Li, Shuai Li, Deheng Ye. arXiv. 11/2022. -->
#### Preprints
- [Adversarial Fine-tuning in Offline-to-Online Reinforcement Learning for Robust Robot Control](https://arxiv.org/abs/2510.13358v1)
    - Shingo Ayabe, Hiroshi Kera, Kazuhiko Kawamoto. arXiv 2025. 10/2025.

- [MOORe: Model-based Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2201.10070v1)
    - Yihuan Mao, Chao Wang, Bin Wang, Chongjie Zhang. arXiv 2022. 01/2022.

- [Launchpad: Learning to Schedule Using Offline and Online RL Methods](https://arxiv.org/abs/2212.00639)
    - Vanamala Venkataswamy, Jake Grigsby, Andrew Grimshaw, Yanjun Qi. arXiv. 12/2022.x

- [Improving Offline-to-Online Reinforcement Learning with Q Conditioned State Entropy Exploration](https://arxiv.org/abs/2310.19805v4)
    - Ziqi Zhang, Xiao Xiong, Zifeng Zhuang, Jinxin Liu, Donglin Wang. arXiv. 10/2023.

- [Guided Online Distillation: Promoting Safe Reinforcement Learning by Offline Demonstration](https://arxiv.org/abs/2309.09408)
    - Jinning Li, Xinyi Liu, Banghua Zhu, Jiantao Jiao, Masayoshi Tomizuka, Chen Tang, Wei Zhan. arXiv. 09/2023.

- [Towards Robust Offline-to-Online Reinforcement Learning via Uncertainty and Smoothness](https://arxiv.org/abs/2309.16973)
    - Xiaoyu Wen, Xudong Yu, Rui Yang, Chenjia Bai, Zhen Wang.  arXiv. 09/2023.
- [Sample Efficient Reward Augmentation in offline-to-online Reinforcement Learning](https://arxiv.org/abs/2310.19805)
    - Ziqi Zhang, Xiao Xiong, Zifeng Zhuang, Jinxin Liu, Donglin Wang. arXiv. 10/2023.

- [AWAC: Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359) [page](https://awacrl.github.io/)
    - Ashvin Nair, Abhishek Gupta, Murtaza Dalal, Sergey Levine. arXiv. 06/2020.

- [Addressing Distribution Shift in Online Reinforcement Learning with Offline Datasets](https://offline-rl-neurips.github.io/pdf/13.pdf)
    - Seunghyun Lee, Younggyo Seo, Kimin Lee, Pieter Abbeel, Jinwoo Shin. Offline RL workshop. 12/2020.

- [Launchpad: Learning to Schedule Using Offline and Online RL Methods](https://arxiv.org/abs/2212.00639)
    - Vanamala Venkataswamy, Jake Grigsby, Andrew Grimshaw, Yanjun Qi. arXiv. 12/2022.

- [Guiding Online Reinforcement Learning with Action-Free Offline Pretraining](https://arxiv.org/abs/2301.12876)
    - Deyao Zhu, Yuhui Wang, Jürgen Schmidhuber, Mohamed Elhoseiny. arXiv. 01/2023.


- [Finetuning from Offline Reinforcement Learning: Challenges, Trade-offs and Practical Solutions](https://arxiv.org/abs/2303.17396)
    - Yicheng Luo, Jackie Kay, Edward Grefenstette, Marc Peter Deisenroth. arXiv. 03/2023.

- [PROTO: Iterative Policy Regularized Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2305.15669) 
    - Jianxiong Li, Xiao Hu, Haoran Xu, Jingjing Liu, Xianyuan Zhan, Ya-Qin Zhang. arXiv. 05/2023.

- [Seizing Serendipity: Exploiting the Value of Past Success in Off-Policy Actor-Critic](https://arxiv.org/abs/2306.02865)
    - Tianying Ji, Yu Luo, Fuchun Sun, Xianyuan Zhan, Jianwei Zhang, Huazhe Xu. arXiv. 06/2023.

- [A Simple Unified Uncertainty-Guided Framework for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2306.07541)
    - Siyuan Guo, Yanchao Sun, Jifeng Hu, Sili Huang, Hechang Chen, Haiyin Piao, Lichao Sun, Yi Chang. arXiv. 06/2023.


- [Sample Efficient Offline-to-Online Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10210487)
    - Siyuan Guo, Lixin Zou, et al.  IEEE Transactions on Knowledge and Data Engineering ( Early Access ). 08/2023.

#### Submitted ICLR 2026   
- [The Three Regimes of Offline-to-Online Reinforcement Learning](https://openreview.net/pdf/74060f4d6c443ffee85396a060e92d6db266182f.pdf)

- [Towards Optimism-Pessimism Trade-off in Model-based Offline-to-Online Reinforcement Learning](https://openreview.net/pdf/120d060d4542687f92284e6544a214497b5b4584.pdf)

- [Action-Free Offline-To-Online RL via Discretised State Policies](https://openreview.net/pdf/e6f62b596a74791650456c58a59a09b94b367996.pdf)

- [Exploration for Deployment-Efficient Reinforcement Learning Agents](https://openreview.net/pdf/96c0afc63f63b87b90069aedfb12250ed862ba49.pdf)

- [Annealing Bridges Offline and Online RL](https://openreview.net/pdf/85276a8a56404961f7e80b5d4e170c03ac85a425.pdf)

- [EXPO: Stable Reinforcement Learning with Expressive Policies](https://openreview.net/pdf/301ad3ea815c2a4dfff671c26a5a374703c7a297.pdf)

- [From Static Constraints to Dynamic Adaptation: Sample-Level Constraint Release for Offline-to-Online RL](https://openreview.net/pdf/2d3f4fe2170134841f0bfd0cb8254b1375c84917.pdf)

- [Trajectory Generation for Offline-to-Online Reinforcement Learning via Entropy Perspective](https://openreview.net/forum?id=B9ftkLlYAj)

- [How to Mitigate the Distribution Shift Problem in Robotics Control: A Robust and Adaptive Approach Based on Offline to Online Imitation Learning](https://openreview.net/pdf/f62fc724b9c5740dbf325b673e439d9003c169d4.pdf)

- [SAMG: Offline-to-Online Reinforcement Learning via State-Action-Conditional Offline Model Guidance](https://openreview.net/pdf/1fd6e6059f99c10f5e90086bb39acb481fb28010.pdf)

- [Explicitly Bounding Q‑Function Estimates for Offline-to-Online Reinforcement Learning](https://openreview.net/pdf/7bf6157235d24916218724d7c69e89d300d0a8d9.pdf)

- [Flow Matching with Injected Noise for Offline-to-Online Reinforcement Learning](https://openreview.net/pdf/4d2fb4e0e6b8d34f75d356202f101530d353f7f0.pdf)

- [Efficient Zero-Shot Coordination via Offline Policy Diversity and Online Belief Reasoning](https://openreview.net/pdf/54b0d92d22d1de327cc5ea4cd6e1e21960c3cab1.pdf)

- [Enhancing Offline-to-Online Reinforcement Learning by Adaptive Experience Aligned Diffusion Sampling](https://openreview.net/pdf/4de6329aa72ec90d4cff9476976a201d7cadc737.pdf)

- [Bridging Offline and Online Reinforcement Learning for LLMs](https://openreview.net/pdf/34c1de5b4eec72ac3cfc0ae3f1af0d7f81ab7a33.pdf)

- [Online Finetuning Decision Transformers with Policy Gradients](https://openreview.net/pdf/e56de6970f4dd7ca2c7ba17bcce203c5545c7852.pdf)

- [Generative Actor Critic](https://openreview.net/pdf/099069256c316a3fd6729fdb657df623da45b0bf.pdf)

### 2025
#### AAMAS 2025
- [Adaptive Offline Data Replay in Offline-to-Online Reinforcement Learning](https://openreview.net/forum?id=wWI1RYngAA)
    - Xu Liu, Tong Yu, Shuai Li. AAMAS 2025 Extended Abstract.



#### NeurIPS 2025
- [Robust Policy Expansion for Offline-to-Online RL under Diverse Data Corruption](https://arxiv.org/abs/2509.24748)
    - Longxiang He, Deheng Ye, Junbo Tan, Xueqian Wang, Li Shen. NeurIPS 2025.
- [Uni-RL: Unifying Online and Offline RL via Implicit Value Regularization](https://openreview.net/forum?id=mjZi8cV18P)
    - Haoran Xu, Liyuan Mao, Hui Jin, Weinan Zhang, Xianyuan Zhan, Amy Zhang. NeurIPS 2025.

#### ICML 2025
- [Offline-to-Online Reinforcement Learning with Classifier-Free Diffusion Generation](https://openreview.net/forum?id=4JbQK1qGpA)
    - Xiao Huang, Xu Liu, Enze Zhang, Tong Yu, Shuai Li. ICML 2025.

- [Online Pre-Training for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2507.08387)
    - Yongjae Shin, Jeonghye Kim, Whiyoung Jung, Sunghoon Hong, Deunsol Yoon, Youngsoo Jang, Geonhyeong Kim, Jongseong Chae, Youngchul Sung, Kanghoon Lee, Woohyung Lim. ICML 2025.

- [Leveraging Offline Data in Linear Latent Contextual Bandits](https://arxiv.org/abs/2405.17324v2)
    - Chinmaya Kausik, Kevin Tan, Ambuj Tewari. ICML 2025. Bandit problem.

#### IJCAI 2025
- [State Revisit and Re-explore: Bridging Sim-to-Real Gaps in Offline-and-Online Reinforcement Learning with An Imperfect Simulator]()
    - Xingyu Chen, Jiayi Xie, Zhijian Xu, Ruixun Liu, Shuai Yang, Zeyang Liu, Lipeng Wan, Xuguang Lan. IJCAI 2025.

#### AAAI 2025
- [Offline-to-online hyperparameter transfer for stochastic bandits](https://arxiv.org/abs/2501.02926)
    - Dravyansh Sharma, Arun Sai Suggala. AAAI 2025. Bandit problem.
- [Enhancing Online Reinforcement Learning with Meta-Learned Objective from Offline Data](https://arxiv.org/abs/2501.07346)
    - Shilong Deng, Zetao Zheng, Hongcai He, Paul Weng, Jie Shao. AAAI 2025.


#### ICLR 2025
- [FOSP: Fine-tuning Offline Safe Policy through World Models](https://openreview.net/pdf/f72da8409213f6155efba9926b0ba16e6a0ae696.pdf)
    - Chenyang Cao, Yucheng Xin, Silang Wu, Longxiang He, Zichen Yan, Junbo Tan, Xueqian Wang. ICLR 2025.
- [Efficient Online Reinforcement Learning Fine-Tuning Need Not Retain Offline Data](https://openreview.net/pdf/02ea87bd0277223354a8716440d0a30c06a5b7dd.pdf)
    - Zhiyuan Zhou, Andy Peng, Qiyang Li, Sergey Levine, Aviral Kumar. ICLR 2025.   

- [Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model](https://openreview.net/pdf/304325920749811806862e3d1b3d3e02ad2dcea9.pdf)
    - Xiu Yuan, Tongzhou Mu, Stone Tao, Yunhao Fang, Mengke Zhang, Hao Su. ICLR 2025.

### 2024
#### ICRA 2024
- [Weighting online decision transformer with episodic memory for offline-to-online reinforcement learning](https://events.infovaya.com/uploads/documents/pdfviewer/1d/8e/132760-2282.pdf)
    - Xiao Ma and Wu-Jun Li. ICRA 2024.

#### AAMAS 2024
- [ANOTO: Improving Automated Negotiation via Offline-to-Online Reinforcement Learning][https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p2195.pdf]
    - Siqi Chen, Jianing Zhao, Kai Zhao, Gerhard Weiss, Fengyun Zhang, Ran Su, Yang Dong, Daqian Li and Kaiyou Lei. AAMAS 2024 Extended Abstract.

#### NeurIPS 2024
- [Optimistic Critic Reconstruction and Constrained Fine-Tuning for General Offline-to-Online RL](https://openreview.net/forum?id=XVfevb9XFx&noteId=rkLIxK5jZ2)
    - Qin-Wen Luo, Ming-Kun Xie, Ye-Wen Wang, Sheng-Jun Huang. NeurIPS 2024.
- [Reinforcement Learning Gradients as Vitamin for Online Finetuning Decision Transformers](https://arxiv.org/abs/2410.24108)
    - Kai Yan, Alexander G. Schwing, Yu-Xiong Wang. NeurIPS Spotlight 2024.
- [Hybrid Reinforcement Learning Breaks Sample Size Barriers In Linear MDPs](https://arxiv.org/abs/2408.04526)
    - Kevin Tan, Wei Fan, Yuting Wei. NeurIPS 2024.

#### ICML 2024
- [Leveraging (Biased) Information: Multi-armed Bandits with Offline Data](https://arxiv.org/abs/2405.02594)
    - Wang Chi Cheung, Lixing Lyu. ICML 2024 Spotlight. Bandit problem.

- [Hybrid Reinforcement Learning from Offline Observation Alone](https://arxiv.org/abs/2406.07253)
    - Yuda Song, J. Andrew Bagnell, Aarti Singh. ICML 2024. 06/2024.

- [Bayesian Design Principles for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2405.20984)
    - Hao Hu, Yiqin Yang, Jianing Ye, Chengjie Wu, Ziqing Mai, Yujing Hu, Tangjie Lv, Changjie Fan, Qianchuan Zhao, Chongjie Zhang. ICML 2024. 

- [Energy-Guided Diffusion Sampling for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2407.12448)
    - Xu-Hui Liu, Tian-Shuo Liu, Shengyi Jiang, Ruifeng Chen, Zhilong Zhang, Xinwei Chen, Yang Yu. ICML 2024. 

- [OLLIE: Imitation Learning from Offline Pretraining to Online Finetuning](https://arxiv.org/abs/2405.17477)
    - Sheng Yue, Xingyuan Hua, Ju Ren, Sen Lin, Junshan Zhang, Yaoxue Zhang. ICML 2024. Imitation Learning.

- [Offline-Boosted Actor-Critic: Adaptively Blending Optimal Historical Behaviors in Deep Off-Policy RL](https://arxiv.org/abs/2405.18520)
    - Yu Luo, Tianying Ji, Fuchun Sun, Jianwei Zhang, Huazhe Xu, Xianyuan Zhan. ICML 2024. 

- [Planning, Fast and Slow: Online Reinforcement Learning with Action-Free Offline Data via Multiscale Planners](https://openreview.net/pdf/fc5c8303e5bc534ea8096e70f71993076a8376f7.pdf)
    - Chengjie Wu, Hao Hu, Yiqin Yang, Ning Zhang, Chongjie Zhang. ICML 2024.


#### AAAI 2024
- [SUF: Stabilized Unconstrained Fine-Tuning for Offline-to-Online Reinforcement Learning](https://ojs.aaai.org/index.php/AAAI/article/view/29083)
    - Jiaheng Feng, Mingxiao Feng, Haolin Song, Wengang Zhou, Houqiang Li. AAAI 2024. 

- [A Perspective of Q-value Estimation on Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2312.07685)
    - Yinmin Zhang, Jie Liu, Chuming Li, Yazhe Niu, Yaodong Yang, Yu Liu, Wanli Ouyang. AAAI 2024. 


#### IJCAI 2024
- [Efficient and Stable Offline-to-online Reinforcement Learning via Continual Policy Revitalization](https://www.ijcai.org/proceedings/2024/477)
    - Rui Kong, Chenyang Wu, Chen-Xiao Gao, Zongzhang Zhang, Ming Li. IJCAI 2024. 

- [ENOTO: Improving Offline-to-Online Reinforcement Learning with Q-Ensembles](https://arxiv.org/abs/2306.06871)
    - Kai Zhao, Yi Ma, Jianye Hao, Jinyi Liu, Yan Zheng, Zhaopeng Meng. IJCAI 2024. arXiv. 06/2023.


<!-- #### UAI 2024
- [Adaptive Offline Data Replay in Offline-to-Online Reinforcement Learning](https://openreview.net/forum?id=wWI1RYngAA)
    - . reviewed at ICLR 2024.  -->



#### RLC 2024
- [Planning to Go Out-of-Distribution in Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2310.05723)
    - Trevor McInroe, Stefano V. Albrecht, Amos Storkey. arXiv, reviewed at ICLR 2024.RLC 2024. 



#### ICLR 2024
- [Offline Data Enhanced On-Policy Policy Gradient with Provable Guarantees](https://arxiv.org/abs/2311.08384v1)
    - Yifei Zhou, Ayush Sekhari, Yuda Song, Wen Sun. ICLR 2024.

- [Uni-O4: Unifying Online and Offline Deep Reinforcement Learning with Multi-Step On-Policy Optimization](https://openreview.net/forum?id=tbFBh3LMKi)
    - Kun Lei, Zhengmao He, Chenhao Lu, Kaizhe Hu, Yang Gao, Huazhe Xu. ICLR 2024.

#### Underreviewed ICLR 24
- [Adaptive Offline Data Replay in Offline-to-Online Reinforcement Learning](https://openreview.net/forum?id=wWI1RYngAA)
    - . reviewed at ICLR 2024. 

- [Bayesian Offline-to-Online Reinforcement Learning : A Realist Approach](https://openreview.net/forum?id=opZTBFnX2G)
    - Hao Hu, Yiqin Yang, Jianing Ye, Ziqing Mai, Yujing Hu, Tangjie Lv, Changjie Fan, Qianchuan Zhao, Chongjie Zhang. reviewed at ICLR 2024 -> Accepted at ICML 2024. 

- [SERA: Sample Efficient Reward Augmentation in offline-to-online Reinforcement Learning](https://openreview.net/forum?id=91DFSjAva8)
    - Ziqi Zhang, Xiao Xiong, Zifeng Zhuang, Jinxin Liu, Donglin Wang. reviewed at ICLR 2024. 


<!-- - [Offline Retraining for Online RL: Decoupled Policy Learning to Mitigate Exploration Bias](https://arxiv.org/abs/2310.08558) -->
<!-- - Max Sobol Mark, Archit Sharma, Fahim Tajwar, Rafael Rafailov, Sergey Levine, Chelsea Finn. arXiv, reviewed at ICLR 2024. 10/2023. -->

- [Planning to Go Out-of-Distribution in Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2310.05723)
    - Trevor McInroe, Stefano V. Albrecht, Amos Storkey. arXiv, reviewed at ICLR 2024. 10/2023.

- [Offline RL for Online RL: Decoupled Policy Learning for Mitigating Exploration Bias](https://openreview.net/forum?id=lWe3GBRem8)
    - Max Sobol Mark, Archit Sharma, Fahim Tajwar, Rafael Rafailov, Sergey Levine, Chelsea Finn. arXiv, reviewed at ICLR 2024. 10/2023.

- [A Simple Unified Uncertainty-Guided Framework for Offline-to-Online Reinforcement Learning](https://openreview.net/forum?id=ZHr0JajZfH)
    - Siyuan Guo, Yanchao Sun, Jifeng Hu, Sili Huang, Hechang Chen, Haiyin Piao, Lichao Sun, Yi Chang. reviewed at ICLR 2024.



- [Automatic Fine-Tuned Offline-to-Online Reinforcement Learning via Increased Simple Moving Average Q-value](https://openreview.net/forum?id=228XQpErvW)
    - . reviewed at ICLR 2024.

- [Guided Decoupled Exploration for Offline Reinforcement Learning Fine-tuning](https://openreview.net/forum?id=gCZyD7WD0w)
    - . reviewed at ICLR 2024.


- [Collaborative World Models: An Online-Offline Transfer RL Approach](https://openreview.net/forum?id=AhcxMGfqQn)
    - Qi Wang, Junming Yang, Yunbo Wang, Xin Jin, Wenjun Zeng, Xiaokang Yang. reviewed at ICLR 2024.




### 2023
#### NeurIPS 2023
- [Policy Finetuning in Reinforcement Learning via Design of Experiments using Offline Data](https://arxiv.org/abs/2307.04354)
    - Ruiqi Zhang, Andrea Zanette. NeurIPS 2023.
- [Reward-agnostic Fine-tuning: Provable Statistical Benefits of Hybrid Reinforcement Learning](https://arxiv.org/abs/2305.10282)
    - Gen Li, Wenhao Zhan, Jason D. Lee, Yuejie Chi, Yuxin Chen. NeurIPS 2023.
- [Cal-QL: Calibrated Offline RL Pre-Training for Efficient Online Fine-Tuning](https://arxiv.org/abs/2303.05479)
    - Mitsuhiko Nakamoto, Yuexiang Zhai, Anikait Singh, Max Sobol Mark, Yi Ma, Chelsea Finn, Aviral Kumar, Sergey Levine. NeurIPS 2023. 03/2023.

#### ICML 2023
- [Jump-Start Reinforcement Learning](https://arxiv.org/abs/2204.02372)
    - Ikechukwu Uchendu, Ted Xiao, Yao Lu, Banghua Zhu, Mengyuan Yan, Joséphine Simon, Matthew Bennice, Chuyuan Fu, Cong Ma, Jiantao Jiao, Sergey Levine, Karol Hausman. ICML 2023. 04/22.
    
- [Efficient Online Reinforcement Learning with Offline Data](https://arxiv.org/abs/2302.02948)
    - Philip J. Ball, Laura Smith, Ilya Kostrikov, Sergey Levine. ICML 2023. 02/2023.

- [Leveraging Offline Data in Online Reinforcement Learning](https://arxiv.org/abs/2211.04974v2)
    - Andrew Wagenmaker, Aldo Pacchiano. ICML 2023. 11/2022.

- [Actor-Critic Alignment for Offline-to-Online Reinforcement Learning](https://openreview.net/pdf/6d9d5c890063d6e7229cc1a65bdbb254efcf5928.pdf)
    -  Zishun Yu, Xinhua Zhang. ICML 2023.

- [Warm-Start Actor-Critic: From Approximation Error to Sub-optimality Gap](https://arxiv.org/pdf/2306.11271)
    - Hang Wang, Sen Lin, Junshan Zhang. ICML 2023 Oral.

- [Semi-Offline Reinforcement Learning for Optimized Text Generation](https://arxiv.org/pdf/2306.09712v1)
    - Changyu Chen, Xiting Wang, Yiqiao Jin, Victor Ye Dong, Li Dong, Jie Cao, Yi Liu, Rui Yan. ICML 2023. Applied to Text Generation.

#### AAAI 2023
- [Adaptive Policy Learning for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2303.07693)
    - Han Zheng, Xufang Luo, Pengfei Wei, Xuan Song, Dongsheng Li, Jing Jiang. AAAI 2023.


#### ICLR 2023
- [Policy Expansion for Bridging Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2302.00935)
    - Haichao Zhang, We Xu, Haonan Yu. ICLR 2023. 02/2023.
- [Hybrid RL: Using both offline and online data can make RL efficient](https://arxiv.org/abs/2210.06718)
    - Yuda Song, Yifei Zhou, Ayush Sekhari, J. Andrew Bagnell, Akshay Krishnamurthy, Wen Sun. ICLR 2023


#### ICRA 2023
- [Learning on the Job: Self-Rewarding Offline-to-Online Finetuning for Industrial Insertion of Novel Connectors from Vision](https://arxiv.org/abs/2210.15206)
    - Ashvin Nair, Brian Zhu, Gokul Narayanan, Eugen Solowjow, Sergey Levine. ICRA 2023.

#### CORL 2023
- [MOTO: Offline Pre-training to Online Fine-tuning for Model-based Robot Learning](https://arxiv.org/abs/2401.03306)
    - Rafael Rafailov, Kyle Hatch, Victor Kolev, John D. Martin, Mariano Phielipp, Chelsea Finn. CORL 2023.

- [Finetuning Offline World Models in the Real World](https://arxiv.org/pdf/2310.16029)
    - Yunhai Feng, Nicklas Hansen, Ziyan Xiong, Chandramouli Rajagopalan, Xiaolong Wang. CORL 2024 Oral. Model based finetuning.

### 2022
#### NeurIPS 2022
- [Reincarnating Reinforcement Learning: Reusing Prior Computation to Accelerate Progress](https://arxiv.org/abs/2206.01626) [page](https://agarwl.github.io/reincarnating_rl/)
    - Rishabh Agarwal, Max Schwarzer, Pablo Samuel Castro, Aaron Courville, Marc G. Bellemare. NeurIPS 2022. 06/2022.

#### ICML 2022
- [Online Decision Transformer](https://arxiv.org/abs/2202.05607v2)
    - Qinqing Zheng, Amy Zhang, Aditya Grover. ICML 2022. 02/2022.

- [Offline Meta-Reinforcement Learning with Online Self-Supervision](https://arxiv.org/abs/2107.03974)
    - Vitchyr H. Pong, Ashvin Nair, Laura Smith, Catherine Huang, Sergey Levine. IML 2022. 07/2021.

#### ICLR 2022
- [MOTO: Offline to Online Fine-tuning for Model-Based Reinforcement Learning](https://openreview.net/forum?id=cH8XVu9hUV&referrer=%5Bthe%20profile%20of%20Rafael%20Rafailov%5D(%2Fprofile%3Fid%3D~Rafael_Rafailov1))
    - Rafael Rafailov, Kyle Beltran Hatch, Victor Kolev, John D Martin, Mariano Phielipp, Chelsea Finn. ICLR 2022 Workshop: Reincarnating Reinforcement Learning. 

#### CORL 2022
- [Offline-to-Online Reinforcement Learning via Balanced Replay and Pessimistic Q-Ensemble](https://arxiv.org/abs/2107.00591)
    - Seunghyun Lee, Younggyo Seo, Kimin Lee, Pieter Abbeel, Jinwoo Shin. CoRL 2022. 07/2021.

- [Don’t Start From Scratch: Leveraging Prior Data to Automate Robotic Reinforcement Learning](https://arxiv.org/pdf/2207.04703.pdf) [page](https://sites.google.com/view/ariel-berkeley/)
    - Homer Walke, Jonathan Yang, Albert Yu, Aviral Kumar, Jedrzej Orbik, Avi Singh, Sergey Levine. CoRL 2022. 07/2022.

#### RSS 2022
- [Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials](https://arxiv.org/abs/2210.05178)
    - Aviral Kumar, Anikait Singh, Frederik Ebert, Mitsuhiko Nakamoto, Yanlai Yang, Chelsea Finn, Sergey Levine. RSS. 10/2022.


### Multi-Agent Reinforcement Learning
- [Online Tuning for Offline Decentralized Multi-Agent Reinforcement Learning](https://ojs.aaai.org/index.php/AAAI/article/view/25973)
    - Jiechuan Jiang, Zongqing Lu. AAAI 2023.

- [M3: Modularization for Multi-task and Multi-agent Offline Pre-training](https://www.ifaamas.org/Proceedings/aamas2023/pdfs/p1624.pdf)
    - Linghui Meng, Jingqing Ruan, Xuantang Xiong, Xiyun Li, Xi Zhang, Dengpeng Xing, Bo Xu. AAMAS 2023.

- [Offline-to-Online Multi-Agent Reinforcement Learning with Offline Value Function Memory and Sequential Exploration](https://arxiv.org/abs/2410.19450)
    - Hai Zhong, Xun Wang, Zhuoran Li, Longbo Huang. AAMAS 2025.

### Journal Papers
- [Offline-to-online reinforcement learning with policy ensemble and policy-extended value](https://link.springer.com/article/10.1007/s10489-025-06972-7)
    - Jiacheng Chen, Jin Zhu & Lin Yang . Applied Intelligence. 02 November 2025

- [EMDSAC-ft: bridging the gap in offline-to-online reinforcement learning through value distribution learning](https://www.sciencedirect.com/science/article/pii/S0950705125017587)
    - Yesen Chen, Teng Zhang, Tao Li, Dongyun Wang. Knowledge-Based Systems. 25 November 2025.