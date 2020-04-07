

### Paper Follows
- ﻿BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer.
    - 2019 CIKM. **BERT4Rec**
    - [official code](https://github.com/FeiSun/BERT4Rec)
    - 随机mask, 训练时将最后一个也mask掉, 预测时预测下一个;
    - 没有预训练，直接从最开始训练；
    - 体现双向能力
    
    
- ﻿Self-Attentive Sequential Recommendation.
    - 2018 ICDM. **SASRec**;
    - [official code](https://github.com/kang205/SASRec)
    - 单向Self-Attentin应用;
    
    
    
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

