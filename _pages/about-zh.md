---
permalink: /zh/
title: "张耀予"
author_profile: true
redirect_from:
  - /zh/experience/
---

<div class="page__language-switch" aria-label="语言切换">
  <a href="/">EN</a><span aria-hidden="true">/</span><strong>中文</strong>
</div>

## 关于我

我是一名系统架构师与优化研究者，目前在华为担任鸿蒙操作系统通信服务团队的技术负责人。我于 2024 年通过华为[天才少年计划](https://career.huawei.com/cn/young-genius)加入华为。我的工作聚焦于端云、设备间及卫星链路上的高效可靠通信系统，技术兴趣包括低带宽传输与低功耗系统协同设计。近期，我也开始关注智能体后训练与运行框架设计，希望探索如何提升智能体在系统与资源约束下的适应、协作与可靠运行能力。

我于 2024 年在[清华大学](https://www.tsinghua.edu.cn/)取得计算机科学与技术博士学位，博士期间就读于[交叉信息研究院（姚班）](https://iiis.tsinghua.edu.cn/)，主要研究大规模网络系统中的优化、控制与博弈方法。在此之前，我于 2019 年本科毕业于[清华大学电子工程系](https://www.ee.tsinghua.edu.cn/)。本科期间，我同时就读于[新雅书院](https://www.xyc.tsinghua.edu.cn/)，并在[经济管理学院](https://www.sem.tsinghua.edu.cn/)辅修经济学。

## 工作经历
{: #experience }

### 远场通信架构师

**2026 年 1 月—2026 年 7 月**

- 带领技术与交付团队，推动通信业务由近场向远场演进，负责端云传输、云侧服务与远场分享架构设计，完成 [HarmonyOS 7 华为分享·远程直传](https://consumer.huawei.com/cn/harmonyos-7/)重点特性交付。
- 围绕蜂窝、Wi-Fi、无网及卫星通信，规划天地一体、多网融合的全场景远场通信架构。
- 面向下一代无网通信和低轨卫星场景下的 VoIP 通话开展技术预研，并与清华大学电子工程系合作研究低带宽通信。
- 作为设备间通信系统级功耗优化项目的技术负责人，协同软件、硬件、芯片、通信框架与算法团队，推动端到端功耗效率取得显著提升。

### 实时通信 SE（系统工程师）

**2025 年 1 月—2025 年 12 月**

- 作为通信服务团队的技术负责人，完成 HarmonyOS 6 无网消息与通话全量特性的端到端设计、技术研究与版本交付。
  - 面向设备间通信中的无线资源冲突、链路资源受限和带宽波动，牵引芯片、操作系统、通信框架与算法团队开展协同设计。
  - 通过跨层资源决策、链路动态管理和音频算法优化，保障无网消息、多设备呼叫与实时寻呼体验。
  - 公开参考：[华为 Mate 80 系列｜Mate X7 及全场景新品发布会](https://consumer.huawei.com/cn/press/events/2025/huawei-mate-80-series-mate-x7-and-all-scenario-new-product-launch-event/) · [华为 Mate 80 野王手机无网通信 7 km 挑战](https://www.bilibili.com/video/BV1DXBYBzENw/)。

![HarmonyOS 6 畅连无网通信发布会公开画面](/images/cv/harmonyos6-no-network-launch.png)

### 系统研究员 / 独立贡献者

**2024 年 7 月—2024 年 12 月**

- 从 0 到 1 构建卫星即时通信原型，贯通应用、操作系统、内核、协议栈与 Modem，完成端到端链路验证。
- 面向极低带宽与高时延卫星链路，完成问题分析、功能规划、方案设计与原型验证。
- 开展低功耗音视频通信架构研究，负责软件、硬件与芯片协同方案的总体设计，并探索基于异构计算的流程重构与底层优化。

## 研究与论文
{: #research }

我的研究关注大规模、不确定、复杂网络中的优化、控制与博弈算法，并探索其在通信网络、计算系统、储能调度和智能电网中的应用。

### 研究方向

#### 大规模控制协调：均值场博弈与聚合博弈
{: .research-heading }

<p class="research-period">2022 年 10 月—2023 年 10 月</p>

面向参与者规模趋于无穷的均值场博弈，以及通信资源和网络带宽受限的大规模聚合博弈，研究复杂网络中多主体的控制与协调问题。相关工作涵盖 V2G 场景中的博弈均衡分析、动态规划、G-prox PDHG 算法，以及隐私保护的聚合博弈协调控制。

#### 带切换成本的在线凸优化
{: .research-heading }

<p class="research-period">2021 年 10 月—2022 年 9 月</p>

研究不确定环境中未知损失与切换成本并存的在线决策问题，针对不同范数下的损失模型提出算法，并探索其在数据中心服务器调度、CDN 与缓存调度、电网冷启动和持续学习中的应用。

#### 非凸储能调度与减排算法
{: .research-heading }

<p class="research-period">2020 年 8 月—2021 年 9 月</p>

围绕电力系统经济成本与环境成本的权衡，研究排放非凸条件下的储能调度算法，在保证收敛性的同时提升求解效率，并拓展至网络设计、流量管理和资源分配问题。

### 期刊论文

1. **Zhang, Y.**, Liu, Q., Sun, J., & Wu, C. (2023). The optimal dynamic regret for smoothed online convex optimization with squared l2 norm switching costs. *Journal of the Franklin Institute*, 360(6), 4297–4330.
2. **Zhang, Y.**, Wu, C., Gu, N., & Yu, Y. (2022). The robustness of low-carbon policies during China’s electricity reform. *Energy Economics*, 111, 106037.
3. **Zhang, Y.**, Sun, J., & Wu, C. (2021). Vehicle-to-grid coordination via mean field game. *IEEE Control Systems Letters*, 6, 2084–2089.
4. **Zhang, Y.**, & Yu, Y. (2021). Carbon Value Assessment of Hydrogen Energy Connected to the Power Grid. *IEEE Transactions on Industry Applications*, 58(2), 2803–2811.
5. Kang, Y., **Zhang, Y.**, Wu, C., Shi, J., Wang, D., & Han, Z. (2023). Efficient Management of Energy Storage at Scale: A Mean Field Game Approach. *IEEE Transactions on Network Science and Engineering*.

#### 在投工作

- **Zhang, Y.**, et al. Distributed Storage Control via Aggregative Game Coordination. Submitted to *IEEE Transactions on Smart Grid*.

### 会议论文

1. Sun, J., **Zhang, Y.**, & Wu, C. (2023). Effective Risk-limiting Carbon Emission Aware Economic Dispatch: An Algorithmic Perspective. *ACM e-Energy 2023*, 84–98.
2. **Zhang, Y.**, Kang, Y., Wu, C., Shi, J., Wang, D., & Han, Z. (2022). Carbon Emission-Aware Storage Control via Mean Field Game Coordination. *IEEE CDC 2022*, 5544–5549.
3. Liu, Q.*, & **Zhang, Y.*** (2022). Learning to Caching Under the Partial-feedback Regime. *IEEE CNSM 2022*, 154–162.
4. **Zhang, Y.***, & Liu, Q.* (2022). Optimal Dynamic Regret for Online Convex Optimization with Squared l2 Norm Switching Cost. *ACC 2022*, 2104–2109.
5. Sun, J., **Zhang, Y.**, Yu, Y., & Wu, C. (2020). Storage control for carbon emission reduction: Opportunities and challenges. *IEEE PESGM 2020*, 1–5.

\* 共同第一作者。

## 荣誉奖项
{: #honors }

- **华为终端 BG 跨领域协作技术突破奖**，2026 年 1 月
- **华为终端 BG 总裁个人奖**，2025 年 12 月（CBG 个人最高荣誉）
- **华为北京研究所优秀技术合作成果奖与北极星奖**，2025 年 12 月与 6 月
- **清华大学启航奖银奖**，2024 年 8 月（全校 Top 20）
- **清华大学—X-lab—雀巢可再生能源奖学金**，2022 年 12 月
- **清华大学交叉信息研究院科研优秀奖学金**，2022 年 9 月
- **清华之友—广药集团奖学金**，2018 年 10 月
- **清华大学公益优秀奖学金**，2017 年 10 月
- **清华大学学业优秀奖学金**，2016 年 10 月
