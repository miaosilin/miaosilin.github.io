---
title: MWG
url: MWG_url
tags: Mathemetical Economics
categories: Notes
date:   2020-06-18 
---

# 偏好与选择

`定义 1.B.1`：若偏好关系$\succsim$具有下列两个性质，则它是理性的:

1. ***完备性***（completeness）:对于所有 $x, y \in X,$ 都有 $x \succsim y$ 或 $y \succsim x$ （或二者都成立）。

2. ***传递性***（transitivity）：对于所有 $x, y, z \in X,$ 若 $x \succsim y$ 且 $y \succsim z,$ 则 $x \succsim z$（非传递性：孔多塞悖论）

`命题 1.B.1`：如果天是理性的，则:

- $\succ$为***非反身***的（irreflexive）[ $x \succ x$ 不成立]和传递的（若 $x \succ y$ 和 $y \succ z,$ 则 $x \succ z$ )。
- $\succ$ 是***反身***的（reflexive）[对于所有 $x, x \sim x]$ 、传递的 $(\text {若 } x \sim y \text { 和 } y \sim z, \text { 则 } x \sim z)$和对称的（symmetric）[若 $x \sim y, \text { 则 } y \sim x]$
- 若 $x \succ y \succsim z,$ 则 $x \succ z$

`命题 1.B.2`：只有理性的偏好关系义才能用效用函数表示。

`定义 1.C.1`: 若选择结构($\mathscr{B}$, C(・))具有下列性质:
若对于满足 $x, y \in B$ 的 $B \in \mathscr{B}$ 我们有 $x \in C(B),$ 则对于满足 $x, y \in B^{\prime}$ 和 $y \in C\left(B^{\prime}\right)$ 的任何 $B^{\prime} \in \mathscr{B}_{\text {参 }}$ 我们也必有 $x \in C\left(B^{\prime}\right)$
那么，我们说该选择结构 ($\mathscr{B}$,C(・) 满足***显示偏好弱公理***（weak axiom of revealed preference）,这个假设反映了我们期望个人的可观测到的选择满足一定程度的***一致性***（定义：若x 被显示至少与y 一样好，则y不可能被显示比x 更受偏好。）

`定义 1.D.1`：给定一个选择结构 $(\mathscr{B}, C(\cdot)),$ 我们说理性偏好关系亚将 $\mathscr{B}$ 上的 $C(\cdot)$ ***理性化***（rationalize），如果对于所有 $B \in \mathscr{S}$ 都有
$$
C(B)=C^{*}(B, \succsim)
$$

也就是说如果义生成了选择结构 $(\mathscr{B}, C(\cdot))$



# 消费者选择

`定义 2.D.1`：瓦尔拉斯预算集或说竞争性预算集 $B_{p, w}=\left\{x \in \mathbb{R}_{+}^{L}: p \cdot x \leq w\right\},$ 是由消费者在 面对市场价格 $p$ 和财富 w 时的所有可行消费束组成的集合。

瓦尔拉斯需求两个假设

`定义 2.E.1`：瓦尔拉斯需求对应 $x(p, w)$ 是***零次齐次***的，若对于任何 $p, w$ 和 $\alpha>0,$ 都有$x(\alpha p, \alpha w)=x(p, w)$（零次齐次是说，如果所有商品的价格和消费者的财富都变动相同的比例，那么他的消费选择不会变动）

`定义 2.E.2`: 瓦尔拉斯需求对应 $x(p, w)$ 满足***瓦尔拉斯法则***，若对于每个 $p \gg 0$, 和 ，$w>0$我们有 $p \cdot x=w$ 对所有 $x \in x(p, w)$ 成立。（瓦尔拉斯法则是说消费者花光了他的财富）

`定义 2.F.1`：瓦尔拉斯需求函数 $x(p, w)$ 满足***显示偏好弱公理***（weak axiom of revealedp reference, WA），如果对于任何两个价格财富状况 ( $p, w$ ) 和 $\left(p^{\prime}, w^{\prime}\right),$ 下列性质都成立:
$$
\text { 若 } p \cdot x\left(p^{\prime}, w^{\prime}\right) \leq w \text { 和 } x\left(p^{\prime}, w^{\prime}\right) \neq x(p, w), \text { 则 } p^{\prime} \cdot x(p, w)>w^{\prime}
$$
**替代效应非正**：
`命题 2.F.2`：若可微的瓦尔拉斯需求函数 $x(p, w)$ 满足瓦尔拉斯法则、零次齐次性以及弱公理，则在任何 $(p, w)$ 处，斯勒茨基矩阵 $S(p, w)$ 对于任何 $v \in \mathbb{R}^{L}$ 都满足 $v \cdot S(p, w) v \leq 0$



# 经典需求理论

`定义 3.B.1`: $\quad X$ 上的偏好关系狀 如果具有下列两个性质，则该偏好关系是理性的:
(i) 完备性: 对于所有 $x, y \in X,$ 都有 $x \succsim y$ 或 $y \succsim x$ (或二者都成立)。
(ii) 传递性: 对于所有 $x, y, z \in X,$ 若 $x \succsim y$ 且 $y \succsim z,$ 则 $x \succsim z$

`定义 3.B.2`: 对于 X 上的偏好关系$\succsim$，若 $x \in X$ 和 $y \gg x$ 意味着 $y \succ x,$ 则称$\succsim$是是弱单调的（weakly monotone）或簡称单调的。若 $y \geq x$ 且 $y \neq x$ 意味着 $y \succ x,$ 则它是强单调的(strongly monotone) 

`定义 3.B.3`: 对于 X 上的偏好关系来说，如果对于任何 $x \in X$ 和任何 $\varepsilon>0$, 都存在 $y \in X$ 使得 $\|y-x\| \leq \varepsilon$ 且 $y \succ x,$ 则称该偏好关系是局部非饱和的（locally nonsatiated）

**位似偏好**

`定义 3.B.6`: $\left.\quad X=\mathbb{R}_{+}^{L} \text { 上的偏好关系天 是位似的（homothetic }\right),$ 若所有无差异集都可以通过沿着任何射线等比例地扩展而联系在一起; 也就是说，若 $x \sim y$ 则 $\alpha x \sim \alpha y,$ 其中 $\alpha \geq 0$ 是任意的。

