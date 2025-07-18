# Scrollytelling with Quarto: Close read Prize

[Scrollytelling](https://posit.co/blog/closeread-prize-announcement/) stories let you explain complicated concepts to readers as they scroll down the page. You could build up a complicated plot layer-by-layer, zoom in on a famous map, highlight a key quote from an interviewee, or even animate your web graphics.

You can visit my scrollytelling website here: [Financial Risk Analysis using the OGARCH model](https://erica-prog.github.io/)

# Abstract 

This article attempts a concise financial risk analysis of top semiconductor industry stocks, leveraging unique models such as the multivariate orthogonal GARCH (OGARCH) model, Value-at-Risk (VaR) and volatility metrics, powered by Yahoo finance data. The article also explores critical factors influencing investment decisions, emphasizing the importance of accounting for unseen volatility events. This article provides readers with an understanding of how these fluctuations impact stock performance and understand that volatility is essential for making informed investment choices in this sector.

# Full Description 

The following stocks are examined in a stock portfolio: Qualcomm (QCOM), Broadcom Inc. (AVGO), Micron Technology, Inc. (MU), Texas Instruments Incorporated (TXN), Advanced Micro Devices, Inc. (AMD), and NVIDIA Corporation (NVDA). The historical daily returns are log-transformed for each stock and analyzed to identify periods of varying volatility sizes during the sampled period (January 1, 2014, to December 31, 2023). The returns are proven to be stationary using Augmented Dickey-Fuller test (ADF test). The multivariate orthogonal GARCH (O-GARCH) model is applied using principal component factors to identify key drivers affecting these components and compute a conditional variance matrix for each period. 

**2025 Update: Furthermore, I examine EWMA, ARIMA, and DCC Volatility Models using the principal component factor model**  

Additionally, a 1% value-at-risk model (VaR) model is calculated to examine the long position of $1 million on the stock portfolio for the next trading day. The reliability of the VaR model is further assessed using a backtesting framework to validate its effectiveness in forecasting risks.

# Preview of Scrollytelling 

![preview of my scrollytellying page](https://github.com/erica-prog/erica-prog.github.io/blob/main/image/preview_scrollytelling.gif)

