## For What 
Understanding Recommendation System Technology And Do Some Implementation Works.

## Important Readings
- [Chapter 9 about RS in MMDS](http://infolab.stanford.edu/~ullman/mmds/ch9.pdf)
- [A repo about RS papers](https://github.com/hongleizhang/RSPapers)
- [A repo about RS system](https://github.com/grahamjenson/list_of_recommender_systems)
- [A repo about DL in RS](https://github.com/robi56/Deep-Learning-for-Recommendation-Systems)
- [Recommender Systems Handbook](http://www.cs.ubbcluj.ro/~gabis/DocDiplome/SistemeDeRecomandare/Recommender_systems_handbook.pdf)(2010)
- [Recommender Systems Handbook 2nd]()(2018)
- [RecSys 2017 summer slides: Deep Learning for Recommender Systems](http://pro.unibz.it/projects/schoolrecsys17/DeepLearning.pdf)


## Categories
- Content Based RS
    - method
        - Create vectors describing items, create vectors with the same components that describe the user's preferences.
- Collaborative Filtering Based RS
    - method
        - The process of identifying similar users and recommending what similar users like.
    - categories
        - neighborhood methods
        - latent factor models
            - Matrix Factorization Based RS
- others
    - Deep Learning Based RS
    - Tree Based RS
    - Stream Based RS
    - Sequence-aware Recommendations

## Features
- information filtering system


## Some Technology Problems
- Cold Start Problem
    - 增加额外信息，比如隐含信息(浏览/点击/购买)；增加兴趣时间动态信息，比如将用户隐向量看作是时间的函数等
- RS Explaination Problem
- The Long Tail Problem
- Scalability
- Accuracy


## Important Systems
- [LightFM](https://github.com/lyst/lightfm) (Python)
- [LibFM](https://github.com/srendle/libfm) (C++)
- [LibRec](https://github.com/guoguibing/librec) (Java)
- [RankSys](https://github.com/RankSys/RankSys) (Java)

## Conferences 
- [RecSys](httpps://recsys.acm.org/)


## Data and Competitions
- [NETFLIX PRIZE COMPETITION, 2006~2009](https://www.netflixprize.com/index.html)
- [Movie Lens]()