**拟线性偏好**

`定义 3.B.7`: $\quad X=(-\infty, \infty) \times \mathbb{R}_{+}^{L-1}$ 上的偏好关系亚 关于商品 $1 （$ 在这种情形下商品 1 称为计价物商品（numeraire commodity））是拟线性的（quasilinear），如果：
（i）所有无差异集彼此之间可以通过沿着商品 1 的坐标轴平行位移而得到。也就是说， 若 $x \sim y,$ 则对于 $e_{1}=(1,0, \ldots, 0)$ 和任何 $\alpha \in \mathbb{R},$ 都有 $\left(x+\alpha e_{1}\right) \sim\left(y+\alpha e_{2}\right)$
（ii）商品 1 是***合意的***（消费者所想要的）; 也就是说，对于所有 $x$ 和 $\alpha>0,$ 都有 $x+\alpha e_{1} \succ x$

`例 3.C.1`: ***字典序偏好关系***。为简单起见，假设 $X=\mathbb{R}_{+}^{2}$ 。将 $x \succsim y$ 定义为: 要么“ $x_{1}>y_{1} "$ 或要么“ $x_{1}=y_{1}$ 和 $x_{2} \geq y_{2} "$ 。这样的偏好关系称为字典序的偏好关系 ( lexicographic

`定义 3.C.1`: $X$ 上的偏好关系止 是***连续的***（continuous），若天在极限运算之下仍能保留。也就是说，对于任何数对序列 $\left\{\left(x^{n}, y^{n}\right)\right\}_{n=1}^{\infty},$ 若 $x^{n} \succsim y^{n}$ 对于所有的 $n$ 都成立， 且$x=\lim _{n \rightarrow \infty} x^{n}$ 和 $y=\lim _{n \rightarrow \infty} y^{n},$ 则 $x \succsim y$

`命题 3.D.2`：假设定义在消费集 $X=\mathbb{R}_{+}^{L}$ 上的局部非饱和的偏好关系$\succsim$，可用连续效用函数$u(\cdot)$ 表示。则瓦尔拉斯需求对应 $x(p, w)$ 具有下列性质:
（i）关于 $(p, w)$ 是***零次齐次***的: $\quad x(\alpha p, a w)=x(p, w)$ 对于任何 $p, w$ 和实数 $\alpha>0$ 都成$\dot{\vec{N}}_{0}$
（ii）***瓦尔拉斯法则***： $\quad p \cdot x=w$ 对于所有 $x \in x(p, w)$ 都成立。
（iii）***凸性/唯一性***：若$\succsim$是凸的，从而 $u(\cdot)$ 是拟凹的，则 $x(p, w)$ 是个凸集。而且，若 $\succsim$为严格凸，从而 $u(\cdot)$ 是严格拟凹的，则 $x(p, w)$ 只有唯一一个元素。

**间接效用函数**：

`命题 3.D.3`：假设定义在消费集 $X=\mathbb{R}_{+}^{L}$ 上的偏好关系亚 是局部非饱和的，该偏好关系能用连续的效用函数 $u(\cdot)$ 表示。间接效用函数 $v(p, w):$
(i) 是零次齐次的。
（ii）关于 w严格递增和关于任何商品 $l$ 的价格 $p_{l}$ 非递增。
（iii）拟召的; 也就是说，集合 $\{(p, w): v(p, w) \leq \bar{v}\}$ 对于任何 $\bar{v}$ 都是句的 $^{(+\rightarrow)}$
（iv）关于 $p$ 和 $w$ 连续。

斯勒茨基方程

命题 3.G.3:（斯勒茨基方程）假设定义在消费集 $X=\mathbb{R}_{+}^{L}$ 上的局部非饱和且严格四的偏好关系$\succsim$，可用连续效用函数 $u(\cdot)$ 表示。那么对于所有 $(p, w)$ 和 $u=v(p, w),$ 我们有
$$
\frac{\partial h_{l}(p, u)}{\partial p_{k}}=\frac{\partial x_{l}(p, w)}{\partial p_{k}}+\frac{\partial x_{l}(p, w)}{\partial w} x_{k}(p, w) \quad 对于所有 l, k 成立
$$
以矩阵符号表示为，
$$
D_{p} h(p, u)=D_{p} x(p, w)+D_{w} x(p, w) x(p, w)^{\mathrm{T}}
$$


# 期望效用理论

`定义 6.B.5`：效用函数U：? $\rightarrow \mathbb{R}$ 具有期望效用形式，如果可以对 N 个结果指定一组数 $\left(u_{1}, \ldots, u_{N}\right)$ 使得对于每个简单彩票$L=\left(p_{1}, \ldots, p_{N}\right) \in \mathscr{E}$ 我们有
$$
U(L)=u_{1} p_{1}+\cdots+u_{N} p_{N}
$$

具有期望效用形式的效用函数U：\mathscr $\rightarrow \mathbb{R}$ 称为社:诺依曼一摩根斯坦期望效用函数（von Neumann-Morgenstern expected utility function $)$

