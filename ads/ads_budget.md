## 资料
- [Facebook广告系统背后的Pacing算法](https://36kr.com/p/5043625.html)
- [预算使用速率调整和排期](https://developers.facebook.com/docs/marketing-api/pacing)

## budget control
- 预算控制
- 广告系统中Pacing，预算控制，以及怎么把预算控制与其他模块相结合的问题
- Pacing是Facebook广告系统中调节花费预算节奏的一个算法，一个类比就是竞跑的运动员：过早冲刺意味着在终点前就没劲了，但过晚冲刺也许你就没完成这次比赛。
- Pacing保证对所有的广告主在竞争前提下自动分配不同的广告预算。Pacing就是优化的核心组件让广告主获得最大的投资回报率（ROI)。
- Pacing就是通过学习同一受众目标内的广告竞争环境来决定最优化出价。是一种DSP内的算法。
- Pacing算法对广告主提供最大的价值


## 基本想法
- 广告主会提供预算/目标/最高竞价，系统会根据这些学习出最有出价。
