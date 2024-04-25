---
layout: page
title: Methods
---

To achieve principled and scalable decision making in OASYS, we have developed the following solutions for multiagent planning and reinforcement learning.

# Modeling Agent Presence

<img src="presence_states.png" class="leftimage">

To address the challenge of modeling **agent openness**, we describe an extension of the Interactive POMDP reasoning framework that augments the agent's decision-making state with a set of *presence states* for each agent -- both for itself and its neighbors -- to track agent openness, as illustrated in the figure above [(Chandrasekaran et al., 2016)](http://www.auai.org/uai2016/proceedings/papers/286.pdf).  At a minimum, each presence state represents a binary state of whether an agent is currently *present* or *absent* from the environment.  Depending on the domain, richer representations are also possible, such as levels of suppressant (e.g., "full", "half", "empty") held by agents in the wildfire fighting application.  By combining the environment state with a presence state variable for each agent in the MAS, the agent can differentiate the nuances of situations caused by agent openness.  

Because the exact presence of other agents might not be directly observed by the planning agent (and instead may only be *partially observable*), the planning agent maintains (1) a stochastic process model of how the presence of each agent changes based on their actions, and (2) a Bayesian probabilistic belief about the presence of each other agent over time.  We proposed an accompanying offline planning algorithm based on PBVI but extended to open multiagent settings to enable agents to plan behaviors when their set of neighbors changes over time in ways critical for maintaining collaborative success.



# Scalability through Selectively Modeling Neighbors

<img src="extrapolation.png" class="leftimage">

Description

# Online Planning with MCTS
Description

# Enhanced Collaboration through Communication

<img src="communication.png" class="leftimage">

Description

# Fully Online Planning through Nested MCTS

Description

