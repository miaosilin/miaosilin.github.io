---
title: PBE 
url: PBE_url
tags: Game Theory
categories: Book Reviews
date:   2020-06-18 
---

# PBE 

## 贝叶斯扩展博弈

Definition 231.1: A Bayesian extensive game with observable actions is a tuple $\left\langle\Gamma,\left(\Theta_{i}\right),\left(p_{i}\right),\left(u_{i}\right)\right\rangle$ where(***贝叶斯扩展型博弈***)

- $\Gamma=\langle N, H, P\rangle$ is an extensive game form with perfect information and simultaneous moves and for each player $i \in N$ （***贝叶斯扩展型博弈由若干个完美信息博弈组合而成***）
- $\Theta_{i}$ is a finite set (the set of possible types of player $i$ ); we write $\Theta=x_{i \in N} \Theta_{i}$（类型空间）
- $p_{i}$ is a probability measure on $\Theta_{i}$ for which $p_{i}\left(\theta_{i}\right)>0$ for all $\theta_{i} \in \Theta_{i},$ and the measures $p_{i}$ are stochastically independent $\left(p_{i}\left(\theta_{i}\right) \text { is the prob. that player } i \text { is selected to be of type } \theta_{i}\right)$ （类型空间对应的概率空间）
- $u_{i}: \Theta \times Z \rightarrow \mathbb{R}$ is a von Neumann-Morgenstern utility function （效用空间组合）

## PBE

Definition 232.1: Let $\left\langle\Gamma,\left(\Theta_{i}\right),\left(p_{i}\right),\left(u_{i}\right)\right\rangle$ be a Bayesian extensive game ***with observable actions***（PBE针对可观测行动博弈）, where $\Gamma=\langle N, H, P\rangle .$ A pair $\left(\left(\sigma_{i}\right),\left(\mu_{i}\right)\right)=\left(\left(\sigma_{i}\left(\theta_{i}\right)\right)_{i \in N, \theta_{i} \in \Theta_{i}},\left(\mu_{i}(h)\right)_{i \in N, h \in H \backslash Z}\right)$where $\sigma_{i}\left(\theta_{i}\right)$ is a behavioral strategy of player $i$ in $\Gamma$ and $\mu_{i}(h)$ is a prob. measure on $\Theta_{i}$ is a perfect Bayesian equilibrium of the game if the following conditions are satisfied:

（PBE的条件）

- ***Sequential rationality***(序贯理性）: For every nonterminal history $h \in H/Z$,every player $i \in P(h),$ and every $\theta_{i} \in \Theta_{i}$ the prob. measure $O\left(\sigma_{-i}, \sigma_{i}\left(\theta_{i}\right), \mu_{-i} \mid h\right)$ is at least as good for type $\theta_{i}$ as $O\left(\sigma_{-i}, s_{i}\right.\left.\mu_{-i} \mid h\right)$ for any strategy $s_{i}$ of player $i$ in $\Gamma$；（*序贯理性*是指每个参与人在其每一个行动时点上都将重新优化自己的选择，并且会把自己将来会重新优化其选择这一点也纳入当前的优化选择当中。）
-  ***Correct initial beliefs***: $\mu_{i}(\emptyset)=p_{i}$ for each $i \in N$ （最开始时，后验概率分布与先验概率分布相同）
- ***Action-determined beliefs***: If $i \in P(h)$ and $a \in A(h)$ then

$$
\mu_{i}(h, a)=\mu_{i}(h) ; \text { if } i \in P(h), a \in A(h), a^{\prime} \in A(h), \text { and } a_{i}=a_{i}^{\prime}
$$

​		then $\mu_{i}(h, a)=\mu_{i}\left(h, a_{i}^{\prime}\right)$

- ***Bayesian updating***: If $i \in P(h)$ and $a_{i}$ is in the support of $\sigma_{i}\left(\theta_{i}\right)(h)$ for some $\theta_{i}$ in the support of $\mu_{i}(h)$ then for any $\theta_{i}^{\prime} \in$ $\Theta_{i}$ we have（根据新信息不停地修正原来的概率分布，在结点h根据行动a猜测是类型i的概率——贝叶斯公式）

$$
\mu_{i}(h, a)\left(\theta_{i}^{\prime}\right)=\frac{\sigma_{i}\left(\theta_{i}^{\prime}\right)(h)\left(a_{i}\right) \cdot \mu_{i}(h)\left(\theta_{i}^{\prime}\right)（在这个类型采取行动a_i的概率）}{\Sigma_{\theta_{i} \in \Theta_{i}} \sigma_{i}\left(\theta_{i}\right)(h)\left(a_{i}\right) \cdot \mu_{i}(h)\left(\theta_{i}\right)（所有类型采取行动a_i的概率）}
$$

## Signaling Game

- $A$ **signaling game** is a Bayesian extensive game with observable actions with two players, a "sender" and a "receiver". The sender is informed of the value of an uncertain parameter $\theta_{1}$ and then chooses an action $m$ (referred to as a **message**, though it may be payoff-relevant). The receiver observes the message (but not the value of $\theta_{1}$ ) and takes an action $a$. Each Player's payoffs depends upon the value of $\theta_{1}$, the message $m$ sent by the sender, and the action $a$ taken by the receiver.
- Formally, a signaling game is a Bayesian extensive game with observable actions $\left\langle\Gamma,\left(\Theta_{i}\right),\left(p_{i}\right),\left(u_{i}\right)\right\rangle$ in which $\Gamma$ is a two-player game form in which first player 1 takes an action then player 2 takes an action, and $\Theta_{2}$ is a **singleton**(不关心参与人2的类型）. 
- The tension in such a game arises from the fact that the receiver controls the action while the sender controls the information. The receiver has an incentive to try to deduce the sender's type from the sender's message, and the sender may have an incentive to mislead the receiver.

**(Spence's model of education):** A worker (the sender) knows her talent $\theta_{1}$ while her employer (the receiver) does not. The value of the worker to the employer is the expectation of $\theta_{1} ;$ we assume that the employer pays the worker a wage $w$ that is equal to this expectation. (The economic story that underlies this assumption is that there are many employers who compete for the worker, so that her wage is driven up to the expectation of $\theta_{1}$.) To model this behavioral assumption we assume that the payoff of the employer is $-(w-$ $\left.\theta_{1}\right)^{2}\left(\text { the expectation of which is maximized when } w=\mathrm{E}\left(\theta_{1}\right)\right)$ The worker's message is the amount $e$ of education that she obtains and her payoff is $w-e / \theta$ (reflecting the assumption that the larger is $\theta$ the easier it is for a worker to acquire education). Assume that the worker's talent is either $\theta_{1}^{L}$ or $\theta_{1}^{H}$ $>\theta_{1}^{L},$ and denote the prob.'s of these values by $p^{L}$ and $p^{H}=1-p^{L} .$Restrict attention to pure strategy equilibria and denote the choices (messages) of the two types by $e^{L}$ and $e^{H}$



## Modelling Reputation

道德高尚不是天生的，而是其想建立自己的声誉。有时对名声一点也不在乎也是一种对自己有利的策略选择

博弈论中不存在性格，只存在策略——只关心你表现出怎么样的形象，什么声誉。

所以影响先天的心理学是重要的，但是工业心理学就不一定了。

如果你从来没有采取某行动，每个人对你类型的猜测应该是不变的。

