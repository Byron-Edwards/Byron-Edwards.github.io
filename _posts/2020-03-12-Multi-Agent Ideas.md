---
title: Multi-agent Ideas
author: Byron
layout: post
---
### Environment

- No time limited on each step, which means the computation can be heavy
- The agent can access the global location of the object, then it is able to construct the memory of global map



### Agent

- Unlimited memory, but the information  of memery will be uncertain if time passes
- Fully communication in any encode, which means can directly share the full obersvation then to construct same memory
- How to perform an optimal action
  - Pathfinding to provide the detailed moving action
  - Task Priority
  - Stradgy

### Questions for TA

- Any time limitation on each time step
- it is not fair to given out the random start point
- we has to modify the environment class to implement our customized agent