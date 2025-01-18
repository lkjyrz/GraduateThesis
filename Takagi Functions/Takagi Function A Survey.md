---
Finish: False
type: Takagi Function
---

# Notations
- $x$的二级展开: $x=0.\varepsilon_1\varepsilon_{2}\cdots=\overset{\infty}{\underset{n=1}{\sum}} \frac{\varepsilon_{n}}{2^{n}}.\varepsilon_n\in\{0,1\}$ 
- 0,1的数量: $I_n=\overset{n}{\underset{k=1}{\sum}}\varepsilon_k,~~~~O_n=n-I_n,D_n=O_n-I_n=\underset{k=1}{\overset{n}{\sum}}(-1)^{\varepsilon_{k}}$ 
- 0,1的稠密度: $d_{1}(x)= \underset{n\rightarrow\infty}{\lim} \frac{1}{n}\underset{k=1}{\overset{n}{\sum}}\varepsilon_{k}, d_{0}(x)=1-d_1(x)$
- $\alpha$-维Hausdorff测度: $\mathcal{H}^\alpha$ 
- A的Hausdorff维数: $\mathrm{dim}_HA$ 
- $f$ 图像的Hausdorff维数: $\mathrm{dim}_H(f)$
# 分析性质
## 导数
>[!tip] Takagi
>The Takagi function T does not possess a finite derivative at any point.

 >[!note] (Billingsley) 
 >Put $\phi_{k}(x)=2^{-k}\phi(2^{k}x)$ for $k=0,1,\cdots$. Fix a point $x$ , for each $n\in \mathbb{N}$, let $\mu_n$ and $\nu_n$ be the dyadic rationals of order $n$ with $\nu_n-\mu_n=2^{-n}$ and $\mu_{n}\le x<\nu_n$. Then,
>$$
\frac{T(\nu_n)-T(\mu_n)}{\nu_n-\mu_{n}}=\sum\limits_{k=0}^{n-1}\frac{\phi_k(\nu_n)-\phi_k(\mu_n)}{\nu_n-\mu_n}
>$$ 


## 连续性