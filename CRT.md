# 中国剩余定理及其扩展 学习笔记 

## 中国剩余定理

[中国剩余定理][1] $\mathrm{(Chinese\;remainder\;theorem(CRT))}$ 是用来解决一元线性同余方程组的一个东西。

具体来说是解这样的方程组：

$$
\left\{
\begin{array}{c}
x\equiv a_1\pmod {m_1}\\ 
x\equiv a_2\pmod {m_2} \\ 
x\equiv a_3\pmod {m_3}\\
\cdots \\
x\equiv a_k\pmod {m_k}
\end{array}
\right.
$$

要求$\forall 1\leq i\not= j\leq k,gcd(m_1,m_2)=1$

令 $M=\prod\limits_{i=1}^{k}m_i$，那么方程的唯一解$x=(\sum\limits_{i=1}^{k}a_i*\frac{M}{m_i}*\mathrm{inv}(\frac{M}{m_i},m_i))\% m$

证明不存在的，记住结论就好了。

## 扩展中国剩余定理


## 参考资料

1. [zyf2000 中国剩余定理与扩展 Lucas定理与扩展 学习笔记](http://blog.csdn.net/clove_unique/article/details/54571216)
2. [百度百科 中国剩余定理][1]


[1]:https://baike.baidu.com/item/%E5%AD%99%E5%AD%90%E5%AE%9A%E7%90%86/2841597?fr=aladdin&fromid=11200132&fromtitle=%E4%B8%AD%E5%9B%BD%E5%89%A9%E4%BD%99%E5%AE%9A%E7%90%86
> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NDc4Nzg0NzVdfQ==
-->