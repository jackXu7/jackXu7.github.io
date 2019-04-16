---
layout: post
title: "zhaopeng day2"
author: "zhaopeng"
date: 2019-04-16
---
<script type="text/javascript"
    src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
矩阵和向量相乘<!-- more -->

线性方程组可以由矩阵和向量相乘表示为:

$$ Ax=b $$

其中$$ A \in \mathbb {R}^{m \times n} $$是一个已知的矩阵，$$ b \in \mathbb {R}^{m} $$是一个已知的向量。向量
$$ x \in \mathbb {R}^{n}  $$中的每一个元素$$ x_i $$都是未知的。矩阵$$ A $$的每一行和$$ b $$中对应的元素构成一个等式约束。我们可以把上式展开为:

\begin{align}

A_{1,:} x = b_{1}

A_{2,:} x = b_{2}

...

A_{m,:} x = b_{m}

\end{align}

或者写作成:

\begin{align}


A_{1,1} x_{1} + A_{1,2} x_{2} + ... + A_{1,n} x_{n} = b_{1}


A_{2,1} x_{1} + A_{2,2} x_{2} + ... + A_{2,n} x_{n} = b_{2}

...

A_{m,1} x_{1} + A_{m,2} x_{2} + ... + A_{m,n} x_{n} = b_{m}

\end{align}

