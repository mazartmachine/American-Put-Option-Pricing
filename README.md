# American-Put-Option-Pricing
1. “Main1.m” and “Main2.m” files are executed to see the comparison between calculated option prices and actual option prices, one can change chosen stock and data to compute American put option prices of different kinds of stocks (paying-dividend and non-paying dividend).
“Main2.m” is the execution file modified by CEV model. One can run two main files to compare the computation results.


2. “PriceCal.m” file is price calculation function without variance reduction method, one can modify the code to disp the computed option prices data.

3. “PriceCalCEVCV.m” files is price calculation function with control variates method, one can modify the code to dips the computed option prices data.

4. “AmericanPutLSM.m” is the function of implementing Longstaff Schwartz method without variance reduction technique.

5. “AmericanPutLSMCV.m” is the function of implementing Longstaff Schwartz method with control variates method. One can modify the code to disp reduced variance of MC estimates.

6. “CEVest.m” file is to estimate parameters of CEV model with different stock series. Given reasonable initial values of parameters, apply MATLAB optimization tools to obtain estimated parameters.

7. “CEVmodeldiv.m” files is the optimization function designed to estimate parameters of CEV model, one can change stock data to obtain estimate different parameters.

8. “Comparison.m”  and “Comparisoncy.m” files are functions returning value and variance of different methods, and drawing the value in a graph. 

9.  "sig.m" is a function calculating the volatility of stock prices.

