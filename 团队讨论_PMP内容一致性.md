# PMP 文档一致性 · 待全组确认

> 📅 2026-05-14
> 📌 用途：定下统一的项目"包装方向"，让 Section 1 / 4-6 / 11 / 12 写下去时不再前后矛盾
> 🎯 决策方式：**默认按推荐方案走**，群里没人反对就直接定稿；如有不同意见请在对应位置留言

---

## 〇、前提说明（很重要，先看这段）

我们这门课叫**软件项目管理**，老师只看：

1. PMP 计划本身**是否合理、专业、覆盖 PMBOK 知识点**
2. 项目细节真实与否**完全不关心**——虚构项目都行
3. 反对 AI 直接生成的文字（最后由各人手动润色解决）

所以**项目怎么包装就看怎么写出来 PMP 最漂亮**。

**👉 核心建议：把整篇 PMP 统一往"商业承包项目"方向包装**——和 Section 7-10 已写的 Luckin Coffee 方向保持一致。这样：
- Cost / Procurement / Quality 几节都有商业内容可写，能展示完整 PMBOK 知识点
- 风险登记册可以列合同风险、SLA 风险、供应商风险等专业项
- 整体 PMP 看起来更"完整、像样"

---

## 一、当前进度

| Section | 负责人 | 状态 |
|---|---|---|
| 1 · Executive Summary | 刘昊普 | ⏳ |
| 2 · Integration Management | 龚知健 | ✅ |
| 3 · Scope Management | 龚知健 | ✅ |
| 4-6 · Schedule / Cost / Quality | 待认领 | ❌ |
| 7-10 · Process / HR / Procurement / Comms | 队员 C | ✅ |
| 11 · Risk Management | 刘昊普 | ⏳ |
| 12 · References | 刘昊普 | ⏳ |

---

## 二、🎯 核心决策

### Q1：整篇 PMP 的包装方向

当前 Section 2-3（学术风）和 Section 7-10（商业风）方向冲突，必须统一。

- ✅ **推荐**：统一为"**商业承包项目**" — 客户是 Luckin Coffee 风格连锁咖啡企业，团队是承接 ESG 平台开发的乙方
- ⬜ 备选：统一为纯学术练习（需要重写 Section 7-10 几十处提及客户的内容，工作量大且不利于展示 PMP 知识点）

**默认按推荐走，有反对意见请回复"反对 Q1"**

---

## 三、📋 沿着"商业包装"方向，几个细节统一

> 以下决策都是 Q1 推荐方案下的细化，如果 Q1 通过，下面这些也一并默认按推荐生效。

### Q2：客户身份

- 当前 Section 2 写"**Five Guys** regional managers"是 bug（Five Guys 是我们 UCD 课的团队代号，不是客户）
- ✅ **推荐**：全文统一为 **Luckin Coffee 风格的虚构客户**（Section 7-10 已是这样）
- 修订方式：刘昊普整理时把 Section 2-3 的客户描述同步成 Luckin Coffee

### Q3：团队规模

| 现状 | 数字 |
|---|---|
| Section 2 散文 | 6 人 |
| Section 2 组织图 | 4 人 |
| Section 8 | 5 人内部 + 1 ESG 顾问 |
| 实际 PMP 课 | 4 人 |

- ✅ **推荐**：文档里统一写 **"5 人内部 + 1 外部 ESG 顾问"**（Section 8 写法）
  - 理由：商业项目通常会有外部顾问，更专业；多 1-2 个虚构岗位不影响实际签名
  - 文档作者署名仍是 PMP 课实际 4 人
- 修订方式：补充 1-2 个虚构成员或岗位填到 Section 2 组织图里

### Q4：技术栈

- ✅ **推荐**：保留 Section 8 的 **Vue3 + Bootstrap + Flask + MySQL + ECharts**（PMP 老师不限技术栈）
- 修订方式：Section 2 散文若涉及前端，补一句 Vue3 即可

### Q5：协作工具

- 当前 Section 2 写 Discord，Section 7-10 写企业级（Jira/Confluence/Tencent Meeting/Enterprise WeChat/GitLab/Prometheus）
- ✅ **推荐**：全文统一为**企业级工具栈**（GitLab + Jira + Confluence + Tencent Meeting + Enterprise WeChat）
- 修订方式：刘昊普整理时把 Section 2 的"Discord/Google Docs"换成企业级对应工具

### Q6：CI/CD 与运维

- ✅ **推荐**：保留 Section 7 的"配置 CI/CD + 自动化测试 + 监控告警"写法（这是 PMP 加分项，展示工程管理能力）

### Q7：预算定位

- 当前 Section 2 写"zero-cost academic endeavor" vs Section 9 大量采购合同 → 矛盾
- ✅ **推荐**：改为**有预算的商业项目**（具体数字由 Section 5 Cost Management 负责人估算，参考 Section 9 已列的采购项目）
- 修订方式：Section 2 把"zero-cost"段删掉，改写为"项目预算包含人力、基础设施、第三方服务采购等"

### Q8：组号

- 当前 Section 2 写 "**Group 5**"
- ❓ **PMP 课实际给我们组分配的编号是？** 请知道的同学补充：____________

### Q9：写作风格

- 现状：Section 2-3 段落派 / Section 7-10 bullet+表格派
- ✅ **推荐**：**不强行统一**，最后整理排版时让两种风格自然过渡即可
- AI 痕迹问题在最后的"去 AI 化"阶段由各人润色自己的章节解决

---

## 四、📅 接下来的执行顺序

如果 Q1-Q9 都按推荐通过：

1. **本周**：刘昊普根据决策修订 Section 2-3（统一客户、工具、预算等表述）
2. **本周**：刘昊普写 Section 11（风险管理）
3. **下周**：队员 B（Section 4-6 负责人）按"商业包装"方向写 Schedule / Cost / Quality
4. **4-6 写完后**：刘昊普写 Section 1（执行摘要）+ 补 Section 12 附录条目
5. **最后阶段**：全组每人对自己的章节做"去 AI 化"人工润色

---

## 五、💬 群里请回复

请大家在群里直接回复以下内容（任选其一）：

- **"全部同意"** → 默认所有推荐方案生效
- **"反对 QX"** → 写出反对的具体决策点和理由
- **"补充 QX：XXX"** → 想补充想法
- **"PMP 课组号是 XX"** → 帮 Q8 填空

---

## 六、最终决策（讨论后填写）

| # | 项 | 最终方案 |
|---|---|---|
| Q1 | 包装方向 | |
| Q2 | 客户 | |
| Q3 | 团队规模 | |
| Q4 | 技术栈 | |
| Q5 | 协作工具 | |
| Q6 | CI/CD | |
| Q7 | 预算 | |
| Q8 | 组号 | |
| Q9 | 风格 | |
