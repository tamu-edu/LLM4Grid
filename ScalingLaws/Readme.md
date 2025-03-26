# Unlocking Multi-Task Electric Energy System Intelligence: Data Scaling Laws and Performance with Limited Fine-Tuning
This repository contains code and information related to the following paper:
[Unlocking Multi-Task Electric Energy System Intelligence: Data Scaling Laws and Performance with Limited Fine-Tuning]

Authors: Shaohuai Liu, Lin Dong, Chao Tian, Le Xie

Texas A&M University, Harvard University


# Introduction
Data scaling has revolutionized research fields like natural language processing, computer vision, and robotics control, providing foundation models with remarkable multi-task and generalization capabilities. In this paper, we investigate whether similar data scaling laws exist in developing foundation models for power systems, and whether appropriate data scaling can yield multi-task, cross-timescales capabilities that can be deployed in unseen operational scenarios. To this end, we conducted a comprehensive empirical study on data scaling by fine-tuning open-source foundation models using labeled data collected from diverse operational tasks and scenarios. We study how a foundation model's scenario generalization performance evolves with the number of training tasks, scenarios, and demonstrations. Our study involved collecting more than 450k demonstrations and implementing independent tests under a rigorous evaluation framework. Our findings reveal several key insights: 
- The generalization performance of a fine-tuned foundation model follows an approximate power-law relationship with the number of demonstrations and scenarios. 
- The fine-tuned model also demonstrates impressive multi-task capabilities, where multi-task training shares similar performance improvements with single-task training as the number of demonstrations increases, without interference among tasks.
- Models with small parameter sizes could have strong performance as well. Model performance does not scale significantly with parameter size. These findings underscore the feasibility of developing multi-task foundation models tailored for power systems, demonstrating that while larger datasets and models generally improve performance, extreme scaling is unnecessary to achieve satisfactory outcomes. 

<image src="/ScalingLaws/Fig1.png" height="400px" width="750px" >

# Key results
- Single-task training vs Multi-task training
  - Single-task training: training/fine-tuning foundation models on a single task
  - Multi-task training: training/fine-tuning foundation models on multi-tasks simutaneously
  - Results for three typical power system tasks are shown below: Optimal power flow, Fault classification, Fault localization

<image src="/ScalingLaws/Single-multitask training_1-3.png" height="260px" width="750px" >

  - Scaling laws are observed in both single-task and multi-task settings
    
<image src="/ScalingLaws/Scaling_law_1-3.png" height="260px" width="750px" >

- Task scalability of foundation models
  - To investigate this, three additional tasks are introduced: Transient prediction, Renewable forecasting, State Estimation
  - In the six-task setting, similar scaling laws are observed as the previous three-task setting.

<image src="/ScalingLaws/Single-multitask training_4-6.png" height="260px" width="750px" >

<image src="/ScalingLaws/Scaling_law_4-6.png" height="260px" width="750px" >

# Code Navigation
`The corresponding codes are under cleaning process and will be shared soon.`

# Data Navigation
`The corresponding data used for this study will be shared soon in [Zenodo].`


# Contact
Please contact us if you need further technical support or search for cooperation. \
Email contact: &nbsp; [Shaohuai Liu](mailto:liushaohuai5@tamu.edu?subject=[GitHub]%20DataScalingLaws), &nbsp; [Lin Dong](mailto:lin.dong@tamu.edu?subject=[GitHub]%20DataScalingLaws)
