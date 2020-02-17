---
title: NTU Weekly Progress Report 20200203
author: Byron
layout: post
---

### Completion (2020/02/03 - 2020/02/16)

- Completed the [Deep Learning and NLP first assignment](https://github.com/Byron-Edwards/NTU/tree/master/courses/nlp) (The first language model). At the same time, I set up the environment, recap the usage of numpy, pandas and get hands dirty on the Pytorch
- Learnt the RL online courses (David Silver) 1-3  
- Familiar with Markdown
- Paper read:
  - [A Review of Cooperative Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1908.03963)
  - [On Multi-Agent Learning in Team Sports Games](https://arxiv.org/abs/1906.10124)
  - [Winning Isn’t Everything: Enhancing Game Development with Intelligent Agents](https://arxiv.org/abs/1903.10545)

### Ideas

- Abount the projects: Both assignment of courses [*Multi-agent*](https://ntulearn.ntu.edu.sg/bbcswebdav/pid-2001367-dt-content-rid-10331026_1/courses/19S2-AI6125/Assignment2_introduction.pdf) and [*AI introduction*](https://ntulearn.ntu.edu.sg/bbcswebdav/pid-2003491-dt-content-rid-10361597_1/courses/19S2-AI6101/RL%20Mini-Project%20%E2%80%93%20How%20to%20Get%20Started.pdf) are related with reinforcement learning, i would like to combine these assignments into the first period of the RL projects

### Questions

Basic

- Q: What's the core difference between value iteration and policy iteration in MDP?
- A: Both of them are based on the dynamic programming
- Q: Can pytorch be used for Java?
- A: No
- Q: on-policy traning and off-policy training
- A: refer to Q-learning and SASAR

Project related

- Q: Policy understanding of model-free DRL? Is it aim to address the pain point of sparse reward, huge search space.
- A: Policy understanding of the DRL is trying to mapping/compress the state-action sequences into low dimensional vector. In an adversarial environment, the low dimensional representation of the adversarial agent (rule based) will generally help our learning agent converage faster during training. it could help our learning agent perform fast, dynamic and accurate response.
- Q: Will the hieratical RL, imitation Learning help on this target?
- A: No, they are different study field

### Next Step

- Complete the Multi-agent Assigment [literature review](https://ntulearn.ntu.edu.sg/bbcswebdav/pid-1959486-dt-content-rid-9994760_1/courses/19S2-AI6125/assignment_1.pdf)(due by 2020/02/23)
- Go through the paper, blog and related materials mentioned by Dr. Zheng
  - [Variational Autoencoders for Opponent Modeling in Multi-Agent Systems](https://arxiv.org/abs/2001.10829)
  - [A Deep Bayesian Policy Reuse Approach Against Non-Stationary Agents](http://papers.nips.cc/paper/7374-a-deep-bayesian-policy-reuse-approach-against-non-stationary-agents.pdf)
  - [From Autoencoder to Beta-VAE](https://lilianweng.github.io/lil-log/2018/08/12/from-autoencoder-to-beta-vae.html)
