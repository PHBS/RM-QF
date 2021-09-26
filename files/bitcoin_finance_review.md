# Quick literature review on bitcoin research (finance/econ perspective)

* Along with the interest in bitcoin/cryptocurrencies/blockchain, __finance and economics__ publications in the field are rapidly growing
* So far the publications mainly appear in [Economics Letters](https://www.sciencedirect.com/journal/economics-letters) and [Financial Research Letters](https://www.journals.elsevier.com/finance-research-letters), which accepts trendy topics in short letter-style articles (<4~5 pages). Recently major finance journals also start accepting Bitcoin-related articles
* Main research question theme is 
  * `Do established theories in finance hold in Bitcoin or not?`
  * `How does Bitcoin compared to other asset classes?`
  * `Market microstructure? (Irrational) investor behavior? etc`

## Bitcoin price efficiency
* Background: 
  * According to efficient market hypothesis (EMH), one should not be able to predict the price based on the past prices since the market price in the news.
  * Research question: __`Is Bitcoin/Cryptocurrency price efficient?`__
  * Price inefficiency is often referred to as __long-term memory__.
* Urquhart, A., 2016. __The inefficiency of Bitcoin.__ [Economics Letters 148, 80–82.](https://doi.org/10.1016/j.econlet.2016.09.019)
  > ... evidence reveals that returns are __significantly inefficient__ over our full sample (~2016), but when we split our sample into two subsample periods, we find that some tests indicate that Bitcoin is __efficient in the latter period__. 
* Nadarajah, S., Chu, J., 2017. __On the inefficiency of Bitcoin.__ [Economics Letters 150, 6–9.](https://doi.org/10.1016/j.econlet.2016.10.033)
* Bariviera, A.F., 2017. __The inefficiency of Bitcoin revisited: A dynamic approach.__ [Economics Letters 161, 1–4.](https://doi.org/10.1016/j.econlet.2017.09.013)
* Tiwari, A.K., Jana, R.K., Das, D., Roubaud, D., 2018. __Informational efficiency of Bitcoin—An extension.__ [Economics Letters 163, 106–109.](https://doi.org/10.1016/j.econlet.2017.12.006)
* Jiang, Y., Nie, H., Ruan, W., 2018. __Time-varying long-term memory in Bitcoin market.__ [Finance Research Letters 25, 280–284.](https://doi.org/10.1016/j.frl.2017.12.009)
* Wei, W.C., 2018. __Liquidity and market efficiency in cryptocurrencies.__ [Economics Letters 168, 21–24.](https://doi.org/10.1016/j.econlet.2018.04.003)
* Vidal-Tomás, D., Ibañez, A., 2018. __Semi-strong efficiency of Bitcoin.__ [Finance Research Letters 27, 259–265.](https://doi.org/10.1016/j.frl.2018.03.013)
* Sensoy, A., 2019. __The inefficiency of Bitcoin revisited: A high-frequency analysis with alternative currencies.__ [Finance Research Letters 28, 68–73.](https://doi.org/10.1016/j.frl.2018.04.002)
  > • Pricing efficiency has been improving in the last few years at the intraday level.  
  > • BTCUSD is slightly more efficient that BTCEUR  
  > • Higher the return frequency, lower the informational efficiency is.  

## Bitcoin as an investment option
* Research question: 
  * __`Can Bitcoin diversify portfolio?`__
* Chan, W.H., Le, M., Wu, Y.W., 2019. Holding Bitcoin longer: __The dynamic hedging abilities of Bitcoin.__ [The Quarterly Review of Economics and Finance 71, 107–113.](https://doi.org/10.1016/j.qref.2018.07.004)
  > Bitcoin is an effective strong hedge against the Euro STOXX, Nikkei, Shanghai A-Share, S&P 500, and the TSX Index under monthly data frequency.
* Bouri et al, 2017. __On the hedge and safe haven properties of Bitcoin: Is it really more than a diversifier?__ [Finance Research Letters 20, 192–198.](https://doi.org/10.1016/j.frl.2016.09.025)
  > • Bitcoin is a suitable diversifier.  
  > • Bitcoin has hedge and safe haven properties against __Asia Pacific stocks__.
* Dyhrberg, A.H., 2016. __Hedging capabilities of bitcoin. Is it the virtual gold?__ [Finance Research Letters 16, 139–144.](https://doi.org/10.1016/j.frl.2015.10.025)
  > ... bitcoin can clearly be used as a hedge against stocks in the Financial Times Stock Exchange Index. Additionally bitcoin can be used as a hedge against the American dollar in the short-term. Bitcoin thereby possess some of the same hedging abilities as __gold__ ...
* __[MA Thesis]__ Shon, D. (2019). Cryptocurrency and CAPM with Bitcoin price based [Mathesis]. Peking University HSBC Business School.

## Influence between Bitcoin and Cryptocurrencies
* Koutmos, D., 2018. __Return and volatility spillovers among cryptocurrencies__. [Economics Letters 173, 122–127.](https://doi.org/10.1016/j.econlet.2018.10.004)
  > • Bitcoin is the dominant contributor of return and volatility spillovers.  
  > • The findings suggest that interdependencies among cryptocurrencies has risen.
* __Tu, Z., Xue, C.__, 2018. __Effect of bifurcation on the interaction between Bitcoin and Litecoin.__ [Finance Research Letters.](https://doi.org/10.1016/j.frl.2018.12.010)
  > • Shocks transmit from Bitcoin to Litecoin before Bitcoin's bifurcation. (Bifurcation = Hardfork)  
  > • Bitcoin bifurcation reverses the direction of shock transmission.
* Katsiampa, P., Corbet, S., Lucey, B., 2019. __Volatility spillover effects in leading cryptocurrencies: A BEKK-MGARCH analysis.__ [Finance Research Letters 29, 68–74.](https://doi.org/10.1016/j.frl.2019.03.009)
  > • We find evidence of bi-directional shock transmission effects between Bitcoin and both Ether and Litecoin.
 
## Price discovery
* Background:
  * __Price discovery__ is the process of determining the price of an asset in the marketplace through the interactions of buyers and sellers. 
  * Research question: `If a financial asset is traded in more than one market (e.g., different exchanges, spot vs futures), which market contribute to the price discovery (i.e. has more __information share__)?`
* Brandvold et al, O.C., 2015. __Price discovery on Bitcoin exchanges.__ [Journal of International Financial Markets, Institutions and Money 36, 18–35.](https://doi.org/10.1016/j.intfin.2015.02.010): Price discovery among different spot exchanges
  > The market leaders with the highest information share are Mt.Gox and BTC-e.
* Brauneis, A., Mestel, R., 2018. __Price discovery of cryptocurrencies: Bitcoin and beyond.__ [Economics Letters 165, 58–61.](https://doi.org/10.1016/j.econlet.2018.02.001): Price discovery across different cryptocurrencies 
  > • Bitcon is the most efficient (the least predictable) cryptocurrency.  
  > • We find that efficiency is positively related to liquidity.

## Bitcoin futures market
* Background: 
  * In traditional asset classes, futures markets lead price discovery (higher __information share__). Low trading cost / leverage --> higher trading volume --> participation of informed traders
  * CBOE/CME started list futures contract on Bitcoin from Dec 2017, giving investors means to short Bitcoin.
  * On 2019.3.15, CBOE stopped offering (new) Bitcoin futures. [Reuters](https://uk.reuters.com/article/us-cboe-bitcoin/cboe-puts-the-brakes-on-bitcoin-futures-idUKKCN1QW261)
* Hale et al, 2018. __How Futures Trading Changed Bitcoin Prices__ [(FRBSF Economic Letter No. 2018–12). Federal Reserve Bank of San Francisco.](https://www.frbsf.org/economic-research/publications/economic-letter/2018/may/how-futures-trading-changed-bitcoin-prices/)
  > The rapid run-up and subsequent fall in the (Bitcoin) price after the introduction of futures (in Dec 2017) does not appear to be a coincidence. Rather, it is consistent with trading behavior that typically accompanies the introduction of futures markets for an asset.
* Corbet et al, 2018. __Bitcoin Futures -- What use are they?__ [Economics Letters 172, 23–27.](https://doi.org/10.1016/j.econlet.2018.07.031)
  > Bitcoin futures are not an effective hedging tool.  
  > • Price discovery is driven by uninformed investors in the spot market.  
  > • Bitcoin futures did not affect the nature of Bitcoin as a speculative asset rather than a currency.
* Baur, D.G., Dimpfl, T., 2019. __Price discovery in bitcoin spot or futures?__ [Journal of Futures Markets 39, 803–817.](https://doi.org/10.1002/fut.22004)
  >  ... find that the spot price leads the futures price. We attribute this result to the higher trading volume and the longer trading hours of the globally distributed bitcoin spot market
* Kapar, B., Olmo, J., 2019. __An analysis of price discovery between Bitcoin futures and spot markets.__ [Economics Letters 174, 62–64.](https://doi.org/10.1016/j.econlet.2018.10.031)
  > Bitcoin futures market dominates the price discovery process.
* Alexander, C., Choi, J., Park, H., Sohn, S., 2019. __[BitMEX](https://www.bitmex.com/) Bitcoin Derivatives: Price Discovery, Informational Efficiency and Hedging Effectiveness.__ Journal of Futures Markets (forthcoming), [SSRN ID 3353583](http://ssrn.com/abstract=3353583)
  > • BitMEX dominates Bitcoin/USD futures trades.  
  > • Bitcoin futures on BitMEX play a dominant role in price discovery.  
  > • The discussion of whether to treat Bitcoin as a mainstream investment asset or not is heated. On this issue, the US Securities and Exchange Commission adopted a conservative position by rejecting several applications for Bitcoin exchange traded funds (ETF), citing concerns about the lack of transparency and potential market manipulation in Bitcoin exchanges. We argue that given the substantial role and influence of Bitcoin futures, regulators should investigate the legitimacy of both Bitcoin futures and spot markets.

## Price manipulation
* Gandal et al, 2018. __Price manipulation in the Bitcoin ecosystem.__ [Journal of Monetary Economics 95, 86–96.](https://doi.org/10.1016/j.jmoneco.2017.12.004)
* Li, T., Shin, D., Wang, B., 2018. __Cryptocurrency Pump-and-Dump Schemes__ [SSRN ID 3267041](http://ssrn.com/abstract=3267041)
* Feng, W., Wang, Y., Zhang, Z., 2018. __Informed trading in the Bitcoin market.__ [Finance Research Letters 26, 63–70.](https://doi.org/10.1016/j.frl.2017.11.009)
* Background on Bitfinex and Tether (USDT) issue:
  * USDT is a cryptocurrency backed by USD collateral. 
  * There is a suspicion that, in 2017, USDT was issued more than the collateral and was used to pump up the Bitcoin price. (Tether and Bitfinex are linked)
  * U.S. regulators are scrutinizing one of the world’s largest cryptocurrency exchanges as questions mount over a digital token linked to its backers. [Bloomberg News](https://www.bloomberg.com/news/articles/2018-01-30/crypto-exchange-bitfinex-tether-said-to-get-subpoenaed-by-cftc)
* Griffin, J.M., Shams, A., 2018. __Is Bitcoin Really Un-Tethered?__ [SSRN ID 3195066](http://ssrn.com/abstract=3195066)
  > ... consistent with the supply-based hypothesis where Tether is used to provide price support and manipulate cryptocurrency prices.
* Wei, W.C., 2018. __The impact of Tether grants on Bitcoin.__ [Economics Letters 171, 19–22.](https://doi.org/10.1016/j.econlet.2018.07.001)
  > • Tether grants did not Granger-cause Bitcoin returns.  
  > • It is unlikely that Tether manipulation caused the 2017 Bitcoin rally.

## Other price anomalies
* Aharon, D.Y., Qadan, M., 2018. __Bitcoin and the day-of-the-week effect.__ [Finance Research Letters. (Forthcoming)](https://doi.org/10.1016/j.frl.2018.12.004)
  > There is evidence of the day-of-the-week effect on Bitcoin at both the mean and the variance levels. Specifically, Mondays are generally associated with higher returns and volatility. Our results reveal that Bitcoin shares common features with classic financial assets such as stocks, bonds and currencies.

## Bitcoin and investor attention
* It has been a popular topic of PHBS MA thesis: Google/Baidu trend index
* Urquhart, A., 2018. What causes the attention of Bitcoin? [Economics Letters 166, 40–44.](https://doi.org/10.1016/j.econlet.2018.02.017)
  > Google trend index... realized volatility and volume significantly influence next day’s attention. ... (but) attention offers no significant predictive power for realized volatility or returns. Therefore the attention of Bitcoin is significantly influenced by the previous day’s high realized volatility and volume.  
* Shen, D., Urquhart, A., Wang, P., 2019. __Does twitter predict Bitcoin?__ [Economics Letters 174, 118–122.](https://doi.org/10.1016/j.econlet.2018.11.007)
  > We find that the number of tweets is a significant driver of next day trading volume and realized volatility ...

## Bitcoin papers in top finance journals
* Transaction fee (as block reward goes to zero)
  * Easley, D., [O’Hara, M.](https://en.wikipedia.org/wiki/Maureen_O%27Hara_(financial_economist)), M., & Basu, S. (2019). **From mining to markets: The evolution of bitcoin transaction fees.** Journal of Financial Economics, 134(1), 91–109. https://doi.org/10.1016/j.jfineco.2019.03.004
* Bitcoin Valuation
  * Schilling, L., & Uhlig, H. (2019). **Some simple bitcoin economics.** Journal of Monetary Economics, 106, 16–26. https://doi.org/10.1016/j.jmoneco.2019.07.002

* Market Arbitrage
  * Makarov, I., & Schoar, A. (2020). **Trading and arbitrage in cryptocurrency markets.** Journal of Financial Economics, 135(2), 293–319. https://doi.org/10.1016/j.jfineco.2019.07.001

