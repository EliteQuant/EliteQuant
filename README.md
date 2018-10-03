# EliteQuant
A list of online resources for quantitative modeling, trading, portfolio management 

Besides those in this list and in [gitee list](https://gitee.com/EliteQuant/EliteQuant), there are lots of other valuable online resources. We are not trying to be exhaustive. Please feel free to contact us if you believe something is worth recommending. A general rule of thumb for open source projects is having already received 10 stars on github.

* [Quantitative Trading Platform](#quantitative-trading-platform)
* [Trading System](#trading-system)
* [Quantitative Library](#quantitative-library)
* [Quantitative Model](#quantitative-model)
* [Trading API](#trading-api)
* [Data Source](#data-source)
* [Cryptocurrency](#cryptocurrency)
* [Websites Forums Blogs](#websites-forums-blogs)
* [Papers and Books](#papers-and-books)

- - -

## Quantitative Trading Platform

* [Quantopian](https://www.quantopian.com/) -- First Python-based online quantitative trading platform; its core library [zipline](https://github.com/quantopian/zipline) and its performance evaluation library [pyfolio](https://github.com/quantopian/pyfolio); and [alphalens](https://github.com/quantopian/alphalens)

* [QuantConnect](https://www.quantconnect.com/) -- C# based online quantitative trading platform; its core library [Lean](https://github.com/QuantConnect/Lean)

* [Quantiacs](https://www.quantiacs.com/) - The Marketplace For Algorithmic Trading Strategies; its [Matlab and Python toolbox](https://github.com/Quantiacs)

* [Numerai](https://numer.ai/) - crowd-sourced trading strategies; its [Python API](https://github.com/numerai/NumerAPI)

* [Collective2](https://trade.collective2.com/) - The platform that allows investors subscribe to top-traders; its [algotrades system](http://www.algotrades.net/)

* [ZuluTrade](https://trade.collective2.com/) - The platform that allows investors subscribe to top-traders

* [Tradingview](https://www.tradingview.com/chart/) - It provides free widges used for example [Huobi](https://www.huobipro.com/zh-cn/eos_usdt/exchange/)

* [Investing.com](https://www.investing.com/indices/us-spx-500-futures-commentary) - Real time multi-assets and markets

## Trading System

* [MetaTrader 5](https://www.metatrader5.com/) - Multi-Asset trading system

* [TradeStation](https://www.tradestation.com/) - Trading system

* [SmartQuant(OpenQuant)](http://www.smartquant.com/) - C# Trading system

* [RightEdge](http://www.rightedgesystems.com/) - Trading system

* [AmiBroker](https://www.amibroker.com/) - Trading system

* [Algo Terminal](https://www.algoterminal.com/) - C# Trading system

* [NinjaTrader](http://ninjatrader.com/) - Trading system

* [QuantTools](https://quanttools.bitbucket.io/) - Enhanced Quantitative Trading Modelling in R

* [pyalgotrade](https://github.com/gbeced/pyalgotrade)  - Python Algorithmic Trading Library

* [finmarketpy](https://github.com/cuemacro/finmarketpy)  - Python library for backtesting trading strategies

* [IBridgePy](http://www.ibridgepy.com/)  - A python system derived from zipline

* [Backtrader](https://www.backtrader.com/)  - Blog, trading community, and [github](https://github.com/backtrader/backtrader)

* [IbPy](https://github.com/blampe/IbPy)  - Interactive Brokers Python API

* [PyLimitBook](https://github.com/danielktaylor/PyLimitBook)  - Python implementation of fast limit-order book

* [qtpylib](https://github.com/ranaroussi/qtpylib)  -  Pythonic Algorithmic Trading via IbPy API and its [Website](http://qtpylib.io/)

* [Quantdom](https://github.com/constverum/Quantdom)  - Python-based framework for backtesting trading strategies & analyzing financial markets [GUI]

* [ib_insync](https://github.com/erdewit/ib_insync)  - Python sync/async framework for Interactive Brokers API

* [bt](https://github.com/pmorissette/bt)  - flexible backtesting for Python

* [TradingGym](https://github.com/Yvictor/TradingGym)  - Trading and Backtesting environment for training reinforcement learning agent or simple rule base algo.

* [OpenHFT](https://github.com/OpenHFT)  - Java components for high-frequency trading

* [libtrading](https://github.com/libtrading/libtrading) -- c api, low latency, fix support

* [thOth](https://github.com/vermosen/thOth) -- open-source high frequency trading library in C++ 11

* [qt_tradingclient](https://github.com/spinlockirqsave/qt_tradingclient_1) -- multithreaded Qt C++ trading application, QuantLib-1.2.1, CUDA 5.0

* [SubMicroTrading](https://github.com/gsitgithub/SubMicroTrading) -- Java Ultra Low Latency Trading Framework

* [WPF/MVVM Real-Time Trading Application](https://www.codeproject.com/Articles/326641/WPF-MVVM-Real-Time-Trading-Application)  - Architechture

* [TradeLink](https://github.com/pracplayopen/core)  - TradeLink, one of the earliest open source trading system

* [Reactive trader](https://github.com/AdaptiveConsulting)  - using reactive Rx framework, includes [reactive trader](https://github.com/AdaptiveConsulting/ReactiveTrader) and [reactive trader cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud). The demo is [here](https://web-demo.adaptivecluster.com/).

* [QuantTrading](https://github.com/letianzj/QuantTrading)  - Pure C# trading system

* [StockTrading](https://github.com/houmie/StockTrading)  - c# system utilising WPF, WCF, PRISM, MVVM, Threading

* [Quanter](https://github.com/dengguoyu/quanter)  - StockTrader

* [StockSharp](https://github.com/StockSharp/StockSharp)  - C# trading system

* [SharpQuant](https://github.com/smartquant/SharpQuant.QuantStudio)  - C# trading system

* [QuantSys](https://github.com/exl3/QuantSys)  - C# trading system

* [StockTicker](https://github.com/danielmarbach/StockTicker)  - C# trading system

* [gotrade](https://github.com/cyanly/gotrade) - Electronic trading and order management system written in Golang

* [gofinance](https://github.com/aktau/gofinance) - Financial information retrieval and munging in golang

* [goib](https://github.com/gofinance/ib) - Pure Go interface to Interactive Brokers IB API 

* [Matlab Trading Toolbox](https://www.mathworks.com/products/trading.html)  - Official toolbox from Matlab; acommpanying [Introduction to Matlab Trading Toolbox](https://www.mathworks.com/matlabcentral/fileexchange/52588-automated-trading-system-development-with-matlab?focused=5253184&tab=example), and [webinar Automated Trading System Development with MATLAB](https://www.mathworks.com/videos/automated-trading-system-development-with-matlab-106851.html), and [webinar Automated Trading with MATLAB](https://www.mathworks.com/videos/automated-trading-with-matlab-81911.html), as well as [webinar A Real-Time Trading System in MATLAB](https://www.mathworks.com/videos/a-real-time-trading-system-in-matlab-92900.html), [Automated Trading with Matlab](https://www.mathworks.com/videos/automated-trading-with-matlab-81911.html), [Commodities Trading with Matlab](https://www.mathworks.com/videos/commodities-trading-with-matlab-81986.html), [Cointegration and Pairs Trading with Econometrics Toolbox](https://www.mathworks.com/videos/cointegration-and-pairs-trading-with-econometrics-toolbox-81799.html)

* [Matlab risk management Toolbox](https://www.mathworks.com/products/risk-management.htmll)  - Official toolbox from Matlab

* [Matlab Walk Forward Analysis Toolbox](http://wfatoolbox.com/)  - toolbox for walk-forward analysis

* [IB4m](https://github.com/softwarespartan/IB4m)  - matlab interface to interactive broker

* [IB-Matlab](http://undocumentedmatlab.com/ib-matlab/)  - introduction to another matlab interface to interactive broker and [demo video](http://undocumentedmatlab.com/ib-matlab/real-time-trading-system-demo)

* [openAlgo Matlab](https://github.com/mtompkins/openAlgo/tree/master/Matlab)  - openAlgo's Matlab library

* [MatTest](MatTest)  - Matlab backtest system

## Quantitative Library

* [Quantlib](http://quantlib.org) -- famous c++ library for quantitative finance; tranlated into other langugages via Swig

* [TA-Lib](https://github.com/mrjbq7/ta-lib) -- Python wrapper for TA-Lib

* [DX Analytics](http://dx-analytics.com/) -- Python-based financial analytics library

* [FinMath](http://finmath.net/) -- Java analytics library

* [OpenGamma](http://www.opengamma.com/) -- Java analytics library named STRATA

* [Quantiacs](https://github.com/Quantiacs) - [Matlab](https://github.com/Quantiacs/quantiacs-matlab) toolbox

* [pyflux](https://github.com/RJT1990/pyflux) - Open source time series library for Python

* [arch](https://github.com/bashtage/arch) -- ARCH models in Python

* [flint](https://github.com/twosigma/flint) - A Time Series Library for Apache Spark

* [Statsmodels](http://www.statsmodels.org) -- Statsmodels’s Documentation


## Quantitative Model

* [deepstock](https://github.com/keon/deepstock) -- Technical experimentations to beat the stock market using deep learning

* [qtrader](https://github.com/filangel/qtrader) -- Reinforcement Learning for Portfolio Management

* [stockPredictor](https://github.com/Nazanin1369/stockPredictor) -- Predict stock movement with Machine Learning and Deep Learning algorithms

* [stock_market_reinforcement_learning](https://github.com/kh-kim/stock_market_reinforcement_learning) -- Stock market environment using OpenGym with Deep Q-learning and Policy Gradient

* [deep-algotrading](https://github.com/LiamConnell/deep-algotrading) -- deep learning techniques from regression to LSTM using financial data

* [deep_trader](https://github.com/deependersingla/deep_trader) --  Use reinforcement learning on stock market and agent tries to learn trading. 

* [Deep-Trading](https://github.com/Rachnog/Deep-Trading) -- Algorithmic trading with deep learning experiments

* [Deep-Trading](https://github.com/ha2emnomer/Deep-Trading) -- Algorithmic Trading using RNN

* [100 Day Machine Learning](https://github.com/Avik-Jain/100-Days-Of-ML-Code) -- Machine Learning tutorial with code

* [Multidimensional-LSTM-BitCoin-Time-Series](https://github.com/jaungiers/Multidimensional-LSTM-BitCoin-Time-Series) -- Using multidimensional LSTM neural networks to create a forecast for Bitcoin price

* [QLearning_Trading](https://github.com/ucaiado/QLearning_Trading) -- Learning to trade under the reinforcement learning framework

* [Day-Trading-Application](https://github.com/jbboltz123/Day-Trading-Application) -- Use deep learning to make accurate future stock return predictions

* [bulbea](https://github.com/achillesrasquinha/bulbea) -- Deep Learning based Python Library for Stock Market Prediction and Modelling 

* [PGPortfolio](https://github.com/ZhengyaoJiang/PGPortfolio) -- source code of "A Deep Reinforcement Learning Framework for the Financial Portfolio Management Problem"

* [gym-trading](https://github.com/hackthemarket/gym-trading) -- Environment for reinforcement-learning algorithmic trading models

* [Thesis](https://github.com/pnecchi/Thesis) -- Reinforcement Learning for Automated Trading

* [DQN](https://github.com/jjakimoto/DQN) -- Reinforcement Learning for finance

* [Deep-Trading-Agent](https://github.com/samre12/deep-trading-agent) -- Deep Reinforcement Learning based Trading Agent for Bitcoin

* [deep_portfolio](https://github.com/deependersingla/deep_portfolio) -- Use Reinforcement Learning and Supervised learning to Optimize portfolio allocation.

* [Deep-Reinforcement-Learning-in-Stock-Trading](https://github.com/shenyichen105/Deep-Reinforcement-Learning-in-Stock-Trading) -- Using deep actor-critic model to learn best strategies in pair trading

* [Stock-Price-Prediction-LSTM](https://github.com/NourozR/Stock-Price-Prediction-LSTM) -- OHLC Average Prediction of Apple Inc. Using LSTM Recurrent Neural Network


## Trading API

* [Interactive Brokers](https://www.interactivebrokers.com) - popular among retail trader

* [Bloomberg API](https://www.bloomberg.com/professional/support/api-library/)  - from Bloomberg

## Data Source

* [Quandl](https://www.quandl.com/) - free and premium data sources

* [iex](https://iextrading.com/trading/market-data/) - free market data

* [one tick](https://www.onetick.com/) - hostorical tick data

* [iqfeed](http://www.iqfeed.net/) - real time data feed

* [quantquote](https://quantquote.com/) - tick and live data

* [algoseek](https://www.algoseek.com/) - historical intraday

* [EOD data](http://eoddata.com/) - historical data

* [EOD historical data](https://eodhistoricaldata.com/) - historical data

* [intrinio](https://intrinio.com/) - financial data

* [arctic](https://github.com/manahl/arctic) - High performance datastore from [Man AHL](https://www.ahl.com/) for time series and tick data 

## Cryptocurrency
* [Blockchain-stuff](https://github.com/Xel/Blockchain-stuff) - Blockchain and Crytocurrency Resources

* [cryptrader](https://cryptotrader.org/) - Node.js Bitcoin bot for MtGox/Bitstamp/BTC-E/CEX.IO; [cryptrade](https://github.com/donfanning/cryptrade) 

* [BitcoinExchangeFH](https://github.com/Aurora-Team/BitcoinExchangeFH) - Cryptocurrency exchange market data feed handler 

* [blackbird](https://github.com/butor/blackbird) -- C++ trading system that does automatic long/short arbitrage between Bitcoin exchanges

* [Peatio](https://www.peatio.tech) -- An open-source crypto currency exchange on [github](https://github.com/peatio/peatio)

* [Qt Bitcoin Trader](https://github.com/JulyIGHOR/QtBitcoinTrader) -- Qt C++ Bitcoin trading

* [ccxt](https://github.com/ccxt/ccxt) -- A JavaScript / Python / PHP cryptocurrency trading library with support for more than 90 bitcoin/altcoin exchanges

* [r2](https://github.com/bitrinjani/r2) -- Qan automatic arbitrage trading system powered by Node.js + TypeScript

* [bcoin](https://github.com/bcoin-org/bcoin) -- Javascript bitcoin library for node.js and [browsers](http://bcoin.io/)

* [XChange](https://github.com/timmolter/XChange) -- Java library providing a streamlined API for interacting with 60+ Bitcoin and Altcoin exchanges

* [Krypto-trading-bot](https://github.com/ctubio/Krypto-trading-bot) -- Self-hosted crypto trading bot (automated high frequency market making) in node.js, angular, typescript and c++

* [freqtrade](https://github.com/gcarq/freqtrade) -- Simple High Frequency Trading Bot for crypto currencies

* [Gekko](https://github.com/askmike/gekko) -- A bitcoin trading bot written in node

* [viabtc_exchange_server](https://github.com/viabtc/viabtc_exchange_server) -- A trading engine with high-speed performance and real-time notification

* [catalyst](https://github.com/enigmampc/catalyst) --  An Algorithmic Trading Library for Crypto-Assets in Python [Enigma](https://enigma.co/)

* [buttercoin](https://github.com/buttercoin/buttercoin) -- Opensource Bitcoin Exchange Software

* [zenbot](https://github.com/DeviaVir/zenbot) --  A command-line cryptocurrency trading bot using Node.js and MongoDB.

* [tribeca](https://github.com/michaelgrosner/tribeca) --  A high frequency, market making cryptocurrency trading platform in node.js

* [rbtc_arbitrage](https://github.com/hstove/rbtc_arbitrage) --  A gem for automating arbitrage between Bitcoin exchanges.

* [automated-trading](https://github.com/balupton/automated-trading) --  Automated Trading: Trading View Strategies => Bitfinex, itBit, DriveWealth

* [gocryptotrader](https://github.com/thrasher-/gocryptotrader) - A cryptocurrency trading bot and framework supporting multiple exchanges written in Golang

* [btcrobot](https://github.com/philsong/btcrobot) - Golang bitcoin trading bot

* [bitex](https://github.com/blinktrade/bitex) -  Open Source Bitcoin Exchange; and its [frint-end](https://github.com/blinktrade/frontend)

* [cryptoworks](https://cryptoworks.co/) - A cryptocurrency arbitrage opportunity calculator. Over 800 currencies and 50 markets; [cryptocurrency-arbitrage](https://github.com/manu354/cryptocurrency-arbitrage)

* [crypto-exchange](https://github.com/passabilities/crypto-exchange) - list of crypto exchanges to interact with their API's in a uniform fashion

* [bitcoin-abe](https://github.com/bitcoin-abe/bitcoin-abe) - block browser for Bitcoin and similar currencies

* [MultiPoolMiner](https://github.com/MultiPoolMiner/MultiPoolMiner) - Monitors crypto mining pools in real-time in order to find the most profitable for your machine. Controls any miner that is available via command line

## Websites Forums Blogs

* [My Quant Blogs](https://letianzj.github.io/) - Personal blog for quant trading, portfolio management, and machine learning. 

* [Top Geeky Quant Blogs](https://alphaarchitect.com/2014/10/13/top-geeky-quant-blogs/#.VECOwfldV8E) - A quant blogs check out list

* [Quantocracy](http://quantocracy.com/) - Aggregation of news on quants

* [seekingalpha](https://seekingalpha.com/) - Seeking Alpha community

* [Quantivity](https://quantivity.wordpress.com/) - quantitative and algorithmic trading

* [Wilmott](https://www.wilmott.com/) - quantitative finance community forum

* [Elitetrader](https://www.elitetrader.com/) -- trading forum

* [nuclearphynance](http://www.nuclearphynance.com/) -- quantitative finance forum

* [Investopedia](https://www.investopedia.com/) -- The Encyclopedia of investments

* [Quantpedia](https://www.quantpedia.com/) -- The Encyclopedia of Quantitative Trading Strategies

* [EpChan](http://epchan.blogspot.com/) -- Dr. Ernie Chan's blog

* [Quantinsti](https://quantra.quantinsti.com/) -- Quant Institute

* [QuantStart](https://www.quantstart.com/) -- Michael Halls-Moore's quantstart, quant trading 101; its Python backtest platform [qstrader](https://github.com/mhallsmoore/qstrader) and [qsforex](https://github.com/mhallsmoore/qsforex)

* [Algotrading 101](https://algotrading101.com/) -- Algo trading 101

* [Systematic Investor](https://systematicinvestor.wordpress.com/) -  [Michael Kapler](https://www.linkedin.com/in/michael-kapler-mmf-cfa-92a1a02/?ppe=1)'s blog, one of the best R quantitative blog; [Systematic Investor Toolkit](https://github.com/systematicinvestor/SIT)

* [R-Finance](https://github.com/R-Finance) - R-Finance repository. It has backtest [quantstrat](https://github.com/R-Finance/quantstrat), [trade blotter](https://github.com/R-Finance/blotter), famous [performance analytics](https://github.com/R-Finance/PerformanceAnalytics) package, and package [portfolio analytics](https://github.com/R-Finance/PortfolioAnalytics), [portfolio attribution](https://github.com/R-Finance/PortfolioAttribution).

* [quantmod](http://www.quantmod.com/) - R modelling and trading framework

* [r programming](http://www.r-programming.org/papers) - Guy Yollin's R backtesting

* [Seer Trading](http://www.seertrading.com) - R Backtest and live trading

* [Trading with Python](http://tradingwithpython.blogspot.com/)

* [python programming finance](https://pythonprogramming.net/finance-tutorials/) -- python finance tutorial and quantopian toturial

* [python for finance](http://www.pythonforfinance.net/) -- python finance

* [Quant Econ](https://quantecon.org/) -- open source python and julia codes for economic modeling; and lectures

* [JuliaQuant](https://github.com/JuliaQuant) -- Quantitative Finance in Julia

* [Portfolio Effect](https://www.portfolioeffect.com/) -- real time portfolio and risk management

* [www.quant365.com](http://www.quant365.com/) -- Henry Moo's blog and trading system; including Sentosa,[pysentosa binding](https://github.com/henrywoo/pysentosa), rsentosa binding and [qblog](https://github.com/henrywoo/qblog).

* [hpc quantlib](https://hpcquantlib.wordpress.com/) -- HPC + QuantLib

* [Quant Corner](https://quantcorner.wordpress.com/)

* [quantstrat trader](https://quantstrattrader.wordpress.com/) - Backtesting trading ideas with R [QuantStrat](https://github.com/R-Finance/quantstrat) package

* [Backtesting Strategies](https://timtrice.github.io/backtesting-strategies/) - Backtesting in R; codes at [Github](https://github.com/timtrice/backtesting-strategies)

* [The Quant MBA](https://thequantmba.wordpress.com/) - good quant blog

* [Foss Trading](http://blog.fosstrading.com/) - Algorithmic trading with free open source software

* [Gekko Quant](http://gekkoquant.com/) - Quantitative Trading

* [Investment Idiocy](https://qoppac.blogspot.com/) - Systematic Trading, Quantitative Finance, Investing, Financial Activism, Economic decision making by Robert Carver; [his book](https://www.amazon.com/Systematic-Trading-designing-trading-investing/dp/0857194453) and [his Python library](https://github.com/robcarver17/pysystemtrade)

* [Quantifiable Edges](http://quantifiableedges.blogspot.com/) - Assessing market action with indicators and history

* [My Simple Quant](http://mysimplequant.blogspot.com/) - Market analysis utilizing historical, back-tessted data

* [Vix and more](http://vixandmore.blogspot.com/) - discussions on Vix

* [Timely Portfolio](http://timelyportfolio.blogspot.com/) - Strategies and tests in R

* [Quantitative Research and Trading](http://jonathankinlay.com/)

* [Qusma](http://qusma.com/) - Quantitative Systematic Market Analysis

* [return and risk](http://www.returnandrisk.com/) -- Quantitative finance, analysis, and applications

* [Physics of Finance](http://physicsoffinance.blogspot.com/) -- Inspiration from physics for thinking about economics, finance and social systems

* [Quantum Financier](https://quantumfinancier.wordpress.com/) -- algorithmic trading

* [Trading the Odds](http://www.tradingtheodds.com/) -- market timing & quantitative analysis

* [CSSA](https://cssanalytics.wordpress.com/) -- new concepts in quantitative research

* [The Practical Quant](http://practicalquant.blogspot.com/)

* [Tr8dr](https://tr8dr.github.io/) - strategies, statistics, computer science, numerical techniques

* [Deniz's Note](http://denizstij.blogspot.com/) - blog of a quant Deniz Turan

* [Quant at risk](http://www.quantatrisk.com/) - quantitative analysis and risk management

* [The R Trader](http://www.thertrader.com/) - Using R in quant finance

* [rbresearch](https://rbresearch.wordpress.com/) - Using R for trading strategy ideas in FX and equity markets

* [NaN Quantivity](https://quantlife.wordpress.com/) - quant trading, statistical learning, coding and brainstorming

* [Factor Investing](https://factorinvestingtutorial.wordpress.com/) - blog on wordpress

* [Meb Faber Research](http://mebfaber.com/)

* [Big Mike Trading](https://www.youtube.com/user/BigMikeTrading/videos) - Youtube chanel in quant trading

* [Mechanical Markets](https://mechanicalmarkets.wordpress.com/)

* [Humble Student of the Markets](http://humblestudentofthemarkets.blogspot.com/)

* [Predict Stock Prices Using RNN](https://lilianweng.github.io/lil-log/2017/07/08/predict-stock-prices-using-RNN-part-1.html)


## Papers and Books
* [AQR Research and Related](https://www.aqr.com/Insights/Research/Journal-Article/)
    * [Ilmanen, Antti. Expected returns: An investor's guide to harvesting market rewards. John Wiley & Sons, 2011.](https://www.amazon.com/Expected-Returns-Investors-Harvesting-Rewards/dp/1119990726)
    * [Pedersen, Lasse Heje. Efficiently inefficient: how smart money invests and market prices are determined. Princeton University Press, 2015.](https://www.amazon.com/Efficiently-Inefficient-Invests-Market-Determined/dp/0691166196/ref=pd_bxgy_2?_encoding=UTF8&pd_rd_i=0691166196&pd_rd_r=b511d2ef-c6e3-11e8-b4bb-f94ae1ae4c7a&pd_rd_w=mGKYZ&pd_rd_wg=14dBQ&pf_rd_i=desktop-dp-sims&pf_rd_m=ATVPDKIKX0DER&pf_rd_p=3f9889ac-6c45-46e8-b515-3af650557207&pf_rd_r=RSR0147DYSQ1X09KCWKH&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=RSR0147DYSQ1X09KCWKH)

* [Ernie Chan's](http://epchan.blogspot.com/) trilogy
    * [Chan, Ernie. Quantitative trading: how to build your own algorithmic trading business. Vol. 430. John Wiley & Sons, 2009.](https://www.amazon.com/Quantitative-Trading-Build-Algorithmic-Business-ebook/dp/B001FA0GGC/ref=as_sl_pc_qf_sp_asin_til?tag=quantitativet-20&linkCode=w00&linkId=I77Y2AV4YZVRZFN7&creativeASIN=B001FA0GGC)
    * [Chan, Ernie. Algorithmic trading: winning strategies and their rationale. Vol. 625. John Wiley & Sons, 2013.](https://www.amazon.com/Algorithmic-Trading-Winning-Strategies-Rationale-ebook/dp/B00CY5HC0U/ref=sr_1_3?s=digital-text&ie=UTF8&qid=1515250115&sr=1-3)
    * [Chan, Ernest P. Machine Trading: Deploying Computer Algorithms to Conquer the Markets. John Wiley & Sons, 2017.](https://www.amazon.com/Machine-Trading-Deploying-Computer-Algorithms/dp/1119219604)
