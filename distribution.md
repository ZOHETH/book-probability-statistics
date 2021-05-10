# Distribution

#### 常见的概率分布

**伯努利分布（两点分布 0-1分布）**

伯努利试验是**单次随机试验**

* 概率质量函数：

  $$
  P(x)=p^x(1-p)^{1-x}=
  \begin{cases}
  p &if\ x=1\\
  q &if\ x=0
  \end{cases}
  $$

* 期望：

  $$
  E(x)=\sum xP(x)=0\times q+1\times p=p
  $$

* 方差：

  $$
  Var(x)=E[(x-E(x))^2]=\sum (x-p)^2P(x)=pq
  $$

**泊松分布 Poisson distribution**

**单位时间**内事件发生**次数**的概率分布.

一定时间内收到的服务请求；站台的候客人数？；机器出现的故障数；自然灾害发生的次数等等

* 概率质量函数

$$
P(X=k)={e^{-\lambda}\lambda^k\over k!}\\
k\in \{0,1,2.....\}
$$



