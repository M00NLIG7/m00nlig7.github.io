---
layout: post
title: Proof
permalink: /Induction-Proof/
mathjax: true
---

## MATH 2720 (01) - DISCRETE MATHEMATICS

### Proof:

proof. We prove $F_0 + F_1 + ... +F_n = F_{n+2} - 1\ for\ all\ n \in \mathbb{N}$ using mathematical induction. For the base case, which is $n = 0$, we compute $F_0 = F_2 - 1$ which is true. Thus proves the base step.\
&nbsp; &nbsp; &nbsp; &nbsp; For the inductive step, we assume $F_0 + F_1 + ... +F_k = F_{k+2} - 1$ and show $F_0 + F_1 + ... +F_k + F_{k+1} = F_{k+3} - 1$. We compute $$F_0 + F_1 + ... +F_k + F_{k+1} = F_{k+3} - 1$$ $$F_{k+1} + F_{k+2} - 1 = F_{k+3} - 1$$ $$F_{k+3} - 1 = F_{k+3} - 1$$

Thus $F_0 + F_1 + ... +F_k + F_{k+1} = F_{k+3} - 1$.\
&nbsp; &nbsp; &nbsp; &nbsp; We conclude $F_0 + F_1 + ... +F_n = F_{n+2} - 1\ for\ all\ n \in \mathbb{N}$
