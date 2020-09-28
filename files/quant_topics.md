# Quant Finance Topics
* Below is an overview of quant finance topics limited by my knowledge and biased by my research

## General Tips
* Pick practical topic. Beneficial to your job or future career?
* Pay attention to practitioner journals:
  * __Risk Magazine__: [Link](https://www.risk.net/risk-magazine)
  * __Journal of Computational Finance__: [Link](https://www.risk.net/journal-of-computational-finance)
  * __Wilmott Magazine__: [Link](https://wilmott.com/category/magazine/)
  * __Journal of Derivatives__: [Link](https://jod.pm-research.com/)
  * __Journal of Portfolio Management__: [Link](https://jpm.pm-research.com)
  * __Financial Analysts Journal__: [Link](https://www.cfainstitute.org/en/research/financial-analysts-journal)
  * __Journal of Financial Data Science__: [Link](https://jfds.pm-research.com/)
  * __Digital Finance__: [Link](https://www.springer.com/finance/journal/42521)
* Use online resources (Q&A, forum, code, etc):
  * Quantitative Finance Stack Exchange: [Link](https://quant.stackexchange.com)
  * Wilmott Forum: [Link](https://forum.wilmott.com/). Technical Forum, Trading Forum, Numerical Methods Forum.
  * Quantopian (The Place For Learning Quant Finance): [Link](https://www.quantopian.com/)
  * Wikipedia / Baidu / Google
  * Github.com
  
# Sell Side Research
* Relatively more established as a academic field: easier to find literature, easier to add contribution
* For sell vs buy side, read 
  * Meucci, A., 2011. **“P” Versus “Q”: Differences and Commonalities between the Two Areas of Quantitative Finance.** SSRN Electronic Journal. https://papers.ssrn.com/abstract=1717163

## Goals of Research
* How to model financial time series / stochastic process?
  * New process to better fit real data?
  * Mathematically tractable model?
* Fast and accurate numerical method
  * Efficient pricing of various derivative products
  * Fast simulation for Monte-Carlo method (Variance reduction?)
  * Calibration of model parameters to market prices
* How to price new derivative product?
  * Method (analytic or MC) available?
* New model to correctly capture the price from market or real time series?

## Stochastic Processes
* Geometric Browniam Motion: Black-Scholes model
* Arithmetic BM: Normal (Bachelier) Model 
* Ornstein-Uhlenbeck (OU) Process: [Wiki](https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process)
* Constant-Elasticity-Of-Variance (CEV) Model: [Wiki](https://en.wikipedia.org/wiki/Constant_elasticity_of_variance_model)
  * Analytic Option Pricing: Schroder, M., 1989. **Computing the constant elasticity of variance option pricing formula.** Journal of Finance 44, 211–219. https://doi.org/10.1111/j.1540-6261.1989.tb02414.x
  * Various Approximation: Larguinho, M., Dias, J.C., Braumann, C.A., 2013. **On the computation of option prices and Greeks under the CEV model.** Quantitative Finance 13, 907–917. https://doi.org/10.1080/14697688.2013.765958
* Stochastic Volatility Models: see [Wiki](https://en.wikipedia.org/wiki/Stochastic_volatility) for SDE.
  * Heston Model: Heston, S.L., 1993. **A closed-form solution for options with stochastic volatility with applications to bond and currency options.** Review of Financial Studies 6, 327–343. https://doi.org/10.1093/rfs/6.2.327
  * SABR Model: Hagan, P.S., Kumar, D., Lesniewski, A.S., Woodward, D.E., 2002. **Managing smile risk.** Wilmott Magazine 2002, 84–108.
  * 3/2 Model: Creator unclear.
  * 4/2 Model: Grasselli, M., 2017. **The 4/2 Stochastic Volatility Model: A Unified Approach for the Heston and the 3/2 Model.** Mathematical Finance 27, 1013–1034. https://doi.org/10.1111/mafi.12124
  * OU Stochastic Process: 
* Jump diffusion: 
  * Kou, S.G., 2002. A Jump-Diffusion Model for Option Pricing. Management Science 48, 1086–1101. https://doi.org/10.1287/mnsc.48.8.1086.166
* Rough Volatility (Fractional Brownian Motion, [Wiki](https://en.wikipedia.org/wiki/Fractional_Brownian_motion))
  * **Gatheral, J.**, Jaisson, T., Rosenbaum, M., 2018. **Volatility is rough.** Quantitative Finance 18, 933–949. https://doi.org/10.1080/14697688.2017.1393551
  * Bayer, C., Friz, P., **Gatheral, J.**, 2016. **Pricing under rough volatility.** Quantitative Finance 16, 887–904. https://doi.org/10.1080/14697688.2015.1099717
  * Glasserman, P., He, P., 2018. Buy Rough, Sell Smooth. SSRN Journal. https://doi.org/10.2139/ssrn.3301669  (Connected to trading strategy)

## Derivative Products (Payout)
* Spread/Basket/Asian Option
  * Krekel, M., de Kock, J., Korn, R., Man, T.-K., 2004. **An analysis of pricing methods for basket options.** Wilmott Magazine 2004, 82–89. 
  * Choi, J., 2018. **Sum of all Black-Scholes-Merton models: An efficient pricing method for spread, basket, and Asian options.** Journal of Futures Markets 38, 627–644. https://doi.org/10.1002/fut.21909
  * Fu, L., 2019. **Pricing Basket Options with Equivalent Bachelier Model** (MA thesis). **Peking University HSBC Business School**, Shenzhen, China.
* Timer Option 
  * Li, C., 2016. **Bessel Processes, Stochastic Volatility, and Timer Options.** Mathematical Finance 26, 122–148. https://doi.org/10.1111/mafi.12041
  * Li, M., Mercurio, F., 2015. **Analytic Approximation of Finite‐Maturity Timer Option Prices.** Journal of Futures Markets 35, 245–273. https://doi.org/10.1002/fut.21659
  * Bernard, C., Cui, Z., 2011. **Pricing timer options.** Journal of Computational Finance 15, 69–104. https://doi.org/10.21314/JCF.2011.228
* Barrier Option (Knock-in, Knock-out), Rainbow Option, Lookback Option, Compound Option, Etc
* Cliquet Option
* Parisian Option
* American/Bermudan Option
* VIX Index (Future, Options on Futures, Etc)
* Variance Swap

## Monte-Carlo Simulation
* Heston Model: 
  * Andersen, L., 2008. **Simple and efficient simulation of the Heston stochastic volatility model.** The Journal of Computational Finance 11, 1–42. https://doi.org/10.21314/JCF.2008.189
  * Broadie, M., Kaya, Ö., 2006. **Exact Simulation of Stochastic Volatility and Other Affine Jump Diffusion Processes.** Operations Research 54, 217–231. https://doi.org/10.1287/opre.1050.0247
* 3/2 Model: Baldeaux, J., 2012. **Exact simulation of the 3/2 model.** Int. J. Theor. Appl. Finan. 15, 1250032. https://doi.org/10.1142/S021902491250032X 
* SABR Model: Cai, N., Song, Y., Chen, N., 2017. **Exact Simulation of the SABR Model.** Operations Research 65, 931–951. https://doi.org/10.1287/opre.2017.1617 | Choi, J., Liu, C., Seo, B.K., 2019. **Hyperbolic normal stochastic volatility model.** Journal of Futures Markets 39, 186–204. https://doi.org/10.1002/fut.21967
* OU Stochastic Volatility Model: Li, C., Wu, L., 2019. **Exact simulation of the Ornstein–Uhlenbeck driven stochastic volatility model.** European Journal of Operational Research 275, 768–779. https://doi.org/10.1016/j.ejor.2018.11.057

## Mix and Match for new contribution (The combinations are unlimited !)
* Model + Product
* Model + Method
* Model + Trading Strategy
* XXX + China Market Data

## Caution
  * Stochastic Process
    * What is the characteristics of stochastic processes? 
    * Why are they popular? What are the strength/weakness?
  * Derivatives
    * What is the economic background of the derivative products?
    * Why certain products are popular?

# Buy Side Research
* Asset management, Portfolio allocation, Trading strategy.
* Sometimes the outcome is not published as academic research.

## Portfolio Selection/Optimization
* Minimum variance portfolio 
* Smart Beta (factor investing)
* Risk parity portfolio ([Wiki](https://en.wikipedia.org/wiki/Risk_parity); Equal Risk Contribution): very popular in asset management industry.
  * Maillard, S., Roncalli, T., Teïletche, J., 2010. **The Properties of Equally Weighted Risk Contribution Portfolios.** The Journal of Portfolio Management 36, 60–70. https://doi.org/10.3905/jpm.2010.36.4.060
  * Chaves, D., Hsu, J., Li, F., Shakernia, O., 2012. **Efficient Algorithms for Computing Risk Parity Portfolio Weights.** The Journal of Investing 21, 150–163. https://doi.org/10.3905/joi.2012.21.3.150
  * Prado, M.L. de, 2016. **Building Diversified Portfolios that Outperform Out of Sample.** The Journal of Portfolio Management 42, 59–69. https://doi.org/10.3905/jpm.2016.42.4.059

## Trading Strategy
* `Alpha` signal:
  * Kakushadze, Z., Serur, J.A., 2018. **151 Trading Strategies.** SSRN Electronic Journal. https://papers.ssrn.com/abstract=3247865
* Can machine learning predict outperforming strategy given economic situation?
* Consider uncommon asset class (e.g., not equity): commodity, interest rates, FX, etc.

## Caution
* Just showing good performance of strategy is NOT enough. 
* Either need add academic connection or show effort.

# FinTech Topics

## Bitcoin Literature Review: [Link](https://github.com/PHBS/RM-F1/blob/master/files/bitcoin_finance_review.md)

## Crypto + Quant Finance
* Bitcoin Option Pricing: which process fits bitcoin option markets better?
  * Madan, D.B., Reyners, S., Schoutens, W., 2019. **Advanced model calibration on bitcoin options.** Digital Finance. https://doi.org/10.1007/s42521-019-00002-1
* VIX index in Cyprocurrency: Alexander, C., & Imeraj, A. (2019). **The Crypto Investor Fear Gauge and the Bitcoin Variance Risk Premium.** SSRN Electronic Journal. https://papers.ssrn.com/abstract=3456853

## Financial Machine Learning:
* Current focus is in asset pricing (return prediction)
* You may often need massive data + computation power. Check availability before! 
* Often there are room for simple but good idea. Consider Replacing linear regression with ML methods?
* Software tool is readily available (sklearn, keras/tensorflow, pytorch, etc)
* Extra new information with Natural Language Processing (NLP). 
* ML method may help you future career!

### Books and Journals
  * López de Prado, M.M., 2018. **Advances in financial machine learning.** Wiley, New Jersey.: [Link](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086) | [Github](https://github.com/ssunger/Advances-in-Financial-Machine-Learning)
  * Hull, J.C., 2019. **Machine Learning in Business: An Introduction to the World of Data Science.** [Link](https://www.amazon.com/Machine-Learning-Business-Introduction-Science/dp/1079988254)
  * Journals: [__Digital Finance__](https://www.springer.com/finance/journal/42521) and [__Journal of Financial Data Science__](https://jfds.pm-research.com/)

### Papers
* Gu, S., Kelly, B., & Xiu, D. (2020). **Empirical Asset Pricing via Machine Learning.** The Review of Financial Studies, 33(5), 2223–2273. https://doi.org/10.1093/rfs/hhaa009 [[SSRN](https://doi.org/10.2139/ssrn.3159577)]
* Moritz, B., Zimmermann, T., 2016. **Tree-Based Conditional Portfolio Sorts: The Relation between Past and Future Stock Returns.** SSRN Journal. https://doi.org/10.2139/ssrn.2740751
* Giglio, S., Liao, Y., Xiu, D., 2018. **Thousands of Alpha Tests.** SSRN Journal. https://doi.org/10.2139/ssrn.3259268
* Chen, L., Pelger, M., Zhu, J., 2019. **Deep Learning in Asset Pricing.** SSRN Journal. https://doi.org/10.2139/ssrn.3350138
* Woo, J., Liu, C., Choi, J., 2018. **Leave-One-Out Least Square Monte Carlo Algorithm for Pricing American Options.** [arXiv:1810.02071](http://arxiv.org/abs/1810.02071) [q-fin, stat]. (Early version in **PHBS MA thesis**)
* Li, K., Mai, F., Shen, R., Yan, X., 2019. **Measuring Corporate Culture Using Machine Learning.** SSRN Electronic Journal. https://doi.org/10.2139/ssrn.3256608
* Lopez de Prado, M., 2019. **Ten Applications of Financial Machine Learning. SSRN Electronic Journal.** https://ssrn.com/abstract=3365271

### MA Thesis Example
* Long, Shuyi (2019). **Smart Beta Investing: A New Method Based on Machine Learning and Black-Litterman Model** [Mathesis]. Peking University HSBC Business School.
  * Used the probability outcome of ML as in input of the Black-Litterman (asset management) model 
* Ge, Desheng (2020). **How can the yield curve predict an economic recession?** [Mathesis]. Peking University HSBC Business School.
  * The negative US Treasury yield spread (e.g., 10y - 3m) is considered as the best recession indicator. This paper verify that the yield curve spread (long - short) is indeed the best recession indicator. But the pair and coefficients can be slightly different.