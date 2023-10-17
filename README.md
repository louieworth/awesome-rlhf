# awesome-offline-rl
Welcome to our curated collection of research and review papers focused on Reinforcement Learning from Human Feedback (RLHF). We encourage you to star, fork, and contribute to this repository. We're actively seeking additional contributors and maintainers! 

Maintained by:

- [Li Jiang](https://louieworth.github.io/), Cornell University

Please follow this format for contributions:
```
- [Paper Title](paper link) [Additional Links]
  - Author1, Author2, and Author3. Published in arXiv/Conference/Journal, Year.
```

For any inquiries, don't hesitate to contact: li.jiang3@mail.mcgill.ca

Some notes:

- This resource is dedicated to the latest papers and does not include past academic works, even those published earlier in 2023. For a review of prominent historical papers, please refer to [this link](https://huggingface.co/blog/rlhf#further-reading).
- Most of the paper organization is credited to [RLHF paper](https://www.craft.me/s/NHvR6dsCVNNW8L).

## Table of Contents

[TOC]

## Papers

### Review/Survey/Position Papers

- [Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2307.15217)
  - Stephen Casper, Xander Davies, Claudia Shi, Thomas Krendl Gilbert, Jérémy Scheurer, Javier Rando, Rachel Freedman, Tomasz Korbak, David Lindner, Pedro Freire, Tony Wang, Samuel Marks, Charbel-Raphaël Segerie, Micah Carroll, Andi Peng, Phillip Christoffersen, Mehul Damani, Stewart Slocum, Usman Anwar, Anand Siththaranjan, Max Nadeau, Eric J. Michaud, Jacob Pfau, Dmitrii Krasheninnikov, Xin Chen, Lauro Langosco, Peter Hase, Erdem Bıyık, Anca Dragan, David Krueger, Dorsa Sadigh, and Dylan Hadfield-Menell. arXiv, 2023.

### RLHF for LLMs: Theory / Methods

Here's how you can format the papers:

- [Understanding the Effects of RLHF on LLM Generalisation and Diversity](https://arxiv.org/abs/2310.06452)
  
  - Robert Kirk, Ishita Mediratta, Christoforos Nalmpantis, Jelena Luketina, Eric Hambro, Edward Grefenstette, Roberta Raileanu. arXiv, 2023.
  
- [SALMON: Self-Alignment with Principle-Following Reward Models](https://arxiv.org/abs/2310.05910)
  
  - Zhiqing Sun, Yikang Shen, Hongxin Zhang, Qinhong Zhou, Zhenfang Chen, David Cox, Yiming Yang, Chuang Gan. arXiv, 2023.
  
- [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](http://arxiv.org/abs/2305.18290)
  - Rafael Rafailov, Archit Sharma, Eric Mitchell, Stefano Ermon, Christopher D. Manning, Chelsea Finn. NeurIPS, 2023.
  
- [RRHF: Rank Responses to Align Language Models with Human Feedback without tears](https://arxiv.org/abs/2304.05302) 
  - Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang. NeurIPS, 2023.

- [Reward Model Ensembles Help Mitigate Overoptimization](https://arxiv.org/abs/2310.02743)

  - Thomas Coste, Usman Anwar, Robert Kirk, David Krueger. arXiv, 2023.

- [Learning Optimal Advantage from Preferences and Mistaking it for Reward](https://arxiv.org/abs/2310.02456)

  - W. Bradley Knox, Stephane Hatgis-Kessell, Sigurdur Orn Adalgeirsson, Serena Booth, Anca Dragan, Peter Stone, Scott Niekum. arXiv, 2023.

- [Enable Language Models to Implicitly Learn Self-Improvement From Data](https://arxiv.org/abs/2310.00898)

- [The Trickle-down Impact of Reward (In-)consistency on RLHF](https://arxiv.org/abs/2309.16155v1)

  - Lingfeng Shen, Sihao Chen, Linfeng Song, Lifeng Jin, Baolin Peng, Haitao Mi, Daniel Khashabi, Dong Yu. arXiv, 2023.

- [Human Feedback is not Gold Standard](https://arxiv.org/abs/2309.16349)

  - Tom Hosking, Phil Blunsom, Max Bartolo. arXiv, 2023.

- [Making PPO even better: Value-Guided Monte-Carlo Tree Search decoding](https://arxiv.org/abs/2309.15028)

  - Jiacheng Liu, Andrew Cohen, Ramakanth Pasunuru, Yejin Choi, Hannaneh Hajishirzi, Asli Celikyilmaz. arXiv, 2023.

- [Stabilizing RLHF through Advantage Model and Selective Rehearsal](https://arxiv.org/abs/2309.10202)

  - Baolin Peng, Linfeng Song, Ye Tian, Lifeng Jin, Haitao Mi, Dong Yu. arXiv, 2023.

- [Exploring the impact of low-rank adaptation on the performance, efficiency, and regularization of RLHF](https://arxiv.org/abs/2309.09055)
  - Simeng Sun, Dhawal Gupta, Mohit Iyyer. arXiv, 2023.
- [RAIN: Your Language Models Can Align Themselves without Finetuning](https://arxiv.org/abs/2309.07124)
  - Yuhui Li, Fangyun Wei, Jinjing Zhao, Chao Zhang, Hongyang Zhang, arXiv, 2023.
- [Statistical Rejection Sampling Improves Preference Optimization](https://arxiv.org/pdf/2309.06657.pdf)
  - Tianqi Liu, Yao Zhao, Rishabh Joshi, Misha Khalman, Mohammad Saleh, Peter J. Liu, Jialu Liu. arXiv, 2023.
- [RLAIF: Scaling Reinforcement Learning from Human Feedback with AI Feedback](https://arxiv.org/abs/2309.00267)
  - Harrison Lee, Samrat Phatale, Hassan Mansoor, Kellie Lu, Thomas Mesnard, Colton Bishop, Victor Carbune, Abhinav Rastogi. arXiv, 2023.

- [Reinforced Self-Training (ReST) for Language Modeling](http://arxiv.org/abs/2308.08998)
  - Caglar Gulcehre, Tom Le Paine, Srivatsan Srinivasan, Ksenia Konyushkova, Lotte Weerts, Abhishek Sharma, Aditya Siddhant, Alex Ahern, Miaosen Wang, Chenjie Gu, Wolfgang Macherey, Arnaud Doucet, Orhan Firat, Nando de Freitas. arXiv, 2023.

- [Peering Through Preferences: Unraveling Feedback Acquisition for Aligning Large Language Models](https://arxiv.org/abs/2308.15812)
  - Hritik Bansal, John Dang, Aditya Grover. arXiv, 2023.

- [Let Me Teach You: Pedagogical Foundations of Feedback for Language Models](https://arxiv.org/abs/2307.00279)
  - Beatriz Borges, Niket Tandon, Tanja Käser, Antoine Bosselut. arXiv, 2023.
- [Generalized Knowledge Distillation for Auto-regressive Language Models](https://arxiv.org/abs/2306.13649)
  - Rishabh Agarwal, Nino Vieillard, Yongchao Zhou, Piotr Stanczyk, Sabela Ramos, Matthieu Geist, Olivier Bachem. arXiv, 2023.
- [Secrets of RLHF in Large Language Models Part I: PPO](http://arxiv.org/abs/2307.04964)
  - Rui Zheng, Shihan Dou, Songyang Gao, Yuan Hua, Wei Shen, Binghai Wang, Yan Liu, Senjie Jin, Qin Liu, Yuhao Zhou, Limao Xiong, Lu Chen, Zhiheng Xi, Nuo Xu, Wenbin Lai, Minghao Zhu, Cheng Chang, Zhangyue Yin, Rongxiang Weng, Wensen Cheng, Haoran Huang, Tianxiang Sun, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang. arXiv, 2023.

- [Learning to Generate Better Than Your LLM](https://arxiv.org/abs/2306.11816)
  - Jonathan D. Chang, Kiante Brantley, Rajkumar Ramamurthy, Dipendra Misra, Wen Sun. arXiv, 2023.
- [Fine-Grained Human Feedback Gives Better Rewards for Language Model Training](https://arxiv.org/abs/2306.01693)
  - Zeqiu Wu, Yushi Hu, Weijia Shi, Nouha Dziri, Alane Suhr, Prithviraj Ammanabrolu, Noah A. Smith, Mari Ostendorf, Hannaneh Hajishirzi. NeurIPS, 2023.

- [Continually Improving Extractive QA via Human Feedback](https://arxiv.org/abs/2305.12473)
  - Ge Gao, Hung-Ting Chen, Yoav Artzi, Eunsol Choi. arXiv, 2023.

- [SLiC-HF: Sequence Likelihood Calibration with Human Feedback](https://arxiv.org/abs/2305.10425)
  - Yao Zhao, Rishabh Joshi, Tianqi Liu, Misha Khalman, Mohammad Saleh, Peter J. Liu. arXiv, 2023.
- [The Wisdom of Hindsight Makes Language Models Better Instruction Followers](http://arxiv.org/abs/2302.05206)
  - Tianjun Zhang, Fangchen Liu, Justin Wong, Pieter Abbeel, Joseph E. Gonzalez. arXiv, 2023.

### RLHF for Other Domains

- [PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback](https://arxiv.org/abs/2307.14936)
  - Bo Shen, Jiaxin Zhang, Taihong Chen, Daoguang Zan, Bing Geng, An Fu, Muhan Zeng, Ailun Yu, Jichuan Ji, Jingyang Zhao, Yuenan Guo, Qianxiang Wang. arXiv, 2023.
- [WizardMath: Empowering Mathematical Reasoning for Large Language Models via Reinforced Evol-Instruct](https://arxiv.org/abs/2308.09583)
  - Haipeng Luo, Qingfeng Sun, Can Xu, Pu Zhao, Jianguang Lou, Chongyang Tao, Xiubo Geng, Qingwei Lin, Shifeng Chen, Dongmei Zhang. arXiv, 2023.
- [Shepherd: A Critic for Language Model Generation](https://arxiv.org/abs/2308.04592)
  - Tianlu Wang, Ping Yu, Xiaoqing Ellen Tan, Sean O'Brien, Ramakanth Pasunuru, Jane Dwivedi-Yu, Olga Golovneva, Luke Zettlemoyer, Maryam Fazel-Zarandi, Asli Celikyilmaz. arXiv, 2023.
- [Reinforcement Learning with Human Feedback for Realistic Traffic Simulation](https://arxiv.org/abs/2309.00709)
  - Yulong Cao, Boris Ivanovic, Chaowei Xiao, Marco Pavone. arXiv, 2023.
- [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2309.14525)
  - Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen, Chuang Gan, Liang-Yan Gui, Yu-Xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell. arXiv, 2023.
- [Motif: Intrinsic Motivation from Artificial Intelligence Feedback](https://arxiv.org/abs/2310.00166)
  - Martin Klissarov, Pierluca D'Oro, Shagun Sodhani, Roberta Raileanu, Pierre-Luc Bacon, Pascal Vincent, Amy Zhang, Mikael Henaff. arXiv, 2023.

### Datasets

[UltraFeedback: Boosting Language Models with High-quality Feedback](https://arxiv.org/abs/2310.01377)

- Ganqu Cui, Lifan Yuan, Ning Ding, Guanming Yao, Wei Zhu, Yuan Ni, Guotong Xie, Zhiyuan Liu, Maosong Sun. arXiv, 2023.

## Blogs/Talks/Reports

### Blogs

- [Illustrating Reinforcement Learning from Human Feedback (RLHF)](https://huggingface.co/blog/rlhf)

  - Nathan Lambert, Hugging Face blog, 2022.

- [Reinforcement Learning for Language Models](https://gist.github.com/yoavg/6bff0fecd65950898eba1bb321cfbd81#reinforcement-learning-for-language-models)
  - Yoav Goldberg, April 2023.

- [RLHF: Reinforcement Learning from Human Feedback](https://huyenchip.com/2023/05/02/rlhf.html)
  - Chip Huyen, 2023.

### Talks

- [Reinforcement Learning from Human Feedback: From Zero to chatGPT](https://www.youtube.com/watch?v=2MBJOuVq380&t=2641s)
- Nathan Lambert, Hugging Face, 2022.
  
- [Reinforcement Learning from Human Feedback: Progress and Challenges](https://www.youtube.com/watch?v=hhiLw5Q_UFg&t=3206s)
  - John Schulman, OpenAI, 2023.
  
- [Scalable Oversight for Large Language Models](https://www.youtube.com/watch?v=0tRAhi4g0QA) 
  - Samuel Bowman, New York University, 2023

### Reports

- [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/abs/2307.09288)

  - Meta, 2023.
- [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774)
  - OpenAI, 2023.

## Open Source Software/Implementations

- [OpenRLHF](https://github.com/OpenLLMAI/OpenRLHF)
  - A Ray-based High-performance RLHF framework (for 34b+ models)
