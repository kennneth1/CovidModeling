# CovidModeling

The purpose of this modeling experiment was to simulate the SIR model using the runge kuttamethod, and fit the model prediction against real covid data 
containing daily new infections in theUS. This process was implemented in python, and the line of best fit was generated with a built-inmodule called curve fitter.  
The fit initially determined optimal parameters values for the SIR modelwith uncertainties ofk= 0.1897±0.0029,γ= 0.018±0.004, andR0= 10.54±2.17.  
While an R0 greater than 1 is expected, this large of anR0likely indicates that the model is overestimating howquickly the virus spreads in the US. 
An extra parameter ”c” was introduced to the SIR model tomitigate error in fitting the early portions of the data. 
