# Fire Smoke and Hemoglobin in US Hemodialysis Facilities
# 美国血液透析机构的火灾烟雾暴露与血红蛋白

[English](#english) · [中文](#中文)

## English

### Paper

**Annual fire smoke exposure and low hemoglobin in 7,297 United States hemodialysis facilities**

Yitao Zheng¹†, Xi Qin²†, Xin Yin³†, Zetong Wu¹, Zhaocheng Ma¹*

¹ School of Public Health, Wuhan University, Wuhan, China  
² School of Computer Science, Wuhan University, Wuhan, China  
³ Department of Biomedical Engineering, Hubei Province Key Laboratory of Allergy and Immune Related Disease, TaiKang Medical School (School of Basic Medical Sciences), Wuhan University, Wuhan, China

† Equal contribution.  
*Correspondence: Zhaocheng Ma — [mzhaocheng@whu.edu.cn](mailto:mzhaocheng@whu.edu.cn)*

### Overview

Anemia requires continuing monitoring and treatment in maintenance hemodialysis. We examined whether smokier years were associated with a greater recorded low-hemoglobin burden at US dialysis facilities, and assessed how future smoke exposure could affect the geographic footprint of today's dialysis services.

The study links public clinical reports with environmental data, evaluates the information available in annual facility-level surveillance, and maps midcentury smoke scenarios onto the existing dialysis network.

### Study design

| Component | Description |
| --- | --- |
| Design | Retrospective ecological panel study |
| Coverage | 7,297 facilities in 1,825 counties across 48 US states |
| Observation years | 2016–2019 and 2021–2022 |
| Analysis size | 39,393 facility-years; 27.2 million eligible adult hemodialysis patient-months |
| Primary exposure | Annual county-level fire-smoke PM₂.₅ concentration |
| Primary outcome | Percentage of eligible patient-months with recorded hemoglobin below 10 g/dL |
| Primary model | Patient-month-weighted regression with facility and state-by-year effects, adjusted for non-smoke PM₂.₅, annual mean temperature, and hot-day count |

Clinical outcomes came from CMS Dialysis Facility Reports. Historical facility locations were linked to county smoke and weather estimates. The source-defined fire-smoke measure includes smoke identified through plume observations, which can encompass wildfire, prescribed burning, and agricultural burning. The year 2020 was excluded because the clinical source omitted its first six months.

### Main findings

- **Annual clinical association:** Each 1 µg/m³ higher annual smoke PM₂.₅ was associated with a **0.03-percentage-point** difference in recorded low-hemoglobin burden (county-clustered nominal 95% interval: **−0.13 to 0.18**). The annual background burden was approximately **21–24%**. Supporting hemoglobin and recording outcomes also showed estimates close to zero.
- **Surveillance and uncertainty:** California contributed **68.4%** of the adjusted smoke variation used for estimation. Sensitivity analyses and 12,000 simulated outcome datasets examined how exposure concentration and spatial and temporal dependence affected inference. Interval coverage varied with the assumed error process.
- **Retrospective prediction:** A validation-selected modeling workflow including smoke reduced weighted prediction error relative to carrying forward the previous observation by **9.0% in 2021**, **8.0% in 2022**, and **6.8% when entire states were held out**. Paired comparisons within model families found little consistent additional predictive information from smoke itself.
- **Midcentury exposure:** Across 28 climate models, projected smoke concentrations at the existing dialysis network reached **2.4–3.0 times** the scenario source's historical baseline by **2046–2055**. The scenario analysis matched **6,600 facilities**, covering **95.3%** of 2022 patient-month weight.

| Emissions scenario | Median 2046–2055 smoke PM₂.₅ | Multiple of historical network baseline | Median share of matched patient-month weight in counties exceeding twice their own historical smoke exposure |
| --- | ---: | ---: | ---: |
| SSP1–2.6 | 1.020 µg/m³ | 2.4× | 56.7% |
| SSP2–4.5 | 1.167 µg/m³ | 2.7× | 69.3% |
| SSP3–7.0 | 1.305 µg/m³ | 3.0× | 77.8% |

The scenario-source historical period is 2011–2020, with a network baseline of 0.434 µg/m³. These summaries hold the observed 2022 facility distribution and patient-month weights fixed and describe future exposure at those locations.

### Interpretation

The study's contribution is twofold: it characterizes the information and uncertainty in annual aggregate surveillance of smoke and low hemoglobin, and quantifies the dialysis service footprint facing substantially higher smoke exposure under published climate scenarios. Short-term clinical responses and treatment changes require more detailed longitudinal patient records. Exploratory reanalysis of two public airway-cell wood-smoke experiments provides biological context, with responses varying by experimental system and exposure pattern.

### About this repository

This repository contains a bilingual introduction based on the version 10 manuscript and Supporting Information. Its sole content file is this README; the manuscript, analysis code, and datasets are maintained separately.

## 中文

### 论文

**美国7,297家血液透析机构的年度火灾烟雾暴露与低血红蛋白负担**

作者：Yitao Zheng¹†、Xi Qin²†、Xin Yin³†、Zetong Wu¹、Zhaocheng Ma¹*

¹ 武汉大学公共卫生学院  
² 武汉大学计算机学院  
³ 武汉大学泰康医学院（基础医学院）生物医学工程系、过敏及免疫相关疾病湖北省重点实验室

† 共同第一作者。  
*通信作者：Zhaocheng Ma — [mzhaocheng@whu.edu.cn](mailto:mzhaocheng@whu.edu.cn)*

### 研究概述

贫血是维持性血液透析中需要持续监测和治疗的问题。我们研究美国透析机构在烟雾更重的年份，记录到的低血红蛋白负担是否更高，并评估未来烟雾暴露变化对现有透析服务分布的影响。

本研究将公开临床报告与环境数据连接，评估年度机构监测能够提供的信息，并将本世纪中叶的烟雾情景映射到现有透析网络。

### 研究设计

| 项目 | 内容 |
| --- | --- |
| 研究类型 | 回顾性生态面板研究 |
| 覆盖范围 | 美国48个州、1,825个县的7,297家机构 |
| 观察年份 | 2016—2019年及2021—2022年 |
| 分析规模 | 39,393个机构年；2,720万个合格成年血液透析患者月 |
| 主要暴露 | 县级年度火灾烟雾PM₂.₅浓度 |
| 主要结局 | 合格患者月中记录为血红蛋白低于10 g/dL的比例 |
| 主要模型 | 按患者月加权，纳入机构固定效应、州与年份交互效应，并调整非烟雾PM₂.₅、年均温及高温天数 |

临床结局来自美国医疗保险和医疗补助服务中心（CMS）的透析机构报告，机构历史位置与县级烟雾及气象估计相匹配。来源定义的火灾烟雾指标依据烟羽观测识别，可涵盖野火、计划烧除及农业焚烧。由于临床来源缺少2020年上半年的数据，研究排除了整个2020年。

### 主要发现

- **年度临床关联：** 年度烟雾PM₂.₅每升高1 µg/m³，记录到的低血红蛋白负担相差 **0.03个百分点**（县级聚类名义95%区间：**−0.13至0.18**）。各年背景负担约为 **21%—24%**，其他血红蛋白及测量记录结局的估计也接近零。
- **监测信息与不确定性：** 加州贡献了用于估计的调整后烟雾变异的 **68.4%**。研究通过敏感性分析及12,000组模拟结局，考察暴露信息集中、空间与时间相关性对推断的影响；区间覆盖率随误差过程假设变化。
- **回顾性预测：** 包含烟雾、由验证集选择的完整建模流程，相比延用前次观测值，将加权预测误差在2021年降低 **9.0%**、2022年降低 **8.0%**，整州留出评估中降低 **6.8%**。同一模型家族内的配对比较显示，烟雾本身提供的额外预测信息较少，且方向不一致。
- **本世纪中叶暴露：** 28个气候模型给出的情景显示，到 **2046—2055年**，现有透析网络的烟雾浓度达到同一情景来源历史基线的 **2.4—3.0倍**。情景分析匹配到 **6,600家机构**，覆盖2022年患者月权重的 **95.3%**。

| 排放情景 | 2046—2055年烟雾PM₂.₅浓度中位数 | 相对历史网络基线的倍数 | 位于烟雾超过本县历史水平两倍地区的匹配患者月权重比例中位数 |
| --- | ---: | ---: | ---: |
| SSP1–2.6 | 1.020 µg/m³ | 2.4倍 | 56.7% |
| SSP2–4.5 | 1.167 µg/m³ | 2.7倍 | 69.3% |
| SSP3–7.0 | 1.305 µg/m³ | 3.0倍 | 77.8% |

情景来源的历史时段为2011—2020年，网络平均基线为0.434 µg/m³。上述汇总固定2022年的机构分布及患者月权重，描述这些位置未来的烟雾暴露。

### 研究意义

本研究一方面刻画了年度汇总监测研究烟雾与低血红蛋白关联时的信息量及不确定性，另一方面量化了公开气候情景下可能面临明显更高烟雾暴露的透析服务范围。短期临床响应和治疗变化仍需更细致的个体纵向记录研究。对两项公开气道细胞木烟实验的探索性再分析提供了生物学背景，实验响应随细胞系统和暴露方式而变化。

### 关于本仓库

本仓库依据第10版论文正文与补充材料编写中英双语介绍，唯一内容文件为本README。论文、分析代码和数据另行管理。
