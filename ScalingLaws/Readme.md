# Unlocking Multi-Task Electric Energy System Intelligence: Data Scaling Laws and Performance with Limited Fine-Tuning
This repository contains code and information related to the following paper:
[Unlocking Multi-Task Electric Energy System Intelligence: Data Scaling Laws and Performance with Limited Fine-Tuning]

Authors: Shaohuai Liu, Lin Dong, Chao Tian, Le Xie

Texas A&M University, Harvard University


# Introduction
Data scaling has revolutionized research fields like natural language processing, computer vision, and robotics control, providing foundation models with remarkable multi-task and generalization capabilities. In this paper, we investigate whether similar data scaling laws exist in developing foundation models for power systems, and whether appropriate data scaling can yield multi-task, cross-timescales capabilities that can be deployed in unseen operational scenarios. To this end, we conducted a comprehensive empirical study on data scaling by fine-tuning open-source foundation models using labeled data collected from diverse operational tasks and scenarios. We study how a foundation model's scenario generalization performance evolves with the number of training tasks, scenarios, and demonstrations. Our study involved collecting more than 450k demonstrations and implementing independent tests under a rigorous evaluation framework. Our findings reveal several key insights: 
- First, the generalization performance of a fine-tuned foundation model follows an approximate power-law relationship with the number of demonstrations and scenarios. 
- Second, the fine-tuned model also demonstrates impressive multi-task capabilities, where multi-task training shares similar performance improvements with single-task training as the number of demonstrations increases, without interference among tasks.
- Lastly, models with small parameter sizes could have strong performance as well. Model performance does not scale significantly with parameter size. These findings underscore the feasibility of developing multi-task foundation models tailored for power systems, demonstrating that while larger datasets and models generally improve performance, extreme scaling is unnecessary to achieve satisfactory outcomes. 


# Key results


