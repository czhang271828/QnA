Q: 如果任意有限子集事件相互独立, 这是否意味着无限事件相互独立? 如果我们有无限多个事件 $A_1$, $A_2$, $\ldots$, 我们可以推出 $\Pr \left(\bigcap _{i=1}^\infty A_i\right)=\prod _{i=1}^\infty\Pr (A_i)$ 吗？

***

A:

> 如果任意有限子集事件相互独立, 这是否意味着无限事件相互独立?

这是你的问题.

> 如果我们有无限多个事件 $A_1,A_2,\cdots$, 我们可以推出 $\Pr \left(\bigcap _{i=1}^\infty A_i\right)=\prod _{i=1}^\infty\Pr (A_i)$ 吗?

这是你的式子. 

首先这个问题和式子不是一回事, 概率为 $0$ 不代表事件不发生.

以下例子对于问题而言是反例, 但公式成立: **记事件 $A_k$ 为第 $k$ 次抛出的硬币是反面, $A_0$ 为有限步内能抛出正面. 那么 $\{A_k\}_{k\geq 0}$ 满足有限事件相互独立之假定.** 

以下例子对问题和式子都是反例, 实际上是不取等的 Fatou 引理: 在 $\mathbb N_+$ 上随机选一个数, 记 $A_k$ 为没选到 $k$, 那么式子左侧是 $0$ 右侧是 $1$. 

如果这可数个事件确实是独立的, 那么可以利用 Dependent choice 公设给出相应的式子. 定义无限事件相互独立需要这个公设, 上文对式子的反驳表明, 现有的公理可以定义少部分'不可能独立的无限事件', 实际上是在在虚空索敌. 我倾向认为这是抽象废话, 例如我们可以规定 $\mathbb R$ 到自身双射具有不动点的概率为 $1-e^{-1}$, 但这本身没什么用. 