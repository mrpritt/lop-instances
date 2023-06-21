# Instances for the linear ordering problem

Given a matrix $M=(m_{ij})\in\mathbb{R}^{n\times n}$ the linear ordering problem is to find a permutation $\pi$ of $[n]$ such that the sum of the values of $M$ above the diagonal after permuting rows and columns by $\pi$, namely $\sum_{i\in[n]}\sum_{j\in[i+1,n]} m_{\pi_i,\pi_j}$, is maximized.

This repository collects known instances from the literature, since previous repositories (e.g. [LOLIB](http://comopt.ifi.uni-heidelberg.de/software/LOLIB) and [OPTISOM](https://grafo.etsii.urjc.es/optsicom)) seem to be defunct.

All files are simple text files, where the first row contains the size of the matrix $n$, followed by the dense matrix in $n$ lines of $n$ coeffients each. Here's an overview of all instance sets.

| Instance set | # instances |
|--------------|-------------|
| Alea         | 300         |
| IO           | 50          |
| MB           | 30          |
| RandA1       | 100         |
| RandA2       | 75          |
| RandB        | 90          |
| SGB          | 25          |
| Spec         | 37          |
| XLOLIB       | 78          |
| XLOLIB2      | 200         |
