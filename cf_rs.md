## CF 优缺点
- 优点
    - 领域无关，不需要很多profile/精细的数据
    - 准确度比基于内容的要高些
    - A major appeal of collaborative filtering is that it is domain free, yet it can address data aspects that are often elusive and difficult to profile using content filtering. While generally more accurate than content-based techniques.(MATRIX FACTORIZATION TECHNIQUES FOR RECOMMENDER SYSTEMS. 2009)
- 缺点
    - 头部效应. Collaborative filtering approach finds similar users and movies by usage data, which leads to popular items that will be easier to be recommended than unpopular items.
    - 冷启动. It is difficult for collaborative filtering to recommend any new movies to users since there are no many usage data associated with these movies.

## 分类
- neighborhood methods
    
- latent factor models
    - MF
    