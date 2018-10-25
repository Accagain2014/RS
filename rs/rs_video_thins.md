
----
- 短视频和长视频推荐的区别？
    - 视频内容上
    - 播放时长比例上

- 视频和文本推荐的不同

- 怎么确定目标
    - 播放完成度？
    


涉及两个思路，一个是离线推荐思路，一个是在线推荐思路；涉及两个方向，一个是算法方向，一个是系统方向。

### 离线推荐思路

### 在线推荐思路
- Real-time Neighborhood-based CF
    - neighborhood-based CF
        - user-based CF
        - item-based CF
    - model-based CF
        - MF
        
### LSTM用于视频推荐缺点
> We have tried LSTM to model user historical behavior data in the sequential manner. But it shows no improvement. Different
from text which is under the constraint of grammar in NLP task,
the sequence of user historical behaviors may contain multiple
concurrent interests. Rapid jumping and sudden ending over these
interests causes the sequence data of user behaviors to seem to be
noisy. A possible direction is to design special structures to model
such data in a sequence way. We leave it for future research. (DIN 2018 KDD Gai Kun)

