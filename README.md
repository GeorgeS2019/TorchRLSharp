# From DeepSharp

# WIP: English version using Mermaid

## policy
  -  [ ] policy-based learning 基于策略函数的学习方法
  -  [ ] value-based learning 基于值函数的学习方法
       -  [ ] 动态规划学习方法 (Dynamic programming learning)
       - [ ] 蒙特卡罗学习方法 (Monte Carlo learning )
  -  [ ] Others


```mermaid
mindmap
  root((Reinforcement<br/>Learning))
    Definitions
      Interactions
          Environment
          Agent
      Elements
         State
         Action
         Strategy<br/>策略
             Deterministic Policy<br/>确定性策略
             Stochastic Policy<br/>随机性策略
         State transfer probability<br/>状态转移概率
         Rewards<br/>即时奖励
      Others
        Episodes
        Trial
        Continuing Tasks
    Policy
      Policy based learning
      Value based learning
        Monte Carlo learning
             Temporal Difference Learning
                 SARSA<br/>State Action Reward State Action
                 QLearning
        Dynamic programming learning
            Policy iteration algorithm
                Policy Evaluation
                Policy Improvement
            Value iteration algorithm
    Markov Decision Process
      Markov Decision Process<br/>马尔科夫决策过程
           Trajectory<br/>轨迹
      Markov Process<br/>马尔科夫过程
   Objective Functions
```
