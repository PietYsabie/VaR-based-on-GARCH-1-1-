# VaR based on GARCH (1-1)
VaR based on GARCH for the Meerdael investment fund returns

Sample excel showing the Valua at Risk using two approaches:

1. Simple Long-Term Variance
2. Variance based on GARCH (1,1) approximation

![image](https://user-images.githubusercontent.com/78446548/115545004-964e1280-a2a3-11eb-8d68-6cc24fe5c302.png)

The calculation follows three steps:

1. Calculate iteratively the next variance based on GARCH(1,1), assuming initial parameters for omega, alpha and beta
2. Optimise the three parameters using excel's solver plugin
3. Calculate the Value-at-Risk

The result is a slightly higher value for the VaR using GARCH modelling, which is likely correct:

![image](https://user-images.githubusercontent.com/78446548/115545290-edec7e00-a2a3-11eb-9ee6-a5c912a141f2.png)
