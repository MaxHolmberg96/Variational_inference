# Variational inference applied to a univariate Gaussian

### Implementation and more is provided in the notebook "Variational_inference_UG.ipynb"

##### Adapted from the two books: Pattern Recognition and Machine Learning Christopher M. Bishop and A Probabilistic Perspective Murphy 2012.

Given a data set:

![](equations/eq_0.png)

which are i.i.d and drawn from a 1d Gaussian which likelihood function is given by:

![](equations/eq_1.png)

Where the conjugate prior distributions for ![](equations/eq_1.5.png) is given by:

![](equations/eq_2.png)

![](equations/eq_3.png)

With the mean field method we factorize the approximate distribution such that it is given by: 

![](equations/eq_4.png)

The following video sequence was generated with 15 data points and the following parameters:

![](equations/eq_5.png)

![Alt Text](vi_ug_15.gif)

And the following shows the exact posterior with the approximate (20 data points):

![Alt Text](vi_ug_exact_20.gif)

Where the exact posterior is given by:

![](equations/eq_6.png)
