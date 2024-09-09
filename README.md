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
- [Papers](https://github.com/linhlpv/awesome-offline-online-RL-papers#papers):
    - [Surveys](https://github.com/linhlpv/awesome-offline-online-RL-papers#surveys)
    - [Offline to Online](https://github.com/linhlpv/awesome-offline-online-RL-papers#offline-to-online)
        - [Underreviewed ICLR 24](https://github.com/linhlpv/awesome-offline-online-RL-papers#underreviewd-iclr-24)

## Papers
### Surveys
- [Pretraining in Deep Reinforcement Learning: A Survey](https://arxiv.org/abs/2211.03959)
    - Zhihui Xie, Zichuan Lin, Junyou Li, Shuai Li, Deheng Ye. arXiv. 11/2022.
### Offline to Online
#### Preprints
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



#### Papers
- [AWAC: Accelerating Online Reinforcement Learning with Offline Datasets](https://arxiv.org/abs/2006.09359) [page](https://awacrl.github.io/)
    - Ashvin Nair, Abhishek Gupta, Murtaza Dalal, Sergey Levine. arXiv. 06/2020.
- [Addressing Distribution Shift in Online
Reinforcement Learning with Offline Datasets
](https://offline-rl-neurips.github.io/pdf/13.pdf)
    - Seunghyun Lee, Younggyo Seo, Kimin Lee, Pieter Abbeel, Jinwoo Shin. Offline RL workshop. 12/2020.

- [Offline-to-Online Reinforcement Learning via Balanced Replay and Pessimistic Q-Ensemble](https://arxiv.org/abs/2107.00591)
    - Seunghyun Lee, Younggyo Seo, Kimin Lee, Pieter Abbeel, Jinwoo Shin. CoRL 2022. 07/2021.



- [Jump-Start Reinforcement Learning](https://arxiv.org/abs/2204.02372)
    - Ikechukwu Uchendu, Ted Xiao, Yao Lu, Banghua Zhu, Mengyuan Yan, Joséphine Simon, Matthew Bennice, Chuyuan Fu, Cong Ma, Jiantao Jiao, Sergey Levine, Karol Hausman. ICML 2023. 04/22.

- [Reincarnating Reinforcement Learning: Reusing Prior Computation to Accelerate Progress](https://arxiv.org/abs/2206.01626) [page](https://agarwl.github.io/reincarnating_rl/)
    - Rishabh Agarwal, Max Schwarzer, Pablo Samuel Castro, Aaron Courville, Marc G. Bellemare. NeurIPS 2022. 06/2022.
- [Don’t Start From Scratch: Leveraging Prior Data to Automate Robotic Reinforcement Learning](https://arxiv.org/pdf/2207.04703.pdf) [page](https://sites.google.com/view/ariel-berkeley/)
    - Homer Walke, Jonathan Yang, Albert Yu, Aviral Kumar, Jedrzej Orbik, Avi Singh, Sergey Levine. CoRL 2022. 07/2022.

- [Hybrid RL: Using Both Offline and Online Data Can Make RL Efficient](https://arxiv.org/abs/2210.06718)
    - Yuda Song, Yifei Zhou, Ayush Sekhari, J. Andrew Bagnell, Akshay Krishnamurthy, Wen Sun. ICLR 2023. 10/2022.

- [Pre-Training for Robots: Offline RL Enables Learning New Tasks from a Handful of Trials](https://arxiv.org/abs/2210.05178)
    - Aviral Kumar, Anikait Singh, Frederik Ebert, Mitsuhiko Nakamoto, Yanlai Yang, Chelsea Finn, Sergey Levine. RSS. 10/2022.

- [MOTO: Offline to Online Fine-tuning for Model-Based Reinforcement Learning](https://openreview.net/forum?id=cH8XVu9hUV&referrer=%5Bthe%20profile%20of%20Rafael%20Rafailov%5D(%2Fprofile%3Fid%3D~Rafael_Rafailov1))
    - Rafael Rafailov, Kyle Beltran Hatch, Victor Kolev, John D Martin, Mariano Phielipp, Chelsea Finn. ICLR 2022 Workshop: Reincarnating Reinforcement Learning. 

- [Launchpad: Learning to Schedule Using Offline and Online RL Methods](https://arxiv.org/abs/2212.00639)
    - Vanamala Venkataswamy, Jake Grigsby, Andrew Grimshaw, Yanjun Qi. arXiv. 12/2022.


- [Guiding Online Reinforcement Learning with Action-Free Offline Pretraining](https://arxiv.org/abs/2301.12876)
    - Deyao Zhu, Yuhui Wang, Jürgen Schmidhuber, Mohamed Elhoseiny. arXiv. 01/2023.

- [Learning on the Job: Self-Rewarding Offline-to-Online Finetuning for Industrial Insertion of Novel Connectors from Vision](https://arxiv.org/abs/2210.15206)
    - Ashvin Nair, Brian Zhu, Gokul Narayanan, Eugen Solowjow, Sergey Levine. ICRA 2023.
    
- [Efficient Online Reinforcement Learning with Offline Data](https://arxiv.org/abs/2302.02948)
    - Philip J. Ball, Laura Smith, Ilya Kostrikov, Sergey Levine. ICML 2023. 02/2023.

- [Policy Expansion for Bridging Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2302.00935)
    - Haichao Zhang, We Xu, Haonan Yu. ICLR 2023. 02/2023.

- [Cal-QL: Calibrated Offline RL Pre-Training for Efficient Online Fine-Tuning](https://arxiv.org/abs/2303.05479)
    - Mitsuhiko Nakamoto, Yuexiang Zhai, Anikait Singh, Max Sobol Mark, Yi Ma, Chelsea Finn, Aviral Kumar, Sergey Levine. NeurIPS 2023. 03/2023.
- [Adaptive Policy Learning for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2303.07693)
    - Han Zheng, Xufang Luo, Pengfei Wei, Xuan Song, Dongsheng Li, Jing Jiang. AAAI 2023. 03/2023.
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

- [Uni-O4: Unifying Online and Offline Deep Reinforcement Learning with Multi-Step On-Policy Optimization](https://openreview.net/forum?id=tbFBh3LMKi)
    - Kun Lei, Zhengmao He, Chenhao Lu, Kaizhe Hu, Yang Gao, Huazhe Xu. reviewed at ICLR 2024.

- [Automatic Fine-Tuned Offline-to-Online Reinforcement Learning via Increased Simple Moving Average Q-value](https://openreview.net/forum?id=228XQpErvW)
    - . reviewed at ICLR 2024.

- [Guided Decoupled Exploration for Offline Reinforcement Learning Fine-tuning](https://openreview.net/forum?id=gCZyD7WD0w)
    - . reviewed at ICLR 2024.

- [Offline Data Enhanced On-Policy Policy Gradient with Provable Guarantees](https://openreview.net/forum?id=RMgqvQGTwH)
    - Yifei Zhou, Ayush Sekhari, Yuda Song, Wen Sun. reviewed at ICLR 2024.

- [Collaborative World Models: An Online-Offline Transfer RL Approach](https://openreview.net/forum?id=AhcxMGfqQn)
    - Qi Wang, Junming Yang, Yunbo Wang, Xin Jin, Wenjun Zeng, Xiaokang Yang. reviewed at ICLR 2024.


#### ICLR 2024


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


#### ICML 2024
- [Bayesian Design Principles for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2405.20984)
    - Hao Hu, Yiqin Yang, Jianing Ye, Chengjie Wu, Ziqing Mai, Yujing Hu, Tangjie Lv, Changjie Fan, Qianchuan Zhao, Chongjie Zhang. ICML 2024. 

- [Energy-Guided Diffusion Sampling for Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2407.12448)
    - Xu-Hui Liu, Tian-Shuo Liu, Shengyi Jiang, Ruifeng Chen, Zhilong Zhang, Xinwei Chen, Yang Yu. ICML 2024. 

- [OLLIE: Imitation Learning from Offline Pretraining to Online Finetuning](https://arxiv.org/abs/2405.17477)
    - Sheng Yue, Xingyuan Hua, Ju Ren, Sen Lin, Junshan Zhang, Yaoxue Zhang. ICML 2024. 

- [Offline-Boosted Actor-Critic: Adaptively Blending Optimal Historical Behaviors in Deep Off-Policy RL](https://arxiv.org/abs/2405.18520)
    - Yu Luo, Tianying Ji, Fuchun Sun, Jianwei Zhang, Huazhe Xu, Xianyuan Zhan. ICML 2024. 


<!-- #### UAI 2024
- [Adaptive Offline Data Replay in Offline-to-Online Reinforcement Learning](https://openreview.net/forum?id=wWI1RYngAA)
    - . reviewed at ICLR 2024.  -->



#### RLC 2024
- [Planning to Go Out-of-Distribution in Offline-to-Online Reinforcement Learning](https://arxiv.org/abs/2310.05723)
    - Trevor McInroe, Stefano V. Albrecht, Amos Storkey. arXiv, reviewed at ICLR 2024.RLC 2024. 



