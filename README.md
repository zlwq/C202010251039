# C202010251039
2020年IMCM比赛论文C题

对于第一个问题，我们没有严格求解，而是直接求出原图的最小生成树，然后在图中求出一个圆。这样就可以通过图中的闭合圆进行任务分配，并且可以根据最小生成树的分岔信息灵活地改变当前策略。

对于第二个问题，我们主要借用MATLAB函数。同时，通过对n和λ取值的讨论以及一系列冗长的计算，得到了相对意义上的最优解，为模型的灵敏度分析提供了一种非常方便的方法。

对于第三个问题，我们采用灰色预测方法，分别通过verhulst和DGM(，)模型，对其预测结果进行比较和优化，最终得到合适的结果。

在第四个问题中，我们将优先级以负对数的形式巧妙地转化为概率矩阵，同时，我们利用第一个问题中的最小生成树从角度上提供最优解
