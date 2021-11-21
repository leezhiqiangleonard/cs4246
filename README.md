# CS4246

## Motivation
Cyber security consists of a collection of methods to protect the integrity, availability of computer systems and electronic data. In the era that internet-connected systems remarkably grow, systems and data become more vulnerable to the increasing cyber attacks. As artificial Intelligence (AI) enables the self-learning attacks, the rapid and ever-evolving attacks require defending to go beyond the classic defense strategies. Machine learning (ML) has been widely applied for attacks detection and data protection.

As a major branch of ML which can closely realize human learning behaviour in an unprecedented environment, reinforcement learning (RL) is considered as adaptable and suitable to decipher cyber security problems. In this project, we touch on the cyberwarfare with reinforcement learning.

## Problem Definition
The target of the project is to study attacker's tactics, implement attacks with RL approach, and review the performance of network against the attacks.

To achieve the goal, we start with building and defining the network with environment, action space and reward definitions. A open-source simulator (https://github.com/microsoft/CyberBattleSim) is deployed as the platform of attacks development and network construction.

Next we set the attackers' baseline model as epsilon-greedy random search. On top of it, we implement the algorithm of a few RL models such as Monte Carlo Tree Search (MCTS) and deep Q-learning(DQL). We further analyze the performance of the different models by cumulative rewards, training time, and response to different environments.
