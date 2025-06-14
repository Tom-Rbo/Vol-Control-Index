Multi-Asset Index with Volatility Control and Leverage  

**Overview**  
This notebook presents the construction and analysis of a multi-asset index that incorporates volatility control and leverage.     
By combining a diverse set of asset classes—including equities, bonds, commodities, and real estate—the objective is to create a robust and balanced portfolio.   
The methodology involves downloading historical price data, calculating returns, and applying a systematic allocation process that targets a specific volatility level through dynamic rebalancing and leverage adjustment.   
The notebook also provides visualizations and key performance metrics to evaluate the effectiveness of the strategy, offering insights into risk management and portfolio optimization in a multi-asset context.  

**Project Objectives**    
- Develop a quantitative model to compute a volatility-controlled portfolio.
- Implement a volatility targeting mechanism using rolling historical volatility.
- Backtest the performance of the Vol Control Index over time.
- Visualize portfolio returns and allocation

**Tools & Technologies**  
- Pandas — data manipulation
- NumPy — numerical operations
- Matplotlib / Seaborn — data visualization
- yfinance — historical price data retrieval
- scipy.stats — statistical calculations

**Improvements & Future Work**    
