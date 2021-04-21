# VaR-based-on-GARCH-1-1-
VaR based on GARCH for the meerdael investment fund returns

Sample excel showing the Valua at Risk using two approaches:

1. Simple Long-Term Variance
2. Variance based on GARCH (1,1) approximation

The calculation follows three steps:

1. Calculate iterative the next variance based on GARCH(1,), assuming initial parameters for omega, aplha and beta
2. Optimise the three parameters using excel's solver plugin
3. Calculate the Value-at-Risk
