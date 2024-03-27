# Awesome-LLM-Prompt-Optimization

\
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)



This repo aims to record advanced papers of LLM prompt tuning and automatic optimization (after 2022).

We strongly encourage the researchers that want to promote their fantastic work to the LLM prompt optimization to make pull request to update their paper's information!


--- 

## Contents

- [Papers](#papers)
  - [LLM Optimization](#llm-optimization)
  - [Fine-tune Methods](#fine-tune-methods)
  - [Programming](#programming)
  - [Human Perference and Feedback](#human-perference-and-feedback)
  - [Ensemble Methods](#ensemble-methods)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Gradient-free Methods](#gradient-free-methods)
  - [In-Context Learning](#in-context-learning)
  - [Bayesian Optimization](#bayesian-optimization)



--- 

## LLM Optimization

**Black-Box Prompt Optimization: Aligning Large Language Models without Model Training** \
*Jiale Cheng, Xiao Liu, Kehan Zheng, Pei Ke, Hongning Wang, Yuxiao Dong, Jie Tang, Minlie Huang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.04155)] [[Github](https://github.com/thu-coai/bpo)] \
7 Nov 2023 

**Language Model Decoding as Direct Metrics Optimization** \
*Haozhe Ji, Pei Ke, Hongning Wang, Minlie Huang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.01041)] \
2 Oct 2023 
 
**Large Language Models as Evolutionary Optimizers** \
*Shengcai Liu, Caishun Chen, Xinghua Qu, Ke Tang, Yew-Soon Ong* \
arXiv 2023 [[Paper](https://arxiv.org/abs/2310.19046)] \
29 Oct 2023 

**OptiMUS: Optimization Modeling Using MIP Solvers and large language models** \
*Ali AhmadiTeshnizi, Wenzhi Gao, Madeleine Udell* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.06116)] [[Github](https://arxiv.org/abs/2310.06116)] \
9 Oct 2023 

**PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization** \
*Xinyuan Wang, Chenxi Li, Zhen Wang, Fan Bai, Haotian Luo, Jiayou Zhang, Nebojsa Jojic, Eric P. Xing, Zhiting Hu* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.16427)] \
25 Oct 2023 

**Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation** \
*Eric Zelikman, Eliana Lorch, Lester Mackey, Adam Tauman Kalai* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.02304)] \
3 Oct 2023 

**Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution** \ 
*Chrisantha Fernando, Dylan Banarse, Henryk Michalewski, Simon Osindero, Tim Rocktäschel* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.16797)] \
28 Sep 2023 

**Connecting large language models with evolutionary algorithms yields powerful prompt optimizers** \
*Qingyan Guo, Rui Wang, Junliang Guo, Bei Li, Kaitao Song, Xu Tan, Guoqing Liu, Jiang Bian, Yujiu Yang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.08532)] \
15 Sep 2023 

**Large Language Models as Optimizers (OPRO)** \
*Chengrun Yang, Xuezhi Wang, Yifeng Lu, Hanxiao Liu, Quoc V. Le, Denny Zhou, Xinyun Chen* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.03409)] \
7 Sep 2023 


**Automatic Prompt Optimization with "Gradient Descent" and Beam Search (APO)** \
*Reid Pryzant, Dan Iter, Jerry Li, Yin Tat Lee, Chenguang Zhu, Michael Zeng* \
EMNLP 2023. [[Paper](https://arxiv.org/abs/2305.03495)][[Github](https://github.com/microsoft/lmops)] \
4 May 2023 

**Large Language Models Are Human-Level Prompt Engineers (APE)** \
*Yongchao Zhou, Andrei Ioan Muresanu, Ziwen Han, Keiran Paster, Silviu Pitis, Harris Chan, Jimmy Ba* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2211.01910)][[Github](https://github.com/keirp/automatic_prompt_engineer)] \
3 Nov 2022 

**Automatic Engineering of Long Prompts** \
*Cho-Jui Hsieh, Si Si, Felix X. Yu, Inderjit S. Dhillon*\
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.10117)] \
16 Nov 2023

