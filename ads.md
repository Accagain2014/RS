## 相关资料
- [repo: Ad-papers](https://github.com/wzhe06/Ad-papers)
- [repo: rtb-papers](https://github.com/wnzhang/rtb-papers)
- [书籍: 计算广告](https://book.douban.com/subject/26596778/) (2015.9)
- [ppt: 计算广告](./readings/第13次课件-计算广告.pdf) (by xujun.)
- [course: Introduction to Computational Advertising. MS&E 239.](https://web.stanford.edu/class/msande239/) (by Stanford 2011.)

## 市场背景/产品逻辑

## 关键总结
- 以广告作为核心的后向变现体系
- 变现, 引擎. (计算广告是研究互联网变现的技术，是互联网产业繁荣发展的引擎.)
- 不在于算法和技术本身，而在于广告的商业逻辑和产品目标。
- 商业逻辑驱动的在线广告产品和技术的升级。
- 计算广告这个领域的复杂性在于,对于任何一项产品或技术都需要放在相应的商业背景下去判断其合理性；而想要了解商业产品上能达到的目标，还需要对技术的现状和难点有相当的认识。
- 以人群为投放目标，以产品为导向的技术型投放模式。
- 在商业逻辑的框架下思考和探索计算广告技术对理解产品/框架/算法非常关键。

## 产品
- Google AdWords (竞价广告业务)



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
- 广告网络(match maker)(ad Network, ADN)
    - 根据广告主/媒体/受众进行广告投放，平衡各方利益；收取广告费用；
    - 关心的问题：收益和市场规模
    - 批量地运营媒体的广告位资源, 按照人群或上下文标签售卖给需求方，并用竞价的方式决定流量分配。

## 重要概念
- 交易终端(Trading Desk, TD)
- 实时竞价(Real Time Bidding, RTB)
- ADX(Ad Exchange): 广告交易平台
- 商业产品概念
    - DSP(Demand-side platform): 与广告主打交道的部分称为需求方平台
    - SSP(Supplier-side platform): 与供给方(媒体)打交道的部分称为服务方平台
    - DMP(Data Management Platform): 是把分散的数据进行整合纳入统一的技术平台
    - 整合营销(integrated marketing): 即通过多种渠道的有机配合来达到整体投放效果的最优。
- 技术
    - 预测模型
    - 机器学习
    - 人群定向


## 广告分类
- 长期
    - 提升品牌/产品形象（eg: 电视广告）
- 短期
    - 提升转化率/销售量（eg: 互联网广告）
- 搜索广告(sponsored search)
    - match maker = publishers
- 上下文广告(contextual ads)
    - match maker /= publishers
- 展示广告(display advertising): 在互联网上展示广告创意的产品形式
- 定向广告(targeted advertising)
    - 受众广告(audience targeting), 即通过技术手段标定某个用户的性别/年龄/其他标签
    - 广告投放(ad serving), 即将广告投送由直接嵌入页面变成实时响应前端请求，并根据用户标签自动决策和返回合适的广告创意

## 广告售卖模式
- 合约广告(agreement-based advertising): 即采用合同约定的方式确定某一广告位在某一时间段为某特定广告主所独占，并且根据双方的要求，确定广告创意和投放策略.
- 竞价广告(auction-based advertising)： 供给方只向广告主保证质即单位流量的成本, 但不再以合约的方式给出量的保证. 也就是对每一次展示都基本按照收益最高的原则来决策.

## 定价机制
- 广义第二高阶(Generalized Second Price, GSP)


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
    - 受众定向

## 指标
- ROI(Return On Investment)投入产出比
- 计费方式
    - CPM 千次展示计费
    - CPC 按用户点击计费
    - CPA 按转化行为结算
    - CPT 按时间结算
    - RPM 千次展示收益(Revenue per Mille)
    

## 关键术语
- 落地页(landing page)： 全称广告落地页, 是用户通过一个广告图点击进来的页面, 是广告主想呈现给用户的广告信息。（通过呈现一个特定页面，为他们指出一条明确的路径继续加深与你网站的关系）
- 原生广告： 指的是一种广告理念, 总的来说是指将广告融入到内容中。

- 边际成本： 指厂商每增加一单位产量所增加的成本。
- 防天窗： 广告一般要有底层的备选广告素材，以防没有合适的广告匹配时页面上开天窗。


