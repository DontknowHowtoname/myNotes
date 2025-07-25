#### 线性收敛机制

Some papers have derived the limits of the generalization error under different converge regimes:

1. Under under the convergence regime $p/n \to \rho \in (0,\infty)$:
2. [Hastie et al. (2022)](https://arxiv.org/abs/1903.08560) derived the limit of the generalization error of the ridgeless least squares for the linear model
3. [Bartlett et al. (2020)](https://arxiv.org/abs/1906.11300) studied nonasymptotic upper and lower bounds on the risk and provide a characterization
4. [Belkin et al.(2020)](https://arxiv.org/abs/1812.11118) calculated the excess risk for two certain linear models
5. [Canatar et al.(2021)](https://arxiv.org/pdf/2106.02261) and [Simon et al.(2023)](https://openreview.net/pdf?id=FDbQGCAViI) investigated the
generaizatinor error for kernel regression
6. [Mei and Montanari(2022)](https://arxiv.org/pdf/1908.05355v4) derived the asymptotics of the random feature regression with $\rho$ random features under the convergence regime $p/d$, $n/d$ tending to a constant, where $d$ is the dimension of the data dimension

#### 多项式收敛机制

Some works extend high-dimensional asymptotics from the linear scaling to the polynomial scaling:

1. [Hu, Lu and Misiakiewicz (2024)*](https://arxiv.org/abs/2403.08160) obtained the convergence of the generalization error of random feature regression in the regime $p/d^{k_1}$, $p/d^{k_2}$ tending to a constant with $k_1, k_2 > 0$
2. [Pandit, Wang and Zhu (2024)](https://arxiv.org/abs/2408.01062) proved the convergence of the generalization error in the kernel ridge regression under the regime $p \approx d^2$
3. Some other papers have studied the limits of the generalization error of kernel ridge regression under $p=d^\alpha$, see[Misiakiewicz (2022)], [Xiao, Hu, Misiakiewicz, Lu and Pennington (2023)](https://arxiv.org/abs/2205.14846), [Ghorbani et al. (2021)*](https://arxiv.org/abs/2105.08508) and etc

#### 尺度率

The optimal match of $p$ and $n$ is closely related to scaling law of large foundational models(see [kaplan et al.(2020)])

1. [kaplan et al.(2020)] first proposed the neural scaling laws of transformer-base foundational models. They noted that the test loss follows a power-law decline with respect to factors such as compute resources, sample size, and model size, and proposed unified formulas incorporating these factors to estimate the test loss
2. [Bahri et al.(2024)] and [Blake (2024)] derived the dependence of the generalization error on one of the data size, model size in the asymptotic regime where the remaining quantities go to infinity from a statistical physics view
3. [Lin et al.(2024)] analyzed neural scaling laws for linear regression problem, showing that the generalization error minus the irreducible error scales with $O(p^{-(\alpha-1)} + n^{-(\alpha-1)/\alpha})$
