# prox-wavelet
Non-smooth optimization methods for image denoising by using wavelet transform.  
# Statement of the Problem. 
Mainly we are dealing with the following equation,
$$
y = Hx + \varepsilon.
$$
The purpose is to obtain $x$ value by using the observation/s $y$ and an information on the distribution of the noise, which in our case Gaussian $\varepsilon$