# **Trading Strategy Optimisation with a Multi-objective Genetic Algorithm**
This research is a Bitcoin trading bot implemented in Python using adaptive AI techniques. The bot uses historical data on the BTC/AUD pair from the Kraken exchange to make buy and sell decisions. The bot is able to make buy and sell decisions based on the following indicators: 
 - Bollinger Bands
 - Keltner Channels
 - True Range
 - Simple Linear Regression



## Abstract
Algorithmic trading, a significant area of research in artificial intelligence, faces the challenges of interpreting and processing extensive and dynamic data. This environment is ideal for implementing adaptive algorithms, such as the evolutionary algorithm NSGA-II used in this paper, notable for its effectiveness in multi-objective optimisation problems. We apply this algorithm, in conjunction with technical indicators, to explore and exploit the search space provided by BTC/AUD market data for a specific trading strategy. Our objective is to demonstrate how NSGA-II, with an optimal parameter configuration, can balance net profit and risk to optimise trading outcomes, as evidenced in the Pareto-front results. Our findings show that by optimizing the parameter values, our NSGA-II driven strategy significantly outperformed a buy-and-hold strategy over the same period.

## Equation
![equation](https://latex.codecogs.com/svg.latex?\Gamma_{N_i}%20=%20\frac{\Gamma_i%20-%20\text{min}(\Gamma)}{\text{max}(\Gamma)-\text{min}(\Gamma)})


![equation](https://latex.codecogs.com/svg.latex?\rho_{N_i}%20=%20\frac{\rho_i}{\text{max}(\rho)})


![equation](https://latex.codecogs.com/svg.latex?S_i%20=%20{\rho_{N_i}}^\alpha\cdot{\Gamma_{N_i}})

More detail content in research paper. 
## Experiment Results

### Data and Strategy Implementation
#### Price Chart with Bollinger Bands and Keltner Channels
![Price Chart with Bollinger Bands and Keltner Channels.png](Figures%2FPrice%20Chart%20with%20Bollinger%20Bands%20and%20Keltner%20Channels.png)
#### Pareto Front Generated
![Pareto_new.png](Figures%2FPareto_new.png)
#### Normalised Pareto Front
![Normalised_Pareto.png](Figures%2FNormalised_Pareto.png)
#### Optimised Strategy Trading Scheme with BTC Prices 
![opt_sol.png](Figures%2Fopt_sol.png)
#### Optimised Strategy Trading Scheme with ETC Prices 
![opt_ETH.png](Figures%2Fopt_ETH.png)
#### Comparison of BTC and ETH Prices 
![BTCvcETH.png](Figures%2FBTCvcETH.png)

## Authors
- [**Dipali Anil**](https://github.com/ophixus)
- [**Zheyuan Deng**]()
- [**Ame Liu**](https://github.com/Ameame1)
- [**Freddie Marsh**]()
- [**Chris Walter**]()
