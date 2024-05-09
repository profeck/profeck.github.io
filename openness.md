---
layout: page
title: Openness
---

Openness can occur in OASYS due to changes in three different key components: the set of agents that interact in the environment, the set of tasks those agents aim to accomplish, and the types of those agents (i.e., their capabilities). 

# Agent Openness

**Agent openness** occurs when the set of agents in the system changes over time. Existing agents may leave, never to return or could rejoin the environment at a later time, and new agents may join in. When an agent leaves, it does so with its capabilities and also its working relationships (implicit or explicit).  Such departure means that the remaining agents, upon detecting the resultant deviations in observed situations or rewards, need to replan or learn new policies in order to adapt to the changing composition of the system and ensure optimality over time.  Replanning may require an agent to model other agents and engage with them or even abandon a task that it no longer can complete without the departed agent, and relearning could require exploring new actions and situations to re-converge on an optimal policy.  Likewise, when a new agent enters the environment, it brings with it potentially new resources and capabilities.  This injection brings new opportunities for the existing agents to complete tasks previously off limits to them, again prompting the need for replanning and relearning to acquire newly optimal solutions.  Even when new agents do not bring new capabilities to an environment, their presence could still disrupt existing plans and learned knowledge.

<br/>
<hr/>
<br/>

# Task Openness

**Task openness** occurs when the set of tasks that agents can work on change over time as new tasks are introduced and prior tasks disappear, which manifests in many real-world applications.  This is common in situations where agents may assume new roles and thus acquire a different set of tasks to accomplish (e.g., promotion or transfer within a company), or where the environment undergoes changes from one phase to another (e.g., driving in the city followed by driving in the interstate).  When there is task openness, an agent that aims to optimize its reasoning given the current set of tasks will need to re-calibrate its policies if new tasks are introduced to its environment or existing tasks become obsolete or no longer desirable.  Likewise, skills acquired or experiences accumulated for an agent to be effective and efficient in accomplishing certain tasks might prove to be only temporarily beneficial if those tasks become obsolete or irrelevant to the agent.

<br/>
<hr/>
<br/>

# Type Openness

**Type openness** occurs when the capabilities and decision-making processes of agents change over time.  Type openness is complimentary to agent openness and has a similar *macro*-level effect -- both change the composition and distribution of capabilities within the system over time.  On the other hand, how they produce such a macro change differs at the *micro-level: under type openness, individual agents who persist in the system change their fundamental abilities and behaviors, whereas agent openness can involve agents of (fixed) types being replaced by other agents of potentially different (fixed) types.  How should an agent make decisions knowing that its own abilities can change over time?  Likewise, how should an agent plan its interactions with others knowing there is the possibility that they could acquire or lose skills over time?  This third form of openness is less understood in the literature, and yet is present in many real-world applications of AI.

