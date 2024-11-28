# Reinforcement-learning
The Path of Reinforcement Learning
Related papers for Reinforcement Learning (we mainly focus on Imitation learning).
## Contents 
* [Goal-conditioned Imitation Learning + Diffusion + feature](#Goal-conditioned-Imitation-Learning+Diffusion+Feature)
    - [Goal-conditioned BC + GAIL](#Goal-conditioned-（BC+GAIL）)
    - [Diffusion](#Diffusion)
    - [Learning Feature](#Learning-Feature)
* [NeurIPS-2019](#NeurIPS-2019)
* [AAAI-2024](#AAAI-2024)
* [RSS-2023](#RSS-2023)
* 
<a id='Goal-conditioned-Imitation-Learning+Diffusion+feature'></a>
## Goal-conditioned Imitation Learning + Diffusion + feature
<!-- ## <span id='Model-Free-Online'>Model Free (Online) RL</span>
### <span id='classic'>Classic Methods</span> -->

<a id='Goal-conditioned-（BC+GAIL）'></a>
### Goal-conditioned BC + GAIL

|  Title | Method | Conference | on/off policy | Action Space | Policy | Description |
| ----  | ----   | ----       |   ----  | ----  |  ---- |  ---- | 
| [Goal-conditioned Imitation Learning](https://arxiv.org/abs/1906.05838) | Goal-BC and Goalgail | NeurIPS2019 | off | Discrete | based on value function | use deep neural network to train q learning and reach the human level in the Atari games; mainly two trick: replay buffer for improving sample efficiency, decouple target network and behavior network |

<a id='Diffusion'></a>
### Diffusion

|  Title | Method | Conference | on/off policy | Action Space | Policy | Description |
| ----  | ----   | ----       |   ----  | ----  |  ---- |  ---- | 
| [DiffAIL: Diffusion Adversarial Imitation Learning](https://arxiv.org/abs/2312.06348) | DiffAIL | AAAI2024 | off | Discrete | based on value function | use deep neural network to train q learning and reach the human level in the Atari games; mainly two trick: replay buffer for improving sample efficiency, decouple target network and behavior network |

<a id='Learning-Feature'></a>
### Learning-Feature

|  Title | Method | Conference | on/off policy | Action Space | Policy | Description |
| ----  | ----   | ----       |   ----  | ----  |  ---- |  ---- | 
| | DQN | Nature15 | off | Discrete | based on value function | use deep neural network to train q learning and reach the human level in the Atari games; mainly two trick: replay buffer for improving sample efficiency, decouple target network and behavior network |

<a id='NeurIPS2019'></a>
## NeurIPS2019
| Paper | Type |
| ---- | ---- |
| [Goal-conditioned Imitation Learnin](https://arxiv.org/abs/1906.05838) | oral |

<a id='AAAI-2024'></a>
## AAAI-2024
| Paper | Type |
| ---- | ---- |
| [DiffAIL: Diffusion Adversarial Imitation Learning](https://arxiv.org/abs/2312.06348) | poster |

<a id='RSS-2023'></a>
## RSS-2023
| Paper | Type |
| ---- | ---- |
| [Goal Conditioned Imitation Learning using Score-based Diffusion Policies](https://arxiv.org/pdf/2304.02532) | oral |
