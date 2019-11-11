# ml-research
A repository Senior Honors Theis: machine learning based investment strategies (work in progress)

In this paper we consider the practical challenge of measuring empirical asset risk premia. The goal of asset pricing is to better understand and explain the return variations of equities using economic factors observed from empirical data. However, cross-sectional expected stock returns are difficult to capture due to market efficiency and unforecastable news events. Traditionally, factor models can be constructed by building linear regressions on asset returns with observed factors which can be used for constructing factor portfolios. However, linear models are known to suffer from overfitting when the number of predictor variables are large, and the set of restrictive statistical assumptions are likely to be broken by empirical data. Luckily, recent progress in machine learning community presents great promise for this challenge. Machine Learning techniques are widely used today for many different areas such as operations research, image recognition, and finance. In the setting of empirical asset pricing, machine learning offers greater flexibility: larger feature set, and fewer model assumptions. Specifically, gradient boosting as a machine learning model has gained widespread popularity in recent years. It is a state-of-the-art regression and classification algorithm that is robust to overfitting by building an ensemble of weak learners. In this paper we present a novel asset pricing methodology using Categorical Boosting (CatBoost), an implementation of gradient boosted decision trees (GBDTs). We propose a learning-to-rank framework for predicting outperforming assets in the US equity market using 99 firm characteristics. The Equity Long/Short portfolio selected by Categorical Boosting achieved a Sharpe Ratio of x, outperforming the benchmark S&P 500 portfolio by y.

References:

Gu, Shihao and Kelly, Bryan T. and Xiu, Dacheng, Empirical Asset Pricing via Machine Learning (September 13, 2019). Chicago Booth Research Paper No. 18-04; 31st Australasian Finance and Banking Conference 2018; Yale ICF Working Paper No. 2018-09. Available at SSRN

Kelly, Bryan T. and Pruitt, Seth and Su, Yinan, Characteristics Are Covariances: A Unified Model of Risk and Return (October 15, 2018). Available at SSRN

Green, Jeremiah, John RM Hand, and X Frank Zhang, 2017, The characteristics that provide independent
information about average us monthly stock returns, The Review of Financial Studies

Gu, Shihao, Bryan T Kelly, and Dacheng Xiu, 2019, Autoencoder asset pricing models, Available at
SSRN

Han, Yufeng and He, Ai and Rapach, David and Zhou, Guofu, Firm Characteristics and Expected Stock Returns (August 6, 2019). Available at SSRN

Moritz, Benjamin and Zimmermann, Tom, Tree-Based Conditional Portfolio Sorts: The Relation between Past and Future Stock Returns (March 1, 2016). Available at SSRN

