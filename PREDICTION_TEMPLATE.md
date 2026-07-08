# Prediction Record Template

This template is used for new prediction records in the IEH Prediction Archive.

Each prediction should map to stable IEH corollary IDs defined in the main repository:

- `COROLLARY_REGISTRY.md`
- `THEORY_MAP.md`

---

# 预测文档模板

本模板用于 IEH 预测仓中的新预测文档。

每一篇预测文档都应通过稳定推论 ID 与主仓理论体系建立映射。稳定 ID 请参见主仓：

- `COROLLARY_REGISTRY.md`
- `THEORY_MAP.md`

---

## Metadata / 元信息

```yaml
---
prediction_id: PRED-YYYY-XXX
title: ""
status: "Active"
phase: ""
primary_corollaries:
  - 
supporting_corollaries:
  - 
related_corollaries:
  - 
legacy_corollary_refs:
  - 
created: YYYY-MM-DD
last_updated: YYYY-MM-DD
---
```

---

## 1. Prediction / 预测

State the prediction clearly and compactly.

用清晰、紧凑的方式陈述预测。

Example:

> Before ASI, AI will restructure warfare not only by improving weapons, but by changing how war capability and war will are generated, targeted, and degraded.

中文示例：

> 在 ASI 到来之前，AI 不只是改进武器，而是会改变战争能力和战争意愿的生成、打击和衰减方式。

---

## 2. Theoretical Basis / 理论依据

Explain which IEH corollaries support this prediction.

说明该预测由哪些 IEH 推论支撑。

Recommended format:

```yaml
primary_corollaries:
  - C13-WAR
supporting_corollaries:
  - C06-SPP
  - C12-GOV
related_corollaries:
  - C07-ASI
```

Then explain briefly:

- why the primary corollary is central;
- how supporting corollaries contribute;
- whether this prediction refines or extends an older mapping.

中文说明：

- 为什么 primary corollary 是核心；
- supporting corollaries 如何提供机制支撑；
- 该预测是否细化或扩展了旧映射。

---

## 3. Mechanism / 机制

Describe the causal mechanism.

Keep this section structured and archival.  
Do not write it as a polished essay.

描述预测背后的因果机制。

本节应保持档案化结构，不应写成完整投稿文章。

Suggested structure:

```text
AI capability change
→ system-level pressure
→ institutional / economic / military / educational response
→ observable outcome
```

中文结构：

```text
AI 能力变化
→ 系统层压力
→ 制度 / 经济 / 军事 / 教育反应
→ 可观察结果
```

---

## 4. Observable Indicators / 可观测指标

List concrete indicators that would support or weaken the prediction.

列出能够支持或削弱该预测的现实指标。

Examples:

- policy changes;
- institutional reforms;
- investment patterns;
- infrastructure expansion;
- military procurement;
- education curriculum changes;
- labor market shifts;
- legal or regulatory changes;
- repeated real-world cases.

中文示例：

- 政策变化；
- 制度改革；
- 投资方向；
- 基础设施扩张；
- 军事采购；
- 教育课程变化；
- 劳动力市场变化；
- 法律或监管变化；
- 重复出现的现实案例。

---

## 5. Evidence Log / 证据日志

Record external evidence over time.

按时间记录外部证据。

Suggested format:

| Date | Evidence | Source / Link | Relevance | Status |
|---|---|---|---|---|
| YYYY-MM-DD |  |  |  |  |

Status options:

| Status | Meaning |
|---|---|
| Supports | The evidence supports the prediction. |
| Partially Supports | The evidence supports part of the prediction. |
| Neutral | The evidence is relevant but not clearly supportive or weakening. |
| Weakens | The evidence weakens the prediction. |
| Contradicts | The evidence contradicts the prediction. |

中文状态：

| 状态 | 含义 |
|---|---|
| Supports | 支持该预测。 |
| Partially Supports | 部分支持该预测。 |
| Neutral | 相关，但暂不明确支持或削弱。 |
| Weakens | 削弱该预测。 |
| Contradicts | 反驳该预测。 |

---

## 6. Falsifiability Conditions / 证伪条件

List conditions that would weaken or falsify the prediction.

列出可能削弱或证伪该预测的条件。

Examples:

1. If the relevant AI capability does not improve beyond current levels by a specified timeframe.
2. If institutions do not respond in the predicted direction.
3. If alternative explanations better account for the observed evidence.
4. If the predicted trend reverses over a sustained period.

