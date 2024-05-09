---
layout: page
title: OASYS
---

## Open Agent Systems

In many real-world applications of AI, the set of actors and tasks are not constant, but instead change over time.  Robots tasked with suppressing wildfires eventually run out of limited suppressant resources and need to temporarily disengage from the collaborative work in order to recharge, or they might become damaged and leave the environment permanently.  In a large business organization, objectives and goals change with the market, requiring workers to adapt to perform different sets of tasks across time.  We call these multiagent systems **open agent systems**, and the *openness* of the sets of agents and tasks  necessitates new capabilities and modeling for decision making compared to planning and learning in *closed* environments.

In this research, we address the challenges to multiagent decision making caused by three types of openness: 

1. **agent openness**, where the set of agents acting in the world change over time.  This could include agents temporarily disengaging from the environment before returning (e.g., autonomous ride-sharing cars recharging when low on energy), new groups of agents joining over time (e.g., new attackers appearing globally in a cybersecurity defense application), or existing agents leaving permanently (e.g., firefighting robots becoming damaged and needing to leave the operations to recover valuable hardware).

2. **task openness**, where the set of tasks that agents aim to accomplish change over time.  This could include new tasks appearing that are novel compared to existing tasks (e.g., transporting ride-sharing passengers for unique events) or popular existing tasks disappearing forever.  It could also entail a gradual shift in the requirements of tasks over time so that tasks gradually become different from their initial context.

3. **type openness**, where the types (i.e., capabilities) of agents change over time.  This could include agents learning new skills and gaining new responsibilities (e.g., promotions of office workers) or robots losing abilities over time (e.g., modeling damage to robots engaged in the field).

<div>
  <iframe style="display: block; margin: auto;" width="560" height="315" src="https://www.youtube.com/embed/vQOK3YNeTDE?si=4NO0ZqwAb893tTxI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  <br/>
</div>

<br/><hr/><br/> 

## Project Details

This project is a multi-institution collaboration led by [Prashant Doshi](https://thinc.cs.uga.edu) of the University of Georgia, [Leen-Kiat Soh](http://cse.unl.edu/~lksoh/) of the University of Nebraska-Lincoln, and [Adam Eck](https://cs.oberlin.edu/~aeck) of Oberlin College.  Our work has been supported by two collaborative grants from the National Science Foundation (add details).

<br/><hr/><br/>

## Publications 

More details about our research on OASYS can be found in:

* Eck, A., Soh, L.-K., & Doshi, P. 2023. Decision Making in Open Multiagent Systems. AI Magazine. 44(4), 508-523. [[link]](https://onlinelibrary.wiley.com/doi/10.1002/aaai.12131)

* Kakarlapudi, A., Anil, G., Eck, A., Doshi, P., & Soh, L.-K. 2022. Decision-Theoretic Planning with Communication in Open Multiagent Systems. Proceedings of the 2022 Conference on Uncertainty in Artificial Intelligence (UAI'22), Eindhoven, Netherlands, August 1-5, 2022 [[link]](https://proceedings.mlr.press/v180/kakarlapudi22a/kakarlapudi22a.pdf) [[Open Review with Appendices]](https://openreview.net/forum?id=H5LUOwUoql5)

* Eck, A., Shah, M., Doshi, P., & Soh, L.-K. 2020. Scalable Decision-Theoretic Planning in Open and Typed Multiagent Systems. Proceedings of the Thirty-fourth AAAI Conference on Artificial Intelligence (AAAI’2020), New York City, NY, February 8-12, 2020. [[link]](https://aaai.org/ojs/index.php/AAAI/article/view/6200) [[Preprint with Appendices]](https://arxiv.org/abs/1911.08642)

* Chandrasekaran, M., Eck, A., Doshi, P., & Soh, L.-K. 2016. Individual Planning in Open and Typed Agent Systems. Proceedings of the 2016 Conference on Uncertainty in Artificial Intelligence (UAI'16), New York City, NY, June 25-29, 2016. [[link]](http://www.auai.org/uai2016/proceedings/papers/286.pdf)

<br/><hr/><br/>

## Implementations

Details about the implementations of our testbeds and solutions can be found in the following GitHub repositories:

* CommunicativeOASYS: the Cython implementation of our UAI'2022 paper above: [https://github.com/OberlinAI/CommunicativeOASYS](https://github.com/OberlinAI/CommunicativeOASYS)
* ScalableOASYS: the Java implementation of our AAAI'2020 paper above: [https://github.com/OberlinAI/ScalableOASYS](https://github.com/OberlinAI/ScalableOASYS)
