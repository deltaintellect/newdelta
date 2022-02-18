---
title: Binomial Theorem
date: 2021-11-08T19:55:54.708Z
draft: false
featured: false
summary: A binomial theorem is used for expanding binomial expressions....
tags:
  - Further Math
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
Consider the following binomial expressions, 

- $(x+y)^{0}=1$
- $(x+y)^{1}=x+y $
- $(x + y)^2 = (x + y)(x + y) = x^{2}+2 x y+y^{2}$
- $(x+y)^{3}=x^{3}+3 x^{2} y+3 x y^{2}+y^{3}$
- $(x+y)^{4}=x^{4}+4 x^{3} y+6 x^{2} y^{2}+4 x y^{3}+y^{4}$
- etc.

Now, the expansion becomes complex when we want to find, for example, $(x + y)^15$. 
So, we need a better alternative. This is where the binomial theorem comes in. 

That is, binomial theorem is a mathematical formula for expanding the binomial expression of the form $(x + y)^n$, for positive values of $n$. The formula is given by

$$
(x+y)^{n}=\left(\begin{array}{l}
n \\
0
\end{array}\right) x^{n} y^{0}+\left(\begin{array}{l}
n \\
1
\end{array}\right) x^{n-1} y^{1}+\left(\begin{array}{l}
n \\
2
\end{array}\right) x^{n-2} y^{2}+\cdots+\left(\begin{array}{c}
n \\
n-1
\end{array}\right) x^{1} y^{n-1}+\left(\begin{array}{l}
n \\
n
\end{array}\right) x^{0} y^{n}
$$.

The above expression can be rewritten as;

$$
(x+y)^{n}=\sum_{k=0}^{n} \begin{pmatrix} n \\ k \end{pmatrix} x^{n-k} y^{k}=\sum_{k=0}^{n} \begin{pmatrix}  n \\ k \end{pmatrix} x^{k} y^{n-k}.
$$

**Guide:**
1. Review Binomial Theorem in your textbook.
2. Download the file below and practice problem solving.

_Don't forget step 1_

| File                       |  Scope                       |             |
| -------------------------- |------------------------------| ----------- |
| Binomial Theorem          | Objective and Subjective Tests    | [Download](https://drive.google.com/uc?export=download&id=1AcVym8hYzEbuHEjd5lY867y7xb9ZqYZi)       |


