## 相关资料
- [repo: Ad-papers](https://github.com/wzhe06/Ad-papers)
- [repo: rtb-papers](https://github.com/wnzhang/rtb-papers)
- [书籍: 计算广告](https://book.douban.com/subject/26596778/) (2015.9)
- [ppt: 计算广告](./readings/第13次课件-计算广告.pdf) (by xujun)

## 组成部分
- 广告主(advertisers)
    - 出资方/广告内容提供者/希望通过媒体展示广告内容，从而影响受众
    - 关心的问题： 投资回报率和广告量
- 媒体(publishers)
    - 广告位提供者/受众通过访问媒体接受广告信息
    - 关心的问题： 每次广告展示/搜索的效益
- 受众(users)
    - 访问媒体网站获取信息，同时接触广告/可能会对广告采取进一步行动(如点击/购买等)
    - 关心的问题： 相关性
- 广告网络(match maker)
    - 根据广告主/媒体/受众进行广告投放，平衡各方利益；收取广告费用；
    - 关心的问题：收益和市场规模

## 广告分类
- 搜索广告(sponsored search)
    - match maker = publishers
- 上下文广告(contextual ads)
    - match maker /= publishers

## 核心问题
- Find the "best match" between a given user in a given context and a suitable advertisement.
- Context
    - 互联网搜索引擎: 搜索广告
    - 媒体网页(publisher page): 上下文广告/展示广告
    - 其他context: 手机/视频/社交网络等
- 核心挑战
    - 如何达到各方利益最大化("best match")
    - 如何构造大规模平台支持上述功能
- 具体问题
    - 广告检索
    - 广告排序
    - 点击后计费 - 拍卖
    - 点击率(CTR)预估
    - 转化率(CVR)预估
    - 程序化交易和实时竞价(real time bidding, RTB)
    

## 指标
- ROI(Return On Investment)投资回报率
- 计费方式
    - CPM 千次展示计费
    - CPC 按用户点击计费
    - CPA 按转化行为结算
    - CPT 按时间结算
    

## 关键术语
- 落地页(landing page)： 全称广告落地页, 是用户通过一个广告图点击进来的页面, 是广告主想呈现给用户的广告信息。（通过呈现一个特定页面，为他们指出一条明确的路径继续加深与你网站的关系）
- 原生广告： 指的是一种广告理念, 总的来说是指将广告融入到内容中。
- ADX(Ad Exchange): 广告交易平台
- DSP(Demand-side platform): 与广告主打交道的部分称为需求方平台
- SSP(Supplier-side platform): 与供给方(媒体)打交道的部分称为服务方平台
- DMP(Data Management Platform): 是把分散的数据进行整合纳入统一的技术平台

## 总结
- 变现, 引擎. (计算广告是研究互联网变现的技术，是互联网产业繁荣发展的引擎.)
   
