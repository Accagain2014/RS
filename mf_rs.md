## papers
- [MATRIX FACTORIZATION TECHNIQUES FOR RECOMMENDER SYSTEMS](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)
    - 2009, IEEE
    - won 2009 Netflix Prize Competetion, $ 1 million.
    - [code](https://github.com/cheungdaven/DeepRec/blob/master/models/rating_prediction/mf.py)
    - 非常简单，经典的MF文章
    - 创新点：分解方式，用户/商品隐含行为属性信息集成，动态兴趣反映(时间的函数：user latent matrix, bias)，置信度处理
    
## 分类
- SVD
    - 问题
        - 当打分矩阵不全时，问题很大，学习不出来隐含意义
        -  Conventional SVD is undefined when knowledge about the matrix is incomplete. Moreover, carelessly addressing only the relatively few known entries is highly prone to overfitting.  
        