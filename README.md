This code is associated with the paper from Han et al., "Deciphering anomalous heterogeneous
intracellular transport with neural networks". eLife, 2020. http://dx.doi.org/10.7554/eLife.52224


# hurst-exp
Estimating Hurst exponents varying in time using neural networks for time series

Ensure you have Python3, tensorflow 1.14 and keras installed.
FBM package used is from https://github.com/crflynn/fbm.

model3densediff_n13.h5 is the saved tensorflow model that has been pre-trained

singleexpest.py is the python script to use to classify a single trajectory with a single Hurst exponent.

multiexpest.py is the python script to use to classify a single trajectory with varying Hurst exponent by using a symmetric moving window.



More information can be found on https://www.biorxiv.org/content/10.1101/777615v2 or message/email me (Daniel S Han).

