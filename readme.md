index
Content location
Abu quantization system source code abupy directory
Abu quantization tutorial abupy_lecture directory
Abu quantification non-programming interface operation abupy_ui directory
"Quantitative Trading Road" sample code ipython／python directory
"The Road to Machine Learning" sample code https://github.com/maxmon/abu_ml
Features
Use a variety of machine learning technologies to intelligently optimize strategies
Instruct the strategy to trade in the real market, improve the real effect of the strategy, and defeat the market
Supported investment markets:
US stocks, A shares, Hong Kong stocks
Futures, options
Bitcoin, Litecoin
Engineering design goals:
Separate basic strategy and strategy optimization supervision module
Improve flexibility and adaptability
APP download & URL
Thank you for using our app!

Computer browser access URL: https://www.abuquant.com
iOS Apple mobile phone AppStore download link
android phone download link page
Quantitative Technology Blog Address
K-line classroom address
Quantify classroom address
APP introduction
Quantification system
Abu Quantitative Comprehensive AI Big Data System, K-line Shape System, Classic Index System, Trend Trend Analysis System, Time Series Dimension System, Statistical Probability System, Traditional Moving Average System for in-depth quantitative analysis of investment products, thoroughly surpassing the user's complex code quantification stage , More suitable for the general population to use, stepping into the 2.0 era of vectorization.

Quantitative model
The above system combines hundreds of seed quantitative models, such as: financial time series loss model, deep form quality assessment model, long-short form combination assessment model, long form stop loss strategy model, short form covering strategy model, big data K-line form Historical combination fitting model, trading holding mentality model, dopamine quantitative model, inertial residual resistance support model, long-short swap retaliation probability model, strength confrontation model, trend angle change rate model, linkage analysis model, time series overreaction model , Slow retaliation reaction model, trend initiation speed model, paired hedging model, etc.



AI quantification
Abu Quantitative develops algorithms from the bottom for AI artificial intelligence and builds an artificial intelligence AI system suitable for quantification. It has trained several scoring models that recognize quantitative features from different angles, and is divided into three departments as a whole: physical model group, dopamine biology Model group, quantitative shape model group. Different family model groups evaluate trends from different perspectives (three directions of main physical transaction entity analysis, crowd psychology, charts, etc.). The family model groups are eliminated by a number of unique identification algorithms and parameter genetic elimination to form ethnic groups, weighted Voting score.

Quantitative strategy
Abu Quantitative combines the traditional quantitative system based on code strategy to predict the timing of future timing signals. The system is based on hundreds of simple seed trading strategies and derives more quantitative trading strategies. New strategies continue to self on the basis of these seeds. Learning, self-growth, continuous division, survival of the fittest, and reproduction under the elimination and selection mechanism, currently used quantitative buy-sell signal strategies total 18496 kinds.

Quantitative application
Abu Quantitative combines a variety of quantitative analysis data to build hundreds of quantitative applications, such as: AI high-energy warning, AI high-light moment, intelligent prediction of the rise and fall, quantification of five falling waves, quantification of five rising waves, resistance support strength analysis, rising triangle breakthrough , Descending triangle, triple bottom (head and shoulders bottom), triple top (head and shoulders top), arc top, arc bottom, dark cloud cover top pattern, ascending trilogy pattern, friend counterattack pattern, single needle dip pattern, shooting Star pattern, multi-sided cannon pattern, rising tweezers line, upward breakthrough box, gap breakthrough gap, golden section line quantification, trend tracking signal, mean value recovery signal, stop loss risk control quantification, take profit protection quantification, comprehensive index analysis Wait.

Install
deploy
It is recommended to use Anaconda to deploy the Python environment, see Quantitative Environment Deployment for details

test
import abupy
Interface operation (non-programming)


More interface operation examples

Use documentation
1: Development of timing strategy
The first section interface operation tutorial video playback address

The timing strategy determines when to buy investment products, and the backtest tells us how the simulated return of this strategy is based on historical data.

The preparation of buying timing factors
Decomposition mode to backtest the strategy step by step
Realization of the selling timing factor
Meeting the right person (stock) at the right time is a kind of happiness

It’s sad to meet the wrong person (stock) at the right time

I sighed when I met the right person (stock) at the wrong time

Meeting the wrong person (stock) at the wrong time is a kind of helplessness

read carefully

2: Optimization of timing strategy
The profit generated by the stop-profit and stop-loss protection strategy is used to control risks.

Basic stop-profit and stop-loss strategy
Risk control stop loss strategy
Profit Protection Take Profit Strategy


read carefully

3: Slippage strategy and transaction fees
Consider the transaction price deviation and handling fee generated when the trading strategy is applied.

