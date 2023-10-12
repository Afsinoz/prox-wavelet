# prox-wavelet
Non-smooth optimization methods for image denoising by using wavelet transform.  
# Statement of the Problem. 
Mainly we are dealing with the following equation,
$$y = Hx + \varepsilon.$$
The purpose is to obtain $x$ value by using the observation/s $y$ and an information on the distribution of the noise, which in our case Gaussian $\varepsilon$

# Proximal Operator 
The proximal methods are one of the fundamental methods which have been used in the context of non-smooth optimization. These methods can be considered for the generalization of Gradient step when searching for a minimizer. The general definition for convex, lower semi continuous and proper function $f:\mathbb{R}^n\to\mathbb{R}$, the proximal operator $\operatorname{prox}_{\lambda f}(u)$ defined as, 
$$\operatorname{prox}_{\lambda f}=\operatorname{argmin}_{x} f(x)+\frac{1}{\lambda}||x-u||_2^2.$$