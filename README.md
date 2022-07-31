# G-Research Crypto Forecasting

In this competition, I will use my machine learning expertise to forecast short term returns in 14 popular cryptocurrencies.The given dataset contains millions of rows of high-frequency market data dating back to 2018.

The simultaneous activity of thousands of traders ensures that most signals will be transitory, persistent alpha will be exceptionally difficult to find, and the danger of overfitting will be considerable. In addition, since 2018, interest in the cryptomarket has exploded, so the volatility and correlation structure in data are likely to be highly non-stationary. The successful contestant will pay careful attention to these considerations, and in the process gain valuable insight into the art and science of financial forecasting.

## Description

•	Based on the real transaction data of 14 cryptocurrencies (highest price, lowest price, opening price, closing price, trading volume, etc.), extract features such as the increase and volume ratio of the last N days; and construct a large-cap index including 14 currencies , and calculate the increase, volume ratio and other characteristics.

•	On the basis of the above features, build machine learning LightGBM and CatBoost models, use RMSE as the loss function, and use sklearn, lightgbm and other modules to build models for training, so as to achieve the effect of predicting the target when given transaction data.

•	The results of the LightGBM and CatBoost models are equally weighted to achieve the top4% ranking.

## Getting Started

### Dependencies

* Kaggle Notebook

## Authors
Siquan Wang

sw3442@cumc.columbia.edu

## Version History

* 0.3
    * Further tuning
* 0.2
    * Various bug fixes and optimizations
* 0.1
    * Initial Release 

## License

N/A

## Acknowledgments

Inspiration, code snippets, etc.
* [competition website]([https://github.com/matiassingers/awesome-readme](https://www.kaggle.com/competitions/g-research-crypto-forecasting))