中文示例：

1. 如果相关 AI 能力在特定时间前没有继续提升；
2. 如果制度没有朝预测方向反应；
3. 如果其他解释更能说明现实证据；
4. 如果预测趋势在较长时期内发生反转。

---

## 7. Current Status / 当前状态

Use one of the following:

| Status | Meaning |
|---|---|
| Active | The prediction is currently being observed. |
| Supported | Evidence has meaningfully supported the prediction. |
| Partially Supported | Some evidence supports the prediction, but the result remains incomplete or mixed. |
| Weakened | Evidence has weakened the prediction. |
| Falsified | Evidence has strongly contradicted the prediction. |
| Archived | The prediction is retained for historical reference, but is no longer actively updated. |

中文对应：

| 状态 | 含义 |
|---|---|
| Active | 正在观察中。 |
| Supported | 已有证据明显支持。 |
| Partially Supported | 部分证据支持，但结果仍不完整或混合。 |
| Weakened | 已有证据削弱该预测。 |
| Falsified | 已有证据强烈反驳该预测。 |
| Archived | 保留为历史记录，不再主动更新。 |

---

## 8. Relation to Existing Prediction Records / 与既有预测文档的关系

If this prediction refines an older record, note it here.

如果本预测细化了旧预测文档，在此说明。

Example:

```yaml
refines:
  - PA-02
refined_by:
  - C13-WAR
legacy_corollary_refs:
  - Corollary VI
```

Possible relation types:

| Field | Meaning |
|---|---|
| `refines` | This prediction refines an older prediction record. |
| `refined_by` | This prediction is further refined by a newer corollary or prediction. |
| `overlaps_with` | This prediction overlaps with another prediction. |
| `supersedes` | This prediction replaces an older prediction. Use sparingly. |

中文对应：

| 字段 | 含义 |
|---|---|
| `refines` | 本预测细化旧预测。 |
| `refined_by` | 本预测被新推论或新预测进一步细化。 |
| `overlaps_with` | 本预测与其他预测存在重叠。 |
| `supersedes` | 本预测替代旧预测，应谨慎使用。 |

---

## 9. Publication Boundary / 投稿边界

This prediction record is not a publication-ready essay.

It is intended to preserve theoretical priority, mechanism clarity, observability, and evidence tracking.

本文档不是投稿成稿。

它用于保留理论优先权、机制清晰度、可观测性和证据追踪。

This document may include:

- prediction statement;
- mechanism;
- observable indicators;
- evidence log;
- status;
- related corollaries.

This document should avoid:

- polished magazine-style openings;
- full op-ed structure;
- full pitch letters;
- publication-ready titles intended for external magazines;
- long narrative passages that can be directly translated into a submitted essay;
- complete case-study development.

中文说明：

本文档可以包含：

- 预测陈述；
- 机制；
- 可观测指标；
- 证据日志；
- 状态；
- 相关推论。

本文档应避免包含：

- 高度打磨的媒体化开头；
- 完整评论文章结构；
- 完整投稿 pitch；
- 面向外部刊物的最终标题；
- 可直接翻译成投稿稿的大段叙事；
- 完整案例展开。

---

## 10. Update History / 更新记录

| Date | Update | Notes |
|---|---|---|
| YYYY-MM-DD | Created | Initial prediction record. |

---

# Blank Template / 空白模板

```markdown
---
prediction_id: PRED-YYYY-XXX
title: ""
status: "Active"
phase: ""
primary_corollaries:
  - 
supporting_corollaries:
  - 
related_corollaries:
  - 
legacy_corollary_refs:
  - 
created: YYYY-MM-DD
last_updated: YYYY-MM-DD
---

# [Prediction Title]

## 1. Prediction

## 2. Theoretical Basis

## 3. Mechanism

## 4. Observable Indicators

## 5. Evidence Log

| Date | Evidence | Source / Link | Relevance | Status |
|---|---|---|---|---|

## 6. Falsifiability Conditions

## 7. Current Status

## 8. Relation to Existing Prediction Records

## 9. Publication Boundary

## 10. Update History

| Date | Update | Notes |
|---|---|---|
| YYYY-MM-DD | Created | Initial prediction record. |
```

---

## Core Rule / 核心规则

> **Prediction records should preserve mechanism and observability, not consume publication expression.**

> **预测文档应保留机制和可观测性，而不是消耗投稿表达。**
