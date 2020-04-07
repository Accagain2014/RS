## people


## papers

> [**LS-PLM (Large Scale Piece-wise Linear Model)**]()
<br> [Learning Piece-wise Linear Models from Large Scale Data for Ad Click Prediction](../materials/readings/ctr/Learning%20Piece-wise%20Linear%20Models%20from%20Large%20Scale%20Data%20for%20Ad%20Click%20Prediction.pdf)
<br> 2017. Alibaba. Kun Gai.
<br> 将分治思想用于LR, 两组参数，一组是分，一组是权重，相乘，从而拟合非线性情况；
<br> 优化方法和分布式实现上创新

----
> [**FTRL (Foloww)**]
<br> [Ad Click Prediction: a View from the Trenches](../materials/readings/ctr/2013%20KDD%20Ad%20Click%20Prediction-%20a%20View%20from%20the%20Trenches.pdf)
<br> 2013 KDD. Google.
<br> 更改SGD优化方式，在保证精度的情况下，保证稀疏。一个样本只有某些权重有用
<br> [code](https://www.kaggle.com/darraghdog/ftrl-revisited-22)

----
> [**GDBT / XGBOOST+LR**]
<br> [Practical Lessons from Predicting Clicks on Ads at Facebook](http://quinonero.net/Publications/predicting-clicks-facebook.pdf)
<br> ADKDD 2014.

----
>
<br> Model Ensemble for Click Prediction in Bing Search Ads. 2017.

----
> [**DIN (Deep Interest Network)**]
<br> [Deep Interest Network for Click-Through Rate Prediction](https://arxiv.org/pdf/1706.06978.pdf)
<br> 2018 KDD. Alibaba. Kun Gai.
<br> [code](https://github.com/zhougr1993/DeepInterestNetwork)(code抽象得还不错！)
<br> 三点贡献： 1. 提出了一种候选广告和行为数据动态联系的方式，对同一个用户来说，不同广告，该用户的行为embedding是不是固定一样的，而是动态变化的;
<br> 2. 提出了一种mini-batch aware regularizer的方法，训练速度增加了。
<br> 3. 基于PReLU，提出了一种data adaptive activation function的方法。
<br> 整体工作，比较solid，且开源了代码，比较全面和丰富

