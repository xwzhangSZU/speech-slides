<!-- .slide: data-background-color="#0b1628" style="text-align:center" -->

# 人工智能记忆问题的"纾解路径"

**文献检索策略与参考文献指引**

<small>AI Memorization & Copyright: Literature Search Strategy</small>

---

<!-- .slide: data-background-color="#141e30" -->

## 核心判断

> "找不到参考文献"这一说法是站不住脚的。第四章所涉及的问题，本质上都是法学中反复讨论过的经典议题——只是在 AI 记忆这一新技术语境下被重新提出。

**01** &nbsp; 为什么一定能找到文献？法律问题具有结构性延续

**02** &nbsp; 按论文子议题，应参考哪些具体文献？

**03** &nbsp; 如何系统化检索跨技术世代的法律问题？

---

<!-- .slide: data-background-color="#141e30" -->

## 没有什么法律问题是全新的

| 经典问题 | 核心分析工具 | 代表文献 |
|---------|------------|---------|
| **谁应承担产品缺陷风险？** | "最低成本避免者"原则 | Calabresi, *The Costs of Accidents* (1970); AI LEAD Act (2025) |
| **中间人如何承担间接侵权责任？** | 帮助侵权 & 替代责任 | *Napster*; *Grokster*; Lin & Guan, "From Safe Harbours to AI Harbours" (2025) |
| **多相似算侵权？** | 实质性相似测试 | Lemley, "How Generative AI Turns Copyright Upside Down" (2024) |

<small>问题不在于"没有文献"，而在于是否具备从旧问题映射到新问题的学术能力。</small>

---

<!-- .slide: data-background-color="#141e30" -->

## 技术连续性决定法律问题的连续性

印刷机 → 录像机 *Sony* (1984) → P2P *Napster* (2001) → *Google Books* (2015) → UGC/DMCA → **AI 记忆 (2023+)**

> **Matthew Sag, "Copyright Safety for Generative AI" (2023)**
> 将生成式 AI 的记忆问题与 *HathiTrust*、*Google Books* 案中的"非表达性使用"判例系统类比，示范了如何用既有 fair use 框架理解全新的 AI 技术风险。

<small>每一代复制技术都曾被认为"前所未有"，但法律学者每一次都成功从既有框架发展出新应对方案。</small>

---

<!-- .slide: data-background-color="#1C2833" style="text-align:center" -->

# 01

## 谁应承担风险

开发者 vs. 用户 vs. 共同承担

---

<!-- .slide: data-background-color="#141e30" -->

## 风险分配的理论基础

- **Calabresi** (1970)：最低成本避免者 → 将责任分配给能以最低成本预防损害的一方
- **Carbonara, Guerra & Parisi** (2016)：损失分担在特定条件下优于"全有或全无"规则
- **Air & Liquid Systems v. DeVries** (2019)：裸金属产品制造商的警告义务

**AI 语境的适用：**

- **Lin & Guan** (2025)：三层角色分配——数据供应商 · 模型开发者 · 部署者
- **Chicago Law Review** (2025)：基于规模与风险等级的分级责任框架
- **AI LEAD Act** (2025)：将 AI 系统归类为"产品"，开发者承担设计缺陷责任

> **Lawfare (2024)：** 即便开发者试图免责，仍可能因制造缺陷组件而承担产品责任

---

<!-- .slide: data-background-color="#141e30" -->

## GEMA v. OpenAI（2025 年 11 月）

*慕尼黑地方法院 · 欧洲首个直接处理 AI 记忆与版权关系的判决*

| 裁定 | 内容 |
|------|------|
| **裁定一** | ChatGPT 对歌词的记忆构成德国著作权法第 16 条的**"复制"** |
| **裁定二** | 输出歌词构成第 19a 条的**"向公众传播"** |
| **裁定三** | 责任归属于 **OpenAI**，而非终端用户 |

> **启示：** 模型架构和数据集选择的决策权在开发者手中，因此开发者应是记忆问题的主要责任承担者。

---

<!-- .slide: data-background-color="#141e30" -->

## Sag 的七项版权安全最佳实践（2023）

