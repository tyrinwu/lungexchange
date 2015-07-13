# lungexchange

The concept of a _lung exchange_ scheme is similar to that of a kidney
exchange scheme, with a key difference being that each patient in a
lung exchange scheme would requires two donors rather than one. To the
best of my knowledge, lung exchange has not yet been implemented in
practice, but the following recent papers discuss theoretical foundations:

- _Lung Exchange_. Haluk Ergin, Tayfun Sönmez, M. Utku Ünver. _Working
  paper_. [Link][1]

- _Mechanism design and implementation for lung exchange_. Suiqian Luo and
  Pingzhong Tang. *IJCAI-2015*, Buenos Aires, Argentina. [Link][2]

The theory of lung exchange was also discussed in a recent
[_Economist_ article][3].

This repository contains my work so far on implementing algorithms for
lung exchange. In particular, it includes integer programming formulations
for:

- Optimisation with unbounded exchange size, using an edge formulation
- Optimisation with bounded exchange size, using a variant of Constantino et al.'s
  [extended edge formulation][4] for kidney exchange
- Optimisation with bounded exchange size, with a variable for each feasible
  exchange.

## Notes on usage



[1] http://www.tayfunsonmez.net/wp-content/uploads/2014/09/lung-exchange-6.pdf
[2] http://iiis.tsinghua.edu.cn/~kenshin/lung.pdf
[3] http://www.economist.com/blogs/freeexchange/2014/09/lung-exchanges
[4] http://www.sciencedirect.com/science/article/pii/S0377221713004244