**Prompt Optimisation with Random Sampling** \
*Yao Lu, Jiayi Wang, Sebastian Riedel, Pontus Stenetorp*\
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.09569)][[Github](https://github.com/yaolu/random-prompt)]  \
16 Nov 2023

**Mixture-of-Experts in Prompt Optimization** \
*Anonymous authors*
ICLR 2024 submission. [[Paper](https://openreview.net/pdf?id=sDmjlpphdB)] \
Oct 2024 

**Prompt Engineering a Prompt Engineer** \
*Anonymous authors*
ICLR 2024 submission. [[Paper](https://openreview.net/forum?id=eojWsJQ2fe)] \
Oct 2024 


## Fine-tuning Methods

**Tuna: Instruction Tuning using Feedback from Large Language Models** \
*Haoran Li, Yiran Liu, Xingxing Zhang, Wei Lu, Furu Wei* \
EMNLP 2023. [[Paper](https://arxiv.org/abs/2310.13385)][[Github](https://github.com/microsoft/lmops)] \
20 Oct 2023 

## Programming 

**DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines** \
*Omar Khattab, Arnav Singhvi, Paridhi Maheshwari, Zhiyuan Zhang, Keshav Santhanam, Sri Vardhamanan, Saiful Haq, Ashutosh Sharma, Thomas T. Joshi, Hanna Moazam, Heather Miller, Matei Zaharia, Christopher Potts* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.03714)][[Github](https://github.com/stanfordnlp/dspy)] \
Oct 2023 


## Human Perference and Feedback

**Eliciting Human Preferences with Language Models** \
*Belinda Z. Li, Alex Tamkin, Noah Goodman, Jacob Andreas* \
arXiv 2023. [[Paper](https://arxiv.org/abs//2310.11589)][[Github](https://github.com/alextamkin/generative-elicitation)] \
17 Oct 2023 



## Ensemble Methods

**Promptboosting: Black-box text classification with ten forward passes** \
*Bairu Hou, Joe O’Connor, Jacob Andreas, Shiyu Chang, Yang Zhang* \
ICML 2023. [[Paper](https://proceedings.mlr.press/v202/hou23b.html)][[Github](https://github.com/UCSB-NLP-Chang/PromptBoosting)] \
23 Jan 2023

**Can Generalist Foundation Models Outcompete Special-Purpose Tuning? Case Study in Medicine** \
*Harsha Nori, Yin Tat Lee, Sheng Zhang, Dean Carignan, Richard Edgar, Nicolo Fusi, Nicholas King, Jonathan Larson, Yuanzhi Li, Weishung Liu, Renqian Luo, Scott Mayer McKinney, Robert Osazuwa Ness, Hoifung Poon, Tao Qin, Naoto Usuyama, Chris White, Eric Horvitz* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.16452)] \
28 Nov 2023

## Reinforcement Learning




**Eureka: Human-Level Reward Design via Coding Large Language Models** \
*Yecheng Jason Ma, William Liang, Guanzhi Wang, De-An Huang, Osbert Bastani, Dinesh Jayaraman, Yuke Zhu, Linxi Fan, Anima Anandkumar* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.12931)][[Github](https://github.com/eureka-research/Eureka)] \
19 Oct 2023


**Query-Dependent Prompt Evaluation and Optimization with Offline Inverse RL** \
*Hao Sun, Alihan Hüyük, Mihaela van der Schaar* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.06553)][[Github](https://github.com/holarissun/Prompt-OIRL)] \
13 Sep 2023 


**Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization** \
*Weiran Yao, Shelby Heinecke, Juan Carlos Niebles, Zhiwei Liu, Yihao Feng, Le Xue, Rithesh Murthy, Zeyuan Chen, Jianguo Zhang, Devansh Arpit, Ran Xu, Phil Mui, Huan Wang, Caiming Xiong, Silvio Savarese* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2308.02151)] \
4 Aug 2023 

**TEMPERA: Test-Time Prompting via Reinforcement Learning** \
*Tianjun Zhang, Xuezhi Wang, Denny Zhou, Dale Schuurmans, Joseph E. Gonzalez* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2211.11890)][[Github](https://github.com/tianjunz/tempera)] \
21 Nov 2022


**RLPrompt: Optimizing Discrete Text Prompts with Reinforcement Learning** \
*Mingkai Deng, Jianyu Wang, Cheng-Ping Hsieh, Yihan Wang, Han Guo, Tianmin Shu, Meng Song, Eric P. Xing, Zhiting Hu* \
EMNLP 2022. [[Paper](https://arxiv.org/abs/2205.12548)][[Github](https://github.com/mingkaid/rl-prompt)] \
25 May 2022 

**Black-box Prompt Learning for Pre-trained Language Models** \
*Shizhe Diao, Zhichao Huang, Ruijia Xu, Xuechun Li, Yong Lin, Xiao Zhou, Tong Zhang* \
TMLR 2023. [[Paper](https://arxiv.org/abs/2201.08531)][[Github](https://github.com/shizhediao/Black-Box-Prompt-Learning)] \
22 Jan 2022 



## Gradient-free Methods 

**PROPANE: Prompt design as an inverse problem** \
*Rimon Melamed, Lucas H. McCabe, Tanay Wakhare, Yejin Kim, H. Howie Huang, Enric Boix-Adsera* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2311.07064v1)] [[Github](https://github.com/rimon15/propane)] \
13 Nov 2023 

**Survival of the Most Influential Prompts: Efficient Black-Box Prompt Search via Clustering and Pruning** \
*Han Zhou, Xingchen Wan, Ivan Vulić, Anna Korhonen* \
EMNLP 2023. [[Paper](https://arxiv.org/abs/2310.12774)] [[Github](https://github.com/cambridgeltl/ClaPS)] \
19 Oct 2023 

**FedBPT: Efficient Federated Black-box Prompt Tuning for Large Language Models** \
*Jingwei Sun, Ziyue Xu, Hongxu Yin, Dong Yang, Daguang Xu, Yiran Chen, Holger R. Roth* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2310.01467v1)] \
2 Oct 2023 

**Language Models as Black-Box Optimizers for Vision-Language Models** \
*Shihong Liu, Samuel Yu, Zhiqiu Lin, Deepak Pathak, Deva Ramanan* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.05950)][[Github](https://github.com/shihongl1998/llm-as-a-blackbox-optimizer)] \
12 Sep 2023 

**InstructZero: Efficient Instruction Optimization for Black-Box Large Language Models** \
*Lichang Chen, Jiuhai Chen, Tom Goldstein, Heng Huang, Tianyi Zhou* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2306.03082)] [[Github](https://github.com/lichang-chen/instructzero)] \
5 Jun 2023 

**BlackVIP: Black-Box Visual Prompting for Robust Transfer Learning** \
*Changdae Oh, Hyeji Hwang, Hee-young Lee, YongTaek Lim, Geunyoung Jung, Jiyoung Jung, Hosik Choi, Kyungwoo Song* \
CVPR 2023. [[Paper](https://arxiv.org/abs/2303.14773)][[Github](https://github.com/changdaeoh/blackvip)] \
26 Mar 2023 


**GrIPS: Gradient-free, Edit-based Instruction Search for Prompting Large Language Models** \
*Archiki Prasad, Peter Hase, Xiang Zhou, Mohit Bansal* \
EACL 2023. [[Paper](https://arxiv.org/abs/2203.07281)][[Github](https://github.com/archiki/grips)] \
Mar 14 2022 

**Black-Box Tuning for Language-Model-as-a-Service** \
*Tianxiang Sun, Yunfan Shao, Hong Qian, Xuanjing Huang, Xipeng Qiu* \
ICML 2022. [[Paper](https://arxiv.org/abs/2201.03514)][[Github](https://github.com/txsun1997/Black-Box-Tuning)] \
10 Jan 2022 

**BBTv2: towards a gradient-free future with large language models** \
*Tianxiang Sun, Zhengfu He, Hong Qian, Yunhua Zhou, Xuanjing Huang, Xipeng Qiu* \ 
EMNLP 2022. [[Paper](https://aclanthology.org/2022.emnlp-main.259/)] [[Github](https://github.com/txsun1997/Black-Box-Tuning)] \
7 Dec 2022 


## In-Context Learning 

**Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data** \
*KaShun Shum, Shizhe Diao, Tong Zhang*\
arXiv 2023. [[Paper](https://arxiv.org/abs/2302.12822)][[Github](https://github.com/shizhediao/automate-cot)] \
24 Feb 2023 

**Automatic Chain of Thought Prompting in Large Language Models** \
*Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola*\
ICLR 2023. [[Paper](https://arxiv.org/abs/2210.03493)][[Github](https://github.com/amazon-science/auto-cot)] \
7 Oct 2022

**Active Example Selection for In-Context Learning** \
*Yiming Zhang, Shi Feng, Chenhao Tan* \
EMNLP 2022. [[Paper](https://arxiv.org/abs/2211.04486)][[Github](https://github.com/ChicagoHAI/active-example-selection)] \
8 Nov 2022 

**Selective Annotation Makes Language Models Better Few-Shot Learners** \
*Hongjin Su, Jungo Kasai, Chen Henry Wu, Weijia Shi, Tianlu Wang, Jiayi Xin, Rui Zhang, Mari Ostendorf, Luke Zettlemoyer, Noah A. Smith, Tao Yu* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2209.01975)][[Github](https://github.com/HKUNLP/icl-selective-annotation)] \
5 Sep 2022 

**Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity** \
*Yao Lu, Max Bartolo, Alastair Moore, Sebastian Riedel, Pontus Stenetorp* \
ACL 2022. [[Paper](https://arxiv.org/abs/2104.08786)] \
3 Mar 2022

**Learning To Retrieve Prompts for In-Context Learning** \
*Ohad Rubin, Jonathan Herzig, Jonathan Berant* \
NAACL-HLT 2022. [[Paper](https://arxiv.org/abs/2112.08633)][[Github](https://github.com/OhadRubin/EPR)] \
16 Dec 2021

## Bayesian Optimization

**Large Language Models to Enhance Bayesian Optimization** \
ICLR 2024 Conference Submission8133 Authors. [[Paper](https://openreview.net/forum?id=OOxotBmGol)] \
23 Sep 2023 


**Bayesian Optimization of Catalysts With In-context Learning** \
*Mayk Caldas Ramos, Shane S. Michtavy, Marc D. Porosoff, Andrew D. White* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2304.05341)] [[Github](https://github.com/ur-whitelab/bo-lift)] \
11 Apr 2023 
