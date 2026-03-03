# 第1章 向量空间
## 1.A $\mathbf{R}^n$ 与 $\mathbf{C}^n$
### 复数

>[!definition] 1.1 定义 复数
>- 一个复数是一个有序对 $(a, b)$ , 其中 $a, b \in \mathbf{R}$ , 但我们把它写成 $a + bi$ .
>- 所有复数构成的集合记为 $\mathbf{C}$ :
>$$\mathbf {C} = \{a + b \mathrm {i}: a, b \in \mathbf {R} \}.$$
>- C上的加法和乘法定义为
>$$(a + b \mathrm {i}) + (c + d \mathrm {i}) = (a + c) + (b + d) \mathrm {i},$$
>$$(a + b \mathrm {i}) (c + d \mathrm {i}) = (a c - b d) + (a d + b c) \mathrm {i},$$
>其中 $a,b,c,d\in \mathbf{R}$
>^def

如果 $a \in \mathbf{R}$ ，我们就把 $a + 0\mathrm{i}$ 等同于实数 $a$ 。于是可以把 $\mathbf{R}$ 看作 $\mathbf{C}$ 的一个子集。我们也常把 $0 + b\mathrm{i}$ 写成 $b\mathrm{i}$ ，并且把 $0 + 1\mathrm{i}$ 写成 $\mathrm{i}$ 。

1777年瑞士数学家莱昂哈德·欧拉最先使用符号i来表示 $\sqrt{-1}$

请自行验证在如上定义的乘法下 $\mathrm{i}^2 = -1$ .
但是不要去背上面的复数乘法公式，只要记住 $\mathrm{i}^2 = -1$ 并利用通常的算术法则（见1.3）就可以把它推导出来.

>[!comment]- aclazy
>![[1.png]]
>^com

>[!instance] 1.2 例
>计算 $(2 + 3\mathrm{i})(4 + 5\mathrm{i})$
>>[!solution]- 解 
>>$(2 + 3\mathrm{i})(4 + 5\mathrm{i})$
>>$= 2\cdot 4 + 2\cdot (5\mathrm{i}) + (3\mathrm{i})\cdot 4 + (3\mathrm{i})(5\mathrm{i})$
>>$\begin{array}{l} = 8 + 1 0 \mathrm {i} + 1 2 \mathrm {i} - 1 5 \\ = - 7 + 2 2 \mathrm {i}. \\ \end{array}$
>^ins

>[!axiom] 1.3 复数的算术性质
>**交换性（commutativity）**
>对所有 $\alpha, \beta \in \mathbf{C}$ 都有 $\alpha + \beta = \beta + \alpha$ , $\alpha \beta = \beta \alpha$
>
>**结合性（associativity）**
>对所有 $\alpha, \beta, \lambda \in \mathbf{C}$ 都有 $(\alpha + \beta) + \lambda = \alpha + (\beta + \lambda)$ , $(\alpha \beta) \lambda = \alpha (\beta \lambda)$
>
>**单位元（identities）**
>对所有 $\lambda \in \mathbf{C}$ 都有 $\lambda + 0 = \lambda, \lambda 1 = \lambda$
>
>**加法逆元（additive inverse）**
>对每个 $\alpha \in \mathbf{C}$ 都存在唯一的 $\beta \in \mathbf{C}$ 使得 $\alpha +\beta = 0$
>
>**乘法逆元（multiplicative inverse）**
>对每个 $\alpha \in \mathbf{C}$ ， $\alpha \neq 0$ 都存在唯一的 $\beta \in \mathbf{C}$ 使得 $\alpha \beta = 1$
>
>**分配性质（distributive property）**
>对所有 $\lambda, \alpha, \beta \in \mathbf{C}$ 都有 $\lambda (\alpha + \beta) = \lambda \alpha + \lambda \beta$ .
>^axm

上述性质可以利用我们所熟悉的实数性质以及复数的加法与乘法的定义来证明. 下面的这个例子给出了复数乘法的交换性的证明. 其他性质的证明留作习题.

>[!comment]- aclazy
>![[2.jpg]]
>![[3.jpg]]
>^com

>[!instance] 1.4 例 
>证明 $\alpha \beta = \beta \alpha$ 对所有 $\alpha, \beta \in \mathbf{C}$ 成立
>> [!proof]- 证明
>> 假设 $\alpha = a + b\mathrm{i}$ ， $\beta = c + d\mathrm{i}$ ，其中 $a,b,c,d\in \mathbf{R}$ .那么，复数乘法的定义表明
>> $$
\begin{array}{l} \alpha \beta = (a + b i) (c + d i) \\ = (a c - b d) + (a d + b c) \mathrm {i} \\ \end{array}
>>$$
>>并且
>>$$
\begin{array}{l} \beta \alpha = (c + d i) (a + b i) \\ = (c a - d b) + (c b + d a) \mathrm {i}. \\ \end{array}
>>$$
>>上面这两组等式和实数的加法与乘法的交换性表明 $\alpha \beta = \beta \alpha$
>^ins

>[!definition] 1.5 定义 $-\alpha$ ，减法（subtraction）、 $1 / \alpha$ ，除法（division）
>
>^def
