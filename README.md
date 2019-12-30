# Variational inference applied to a univariate Gaussian

##### Adapted from the two books: Pattern Recognition and Machine Learning Christopher M. Bishop and A Probabilistic Perspective Murphy 2012.

Given a data set $D$ = {$x_1, ..., x_N$} which are i.i.d and drawn from a 1d Gaussian which likelihood function is given by:

$p(D | \mu, \tau) = (\frac{\tau}{2\pi}))^{\frac{N}{2}} exp (-\frac{\tau}{2}\sum_{n=1}^N(x_n - \mu)^2)$

Where the conjugate prior distributions for $\mu$ and $\tau$ is given by:

$p(\mu | \tau) = \mathcal{N}(\mu | \mu_0, (\k_0\tau)^{-1})$

$p(\tau) = Gam(\tau | a_0, b_0)$

With the mean field method we factorize the approximate distribution such that it is given by: 

$q(\mu, \tau) = q_\mu(\mu)q\tau(\tau)$

The following video sequence was generated with 15 data points and the following parameters:
$\mu_0 = 0$,  $\kappa_0 = 1$, $a_0 = 1$ and $b_0 = 1$.

![Alt Text](vi_ug_15.gif)
