# MasterCapstone
This repo contains the python script and [report](https://github.com/OscarTheFE/MasterCapstone/blob/main/Capstone_Project__Market_Regime.pdf) of my master capstone paper. 
## Background: 
The term market regime refers to the collective behavior of traders, which is usually a
cluster of persistent market conditions. Market regimes are vital to researchers due to their relation to the
global economy and asset valuation. Forecasting market trends can be extremely useful for portfolio managers,
especially when facing financial downturns or catastrophic black swan events. While statistical modeling is still
the primary method used in building market-regime switching models, to make regime-switching prediction
more interpretable, we considered an approach based on 9 machine learning methods.
## Method: 
The principal component analysis is a proven useful technique in dimensional reduction and
feature selection. The selection is made based on a set of 40 technical, fundamental and macroeconomic features.
K-Means is used as the baseline model due to its simplicity. Other machine learning techniques used
include classification,tree-based model, and hidden Markov model(HMM). K-means clustering and HMM are
the only unsupervised learning algorithms used. The Hidden Markov model is a popular technique for detecting
the underlying sequence of persistent states, which is a great fit for the market regime identification challenge.
Other supervised models, such as Support-vector machines (SVM), gradient boosted decision trees (GBDT),
and Random forest (RF), are robust supervised learning algorithms used in this research.
## Conclusion:
This analysis shows why Machine Learning techniques are extremely powerful tools in market regime
detection. First, Machine Learning techniques are capable of providing evidence of significant relationships
between public economic features and persistent market regimes. This paper explored 9 different models and
discovered the best model for market regime detection are Hidden Markov Model and Linear Discriminant
Analysis. Tree-based models such as Gradient Boosting Decision Tree are the second-best model. Second,
the time frame analysis allows people to grasp additional information about when a market regime switch is
going to occur. Market regime-switching is more likely to happen and easier to detect on a monthly basis.
Lastly, feature selection can help improve the efficiency of modeling without the sacrifice of market regime
classification accuracy. With only 20 features machine learning models can generate precise market regime
classification.
