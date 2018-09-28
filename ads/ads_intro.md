## 相关资料
- [repo: Ad-papers](https://github.com/wzhe06/Ad-papers)
- [repo: rtb-papers](https://github.com/wnzhang/rtb-papers)
- [书籍: 计算广告](https://book.douban.com/subject/26596778/) (2015.9)
- [CIKM Tutorial 2016: Learning, Prediction and Optimisation in RTB Display Advertising](../readings/surveys/cikm-2016-rtb-full.pdf)(by zhang weinan.)
- [ppt: 计算广告](../readings/第13次课件-计算广告.pdf) (by xujun.)
- [course: Introduction to Computational Advertising. MS&E 239.](https://web.stanford.edu/class/msande239/) (by Stanford 2011.)
- [a kaggle competetion: Click-Through Rate Prediction](https://www.kaggle.com/c/avazu-ctr-prediction)
- [a kaggle competetion: Display Advertising Challenge](https://www.kaggle.com/c/criteo-display-ad-challenge)
- [a useful csdn: 计算广告干货整理](https://blog.csdn.net/a819825294/article/details/53540245) (2016.12)
- [a useful jianshu: 计算广告资料汇总](https://www.jianshu.com/p/8c591feb9fc4)
- [报告：中国网络广告市场年度监测报告。艾瑞咨询。2018.](../readings/stats/2018年中国网络广告市场年度监测报告-简版.pdf)
- [知乎专栏：从最近的比赛学习CTR/CVR](https://zhuanlan.zhihu.com/p/35046241)


## 市场背景/产品逻辑

## 关注人物
- [王喆](https://github.com/wzhe06/Ad-papers)
- [张伟楠](http://wnzhang.net/)
- 

## 关键总结
- 以广告作为核心的后向变现体系
- 变现, 引擎. (计算广告是研究互联网变现的技术，是互联网产业繁荣发展的引擎.)
- 不在于算法和技术本身，而在于广告的商业逻辑和产品目标。
- 商业逻辑驱动的在线广告产品和技术的升级。
- 计算广告这个领域的复杂性在于,对于任何一项产品或技术都需要放在相应的商业背景下去判断其合理性；而想要了解商业产品上能达到的目标，还需要对技术的现状和难点有相当的认识。
- 以人群为投放目标，以产品为导向的技术型投放模式。
- 在商业逻辑的框架下思考和探索计算广告技术对理解产品/框架/算法非常关键。
- 竞价交易模式的本质是将量的约束从交易过程中去除，仅仅采用"价高者得"的简单决策方案来投放每一次广告。
- 从市场规模来看，搜索广告占整个在线广告市场的一半以上
- 搜索广告：是以上下文查询词为粒度进行受众定向，并按照竞价方式售卖和CPC结算的广告产品。
- 

## 产品
- 搜索竞价广告
    - Google AdWords (竞价广告业务)
    - Yahoo! Advertising
    - 淘宝直通车
- 展示竞价广告
    - Google AdSense
    - Google Display Network(GDN)
    - 淘宝客 (阿里妈妈) 放弃 淘宝联盟
- 广告交易平台
    - RightMedia(美国最大的网络广告交易平台之一， 雅虎收购，2015年下线)
    - DoubleClick Adx(将Google Adwords和Google AdSence融合)
- DSP产品
    - Criteo(法国广告技术公司)
    - InviteMedia(被google收购 -> DoubleClick Bid Manager)
    - 聚效(mediaV DSP)
- SSP产品(和ADX功能有较大重叠)
    - Admeld(2011被google以4亿美金收购，整合在DoubleClick for Publishers(DFP)广告管理系统)
    - Rubicon
- 数据管理和交易平台 DMP产品
    - BlueKai
    - AudienceScience(广告市场上首先明确提出受众定向这一概念的公司)
- 原生广告相关产品
    - 前进四路：内容即广告
    - 信息流广告
        - 起源于社交网络(Twitter, -> Facebook/微博/QQ空间)
        - 非社交类媒体，Yahoo!首页、今日头条等 （信息流中的各条内容相关性并不强）
    - 搜索广告
    - 软文广告
    - 联盟
    - InMobi（印度，广告技术公司）
    - OutBrain(以色列，网络推荐引擎服务，从投放广告创意变成了投放付费内容)
- 实时竞价
    - 品友互动 iPinYou
    - 悠易 YOYI

## 技术
- 需求端
    - 功能
        - 按照广告主预算跨媒体一站式采买人群的功能
        - 机器决策的ROI优化功能
    - 问题
        - 如何挑选合适的目标人群
        - 如何对各个目标人群给出合适的出价
    - 产品
        - 搜索引擎营销
            - 关键词选择和出价
        - 媒介购买平台（交易平台, Trading Desk: TD）
    

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
    - 广告网络的产品功能是批量聚合各媒体的剩余流量，按照人群或上下文标签的流量切割方式售卖给广告主。
    - 分类
        - 水平广告网络
        - 垂直广告网络

## 重要概念
- 交易终端(Trading Desk, TD)
- 实时竞价(Real Time Bidding, RTB)
- ADX(Ad Exchange): 广告交易平台
    - 是程序化交易时代的关键产品，负责将媒体流量以拍卖的方式售卖给DSP, 可以类比于证券市场中的交易所
    
- 商业产品概念
    - DSP(Demand-side platform): 与广告主打交道的部分称为需求方平台
    - SSP(Supplier-side platform): 与供给方(媒体)打交道的部分称为服务方平台
    - DMP(Data Management Platform): 是把分散的数据进行整合纳入统一的技术平台
    - 整合营销(integrated marketing): 即通过多种渠道的有机配合来达到整体投放效果的最优。
- 技术
    - 预测模型
    - 机器学习
    - 人群定向
- 广告产品形态
    - 面向需求方的接口
    - 面向供给方的接口
    - 中间的投放系统及匹配策略
    
## 实时竞价
- 为什么需要
    - 在加工人群标签的过程中需要利用到广告主的数据，这样的标签叫定制化用户标签。
    - 广告网络中，人群的定义方式都是广告平台决定，需求方基本没有加工的自由。然后，在实时竞价交易中，服务于品牌广告主的DSP可以根据市场上采买的各种数据为某个特定的广告主特有的人群，完成更加符合其市场策略的人群触及。
    - 实时竞价的交易方式给了广告主最大的流量选择空间
    - 实时是指需求方实时地，也就是每次展示时参与广告竞价
- 程序化交易
    - 在实时竞价产生后，广告交易越来越多地依赖机器间在线的协商而非事先约定或人工操作完成，这样的交易方式称为程序化交易
- 广告交易平台ADX
    - 询价优化
    - CPM结算方式(需求方可以准确预估点击率，并给出合理出价)
    - 托管 -> 私有交易 -> 公开交易
- 产品
    - DoubleClick Adx
- 与推荐关系
    - 由于可以细分到每次展示的粒度来决策和出价，这使得需求方可以向一个推荐系统那样精细化进行广告活动，也使得推荐和广告这两项重要的互联网技术找到了完美的契合点。

## 原生广告
- 原生概念
    - 表现原生：将广告的展示风格和样式变得与内容相一致，从而做到产品形式上的"原生";（社交网络信息流）
    - 意图原生：将广告的投放决策逻辑与内容生产相一致，从而做到用户意图上的"原生";
    - 搜索广告在两方面都是原生的
- 植入式原生广告
    
    

## 互联网广告的技术特点
- 技术和计算方向
    - 数字媒体的特点使在线广告可以进行精细的受众定向，而技术又使得广告决策和交易朝着计算驱动的方向发展。
- 效果的可衡量性
    - 

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
    - eCPM(expected cost per mille) 估计的千次展示收益
    - CPM(cost per mille, in Latin mille means thousand) 千次展示成本
    - RPM(Revenue per Mille) 千次展示收入
    - CPC(cost per click) 按用户点击计费
    - CPA(cost per action) 按转化行为结算
    - CPS(cost per sale)
    

## 关键术语
- 落地页(landing page)： 全称广告落地页, 是用户通过一个广告图点击进来的页面, 是广告主想呈现给用户的广告信息。（通过呈现一个特定页面，为他们指出一条明确的路径继续加深与你网站的关系）
- 原生广告： 指的是一种广告理念, 总的来说是指将广告融入到内容中。
- 边际成本： 指厂商每增加一单位产量所增加的成本。
- 防天窗： 广告一般要有底层的备选广告素材，以防没有合适的广告匹配时页面上开天窗。
- 标的物：指当事人双方权利义务指向的对象。


- GD(Guaranteed Delivery): 担保式投送
- 标的物：指当事人双方权利义务指向的对象。
- SEM(Search Engine Marketing) 搜索引擎营销：搜索广告的媒体采买和ROI优化的服务
- MRP(Market Reserve Price) 市场保留价/起价/底价: 为了控制广告的质量和保持一定的出售单价，竞价广告市场设置的一个赢得拍卖位置的最低价格
- CDN(Content Delivery Network), 内容分发网络



## 问题
- 竞价的模式对广告主是不是更麻烦了？没有了量的约束？
- response prediction 指的是什么？
- Design algorithms to make the best match between the advertisers and Internet users with economic constraints.
