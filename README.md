# knapsack-problem
knapsack problem using evolutionary algorithm with two selection methods


We can define the **fitness function** as follows:
\begin{aligned}
\\fitness=\sum_{i=1}^nc_iv_i;\qquad if\quad \sum_{i=1}^nc_iw_i <= M \\ 
fitness=0;\qquad\qquad\qquad\qquad\quad otherwise
\end{aligned}
Where:
>\begin{align}
n = chromosome\ length\qquad\qquad\qquad\ \\
c_i = ith\ gene\qquad\qquad\qquad\qquad\qquad\quad\ \\
v_i = ith\ value\qquad\qquad\qquad\qquad\qquad\quad\\
w_i = ith\ weight\qquad\qquad\qquad\qquad\qquad\ \\
M = Maximum\ weight\ of\ the\ bag\qquad
\end{align}
