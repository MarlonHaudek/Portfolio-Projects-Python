# Application of Bayesian Machine Scientist by Guimera et al. (2020) on Black Scholes model

This project uses the Bayesian Machine Scientist explained by Guimera et al. for replicating the Black Scholes model.
For anybody who is interested in the functioning of the Bayesian Machine Scientist I refer to the paper 
Guimera, R, Reichardt, I, Aguilar-Mogas, A, Massucci, FA, Miranda, M, Pallares, J, Sales-Pardo, M. [A Bayesian machine scientist to aid in the solution of challenging scientific problems](http://dx.doi.org/10.1126/sciadv.aav6971), Sci. Adv. 6 (5) , eaav6971 (2020).

## Set Up explanation

The main program is located in the file "Option Pricing Black Schholes.ipynb".
This codes assess the given Bayesian Machine Scientist Code by Guimera et al. and the Black Scholes model.

In order to replicate the Black Scholes model, I simulated random data by using the Black Scholes model.
In the next step I plan to use this labeled data for the Bayesian Machine Scientist in order to 
replicate the Black Scholes model. 
Unfortunately, there is an error of the sympify package which I was not able to solve up until now. 
The purpose of publication of this code is to enrich the existing GitHub codes and gain advantages
from the community in order to resolve the error. 


## Next Steps
After the error is solved I am curious to find out whether the Bayesian Machine Scientist is able to replicate the 
Black Scholes model. If so, I plan to apply the Bayesian Machine Scientist on real option prices to receive a
closed-from model to compute the prices. Then I plan to compare those findings with the existing literature. 
