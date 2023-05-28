# Instances for the linear ordering problem

Given a matrix $M=(m_{ij})\in\mathbb{Z}^{n\times n}$ the linear ordering problem is to find a permutation $\pi$ of $[n]$ such that the values of $M$ after permuting rows and coluçmns by $\pi$, namely $\sum_{i\in[n]}\sum_{j\in[i+1,n]} m_{\pi_i,\pi_j}$, is maximized.

This repository collects known instances from the literature, since previous repositories (e.g. [[http://comopt.ifi.uni-heidelberg.de/software/LOLIB/]] and [[https://grafo.etsii.urjc.es/optsicom/]] seem defunct.

All files are simple text files, where the first row contains the size of the matrix $n$, and the following $n$ lines correspond to the lines of the matrix (i.e. each contains n coefficients).

