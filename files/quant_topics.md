# Quant Finance Topics
* Below is an overview of quant finance topics limited by my knowledge and biased by my research

# Sell Side Research
* Relatively more established as a academic field: easier to find literature, easier to add contribution

## Goals of Research
* How to model 
* Fast and accurate numerical method
  * Fast simulation
  * Pricing various derivative products
  * Calibration of model parameters to market prices
* How to price new derivative product?
  * New model to correctly capture the price from market

## Stochastic Processes
* Geometric Browniam Motion: Black-Scholes model
* Arithmetic BM: Normal (Bachelier) Model 
* Ornstein-Uhlenbeck (OU) Process: [Wiki](https://en.wikipedia.org/wiki/Ornstein%E2%80%93Uhlenbeck_process)
* Constant-Elasticity-Of-Variance (CEV) Model: [Wiki](https://en.wikipedia.org/wiki/Constant_elasticity_of_variance_model)
  * Analytic Option Pricing: Schroder, M., 1989. Computing the constant elasticity of variance option pricing formula. Journal of Finance 44, 211–219. https://doi.org/10.1111/j.1540-6261.1989.tb02414.x
  * Various Approximation: Larguinho, M., Dias, J.C., Braumann, C.A., 2013. On the computation of option prices and Greeks under the CEV model. Quantitative Finance 13, 907–917. https://doi.org/10.1080/14697688.2013.765958
* Stochastic Volatility Models: see [Wiki](https://en.wikipedia.org/wiki/Stochastic_volatility) for SDE.
  * Heston Model: Heston, S.L., 1993. **A closed-form solution for options with stochastic volatility with applications to bond and currency options.** Review of Financial Studies 6, 327–343. https://doi.org/10.1093/rfs/6.2.327
  * SABR Model: Hagan, P.S., Kumar, D., Lesniewski, A.S., Woodward, D.E., 2002. **Managing smile risk.** Wilmott Magazine 2002, 84–108.
  * 3/2 Model: Creator unclear.
  * 4/2 Model: Grasselli, M., 2017. **The 4/2 Stochastic Volatility Model: A Unified Approach for the Heston and the 3/2 Model.** Mathematical Finance 27, 1013–1034. https://doi.org/10.1111/mafi.12124
  * OU Stochastic Process: 
* Jump diffusion: 
  * Kou, S.G., 2002. A Jump-Diffusion Model for Option Pricing. Management Science 48, 1086–1101. https://doi.org/10.1287/mnsc.48.8.1086.166
* Rough Volatility (Fractional Brownina Motion, [Wiki](https://en.wikipedia.org/wiki/Fractional_Brownian_motion))
  * **Gatheral, J.**, Jaisson, T., Rosenbaum, M., 2018. **Volatility is rough.** Quantitative Finance 18, 933–949. https://doi.org/10.1080/14697688.2017.1393551
  * Bayer, C., Friz, P., **Gatheral, J.**, 2016. **Pricing under rough volatility.** Quantitative Finance 16, 887–904. https://doi.org/10.1080/14697688.2015.1099717

## Derivative Products (Payout)
* Barrier Option (Knock-in, Knock-out), Rainbow Option, Spread/Basket/Asian Option, Lookback Option, Compound Option
* Timer Option 
  * Li, C., 2016. **Bessel Processes, Stochastic Volatility, and Timer Options.** Mathematical Finance 26, 122–148. https://doi.org/10.1111/mafi.12041
  * Li, M., Mercurio, F., 2015. **Analytic Approximation of Finite‐Maturity Timer Option Prices.** Journal of Futures Markets 35, 245–273. https://doi.org/10.1002/fut.21659
  * Bernard, C., Cui, Z., 2011. **Pricing timer options.** Journal of Computational Finance 15, 69–104. https://doi.org/10.21314/JCF.2011.228
* Cliquet Option
* Parisian Option
* American/Bermudan Option
* VIX Index (Future, Options on Futures, Etc)
* Variance Swap

## Exact Monte-Carlo Simulation
* Heston Model: Broadie, M., Kaya, Ö., 2006. Exact Simulation of Stochastic Volatility and Other Affine Jump Diffusion Processes. Operations Research 54, 217–231. https://doi.org/10.1287/opre.1050.0247
* 3/2 Model: Baldeaux, J., 2012. Exact simulation of the 3/2 model. Int. J. Theor. Appl. Finan. 15, 1250032. https://doi.org/10.1142/S021902491250032X 
* SABR Model: Cai, N., Song, Y., Chen, N., 2017. Exact Simulation of the SABR Model. Operations Research 65, 931–951. https://doi.org/10.1287/opre.2017.1617 | Choi, J., Liu, C., Seo, B.K., 2019. **Hyperbolic normal stochastic volatility model.** Journal of Futures Markets 39, 186–204. https://doi.org/10.1002/fut.21967
* OU Stochastic Volatility Model: Li, C., Wu, L., 2019. **Exact simulation of the Ornstein–Uhlenbeck driven stochastic volatility model.** European Journal of Operational Research 275, 768–779. https://doi.org/10.1016/j.ejor.2018.11.057

## Mix and Match for new contribution
* Model + Product
* Model + Method
* Product + China Market Data

## Tips
* Pay attention to practitioner journals:
  * __Risk Magazine__: [Link](https://www.risk.net/risk-magazine)
  * __Journal of Computational Finance__: [Link](https://www.risk.net/journal-of-computational-finance)
  * __Wilmott Magazine__: [Link](https://wilmott.com/category/magazine/)
  * __Journal of Derivatives__: [Link](https://jod.pm-research.com/)
  * __Journal of Portfolio Management__: [Link](https://jpm.pm-research.com)
  * __Financial Analysts Journal__: [Link](https://www.cfainstitute.org/en/research/financial-analysts-journal)
* Use online resources (Q&A, forum, code, etc):
  * Quantitative Finance Stack Exchange: [Link](https://quant.stackexchange.com)
  * Wilmott Forum: [Link](https://forum.wilmott.com/). Technical Forum, Trading Forum, Numerical Methods Forum.
  * Quantopian (The Place For Learning Quant Finance): [Link](https://www.quantopian.com/)
  * Github.com

## Caultion
  * Stochastic Process
    * What is the characteritics of stochastic processes? 
    * Why are they popular? What are the strength/weakness?
  * Derivatives
    * What is the economic background of the derivative products?
    * Why certain products are popular?

# Buy Side Research
* Less established as an academic research.

## Profolio Selection/Optimization
* Min variance, Risk Parity ([Wiki](https://en.wikipedia.org/wiki/Risk_parity); Equal Risk Contribution)

## Trading Strategy
* Alpha strategy

## Caution
* Just showing good performance of strategy is NOT enough. Need add academic components.

# FinTech Topics

## Bitcoin Literature Review: [Link](https://github.com/PHBS/RM-F1/blob/master/files/bitcoin_finance_review.md)

## Crypto + Quant Finance
* Bitcoin Option Pricing: which process fits bitcoin option markets better?
  * Madan, D.B., Reyners, S., Schoutens, W., 2019. Advanced model calibration on bitcoin options. Digit Finance. https://doi.org/10.1007/s42521-019-00002-1
* VIX index in Cyprocurrency: Alexander, C., Imeraj, A., 2019. The Crypto Investor Fear Gauge and the Bitcoin Variance Risk Premium (SSRN Scholarly Paper No. ID 3383734). Social Science Research Network, Rochester, NY.

## Financial Machine Learning:

### Books and Jorunals
  * __Advances in Financial Machine Learning__: [Link](https://www.wiley.com/en-us/Advances+in+Financial+Machine+Learning-p-9781119482086) | [Github](https://github.com/ssunger/Advances-in-Financial-Machine-Learning)
  * __Digital Finance__: [Link](https://www.springer.com/finance/journal/42521)
  * __Journal of Financial Data Science__: [Link](https://jfds.pm-research.com/)
 
 
