# risk_management workgroup to the university

Aproach: 
Collect SP500 daily close returns during one year, use that data to forecast future volatility and asset returns using MLE.
With that and using some paramters given by the task sheet, we developed a BSM formula and MC simulations to estimate a fair value to the option and compared the results.  Plots are in the appendix of the main notebook,

Code structure:
* We used Functional programming 
* We used 4 notebooks. The main is where we answered the questions and used the helper functions provided by the other notebooks.
* mle.ipynb is where we have our maximum likelihood function
* Black&scholes.ipynb is where we have our BSM and BSM greeks functions
* monte_carlo.ipynb is where we have our Monte carlo simulations functions, our options payoff functions, and the longstaff schwartz (2001) algorithm to value american options