Slippage buying and selling price determination and strategy realization
Calculation of transaction fee and custom fee
type date symbol commission
buy 20150423 usTSLA 8.22
buy 20150428 usTSLA 7.53
sell 20150622 usTSLA 8.22
buy 20150624 usTSLA 7.53
sell 20150706 usTSLA 7.53
sell 20150708 usTSLA 7.53
buy 20151230 usTSLA 7.22
sell 20160105 usTSLA 7.22
buy 20160315 usTSLA 5.57
sell 20160429 usTSLA 5.57
read carefully

4: Timing backtesting and position management of multiple stocks
Realize timing strategy for multiple stocks, and control risk through position management strategy.

Multiple stocks use the same factor for timing
The realization of custom position management strategy
Multiple stocks use different factors for timing
Use parallelism to improve timing efficiency


read carefully

5: Development of stock selection strategies
A good strategy requires a good target.

Preparation of stock selection factors
Parallel execution of multiple stock selection factors
Use parallelism to improve the efficiency of stock selection operations
read carefully

6: Measurement of backtest results
The right measurement leads the right direction.

Basic usage of metrics
Visualization of metrics
Extend custom measurement class
read carefully

7: Find the optimal parameters and scores of the strategy
Through a customized scoring mechanism, find the most reasonable parameters of a strategy, such as: How many days of moving average should be considered?

Parameter value range
Grid Search to find the optimal parameters
Scoring of measurement results
Scores with different weights
Implementation of custom scoring class
read carefully

8: Backtesting of the A-share market
A backtest example of the A-share market
Special handling of price limit
Analyze multiple sets of transaction results
read carefully

9: Backtest of the Hong Kong stock market
Backtest example of the Hong Kong stock market
Optimize strategy to improve the stability of the system
Encapsulate the'strategy' of the optimization strategy as a class decorator
read carefully

10: Bitcoin, Litecoin backtest
Bitcoin, Litecoin trend data analysis
Visual analysis of Bitcoin and Litecoin trends
Bitcoin, Litecoin market backtest
read carefully

11: Backtesting of the futures market
Characteristics of the futures market
Backtesting of bullish contracts
Backtesting of bearish contracts
Displacement distance ratio optimization strategy
read carefully

12: Machine learning and Bitcoin example
How to correctly use machine learning technology in quantitative trading of investment products?

Bitcoin feature extraction
Use of built-in machine learning module in abu
Test set verification and unbalanced technology
Inherit AbuMLPd to encapsulate data processing
read carefully

13: Quantitative technical analysis application
Three hypotheses of technical analysis: market behavior covers everything; prices move along trends; history will repeat itself.

Resistance line, support line is drawn automatically
Gap technical analysis
Technical analysis of traditional technical indicators
read carefully

14: Quantitative correlation analysis application
Behind similar investment product data are often investors with similar behavior patterns.

Related similarity measure
Distance measurement and similarity
Application of similar related interfaces
Natural relevance
read carefully

15: Quantitative trading and search engines
For failed trades generated by the search strategy, the referee intercepts impulsive traders.

Backtesting of split training set transactions
Manual analysis of transactions
Principles of Referee System
Angle referee
Give a macroscopically reasonable explanation
Optimal classification cluster screening


read carefully

16: UMP chief referee trading decision
Gap referee
Price referee
Volatility referee
Verify that the referee is competent, and turn on the referee interception mode in the abu system
Organize referees to make more complex comprehensive rulings
Let the referee learn how to cooperate and make the most correct judgment by himself
read carefully

17: UMP linesman trading decision
Angle Linesman
Price lineman
Volatility linesman
Comprehensive linesman
Verify that the linesman is competent
Turn on the sideman interception mode in the abu system
read carefully

18: Custom referee decision transaction
Train new referees from different perspectives
Train new linesmen from different perspectives
Add a new perspective to record the game (record backtest features)
The referee uses a new perspective to make transactions
Linesman uses a new perspective to make trade decisions
The design goals of the ump module in abupy are:

No need to hard code in specific strategies
No need to manually set the threshold, that is, make the code logic clear
Separate basic strategy and strategy optimization supervision module to improve flexibility and adaptability
Discover the hidden trading strategy problems in the strategy
You can continuously learn new transaction data
read carefully

19: Data source
Abu supports the market and trading of various financial investment products such as stocks, futures, digital currencies, and is highly customizable.

Data mode switching
Data storage switch
Data source switching
Update of market-wide data
Access to external data sources, stock data sources
Access to external data sources, futures data sources
Access to external data sources, Bitcoin, Litecoin data sources
read carefully

More Abu Quantitative Technical Articles

Follow Abu quant WeChat public account: abu_quant
