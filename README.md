# 航运碳排放研究：进度、方法与外部交流

更新于2026-10-21，最新资料包为 **SE-EXCHANGE-20261021-R02**，覆盖R28—R30及本轮独立复核。

## 阅读入口

[当前进度与结果解释：我们如何走到R30](runs/SE-EXCHANGE-20261021-R02/PROGRESS_EXPLAINED_ZH.md)

这份说明从研究问题、数据难点、计算步骤和真实结果讲起，阅读时无需访问私有工作仓库。需要进一步核对计算定义时，阅读[方法与不确定性](runs/SE-EXCHANGE-20261021-R02/METHODS_AND_LIMITS.md)；后续选择见[研究决策与下一步](runs/SE-EXCHANGE-20261021-R02/NEXT_STEP_DISCUSSION.md)。

**当前结论**：一个局部码头过程已完成两参照描述性试算。对两个正常参照的模型子总量差分别为−10.883和+1.743吨CO₂，等权差为−4.570吨；约99.1%的等权差对应靠泊时长与默认机组负荷。完整过程点估计、全航次气旋因果效应和实测燃料精度仍未建立。建议收束该单一案例的继续扩展，保留计算模块，并重新确定能够支持航行过程研究的数据单位。

## 复核材料

- [三项比较及其条件界限](runs/SE-EXCHANGE-20261021-R02/evidence/contrasts.csv)
- [各过程活动与模型子总量](runs/SE-EXCHANGE-20261021-R02/evidence/activity_state_ledger.csv)
- [逐状态、逐机组差值](runs/SE-EXCHANGE-20261021-R02/evidence/paired_state_engine_differences.csv)
- [来源、版本和公开边界](runs/SE-EXCHANGE-20261021-R02/source_registry.json)
- [本轮独立检查范围](runs/SE-EXCHANGE-20261021-R02/INDEPENDENT_CHECKS.md)
- [截至R27的历史简报](runs/SE-EXCHANGE-20261020-R01/REVIEW_BRIEF_ZH.md)
- [滚动状态](state/CURRENT.md)

## 协作边界

本仓库保存作者授权的脱敏说明、聚合结果和方法讨论。原始AIS、船舶身份、精细轨迹、商业船舶参数、公司燃料记录、第三方全文和正式稿件继续保存在受控工作区。公开别名仅用于连接本资料包的结果表。

执行者完成计算与自检，Chat进行固定结果独立审阅，作者决定新研究、数据访问、稿件、公开范围、合并和投稿。本次更新用于进度交流，未启动外部平台任务或新一轮经验计算。历史版本目录保留原内容；本文件和state/CURRENT.md是滚动导航。
