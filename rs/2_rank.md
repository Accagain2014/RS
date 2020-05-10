

### Paper Follows & Code Reading
- **[BERT4Rec]** BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer.
    - 2019 CIKM. 
    - [official code](https://github.com/FeiSun/BERT4Rec)
    - 双向Self-Attention应用;
    - 随机mask, 训练时将最后一个也mask掉, 预测时预测下一个;
    - 没有预训练，直接从最开始训练;
    
        
- **[SASRec]** Self-Attentive Sequential Recommendation.
    - 2018 ICDM.
    - [official code](https://github.com/kang205/SASRec)
    - 单向Self-Attentin应用;
    
  
- **[MIMN]** Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction
    - 2019 KDD. 
    - [official code](https://github.com/UIC-Paper/MIMN)
        - 用户兴趣网络更新和商品预测分开；
        - 多通道记忆网络 + 记忆权重归一化;
        
**MIND**

        
- **[Wide & Deep]** Wide & Deep Learning for Recommender Systems
    - 2016. 
    - [用NumPy手工打造 Wide & Deep](https://zhuanlan.zhihu.com/p/53110408) [stasi009/NumpyWDL](https://github.com/stasi009/NumpyWDL)
    - [models/official/r1/wide_deep](https://github.com/tensorflow/models/tree/master/official/r1/wide_deep)
    - 

- **[FTRL]** Ad Click Prediction: a View from the Trenches
    - a
 
DeepFM
    - [ChenglongChen/tensorflow-DeepFM](https://github.com/ChenglongChen/tensorflow-DeepFM)
    - [TensorFlow Estimator of Deep CTR --DeepFM/NFM/AFM/FNN/PNN](https://zhuanlan.zhihu.com/p/33699909)
    
    
Google Deep & Cross Network
    - 允许显式指定交叉阶次
    
    
    
    
### 序列模型
- Markov Chains (MCs)
    - pros
        - MC-based methods perform best in extremely sparse datasets
        - Characterize short-range item transitions for recommendation
    - cons
        - Fail to capture the intricate dynamics of more complex scenarios
    - methods
        - **FPMC**, Fuses an MF term and an item-item transition term to capture long-term preferences and short-term transitions respectively
        
- CNN Based
    - Caser
        - Convolutional Sequence Embedding (**Caser**), a CNN-based method, views the embedding matrix of L previous items as an ‘image’ and applies convolutional operations to extract transitions

- Recurrent Neural Networks (RNNs)
    - pros
        - RNNs perform better in denser datasets
    - methods
        - **GRU4Rec**
- Transformer

- [chenghu17/Sequential_Recommendation](https://github.com/chenghu17/Sequential_Recommendation.git)



### Methods
- MF
- MC
- FMC(Factorized Markov Chains)
- FPMC(Factorized Personalized Markov Chains)
- FISM(Factorized Item Similarity Models)
- TransRec(Translation-based Recommendation)
- GRU4Rec
- AutoRec
- AFM(Attentional Factorization Machines)