`定义6.C.1`:如果对于某个决策者来说,对于任何彩票 $F(\cdot),$ 他认为能确定产生金额 $\int x d F(x)$ 的退化彩票至少与彩票 $F(\cdot)$ 本身一样好，我们说该决策者是个风险厌恶者或者说他是风险厌恶的（risk aversion）。如果决策者在这两个彩票之间总是[即对于任何 F() J无差异的，我们说他是风险中性的（risk neutral）。最后，如果仅当这两个彩票是相同的[即当 $F(\cdot)$ 是退化 的时，决策者才认为这两个彩票无差异，那么我们说他是严格厌恶风险的（strictly risk averse）

`命题 6.C.1`: 假设某个决策者是期望效用最大化者，他在货币量上的效用函数是伯努利效用 函数 $u(\cdot) \bullet$ 那么下列性质是等价的:
（i）决策者是厌恶风险的。
(ii) $u(\cdot)$ 是凹的。
(iii) $c(F, u) \leq \int x d F(x)$ 对于所有 $F(\cdot)$ 都成立。
(iv) $\pi(x, \varepsilon, u) \geq 0$ 对于所有 $x$ 和 $\varepsilon>0$ 都成立。



# 市场均衡

***第一基本福利定理***。如果每种相关的商品在市场中以公开价格交易[即如果存在一组完全市场（complete markets）]，而且家庭和企业的行为是完全竞争 的（即都是价格接受者），那么市场结果是帕累托最优的。也就是说，当市场 是完全的，任何意争均衡必定是帕累托最优的。
***第二基本福利定理***。如果家庭的偏好和企业的生产集都是兄的，而且存在着 一组完全市场（商品以公开价格交易，每个个体都是价格接受者），那么：如果可对财富进行定额转移（lump-sum transfers），任何帕累托最优结果都是竞争均衡。

`定义 10.B.1`: 一个经济配置（economic allocation） $\left(x_{1}, \ldots, x_{I}, y_{1}, \ldots, y_{J}\right)$ 对每个消费者
$i=1, \ldots, I$ 指定了一个消费向量 $x_{i} \in X_{i},$ 对每个企业 $j=1, \ldots, J$ 指定了一个生产向量 $y_{j} \in Y_{k} \circ$ 对于配置 $\left(x_{1}, \ldots, x_{I}, y_{1}, \ldots, y_{J}\right),$ 如果
$\sum_{i=1}^{I} x_{l i} \leq \omega_{l}+\sum_{j=1}^{J} y_{l j}$ 对于 $l=1, \ldots, L$ 都成立
那么我们说该配置是可行的（feasible）因此，在某个经济配置中，如果每种商品的总消费量不大于该商品的初始亭赋和生产量之和，那么该配置是可行的。

`定义 10.B.3`: 配置 $\left(x_{1}^{*}, \ldots, x_{I}^{*}, y_{1}^{*}, \ldots, y_{J}^{*}\right)$ 和价格向量 $p^{*} \in \mathbb{R}^{L}$ 构成了一个竟争均衡或称瓦尔拉
斯均衡，如果它们能满足下列条件:
(i) 利润最大化: 对于每个企业 $j, \quad y_{j}^{*}$ 是下列最大化问题的解
$$
\operatorname{Max}_{y_{j} \in Y_{j}} p^{*} \cdot y_{j}
$$

（ii）效用最大化: 对于每个消费者 $i, \quad x_{i}^{*}$ 是下列最大化问题的解
$$
\begin{array}{l}
\underset{x_{i} \in X_{i}}{\operatorname{Max}} u_{i}\left(x_{i}\right) \\
\quad \text { s.t. } \quad p^{*} \cdot x_{i} \leq p^{*} \cdot \omega_{i}+\sum_{j=1}^{J} \theta_{i j}\left(p^{*} \cdot y_{j}^{*}\right)
\end{array}
$$

（iii）市场出清: 对于每种商品 $l=1, \ldots, L$
$$
\sum_{i=1}^{I} x_{l i}^{*}=\omega_{l}+\sum_{j=1}^{J} y_{l j}^{*}
$$
均衡配置和价格独立于禀赋和产权份额的分配。

`命题 10.D.1`:（福利经济学第一基本定理）如果价格 $p^{*}$ 和配置 $\left(x_{1}^{*}, \ldots, x_{I}^{*}, q_{1}^{*}, \ldots, q_{J}^{*}\right)$ 构成了一 个竞争均衡，那么 $\left(x_{1}^{*}, \ldots, x_{I}^{*}, q_{1}^{*}, \ldots, q_{J}^{*}\right)$ 这个配置是帕累托最优的。



# 外部性与公共物品

一般来说，如果存在外部效应，竞争均衡不是帕累托最优的。



# 市场势力