1. 训练数据中不应包含同一作品的**重复副本**（数据去重）
2. 仔细考虑**模型规模与训练数据的比例**关系
3. 针对版权/商标敏感性的 **RLHF 训练**应成为标准流程
4. 应考虑**限制侵权输出**的策略（过滤/限制模型输出）
5. 存在显著版权风险的 LLM **不应开源**
6. 应保留**训练数据来源**的详细记录
7. 图像训练数据的文本描述应**避免唯一性描述**

<small>补充技术手段：差分隐私 · 机器遗忘（machine unlearning）· EU AI Act 实践守则 Measure 4</small>

---

<!-- .slide: data-background-color="#1C2833" style="text-align:center" -->

# 02

## 法律能做什么

事前标准设定 & 事后结果判定

---

<!-- .slide: data-background-color="#141e30" -->

## 路径一：事前标准设定

**"不通过标准不准上市"**

- **EU AI Act**：高风险 AI 事前合规评估 · 技术文档编制 · CE 标志 · 借鉴医疗器械监管逻辑
- **EU 产品责任指令 (PLD)**：2024 年 12 月生效，首次将软件/AI 归类为"产品"；引入**持续学习责任**
- **FDA 监管模型**：七步可信度评估框架 · 软件预认证项目
- **ISO/IEC 42001**：AI 管理系统标准，基于风险的治理方法

> **EU AI Act Code of Practice (2025)：** Measure 4 要求模型提供者实施技术保障措施以防止生成侵权输出

---

<!-- .slide: data-background-color="#141e30" -->

## 路径二：事后结果判定

**"实质性相似"测试**

法院立场：**拒绝采纳刚性量化阈值**——"复制文本的百分比"不是决定性标准（2026 年 1 月裁决）

- **Sag**：大多数情况联系经高度衰减，但版权角色、歌词等特定场景风险显著升高
- **Copyright Alliance** (2025)：输入阶段与输出阶段是两个独立侵权行为
- **GEMA v. OpenAI**：简单提示即可获得逐字版权内容 → 即构成侵权
- **美国版权局** (2025)：是否采取输出过滤措施**本身就是侵权判定的重要考量因素**

<small>输出过滤（output filter）争议：EU AI Act 早期草案 Measure 2.9 因过度阻止合法使用风险被强烈反对</small>

---

<!-- .slide: data-background-color="#141e30" -->

## 系统化文献检索：五步法

**1 · 识别法学结构**
"谁该承担风险" → 侵权法·风险分配 ｜ "设标准不准上市" → 事前监管 vs. 事后救济

**2 · 搜索先行技术的同类结构**
印刷机 → 录像机 → P2P → 搜索引擎 → UGC → AI 记忆

**3 · 利用关键学者的文献网络**
Sag (Emory) · Lemley (Stanford) · Samuelson & Sprigman (Berkeley/NYU) · Lee, Cooper & Grimmelmann (Cornell)

**4 · 追踪最新判例与立法**
*Bartz v. Anthropic* · *GEMA v. OpenAI* · Copyright Office Report · AI LEAD Act · EU AI Act

**5 · 跨领域检索**
产品责任法 · 数据隐私法 · 平台责任法 · 行政法事前许可

---

<!-- .slide: data-background-color="#141e30" -->

## 三种认知偏差与方法论启示

**偏差一：窄化搜索**
只搜索"AI memorization copyright"，忽略与产品责任、中间人责任的同构性。**应先拆解法学结构，再按结构搜索。**

**偏差二：忽略技术连续性**
AI 记忆是复制技术演进的最新章节。只盯着"AI"而不回顾技术史，自然觉得文献空白。

**偏差三：混淆"没有文献"与"没有直接对口文献"**
法学研究的价值恰恰在于将既有原则应用于新情境。版权法存在大量"潜在空间"需要学者去发掘。

> 关键在于：是否具备从旧问题映射到新问题的**学术视野**。

---

<!-- .slide: data-background-color="#0b1628" style="text-align:center" -->

# Thank You

问题不在于"没有文献"

而在于是否具备从旧问题映射到新问题的学术能力

<small>"法学论文的核心贡献不是发现别人从未讨论过的问题，而是以更清晰的框架、更充分的论证来回应现实中的法律挑战。"</small>
